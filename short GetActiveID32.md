# short getActiveID32 [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark206">&zwnj;</a>Windows, Linux, Mac</p>

## API Call
short getActiveID32(short wBufMaxSz)
## DESCRIPTION
Read the active ID from the device and buffer the data for the function getActiveID_byte().

## PARAMETERS
wBufMaxSz specifies the size of the character buffer. A max of 32 will be used so this is useful only to limit the buffer transfer.

## RETURNS
Number of bits read from card. Zero if no card present or error.

## SEE ALSO

