# Configure proxy server for Visual Studio 2022
1. Find devenv.exe.config (the configuration file of devenv.exe) in:  
  %ProgramFiles%\Microsoft Visual Studio\2022\Enterprise\Common7\IDE  
  or  
  %ProgramFiles(x86)%\Microsoft Visual Studio\2022\Enterprise\Common7\IDE  
2. In the configuration file, find the <system.net> block, and then add this code:
```
<defaultProxy enabled="true">
    <proxy bypassonlocal="true" proxyaddress="http://yourproxy:port"/>
</defaultProxy>
```
