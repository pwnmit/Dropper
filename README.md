#For current USER
reg add "HKCU\Software\Microsoft\Windows\CurrentVersion\Run" /v MySoftware /t REG_SZ /d "\"C:\Program Files\MySoftware\app.exe\"" 

#For entire MACHINE
 reg add "HKLM\Software\Microsoft\Windows\CurrentVersion\Run" /v MySoftware /t REG_SZ /d "\"C:\Program Files\MySoftware\app.exe\"" /f 
