# DWORD ReadSerialPort [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark111">&zwnj;</a>Windows, Linux, Mac<a name="bookmark112">&zwnj;</a></p>

## API Call
DWORD ReadSerialPort(char *buf, DWORD count)
## DESCRIPTION
Check for serial data on connected COM port and receive available bytes. This uses a two second timeout.

## PARAMETERS
pointer to char buffer, and count of max desired characters to receive.

## RETURNS
Actual number of characters received.

## SEE ALSO
[QuickReadSerialPort() ](QuickReadSerialPort() .md), [quickReadSerialPort_char() ](quickReadSerialPort_char() .md)
