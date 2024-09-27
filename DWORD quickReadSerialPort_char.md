# DWORD quickReadSerialPort_char [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark375">&zwnj;</a>Windows, Linux, Mac<a name="bookmark376">&zwnj;</a></p>

## API Call
DWORD quickReadSerialPort_char(short index)
## DESCRIPTION
C# interface to check for serial data on connected COM port and receive available bytes. This function sets the timeout

## PARAMETERS
index == -1 zero internal buffer calls readSerialPort() and fills up to 1024 byte internal buffer.

## RETURNS
index == -1 returns actual number of characters received. else returns character at index from internal buffer.

## SEE ALSO
[readSerialPort_char() ](readSerialPort_char() .md), [ReadSerialPort() ](ReadSerialPort() .md), [QuickReadSerialPort() ](QuickReadSerialPort() .md)
