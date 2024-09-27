# DWORD QuickReadSerialPort [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark100">&zwnj;</a>Windows, Linux, Mac<a name="bookmark101">&zwnj;</a></p>

## API Call
DWORD QuickReadSerialPort(char *buf, DWORD count)
## DESCRIPTION
Check for serial data on connected COM port, and receive available bytes.

## PARAMETERS
pointer to char buffer, and count of max desired characters to receive.

## RETURNS
Actual number of characters received.

## SEE ALSO
[readSerialPort_char() ](readSerialPort_char() .md), [ReadSerialPort() ](ReadSerialPort() .md)
