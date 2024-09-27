# BYTE getActiveID_byte [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark207">&zwnj;</a>Windows, Linux, Mac<a name="bookmark208">&zwnj;</a></p>

## API Call
BYTE getActiveID_byte(short index)
## DESCRIPTION
This function should be called after getActiveID32() This function will return the byte at the give index 0..31 Index 0 is the Least Significant Byte holding Bits 0..7

## PARAMETERS
index value 0 through 7 inclusive.

## RETURNS
Returns the byte at buffer[index] from the card read by GetActiveID() or GetActiveID32() or getActiveID32()

## SEE ALSO

