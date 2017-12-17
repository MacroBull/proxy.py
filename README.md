proxy.py for Qt online installer
========

Lightweight HTTP Proxy Server in Python.
Pick your desired mirror in proxy.py

Features
--------

- Distributed as a single file module
- No dependency other than the Python standard library
- Support for http, https, websockets request proxy


Usage
-----

```
$ proxy.py -h
usage: proxy.py [-h] [--hostname HOSTNAME] [--port PORT]
                [--log-level LOG_LEVEL]

proxy.py v0.1

optional arguments:
  -h, --help            show this help message and exit
  --hostname HOSTNAME   Default: 127.0.0.1
  --port PORT           Default: 8899
  --log-level LOG_LEVEL
                        DEBUG, INFO, WARNING, ERROR, CRITICAL

Having difficulty using proxy.py? Report at:
https://github.com/abhinavsingh/proxy.py/issues/new
```
