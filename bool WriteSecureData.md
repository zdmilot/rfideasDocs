# bool WriteSecureData [Traffic]

Works with Unknown platform

## API Call
bool WriteSecureData(BYTE *blobBuffer, int blobLen)
## DESCRIPTION
Write the configuration as requested in header(blob details: Type, config, length, BSV).

## PARAMETERS
blobBuffer pointer (reference) to character buffer to send the blob details and data to reader* bloblen is the interger value for length of buffer whose pointer (reference) is sent.

## RETURNS
Returns true on success and false on failure.

## SEE ALSO

