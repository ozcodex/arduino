
all: upload

compile:
	arduino-cli compile --export-binaries --verbose --fqbn digistump:avr:digispark-tiny8 blink.ino
	
upload:
	arduino-cli compile --upload --port /dev/ttyUSB0 --verbose --fqbn digistump:avr:digispark-tiny8 blink.ino

