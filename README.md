# cookiestxt

A version of Python's MozillaCookieJar that produces cookies.txt files
that are compatible with curl/wget.

MozillaCookieJar is a *great* idea.  It just doesn't work well right
now without [this patch](https://bugs.python.org/issue17164).  So,
I've applied the patch here.

Use it like you would use MozillaCookieJar.

```python
from cookiestxt import MozillaCookieJar
cj = MozillaCookieJar()
...
```
