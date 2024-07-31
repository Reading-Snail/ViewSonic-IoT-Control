# ViewSonic-IoT-Control
This Project aims to remotely control ViewSonic projector (RS232) via HTTP

## Structure
ViewSonic Projector <=> RS232 Interface <=> RS232 to TTL Convertor <=> ESP8266 <=> HTTP
![image](https://github.com/user-attachments/assets/9c17a390-dceb-451d-a0f2-82b6a11547f5)


## Requirement
- Projector: ViewSonic Project with RS232 port
- RS232 to TTL Convertor
- MicroController: ESP8266
- Testing Jump Cables

## Plan
1. Get all the components (RS232toTTL, ESP8266, TestingCables)
2. Install MicroPython
3. Install Thonny IDE
4. Wrtie code for micro-controller to control projector
6. Set Homebridge plugin (MultiSwitcheroo) to send HTTP signal to the micro-controller
