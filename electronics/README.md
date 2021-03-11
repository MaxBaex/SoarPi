# PCB Design(s)

## Planned part usage
- Display:  NHD-7.0-HDMI-HR-RSXP-CTU,   very small alternative: NHD-4.3-HDMI-HR-RSXP-CTU   
- Encoders: PEC11H-4225F-S0024 
- Raspberry PI 3B  (due to lower current consumption compared to the 4B)
- Pushbuttons: 3-1825910-5  (4.9mm actuator length) 
- Ambient light lensor: BH1750
- Sound amplifier: PAM8403  (using use the 3.5mm connector) 
- Adapter PCB: To be designed.
- RS232 via FT232RL + MAX232 connected via micro usb to Raspberry.
- CAN via MCP2515 + SPI)  https://crycode.de/can-bus-am-raspberry-pi 


## Raspberry Pi GPIO Pin Mapping:
- GPIO4 : OneWire


