# BSHRT setCfgFlags3_bUseNumKP [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark408">&zwnj;</a>Windows, Linux, Mac</p>

## API Call
BSHRT setCfgFlags3_bUseNumKP(short value)
## DESCRIPTION
C# interface for safe code. Set CfgFlags3 member&#39;s bUseNumKP value. You must call ReadCfg() first. This function calls SetFlags3() internally. When true digit are keystroked from the numeric keypad and not the top horizontal row of digits. The digits are the same but the USB scan codes are different for each keyboard key.

## PARAMETERS
Set member name to value of short.

## RETURNS
BSHRT value from GetFlags3() if failed or SetFlags3().

## SEE ALSO

