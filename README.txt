Home Automation flash.bin file

Read code from arduino:

avrdude -p m328p -P /dev/ttyACM0 -c arduino -U flash:r:flash.bin:r

Find your port by which arduino is connected

Port: /dev/ttyACM0

flash.bin : it will be the file name of binary.


Write code in binary in arduino.

Find your port by which arduino is connected

Port: /dev/ttyACM0

avrdude -p m328p -P /dev/ttyACM0 -c arduino -U flash:w:flash.bin



