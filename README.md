# piVirtualWire
Python VirtualWire module for Raspberry Pi and 433MHz RF modules

## Dependencies

This code depends on **pigpio** library and can not be used without it.

**Pigpio** library is available at [this site](http://abyz.co.uk/rpi/pigpio/)

```
wget abyz.co.uk/rpi/pigpio/pigpio.zip
unzip pigpio.zip
cd PIGPIO
make
make install
```

pigpio has to be running as a service. To start:
`sudo /home/pi/PIGPIO/pigpiod`

##Hardware
This has been tested with FS1000A sender and XY-MK-5V receiver. Communication over Virtual Wire was successful with Arduino Uno and Arduino Pro Micro.