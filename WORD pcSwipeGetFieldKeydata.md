# WORD pcSwipeGetFieldKeydata [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark315">&zwnj;</a>Windows, Linux, Mac<a name="bookmark316">&zwnj;</a></p>

## API Call
WORD pcSwipeGetFieldKeydata(WORD field, BSHRT kindex)
## DESCRIPTION
Get the keystroke data for a given field. In USB HID keyboard emulation each key is 2 bytes the code and shift modifiers. Even key index bytes are the scan code and odd key index bytes are the shift modifiers.

## PARAMETERS
field number 1..N, key index, value.

## RETURNS
return value of key.

## SEE ALSO

