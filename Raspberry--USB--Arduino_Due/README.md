# USB communication RaspberryPi <-> Arduino Due

* Due has two usb ports -> need to determine on which USB slot the programmer/native port is connected  


```
│
├───arduino_due
│       arduino_due.ino                # Arduino sketch (serial communication with basic CRC)
│       start_usb.sh                   # Call utility to activate/deactivate usb port
│       upload.sh                      # Shell script to upload sketch from raspberry
│       verify.sh                      # Shell script to verify sketch from raspberry
│
└───raspberry
        find_port.py                   # find where Due programmer/native ports are connected
        get_watt_from_arduino_due.py   # Serial communication with basic CRC
```
