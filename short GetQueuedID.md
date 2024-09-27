# short GetQueuedID [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark77">&zwnj;</a>Windows, Linux, Mac<a name="bookmark78">&zwnj;</a></p>

## API Call
short GetQueuedID(short clearUID, short clearHold)
## DESCRIPTION
Read the Queued ID data from the reader.

## PARAMETERS
If clearUID is set then the card, and overrun counters will be

## RETURNS
Returns TRUE success, or FALSE failed (perhaps function is not available in the firmware). IF TRUE use GetQueuedID_index() to get the rest of the data from the library.

## SEE ALSO
[GetQueuedID_index(short index) ](GetQueuedID_index(short index) .md), [GetQueuedID_index() ](GetQueuedID_index() .md)
