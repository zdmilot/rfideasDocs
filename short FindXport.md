# short FindXport [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark13">&zwnj;</a>Windows, Linux, Mac<a name="bookmark14">&zwnj;</a></p>

## API Call
short FindXport(short ip0,
## DESCRIPTION
Ethernet readers use an Xport interface to convert serial data to Ethernet.

## PARAMETERS
IP address range ip0,ip1,ip2 first 3 digits of IP, ip3begin .. ip3end inclusive range of IP addresses to check for an Xport device.

## RETURNS
1..254 last digit of IP address of firstt found device. If none found return 0.

## SEE ALSO

