# BSHRT pcSwipeSetBeeper [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark347">&zwnj;</a>Windows, Linux, Mac<a name="bookmark348">&zwnj;</a></p>

## API Call
BSHRT pcSwipeSetBeeper(WORD i, WORD count, BSHRT longBeep)
## DESCRIPTION
Set the beeper length/count color for one of the 2 states, PCSWIPE_STATE_GOOD, PCSWIPE_STATE_BAD. SEE BEEPER_STATE_*

## PARAMETERS
Set value = BEEPER_STATE, count, long beep flag

## RETURNS
TRUE = Success / FALSE = Failure

## SEE ALSO
[pcSwipeGetBeeper() ](pcSwipeGetBeeper() .md)
