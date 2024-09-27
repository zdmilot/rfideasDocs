# BSHRT SetFlags3 [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark147">&zwnj;</a>Windows, Linux, Mac<a name="bookmark148">&zwnj;</a></p>

## API Call
BSHRT SetFlags3(tsCfgFlags3 *psCfgFlgs)
## DESCRIPTION
Set the values from the data structure into the device. This does NOT write the configuration items to the device, just to library memory. pcSwipe only uses the bUseNumKP flag of this structure.

## PARAMETERS
psCfgFlgs3 pointer to structure to write Configuration Flags3 information.

## RETURNS
TRUE = Success / FALSE = Failure

## SEE ALSO

