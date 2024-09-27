# BSHRT SetBprRlyCtrl [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark130">&zwnj;</a>Windows, Linux, Mac</p>

## API Call
BSHRT SetBprRlyCtrl(tsBprRlyCtrl *psBRCtrl)
## DESCRIPTION
Set beeper (and relay on OEM W2-USB readers) controls.

## PARAMETERS
psBRCtrl pointer to structure containing new beeper/relay control bit. Use WriteCfg() to update the hardware outputs.

## RETURNS
TRUE = Success / FALSE = Failure

## SEE ALSO
[GetBprRlyCtrl() ](GetBprRlyCtrl() .md)
