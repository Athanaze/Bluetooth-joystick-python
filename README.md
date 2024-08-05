# Bluetooth-joystick-python

import bluetooth

nd = bluetooth.discover_devices()

for b in nd:
	print(b)

# Should print the phone's address, e.g. 48:2C:A0:2B:36:B2
