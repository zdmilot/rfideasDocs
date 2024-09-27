# WORD pcSwipeGetBeeper [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark308">&zwnj;</a>Windows, Linux, Mac<a name="bookmark309">&zwnj;</a></p>

## API Call
WORD pcSwipeGetBeeper(WORD i)
## DESCRIPTION
Get the beeper count for one of the 3 states. SEE PCSWIPE_STATE_*

## PARAMETERS
state see #define PCSWIPE_STATE_

## RETURNS
0..N for short beeps bit 7 set for long beeps 0,1,2,3,4,80,0x81,0x82

## SEE ALSO
[pcSwipeSetBeeper() ](pcSwipeSetBeeper() .md)
