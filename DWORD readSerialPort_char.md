# DWORD readSerialPort_char [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark379">&zwnj;</a>Windows, Linux, Mac<a name="bookmark380">&zwnj;</a></p>

## API Call
DWORD readSerialPort_char(short index)
## DESCRIPTION
C# interface to check for serial data on connected COM port and receive available bytes. This uses a two second timeout.

## PARAMETERS
index == -1 zero internal buffer calls readSerialPort() and fills up to 1024 byte internal buffer.

## RETURNS
index == -1 returns actual number of characters received. else returns character at index from internal buffer.

## SEE ALSO
[ReadSerialPort() ](ReadSerialPort() .md), [quickReadSerialPort_char() ](quickReadSerialPort_char() .md)
