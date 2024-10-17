**Установка имени и e-mail коммиттера**  
$ git config --global user.name "Surname, Name"  
$ git config --global user.email "your_mail@domain.ru"  

**Установить редактор**  
$ git config --global core.editor "'C:/Program Files/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"  

**Установить ветку по-умолчанию**  
$ git config --global init.defaultBranch main  

**Установить параметры окончания строки**  
$ git config --global core.autocrlf false  
$ git config --global core.safecrlf warn  

**Отмена замены символов восьмеричными кодами**  
$ git config --global core.quotePath false  

**Разрешить длинный путь к файлу**  
$ git config --global core.longpaths true  

**Установить размер буфера**  
$ git config --global http.postBuffer 1048576000  

**Установить альтернативный DiffTool kdiff3**  
$ git config --global diff.tool kdiff3  
$ git config --global difftool.kdiff3.cmd "'C:/Program Files/KDiff3/kdiff3.exe' \$LOCAL \$REMOTE"  
