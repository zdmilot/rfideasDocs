# const char * pcSwipeGetTrackFieldOffset [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark342">&zwnj;</a>Windows, Linux, Mac</p>

## API Call
const char * pcSwipeGetTrackFieldOffset(WORD track,
## DESCRIPTION
This calls GetTrackData() and parses the desired field and offset up to the the length or termination byte. If the field can not be found then the beginning of the track is returned.

## PARAMETERS
Track 1,2,3, field number 1..N, offset in bytes to skip after finding the field, the length in bytes to return unless the termination byte is found first. ToAscii flag can be set to return data in ASCII format.

## RETURNS
BYTE * up to 256 bytes. Buffer of nulls returned on any error.

## SEE ALSO

