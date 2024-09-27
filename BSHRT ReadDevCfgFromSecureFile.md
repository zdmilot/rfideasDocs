# BSHRT ReadDevCfgFromSecureFile [Traffic]

Works with Unknown platform

## API Call
BSHRT ReadDevCfgFromSecureFile(char* szFileName)
## DESCRIPTION
It will check whether the secure Key which is present in the file is valid or not. Then it will Open and read an ASCII file and load the setting into the library memory. The device can be flashed by calling WriteCfg(). This function reads files created with the WriteDevCfgToSecureFile() function.

## PARAMETERS
szFileName file name that may include complete path to the file name.

## RETURNS
TRUE / Success secure key is valid and ASCII file was read. FALSE - secure key is invalid, file could not be read.

## SEE ALSO

