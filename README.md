# Hybrid-Notifications

mark_burns@dell.com

v2 - Silent alarm functionality to get through Focus Assist

v3 - 365 day scheduled task duration

v4 - 2 mins and hide notifications if wwahost is running always

Display notifactions while device is hybrid joining, then restart at end

Toast notifications instead of full screen blocks

Speeds up hybrid join by triggering task

![image](https://user-images.githubusercontent.com/88446677/185159523-9324d589-c35b-450b-91c4-199e9b073f47.png)

Scheduled tasks to run regularly === https://oofhours.com/2020/05/19/renaming-autopilot-deployed-hybrid-azure-ad-join-devices/

Scheduled task to display notifications to user === https://byteben.com/bb/deploy-service-announcement-toast-notifications-in-windows-10-with-memcm/

Custom protocol to restart device === https://www.imab.dk/windows-10-toast-notification-script/

Replacement for UserESP === https://docs.microsoft.com/en-us/troubleshoot/mem/intune/understand-troubleshoot-esp

Also recommend script to speed up AD Connect sync - https://github.com/markmburns/SyncNewAutopilotComputersToAAD

Win32 install cmd: powershell.exe -noprofile -executionpolicy bypass -file .\Hybrid-Notifications.ps1

Win32 uninstall: cmd.exe /c del %ProgramData%\Dell\Hybrid-Notifications\Hybrid-Notifications.ps1.tag

Win32 detection: %ProgramData%\Dell\Hybrid-Notifications\Hybrid-Notifications.ps1.tag
