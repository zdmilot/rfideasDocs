# long GetQueuedID_index [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark79">&zwnj;</a>Windows, Linux, Mac<a name="bookmark80">&zwnj;</a></p>

## API Call
long GetQueuedID_index(short index)
## DESCRIPTION
Return specific part of the data read by GetQueuedID() GetQueuedID() actually gets data from the reader,

## PARAMETERS
index 0..35

## RETURNS
index 0..31 = Bytes 0..31 of the UserID index 32 = short Number of bits read 0-256.

## SEE ALSO

