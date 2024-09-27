# char getDevName_char [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark241">&zwnj;</a>Windows, Linux, Mac<a name="bookmark242">&zwnj;</a></p>

## API Call
char getDevName_char(short index)
## DESCRIPTION
getDeviceName character by character. When the index is zero the device name is gathered from the device. The user may then read the rest of the buffered string character by character.

## PARAMETERS
index value 0 through 126 inclusive.

## RETURNS
Returns the byte at buffer[index] from the GetDevName() function call.

## SEE ALSO

