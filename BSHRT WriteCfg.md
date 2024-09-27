# BSHRT WriteCfg [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark186">&zwnj;</a>Windows, Linux, Mac<a name="bookmark187">&zwnj;</a></p>

## API Call
BSHRT WriteCfg(void)
## DESCRIPTION
A call to this function writes all configuration information in the library memory space to the device for non-volatile storage. Any changed parameters take effect immediately after WriteCfg(). The actual write internally within the device is not done until all critical pending actions are complete. This may take up to two seconds, typically 1200 msec to complete.

## PARAMETERS
None

## RETURNS
TRUE = Success / FALSE = Failure

## SEE ALSO

