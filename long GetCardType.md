# long GetCardType [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark31">&zwnj;</a>Windows, Linux, Mac<a name="bookmark32">&zwnj;</a></p>

## API Call
long GetCardType(void)
## DESCRIPTION
Get the Card Type 0x0000..0xFFFE for the given configuration. See #define CARDTYPE_&lt;name&gt; in pcProxAPI.h

## PARAMETERS
None

## RETURNS
0..0xFFFE for valid card types. -1 for error, disconnected, or non pcProx Plus reader.

## SEE ALSO
[SetCardTypePriority() ](SetCardTypePriority() .md), [GetActConfig() ](GetActConfig() .md)
