
# Guide for share files with Resilio Sync

This is guide and testground for syncing file with Resilio Sync.

  https://www.resilio.com/individuals/

  https://www.resilio.com/platforms/desktop/

  https://help.resilio.com/hc/en-us/articles/205505969-How-to-Silently-Install-Resilio-Sync


## Installing in Windows

Quick version:
Download 'Resilio-Sync_x64.exe' and install it.
  https://download-cdn.resilio.com/stable/windows64/Resilio-Sync_x64.exe


Here is batch script for downloading and installing Resilio Sync.

```bat
C:

cd "%HOMEDRIVE%%HOMEPATH%\Downloads"

PowerShell -Command "& {$client = new-object System.Net.WebClient; $client.DownloadFile('https://download-cdn.resilio.com/stable/windows64/Resilio-Sync_x64.exe','.\Resilio-Sync_x64.exe')}"

Resilio-Sync_x64.exe /PERFORMINSTALL /S
```



## Installing in Linux (deb)

  TODO

## Installing in BSD

  TODO

## Installing in Mac OS X

  TODO

## Installing in Android

  TODO

## Installing in iOS

  TODO


