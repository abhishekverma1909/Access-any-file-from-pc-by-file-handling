# Access-any-file-from-pc-by-file-handling
import os,sys
fname=input('Enter your file name:=')
if os.path.isfile(fname):
    print('File Exists',fname)
    f=open(fname,'r')
    print('The content of file is')
    print(f.read())
else:
    print('File does not exists',fname)
sys.exit(0)
