# dotfiles-ws
Windows Registry Editor Version 5.00

[HKEY_CURRENT_USER\Control Panel\Accessibility\Keyboard Response]
"AutoRepeatDelay"="320"
"AutoRepeatRate"="16"
"DelayBeforeAcceptance"="0"
"BounceTime"="0"
"Flags"="59"


```posh
Set-Location "HKCU:\Control Panel\Accessibility\Keyboard Response"
Set-ItemProperty -Name AutoRepeatDelay       -Value 320
Set-ItemProperty -Name AutoRepeatRate        -Value 16
Set-ItemProperty -Name DelayBeforeAcceptance -Value 0
Set-ItemProperty -Name BounceTime            -Value 0
Set-ItemProperty -Name Flags                 -Value 59
```
