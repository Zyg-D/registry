If your Logon screen (a.k.a. sing-in screen) is different from your Lock screen, delete this registry key:

    HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Authentication\LogonUI\Creative\<your__ SID>

`<your__SID>` can be found under key 

    HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ProfileList
    
see values `ProfileImagePath`.
