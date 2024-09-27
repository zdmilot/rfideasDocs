# BSHRT USBDisconnect [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark180">&zwnj;</a>Windows, Linux, Mac<a name="bookmark181">&zwnj;</a></p>

## API Call
BSHRT USBDisconnect(void)
## DESCRIPTION
This function closes the open handle to ALL USB device(s) and/or open serial port(s). It may be called at any time even if USBConnect() has not been called. It is good practice is to call USBDisconnect before calling any Connect function to clear any pending errors.

## PARAMETERS
None

## RETURNS
Always TRUE = Success

## SEE ALSO

