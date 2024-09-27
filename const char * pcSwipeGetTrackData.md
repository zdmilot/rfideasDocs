# const char * pcSwipeGetTrackData [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark336">&zwnj;</a>Windows, Linux, Mac<a name="bookmark337">&zwnj;</a></p>

## API Call
const char * pcSwipeGetTrackData(WORD track, BSHRT toAscii)
## DESCRIPTION
Get the data from the track. All data is returned including field separators and sentinels and the LRC.

## PARAMETERS
Track 1,2,3

## RETURNS
BYTE * to 256 bytes. Buffer of nulls returned on any error.

## SEE ALSO
[pcSwipeClearDataAvailable() ](pcSwipeClearDataAvailable() .md), [pcSwipeIsDataAvailable() ](pcSwipeIsDataAvailable() .md), [GetActiveID() ](GetActiveID() .md)
