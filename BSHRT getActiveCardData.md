# BSHRT getActiveCardData [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark201">&zwnj;</a>Windows, Linux, Mac<a name="bookmark202">&zwnj;</a></p>

## API Call
BSHRT getActiveCardData(void)
## DESCRIPTION
Read the Active Card Data. This returns three main pieces of informations: The ScanCount, Card Serial Number (CSN), and Card ID (ID). The Scan count is a one byte value that starts at zero duing powerup and increments and wraps from 255 back to zero. The CSN is preceded by the byte count of the CSN size. The ID is preceded by the Bit Count of the card ID. Here is an example of the third card read, scan count = 3, the CSN is 0x12,0x34,0x56,0x78 and a 26 bit ID

## PARAMETERS
None

## RETURNS
Returns TRUE = Success, FALSE Error or no card read or function not supported in Firmware.

## SEE ALSO

