# USBlyzer-Licence-fix
Fix for USBlyzer which licence cannot be buyed

PowerShell command to run:  
``` PowerShell
reg delete "HKEY_CURRENT_USER\Software\USBlyzer\General" /v CfgId /f
```

## How to reset free-trial manually

Go to Windows register path: `Computer\HKEY_CURRENT_USER\Software\USBlyzer\General`

Delete `CfgId` key.
