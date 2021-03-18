# Between a Raspberry PI and a Smartphone based solution. 


## Raspberry PI
### Pros
- Raspbian based software which is very versatile
- Nicer integration into the pannel
- Easier to add feature such as ADS-B traffic reception via DVB-T Stick
- Easier to connect a USB Stickcontrol. 
- More interfaces e.g. one wire for Temperaure or Humidity Sensors

### Cons
- Hardware development more effort as display sourcing required. Hard to find a suitable display.
- More fundamental development effort if display has no HDMI interface
- LTE integration harder as additional hardware required.
- Risk of possible display related EMC issues
- High Power Consumption (> 6W)


## Smartphone
### Pros
- Sunlight readable smartphones easily available
- Update to new hardware quick and simple
- LTE available by default
- Since there is a backup battery, the system continues to run even if the board power supply is briefly interrupted
- Low Power Consumption (< 3W)

### Cons
- Battery drains unused during winter
- Read-Only configuration might be harder to achieve
- Removing bloatware which asks for updates might require a custom ROM (e.g. LineageOS)
- The on/off button must be operated somehow, which is mechanically difficult

### Notes
- Android based software
- Provides features which are not used: backside camera
- IOs can be extended with [Android ioio](https://github.com/ytai/ioio/wiki)
