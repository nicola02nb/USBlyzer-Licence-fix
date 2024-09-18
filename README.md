# USBlyzer-Licence-fix
Fix for USBlyzer licence which cannot be buyed (http://www.usblyzer.com/purchase.htm?ref=USBlyzer&src=rd&ver=2.1)

PowerShell command to run:  
``` PowerShell
reg delete "HKEY_CURRENT_USER\Software\USBlyzer\General" /v CfgId /f
```

## How to reset free-trial manually

Go to Windows register path: `Computer\HKEY_CURRENT_USER\Software\USBlyzer\General`

Delete `CfgId` key.
