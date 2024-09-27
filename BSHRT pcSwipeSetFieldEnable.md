# BSHRT pcSwipeSetFieldEnable [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark349">&zwnj;</a>Windows, Linux, Mac<a name="bookmark350">&zwnj;</a></p>

## API Call
BSHRT pcSwipeSetFieldEnable(WORD field, WORD enable)
## DESCRIPTION
Enable the user field of the active device. Enable fields will keystroke out delimiter data, disabled fields will not.

## PARAMETERS
user field number 1..11, TRUE | FALSE

## RETURNS
TRUE = Success / FALSE = Failure

## SEE ALSO
[WriteCfg() ](WriteCfg() .md)
