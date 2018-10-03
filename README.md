# pido
Multithreading download with python

Modify from https://code.activestate.com/recipes/578220-multithreading-downloader-class/

Install:
<code>pip install dumpy</code>

Usage:
<code>pido.py -h
usage: pido.py [-h] [-u URL] [-f FILE] [-s n] [-t n]

optional arguments:
  -h, --help            show this help message and exit
  -u URL, --url URL     download link
  -f FILE, --file FILE  download links in a file
  -s n, --timeout n     set timeout (default is 30s)
  -t n, --thread n      set threads [8,16,32,64...](default is 16)
  </code>
