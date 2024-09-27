# char getPartNumberString_char [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark292">&zwnj;</a>Windows, Linux, Mac<a name="bookmark293">&zwnj;</a></p>

## API Call
char getPartNumberString_char(short index)
## DESCRIPTION
Read the device part number string character by character. This is a 24 (MAXPRODUCTNAMESZ) character string such as &quot;MS0-00M1AKU&quot; and null terminated if less then 24 characters are used. When the index is zero, the serial number

## PARAMETERS
index 0 through 23 inclusive.

## RETURNS
Returns the character of index position of the part number string.

## SEE ALSO

