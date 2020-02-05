# EmoCheckPowerShell

Author: Zane Gittins

## Description 

PowerShell implementation of JPCerts EmoCheck. Searches for Emotet based on process names. All credit goes to JPCERT from this PowerShell code was adapted.

Detects Emotet based on the unique way Emotet chooses it's process name from the following keywords:

```plaintext
duck,mfidl,targets,ptr,khmer,purge,metrics,acc,inet,msra,symbol,driver
sidebar,restore,msg,volume,cards,shext,query,roam,etw,mexico,basic,url
createa,blb,pal,cors,send,devices,radio,bid,format,thrd,taskmgr,timeout
vmd,ctl,bta,shlp,avi,exce,dbt,pfx,rtp,edge,mult,clr,wmistr,ellipse,vol
cyan,ses,guid,wce,wmp,dvb,elem,channel,space,digital,pdeft,violet,thunk
```

## Credits

* https://github.com/JPCERTCC/EmoCheck