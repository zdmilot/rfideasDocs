# char getVidPidVendorName_char [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark302">&zwnj;</a>Windows, Linux, Mac<a name="bookmark303">&zwnj;</a></p>

## API Call
char getVidPidVendorName_char(short index)
## DESCRIPTION
Return the VendorName string for the active device. This comes from the optional pcProxVidPid.txt file.

## PARAMETERS
index value 0 through 31 inclusive.

## RETURNS
Returns the character at buffer[index] from the GetVidPidVendorName() function call.

## SEE ALSO

