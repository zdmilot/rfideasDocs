# DWORD WriteSerialPort [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark192">&zwnj;</a>Windows, Linux, Mac<a name="bookmark193">&zwnj;</a></p>

## API Call
DWORD WriteSerialPort(char *buf, DWORD count)
## DESCRIPTION
Write data to serial port. This allows user to also do their own MFP24 or ACP commands while using the binary protocol on the reader.

## PARAMETERS
pointer to char buffer, and count of max desired characters to transmit.

## RETURNS
Actual number of characters sent.

## SEE ALSO
[QuickReadSerialPort() ](QuickReadSerialPort() .md), [quickReadSerialPort_char() ](quickReadSerialPort_char() .md)
