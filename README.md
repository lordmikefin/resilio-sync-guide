
# Guide for share files with Resilio Sync

This is guide and testground for syncing file with Resilio Sync.

  https://www.resilio.com/individuals/

  https://www.resilio.com/platforms/desktop/

  https://help.resilio.com/hc/en-us/articles/205505969-How-to-Silently-Install-Resilio-Sync


## Read only key for my test share

This is permanent key for connecting my test share.
I DO NOT recommend this method.

You should always use temporaty link for sharing. Temporary links will expire.
It is safer.

Read only key:
```
B66VIKY3A34K6UE3L3W44ZGRBWEM3MSBK
```

Read more about [Sync folder with a key](sync/with-key.md)


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

"%HOMEDRIVE%%HOMEPATH%\AppData\Roaming\Resilio Sync\Resilio Sync.exe"
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


