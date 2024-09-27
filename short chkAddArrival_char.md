# short chkAddArrival_char [Traffic]

Works with Unknown platform

## API Call
short chkAddArrival_char(short index, char c)
## DESCRIPTION
C# interface to Check device add arrival function.

## PARAMETERS
index 0..255. 255 trigger I/O call. When index is 0 internal DeviceName buffer is zeroed out.

## RETURNS
Check to see if device is in the list held by the library TRUE = Success / FALSE = Failure

## SEE ALSO
[ChkAddArrival() ](ChkAddArrival() .md), [ChkDelRemoval() ](ChkDelRemoval() .md)
