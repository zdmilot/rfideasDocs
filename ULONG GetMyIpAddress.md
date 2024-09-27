# ULONG GetMyIpAddress [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark73">&zwnj;</a>Windows, Linux, Mac</p>

## API Call
ULONG GetMyIpAddress(void)
## DESCRIPTION
Return the IP address of the local machine as an unsigned long. If dotted quad is 192.168.1.2 then the long in hex will be 0x0201A8C0. To convert to bytes as ip1,ip2,ip3,ip4 shift the byte in mutiples of eight as follows:

## PARAMETERS
None

## RETURNS
Unsigned long. Least significant byte is the first byte of the dotted quad notation.

## SEE ALSO
[SetDevTypeSrch(PRXDEVTYP_TCP) ](SetDevTypeSrch(PRXDEVTYP_TCP) .md)
