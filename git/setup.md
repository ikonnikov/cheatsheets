**Установка имени и e-mail коммиттера**  
```
$ git config --global user.name "Surname, Name"
$ git config --global user.email "your_mail@domain.ru"
```

**Установить редактор**  
```Shell
$ git config --global core.editor "'C:/Program Files/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"
```

**Установить ветку по-умолчанию**  
```Shell
$ git config --global init.defaultBranch main
```

**Установить параметры окончания строки**  
```Shell
$ git config --global core.autocrlf false
$ git config --global core.safecrlf warn
```

**Отмена замены символов восьмеричными кодами**  
```Shell
$ git config --global core.quotePath false
```

**Разрешить длинный путь к файлу**  
```Shell
$ git config --global core.longpaths true
```

**Установить размер буфера**  
```Shell
$ git config --global http.postBuffer 1048576000
```

**Установить альтернативный DiffTool kdiff3**  
```Shell
$ git config --global diff.tool kdiff3
$ git config --global difftool.kdiff3.cmd "'C:/Program Files/KDiff3/kdiff3.exe' \$LOCAL \$REMOTE"
```
