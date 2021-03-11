# Concept Description
- 12V power supply for raspberry pi, display and peripherals
- CAN interface
- Sound amplifier for a small 1-3W mono loudspeaker
- Brightness sensor for display illumination dimming. 
- some mechanical encoders at the corners which can also be used for mounting the display onto the panel
- some mechanical keys
- Rust based encoder and key drivers


## External connector definition:
- ?? Power Supply  
- ?? Loudspeaker 
- RJ45 IGC for RS232  (at least 2)
- RJ45 CAN (1 - 2)
- 3.5mm OneWire Temperature sensor 
- USB (how many and for what?)
- GPIO for manual circling / straight flight mode switch?


## To check (if it works!): 
- Works reading 4 encoder signals and 8 buttons with the Raspberry PI directly flawless? 
- Is the display a good choice for a cockpit?
- Does the display enclosure size fit into a typical glider panel?
- Are ventilation holes required in the backplane especially on hot conditions? 
- How critical is a regualar power interruption of the raspberry pi?  A proper shutwdown is unrealistic. UPS required? RPI USV+, StromPi 3, https://juice4halt.com/, Read-Only Filesystem?