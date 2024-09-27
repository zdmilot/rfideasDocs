# short chkDelRemoval_char [Traffic]

Works with Unknown platform

## API Call
short chkDelRemoval_char(short index, char c)
## DESCRIPTION
C# interface to Check device removal function.

## PARAMETERS
index 0..255. 255 trigger I/O call. When index is 0 internal DeviceName buffer is zeroed out.

## RETURNS
Check to see if device is in the list held by the library TRUE = Success / FALSE = Failure

## SEE ALSO
[chkAddArrival_char() ](chkAddArrival_char() .md), [ChkAddArrival() ](ChkAddArrival() .md)
