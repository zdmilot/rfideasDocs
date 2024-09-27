# BSHRT pcSwipeSetActiveID [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark345">&zwnj;</a>Windows, Linux, Mac<a name="bookmark346">&zwnj;</a></p>

## API Call
BSHRT pcSwipeSetActiveID(WORD track,
## DESCRIPTION
Set the area of the magstripe card that GetActiveID should return. This makes the pcSwipe backwards compatible with the pcProx API function Call GetActiveID() / GetActiveID32(). It is recommended to use pcSwipeGetTrackData_BYTE() for newer projects, since GetActiveID

## PARAMETERS
Track 1,2 or 3, field number, offset within field.

## RETURNS
TRUE = Success / FALSE = Failure.

## SEE ALSO
[GetActiveID() ](GetActiveID() .md), [GetActiveID32() ](GetActiveID32() .md)
