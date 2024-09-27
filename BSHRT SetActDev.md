# BSHRT SetActDev [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark122">&zwnj;</a>Windows, Linux, Mac<a name="bookmark123">&zwnj;</a></p>

## API Call
BSHRT SetActDev(short iNdx)
## DESCRIPTION
Set the active device. Up to MAXDEVSOPEN devices may be present. The selected device is the active device that ReadCfg() and WriteCfg() operate on.

## PARAMETERS
Set the active device where iNdx selects a new device for processing. This does not require a WriteCfg() to be performed as it is only selecting the device to which we are communicating with via the library.

## RETURNS
TRUE = Success / FALSE = Failure index out of range

## SEE ALSO

