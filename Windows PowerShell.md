
not to be confused with [[PowerShell]].

comes with windows.
# basic commands
### cd
### mkdir
### ni
### ri



# customizing
to change background color and text color scheme, right click on top bar and change defaults

to change default start up folder or specific color preferences run: `echo $profile` to determine where Windows expects your profile file to exist. Navigate there ([[Windows PowerShell#basic commands#cd|cd]]), making any directories along the way ([[Windows PowerShell#basic commands#mkdir|mkdir]]), then making the profile file ([[Windows PowerShell#basic commands#ni|ni]]), then opening the directory in an editor ([[Visual Studio Code#code command|code]]) to change your profile file. 

```
Set-Location C:\your\default\directory\
Set-PSReadLineOption -Colors @{ String = 'Gray' } (this specifically changes "strings" to Gray)
```