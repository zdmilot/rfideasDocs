# long pcSwipeGetSystemInternalCount [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark334">&zwnj;</a>Windows, Linux, Mac</p>

## API Call
long pcSwipeGetSystemInternalCount(int index)
## DESCRIPTION
This returns internal pcSwipe diagnostic counters. An index of 0 returns the number of watchdog resets. An index of 1 returns the number of stack underflows. An index of 2 returns the number of stack overflows. An index of 3 returns the number of times the unit self-corrected its flash memory. If power is removed during flash writes the flash memory checksum is not updated, the

## PARAMETERS
None

## RETURNS
DWORD 0..4,294,967,295

## SEE ALSO

