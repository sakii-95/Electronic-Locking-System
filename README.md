# Electronic-Locking-System

---

### Introduction
Using a Bluetooth device to enter a security pin and activate a locking mechanism 
This task was to be undertaken as a group, this required the team to develop a locking and unlocking system through serial communication. Using a PIC18F-4520 micro controller, we had to implement this system onto a practical hardware. The micro controller would be remotely controlled using a serial interface, this would communicate with a wireless Bluetooth device such as a mobile phone that would require a user input remotely. 
The code is first created by the user upon initial access, this would be an access code, followed by this, another code is created by the user that shall determine whether to lock or unlock the system. The data is then stored into the EEPROM of the microcontroller to access the device again later on. After 3 failed attempts the system shall sound an alarm and flash an LED while remaining inactive for a short period. 

---

### Procedure

The EERPOM stand for electrically erasable programmable read-only memory. This shall be used to store the access code and the lock/unlock code of the system. The reason this is used is so that the system cannot be hacked and checks whether the input password is correct, also this will store the data so the initial code is not reset each time it is accessed again. 
Several components are also required when implementing the circuit;
Solenoid – a solenoid is a cylindrical coil of wire that acts as a magnet when electrical current flows through. The device creates a magnetic field which then creates a mechanical motion, this device is what shall be used to determine the state of whether the system is locked or unlocked. A solenoid requires a lot of power so the addition of a power transistor and rectifier diode need to be included for the solenoid to work appropriately. 
Switch-  the driver interface shall contain a reed relay device such as the EDR101A0500, two of these are required for both sides of the solenoid. The reed relay controls the flow of the current to act as the switch, if there is enough current flowing the relay then the magnet will activate the switch, thus depending on which relay has more EMF, the system will lock or unlock. 
Rectifier diode- A diode allows flow or electricity in only one direction, as they are capable of high current flow, they can control the change of alternating current into direct current. 
Transistor- A transistor is a device that can either be used as an amplifier or a switch, in this case it shall be used for the interface to receive the current signal and enable current flow for the switch to activate. Most importantly, the transistor shall help to control the electricity so the switch doesn’t become over loaded. 
TX/RX- transmitting and receiving shall be used for the desired system so that we can accommodate wireless communication through a mobile device. A matching board rate from both the microprocessor and receiver is essential so that the data is not lost.
Alarm- a simple buzzer and LED shall be used to create the alarm. They shall be programmed to detect the status of the device so that if the user fails to access the system then the LED shall emit and the buzzer shall sound. 

---

### Youtube Link

https://www.youtube.com/watch?v=qolxyKKJSvk
