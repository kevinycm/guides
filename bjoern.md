
Installation guide on Mac OS for python bjoern

1) execute command "brew install libev" for installing the libev which bjoern required
    
2) execute command "find /usr -name ev.h" for getting the libev's installation location

   on my system, they are: 
        /usr/local/Cellar/libev/4.22/include/ev.h
        /usr/local/include/ev.h
        
3) download bjoern source package

4) execute command "tar zxvf bjoern-1.4.3.tar.gz"

5) execute command "cd bjoern-1.4.3"

6) execute command "CFLAGS=-I/usr/local/include LDFLAGS=-L/usr/local/lib python setup.py install" 

7) done