# BSHRT SetDevTypeSrch [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark139">&zwnj;</a>Windows, Linux, Mac<a name="bookmark140">&zwnj;</a></p>

## API Call
BSHRT SetDevTypeSrch(short iSrchType)
## DESCRIPTION
Set the type of device interface USB and/or Serial to search for when connecting using USBConnect().

## PARAMETERS
iSrchType 0=USB only, 1=Serial (RS-232) Only, -1=Both USB and Serial

## RETURNS
TRUE = Success / FALSE = Failure (invalid parameter) Default is both devices USB and Serial.

## SEE ALSO
[ComConnect() ](ComConnect() .md)
