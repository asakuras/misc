# How to use python2 and python3 at the same time

1. Change the file in python2 directory from python.exe and pythonw to python2.exe and pythonw2.exe (Default directory: C:/Python27).
 
2. Change the file in python3 directory from python.exe and pythonw to python3.exe and pythonw3.exe (Default directory: C:/Users/asakuras/AppData/Local/Programs/Python/Python35).
 
3. Configure the environment variable.
 
4. (Optional) Change the archive by create the 'pip.ini' at the C:/Users/asakuras/pip, if the folder pip doesn't exist, just create it.
 
```
[global]
timeout = 6000
index-url = https://pypi.tuna.tsinghua.edu.cn/simple
trusted-host = pypi.tuna.tsinghua.edu.cn
```

5. Type the command below in the cmd:

```
python2 -m pip install --upgrade pip --force-reinstall
python3 -m pip install --upgrade pip --force-reinstall
```
