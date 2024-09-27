# bool ReadSecureData [Traffic]

Works with Unknown platform

## API Call
bool ReadSecureData(BYTE *headerBuffer, BYTE *dataBuffer)
## DESCRIPTION
Read the configuration as requested in header(blob details: Type, config, length, BSV).

## PARAMETERS
headerBuffer pointer (reference) to character buffer to send the blob details to reader* dataBuffer pointer (reference) to character buffer to get the data present on reader*

## RETURNS
Returns true on success and false on failure.

## SEE ALSO

