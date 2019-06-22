# color
Colors Package for Windows.

> USAGE:  Copy this file into **site-packages** folder or into a **soft-linked** folder and **import**


# kc_colors

 - Version kc_colors1.0

 - Author: Krishna Chouhan
 - E-mail: krishna.chouhan34@gmail.com

 - About:
   - This module was suppose to be help color the outputs.
   
   - In case of command prompt, this should work without any problem.
   
   - In case if its not working in windows-10: 
     - goto REGEDIT
     - HKEY_CURRENT_USER
       - Add a DWORD value
         - name: VirtualTerminalLevel
         - value: 1
     - for Details see the issue: https://github.com/ytdl-org/youtube-dl/issues/15758
                 - Image: https://user-images.githubusercontent.com/5589855/36943005-11e41fe2-1f36-11e8-9401-7ac40d300f10.png
 - Known Issues:
   - Doesn't works well with tqdm.


## Usage:

```

import kc_colors

kc_colors._Warning_B('Deprecated use!')
```
