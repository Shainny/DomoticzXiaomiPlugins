# DomoticzXiaomiPlugins

This project is an attempt to make Python plugins for Xiaomi devices in Domoticz, using the python-miio library.

# See

- Domoticz : https://github.com/domoticz/domoticz
- python-miio : https://github.com/rytilahti/python-miio

# Troubleshooting

- Device[X].Update() crash domoticz if called whith implicit parameters. See https://github.com/domoticz/domoticz/issues/2092
- Calling python-miio seems to freeze domoticz's plugin system. Don't know why but similar project faced the same issue. See https://github.com/mrin/domoticz-mirobot-plugin

# Help

- Domoticz device types : https://github.com/domoticz/domoticz/blob/development/hardware/hardwaretypes.h
