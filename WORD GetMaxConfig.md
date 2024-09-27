# WORD GetMaxConfig [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark71">&zwnj;</a>Windows, Linux, Mac<a name="bookmark72">&zwnj;</a></p>

## API Call
WORD GetMaxConfig(void)
## DESCRIPTION
Get number of pcProx Plus Reader Configurations. For pcProx Plus dual frequency readers this will be 1 or more and 0 for Legacy non pcProx Plus readers.

## PARAMETERS
none

## RETURNS
0, 1..N -- 0 for pcProx, 1 to N where N is max N-1 Config for pcProx Plus.

## SEE ALSO
[GetActConfig() ](GetActConfig() .md)
