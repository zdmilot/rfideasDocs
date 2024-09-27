# void SetMarkerFunction [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark166">&zwnj;</a>Windows, Linux, Mac</p>

## API Call
void SetMarkerFunction(RFPRXLOG pfLog)
## DESCRIPTION
Set function to be used as a callback to log errors.

## PARAMETERS
The pfLog should have the prototype of pfCallBackLog(char szBuf, int ilen);

## RETURNS
void

## SEE ALSO

