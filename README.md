# Proxy Pool
To get workable proxy IP addresses of US.

The proxy IP addresses come from [freeproxylists](http://www.freeproxylists.net/us.html)

I revised the project of [kapythone](https://github.com/kapythone/ProxyFactory) to make it work for Python 2.7 and people in US.

# Rely
* Python 2.7
* PhantomJS
* Selenium

# How to use
Example:

```python
from proxy_pool import ProxyFactory
pp = ProxyFactory()
pp.Run()
print pp.avaiProxyPairs
```
All the available and workable IP addresses are stored in **pp.avaiProxyPairs** in the example.