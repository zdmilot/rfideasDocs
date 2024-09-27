# BSHRT SetIpPort [Traffic]

Works with Unknown platform

## API Call
BSHRT SetIpPort(BYTE i0,
## DESCRIPTION
Set the TCP/IP/UDP source address to be used to connect to Ethernet readers. A call to USBConnect() will check USB, TCP/IP and Serial ports in that order.

## PARAMETERS
byte dotted ip notation such as 192.168.0.1 port 10,001 SetIpPort(192,168,0,1, 10001);

## RETURNS
Always returns TRUE / Success

## SEE ALSO
[FindXport() ](FindXport() .md)
