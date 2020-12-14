# xcore407i-CNC

CNC Controller based on STM32 MCU core board, STM32F407IGT6 with comunication on Ethernet via TCP/Telnet commands .
- **Peripherals**
  - Control up to 6 coordinated axes (XYZABC)
  - Dual motors axes can optionally auto square using a home switch and independent control for each motor.
  - Motor drivers can be dynamically assigned to axes, so a 4 motor XYZA controller could be converted to a XYYZ (dual motor Y axis) without any hardware changes.
  - Step rates up to 200,000 per/second. (200kHz for all axes)
  - 32 programmable isolated with 12V input voltage  INPUTS (E-Stop,Limits,Probe,Reset,PAUSE,START)
  - 16 programmable OUTPUTS with open collector (ULN2803) 
  - RS485 to comunication for VFD with change frequency , read all parameters from VFD
  - 2 small relay 
  - Ethernet to comunication of LAN with TCP/IP over telnet 

<img src="https://github.com/rafik84/xcore407i-CNC/blob/main/board.jpg">
