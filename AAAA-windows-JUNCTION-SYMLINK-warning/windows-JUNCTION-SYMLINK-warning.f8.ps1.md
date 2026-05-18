AAAA-windows-JUNCTION-SYMLINK-warning

# some tools have bugs when i MOVE-JUNCTION-SYMLINk--should-rather-use-LNK-files

# junctions can be deleted using wexplorer gui

# warning ..windows do, by themselves, patch lnk files




# 20260518   HOPE FOR Junction TO  Junction

moving
not split
1 dir
junctioned from elsewhere


# before transaction

cmd /c dir /a   "C:\Users\marti\AppData\Roaming\Code\User\" | clip

 Directory of C:\Users\marti\AppData\Roaming\Code\User

05/18/2026  18:41    <DIR>          globalStorage
05/18/2026  18:19    <DIR>          History
04/11/2025  10:25             3,118 keybindings.json
12/30/2025  10:58    <DIR>          profiles
05/01/2026  12:24            16,126 settings.json
05/02/2022  22:43    <JUNCTION>     snippets [C:\Users\marti\OneDrive\roam-code-us-snipp\]
05/18/2026  11:48    <DIR>          workspaceStorage
               7 Dir(s)  68,395,401,216 bytes free

snippets is a junction to a dir in OneDrive,


# after transaction

05/02/2022  22:43    <JUNCTION>     snippets

 [C:\Users\marti\OneDrive\roam-code-us-snipp\]
is a junction to \Users\marti\OneDrive\Dokumenty\roam-code-us-snipp\




# tests

cmd /c dir /a   "C:\Users\marti\AppData\Roaming\Code\User\snippets"



related
C:\Users\marti\OneDrive\Dokumenty\Code-User-snippets-markdown.json.publ.md
will be moved tooo


"C:\Users\marti\OneDrive\roam-code-us-snipp"
"C:\Users\marti\OneDrive\

# omg.. a name  mangled   by ai   ..  Dokuments__s__ERROR   __k__ __s__ 
english name is Documents, 
i am not German // Dokuments__s__ERROR
i am Czech  
windows forced us to use czech Dokumenty   //// __y__ yyyyyy


\roam-code-us-snipp"





notepad C:\Users\marti\OneDrive\Dokumenty\AAAA-windows-JUNCTION-SYMLINK-warning\windows-JUNCTION-SYMLINK-warning.f8.ps1
close all vscode

git push

move the dir

###robo Dokuments__s__ERROR
robo Dokumenty

git push

explorer delete the junction


cmd /c mkl





cd .\dotfiles

. "C:\Program Files\WindowsApps\Microsoft.SysinternalsSuite_2022.11.1.0_x64__8wekyb3d8bbwe\Tools\junction.exe"
C:\Pf\WindowsApps\Microsoft.SysinternalsSuite_2022.11.1.0_x64__8wekyb3d8bbwe\Tools\junction.exe ".\dotfiles"



C:\Users\marti\OneDrive\dotfiles\dotfiles: UNKNOWN MICROSOFT REPARSE POINT



Junction v1.07 - Creates and lists directory links
Copyright (C) 2005-2016 Mark Russinovich
Sysinternals - www.sysinternals.com

The first usage is for displaying reparse point information, the
second usage is for creating









cmd /c dir /al /s
cd ..
cd c:\pf\git
cmd /c dir /al






exit

https://superuser.com/questions/167076/how-can-i-delete-a-symbolic-link

https://learn.microsoft.com/en-us/answers/questions/63800/cannot-delete-junction-that-points-to-directory-th.html



XXXXX erroneously deletes symlinks to full directories in the path of a file being deleted
#9419
akuktin opened this issue on Apr 22, 2020 · 4 comments · Fixed by #9457



