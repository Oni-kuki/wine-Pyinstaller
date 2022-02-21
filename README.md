# wine-Pyinstaller
---------------------- 

```sh
apt-get install wine  
wget https://www.python.org/ftp/python/2.7.9/python-2.7.9.amd64.msi  
wine msiexec /i python-2.7.9.amd64.msi /qb
```
----------------------  
If you need to compile a 32bit executable
```sh
sudo dpkg --add-architecture i386 && sudo apt-get update && sudo apt-get install wine32
```

```sh
cd ~/.wine/drive_c/Python27
wine python.exe Scripts/pip.exe install pyinstaller==2.1
```
