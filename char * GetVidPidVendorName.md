# char * GetVidPidVendorName [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark90">&zwnj;</a>Windows, Linux, Mac<a name="bookmark91">&zwnj;</a></p>

## API Call
char * GetVidPidVendorName(void)
## DESCRIPTION
Return the VendorName string for the active device. This comes from the optional pcProxVidPid.txt file.

## PARAMETERS
None

## RETURNS
Returns the pointer to a static buffer. For non pcProx devices a pointer to an empty string is returned.

## SEE ALSO

