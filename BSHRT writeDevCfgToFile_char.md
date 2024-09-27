# BSHRT writeDevCfgToFile_char [Traffic]

Works with <p class="s1" style="padding-top: 2pt;padding-left: 5pt;text-indent: 0pt;text-align: left;"><a name="bookmark467">&zwnj;</a>Windows, Linux, Mac<a name="bookmark468">&zwnj;</a></p>

## API Call
BSHRT writeDevCfgToFile_char(short index, char c)
## DESCRIPTION
The C# interface to WriteDevCfgToFile(). The file name is sent one character at a time at the given index, at index 255 the function WriteDevCfgToFile is called with it&#39;s return value.

## PARAMETERS
index 0..255. 255 trigger I/O call. When index is 0 internal filename buffer is zeroed out.

## RETURNS
<br/>

## SEE ALSO
[readDevCfgFmFile_char() ](readDevCfgFmFile_char() .md), [ReadDevCfgFmFile() ](ReadDevCfgFmFile() .md)
