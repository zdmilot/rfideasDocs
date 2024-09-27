# BSHRT pcSwipeSetFieldShowLRC [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark363">&zwnj;</a>Windows, Linux, Mac<a name="bookmark364">&zwnj;</a></p>

## API Call
BSHRT pcSwipeSetFieldShowLRC(WORD field, BSHRT enable)
## DESCRIPTION
Set the field Show LRC, when set the LRC (Logical Redundancy Check) byte will be show in hex. Typically this is off. The LRC byte is

## PARAMETERS
user field number 1..11, TRUE | FALSE

## RETURNS
TRUE = Success / FALSE = Failure

## SEE ALSO
[WriteCfg() ](WriteCfg() .md)
