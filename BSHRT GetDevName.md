# BSHRT GetDevName [Traffic]

Works with Unknown platform

## API Call
BSHRT GetDevName(char *szName)
## DESCRIPTION
Get Device Name, this can be a long USB device name the users

## PARAMETERS
szName A string containing COMx, or USB PID VID of the communications port the reader is found on.

## RETURNS
The active RS-232 or Virtual COM port number (1, 2, ...). 999 will be returned for USB devices.

## SEE ALSO
[rf_GetDevName() ](rf_GetDevName() .md)
