# BSHRT getActiveCardData_byte [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark203">&zwnj;</a>Windows, Linux, Mac<a name="bookmark204">&zwnj;</a></p>

## API Call
BSHRT getActiveCardData_byte(short index)
## DESCRIPTION
After the call to getActiveCardData() which reads the card scan count, CSN, and card ID into an internal buffer, the bytes from the buffer are retrieved using this function.

## PARAMETERS
Index into byte buffer.

## RETURNS
Returns 0..FF = Error or no card read. Or return 0 if index is out of range. and return unsupported code for non pcProx devices.

## SEE ALSO

