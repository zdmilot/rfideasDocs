# BSHRT ReadCfg [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark104">&zwnj;</a>Windows, Linux, Mac<a name="bookmark105">&zwnj;</a></p>

## API Call
BSHRT ReadCfg(void)
## DESCRIPTION
A call to this function pulls the device configuration information into the library memory space to be manipulated by the Get*() and Set*() functions. After altering the data the user must call WriteCfg() to write the changes back to device so they can take effect.

## PARAMETERS
None

## RETURNS
TRUE = Success / FALSE = Failure

## SEE ALSO

