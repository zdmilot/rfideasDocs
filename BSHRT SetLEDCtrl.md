# BSHRT SetLEDCtrl [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark162">&zwnj;</a>Windows, Linux, Mac<a name="bookmark163">&zwnj;</a></p>

## API Call
BSHRT SetLEDCtrl(tsLEDCtrl *psLEDCtrl)
## DESCRIPTION
Controls LED color red, green, or amber.

## PARAMETERS
psLEDCtrl pointer to structure containing new LED control information. if bVolatile is true then this does NOT write the configuration

## RETURNS
TRUE = Success / FALSE = Failure

## SEE ALSO

