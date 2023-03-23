# Morse-Code-Transciever

Hardware:
Laser diode, button switch, photoresistor, LCD display, Arduino 2560 MEGA. 


General:
Laser diode transmitted at speeds up to 50 ms from distances of 50 feet from the receiver.

Receiver processed laser pulses using morse code standards and output the decrypted morse code into english and output to LCD display.



LabVIEW:

English was input in LabVIEW sent through a morse encrypter and then fed to the LASER diode. 

The receiver detected rising and falling edges in order to differentiate a space between morse character or a character itself. 

Receiver also timed how long the diode was in a high or low state for. 

Receiver also had error validation by keeping track of the 3 most recent states and ensuring we don't get double readings. 
