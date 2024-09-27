# BSHRT GetLibVersion [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark69">&zwnj;</a>Windows, Linux, Mac<a name="bookmark70">&zwnj;</a></p>

## API Call
BSHRT GetLibVersion(short* piVerMaj,
## DESCRIPTION
Get the version of the library code. This does not communicate with any device. It returns constants from the DLL or Linux shared library.

## PARAMETERS
piVerMaj pointer or NULL (reference) to integer to receive the major version piVerMin pointer or NULL (reference) to integer to receive the minor version piVerDev pointer or NULL (reference) to integer to receive the build version

## RETURNS
Null pointers will not be used to return data. Returns Always TRUE / Success

## SEE ALSO

