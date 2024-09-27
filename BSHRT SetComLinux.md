# BSHRT SetComLinux [Traffic]

Works with Unknown platform

## API Call
BSHRT SetComLinux(WORD index, const char *devName)
## DESCRIPTION
Map Linux /dev/tty name to serial port number 1..MAXLINUXCOMPORT This allows traditional functions calls to work on Linux devices

## PARAMETERS
COM port 1..MAXLINUXCOMPORT, hold MAXLINUXDEVPATH characters.

## RETURNS
TRUE / Success else FALSE index out of range, or non Linux OS.

## SEE ALSO
[SetComSrchRange() ](SetComSrchRange() .md)
