Description
===========
* xyloni_set_vccio.py - Modify the VCCIO on Xyloni <br/>


## Dependencies
Under efinity/bin/ <br/>
On Windows:
```
setup.bat
```

On Ubuntu:
```
./setup.sh
```

## Usage
-arg1 VCC_IO1 = 1.8V,2.5V,3.3V<br/>
-arg2 VCC_IO2 = 1.8V,2.5V,3.3V<br/>

## Example
```
python3 xyloni_set_vccio.py 1.8V 1.8V
```
VCC_IO1 and VCC_IO2 will set to 1.8v<br/>

## WARNING!!!
Powering down the FTDI chip seems to reset the VCC_IO1/VCC_IO2 voltages back to default of 3.3v. Careful what is hooked up to GPIO pins as some IO may come up at that voltage!
