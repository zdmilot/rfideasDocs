# BSHRT GetTimeParms [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark86">&zwnj;</a>Windows, Linux, Mac<a name="bookmark87">&zwnj;</a></p>

## API Call
BSHRT GetTimeParms(tsTimeParms *psTimeParms)
## DESCRIPTION
Get device timing information. Times are in milliseconds, keyboard times have a granularity of 4ms, card times have 48ms.

## PARAMETERS
psTimeParms pointer to structure containing timing information from device.

## RETURNS
TRUE = Success / FALSE = Failure

## SEE ALSO

