# Hybrid-Notifications
Display notifactions while device is hybrid joining, then restart at end
Toast notifications instead of full screen blocks 
Scheduled tasks to run regularly === https://oofhours.com/2020/05/19/renaming-autopilot-deployed-hybrid-azure-ad-join-devices/
Scheduled task to display notifications to user === https://byteben.com/bb/deploy-service-announcement-toast-notifications-in-windows-10-with-memcm/
Custom protocol to restart device === https://www.imab.dk/windows-10-toast-notification-script/
Replacement for UserESP === https://docs.microsoft.com/en-us/troubleshoot/mem/intune/understand-troubleshoot-esp
Also recommend script to speed up AD Connect sync
Win32 install cmd: powershell.exe -noprofile -executionpolicy bypass -file .\Hybrid-Notifications.ps1
Win32 uninstall: cmd.exe /c del %ProgramData%\Microsoft\RenameComputer\Hybrid-Notifications.ps1.tag
Win32 detection: %ProgramData%\Dell\Hybrid-Notifications\Hybrid-Notifications.ps1.tag
