# pido

* Multithreading download with python
* Modify from https://code.activestate.com/recipes/578220-multithreading-downloader-class/

##Installing:
```
pip install dumpy
```

##Usage:
```
pido.py -h
usage: pido.py [-h] [-u URL] [-f FILE] [-s n] [-t n]

optional arguments:
  -h, --help            show this help message and exit
  -u URL, --url URL     download link
  -f FILE, --file FILE  download links in a file
  -s n, --timeout n     set timeout (default is 30s)
  -t n, --thread n      set threads [8,16,32,64...](default is 16)
  ```
  
##Example
```
python pido.py -u "http://f90.x8top.net/2107tmp/cf/soft/2018/9/ba/1/vlc-3.0.4-win32.exe"

[+] Set timeout to 30 seconds
[+] Downloading to vlc-3.0.4-win32.exe...
[+] Running 32 processes...
38.35 MB / 38.35 MB [######################] [100.00%]
[+] File is downloaded.
```
 
```
python pido.py -f "path\\to\\downloadlinks.txt"
```
![alt text](https://raw.githubusercontent.com/vanduan/pido/master/recorded_1.png)
