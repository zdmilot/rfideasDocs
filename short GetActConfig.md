# short GetActConfig [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark16">&zwnj;</a>Windows, Linux, Mac<a name="bookmark17">&zwnj;</a></p>

## API Call
short GetActConfig(void)
## DESCRIPTION
Get the active configuration ( 0..N ) of the pcProx Plus. For devices that only have one configuration this will return 0. All devices have one configuration, so zero is always valid.

## PARAMETERS
None

## RETURNS
0, 1, 2..N

## SEE ALSO
[GetMaxConfig() ](GetMaxConfig() .md)
