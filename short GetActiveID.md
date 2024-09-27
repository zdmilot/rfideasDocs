# short getActiveID [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark205">&zwnj;</a>Windows, Linux, Mac</p>

## API Call
short getActiveID(short wBufMaxSz)
## DESCRIPTION
Read the active data from the card presently on the reader. This function will return the number of bits read.

## PARAMETERS
wBufMaxSz specifies the size of the character buffer. A max of 8 will be used so this is useful only to limit the buffer

## RETURNS
Returns the number of bits received from the reader representing the ID. The return count represents how many bits in the buffer are valid ID bits,

## SEE ALSO

