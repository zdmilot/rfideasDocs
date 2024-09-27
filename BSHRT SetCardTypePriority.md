# BSHRT SetCardTypePriority [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark131">&zwnj;</a>Windows, Linux, Mac<a name="bookmark132">&zwnj;</a></p>

## API Call
BSHRT SetCardTypePriority(WORD cardType, BSHRT priority)
## DESCRIPTION
Set the Card Type 0x0000..0xFFFF for the active configuration. See #define CARDTYPE_&lt;name&gt; in pcProxAPI.h

## PARAMETERS
Sixteen bit card type, and priority bit.

## RETURNS
TRUE success, FALSE failed, disconnected, or non pcProx Plus reader.

## SEE ALSO
[GetCardType() ](GetCardType() .md), [SetActConfig() ](SetActConfig() .md)
