# DWORD GetFirmwareVersion [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark44">&zwnj;</a>Windows, Linux, Mac<a name="bookmark45">&zwnj;</a></p>

## API Call
DWORD GetFirmwareVersion(short hardware, short module)
## DESCRIPTION
Some devices have multiple firmware versions to report. This function returns

## PARAMETERS
Hardware 0 = Main CPU, 1 = Aux Cpu, 2-FF unused Module 0 = Application, 1 = Bootloader, 2 = Modem

## RETURNS
0x000001 .. 0xFFFFFF for valid versions, 0 or code set by SetUnsupportedProductErrorCode() indicates unavailable.

## SEE ALSO

