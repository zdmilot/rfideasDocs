# short GetDevByLUID [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark35">&zwnj;</a>Windows, Linux, Mac</p>

## API Call
short GetDevByLUID(short LUID, short index)
## DESCRIPTION
Find the device index used by SetActDev and GetActDev for the given LUID Start at the active device index parameter. If index &lt; 0 then -1 is returned.

## PARAMETERS
Logical Unit ID 0 .. 65535

## RETURNS
0..N else -1 for not found

## SEE ALSO
[SetLUID() ](SetLUID() .md)
