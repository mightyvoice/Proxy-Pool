# Proxy Pool
To get workable proxy IP addresses of US.

The proxy IP addresses come from [freeproxylists](http://www.freeproxylists.net/us.html)

I revised the project of [kapythone](https://github.com/kapythone/ProxyFactory) to make it work for Python 2.7 and people in US.

# Based on
* Python 2.7
* [PhantomJS](http://phantomjs.org/)
* [Selenium](http://selenium-python.readthedocs.io/)
* [Requests](http://docs.python-requests.org/en/master/)

# How to use

After installing **PhantomJS**, change the **PhantomJS_Dir** to your own directory in the **proxy_pool.py** file.

Example:

```python
from proxy_pool import ProxyFactory
pp = ProxyFactory()
pp.Run()
print pp.avaiProxyPairs
```
All the available and workable IP addresses are stored in **pp.avaiProxyPairs** in the example.