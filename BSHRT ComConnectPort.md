# BSHRT comConnectPort [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark200">&zwnj;</a>Windows, Linux, Mac</p>

## API Call
BSHRT comConnectPort(WORD iPort)
## DESCRIPTION
Connect to one serial device on COM port iPort (1..256)

## PARAMETERS
Port number 1..256 representing COM1 thru COM256 on Windows.

## RETURNS
TRUE = Success / FALSE = Failure

## SEE ALSO
[usbConnect() ](usbConnect() .md), [comConnect() ](comConnect() .md), [ComConnectPort() ](ComConnectPort() .md)
