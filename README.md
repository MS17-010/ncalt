mygmap
======

Simple ncat alternative script.
Use it for remote shell access.

The code is Python 2, but Python 3 compatible.

Installation
============


```
pip install mygmap
```

Example
=======

Listen on a socket
```
python -m ncalt -l -t 127.0.0.1 -p 4444
```    

Connect to socket
```
python -m ncalt -t 127.0.0.1 -p 4444
```

Here is the output:
```
1
```
