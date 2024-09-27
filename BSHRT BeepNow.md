# BSHRT BeepNow [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark0">&zwnj;</a>Windows, Linux, Mac<a name="bookmark1">&zwnj;</a></p>

## API Call
BSHRT BeepNow(BYTE count, BSHRT longBeep)
## DESCRIPTION
Call this function with the number of desired short or long beeps. This API is thread-safe.

## PARAMETERS
count 1..N beeps, longBeep = TRUE, short beep = FALSE. Range 1..5 short beeps and 1..2 long beeps.

## RETURNS
TRUE = Success / FALSE = Failure / user defined Unsupported.

## SEE ALSO
[pcSwipeGetBeeper() ](pcSwipeGetBeeper() .md), [pcSwipeSetBeeper() ](pcSwipeSetBeeper() .md)
