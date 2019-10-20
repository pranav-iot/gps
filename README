# gps

GPS Pins	Details		RaspberryPin 	PinFunction
VCC 		Power 		Pin 1 			3.3V Power
GND 		Ground 		Pin 39 			GND
TXD Data 	Output 		Pin 10 			(UART_RXD0) GPIO15
RXD Data 	Input 		Pin 8 			(UART_TXD0) GPIO14

GPS Config for Raspberry Pi
Step 1: Enable UART on the RaspberryPi using the command
	raspi-config
Step 2: Select the Interfacing Options
Step 3: In interfacing options select Serial.
Step 4: After which you will get a message to "login shell to be accessible over the serial"
Step 5: Select No option
Step 6: Next message will be "Would you like the serial port hardware to be enabled"
Step 7: To the next message select ok and <Enter>
Step 8: Type the command:
	$>> ls /dev
	check for serial0->ttyS0 & serial1->ttyAMA0
Step 9: sudo python3 gps.py