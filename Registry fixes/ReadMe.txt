Windows 10 loads default theme colors from
[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Themes\DefaultColors]
after every lock/sleep/hibernate/crash. 
Make a backup of that key, take ownership of it, and then delete that whole key (defualtcolors). 
[EXPERIMENTAL:  THEN REPLACE WITH THE REGISTRY KEY.]

Apply the Dark.reg file fix for dark themes and reboot.