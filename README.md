# usb-rubber-ducky--mimikatz-in-mem
USB-Rubber-Ducky Payload - Mimikatz in Memory w UAC Bypass

This is a pyalod for the USB Rubber Ducky. It uses PowerShell to download and execute Mimikatz in memory.

For in memory Mimikatz this uses PowerSploit's (Joe Bialek's) Invoke-Mimikatz.ps1. For UAC bypass / admin prompt this uses Darren Kitchen's payload from here: https://forums.hak5.org/index.php?/topic/30100-payload-faster-uac-bypass/

Feature : Status
------
    Get Admin command prompt (required for Mimikatz) : COMPLETE
    Download and execute Mimikatz in Memory : COMPLETE
    Option to pipe output to an hidden data stream on disk : COMPLETE
    Option to pipe output over network (GET requests?) : THINKING ABOUT IT
