# Electronic-Locking-System

---

### Table of Contents
Using a Bluetooth device to enter a security pin and activate a locking mechanism 
This task was to be undertaken as a group, this required the team to develop a locking and unlocking system through serial communication. Using a PIC18F-4520 micro controller, we had to implement this system onto a practical hardware. The micro controller would be remotely controlled using a serial interface, this would communicate with a wireless Bluetooth device such as a mobile phone that would require a user input remotely. 
The code is first created by the user upon initial access, this would be an access code, followed by this, another code is created by the user that shall determine whether to lock or unlock the system. The data is then stored into the EEPROM of the microcontroller to access the device again later on. After 3 failed attempts the system shall sound an alarm and flash an LED while remaining inactive for a short period. 
