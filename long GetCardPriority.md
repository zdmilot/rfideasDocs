# long GetCardPriority [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark30">&zwnj;</a>Windows, Linux, Mac</p>

## API Call
long GetCardPriority(void)
## DESCRIPTION
Get the Card Type Priority for the active configuration. A long integer is used to detect errors. The Priority is 0 or 1, and a -1 indicates an error.

## PARAMETERS
None

## RETURNS
0 = Low priority, 1 = high priority, -1 error.

## SEE ALSO
[SetCardTypePriority() ](SetCardTypePriority() .md), [GetActConfig() ](GetActConfig() .md)
