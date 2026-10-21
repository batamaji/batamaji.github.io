+++
title = 'Hello world'
date = 2026-10-21T12:00:00+03:00
tags = ['meta']
+++

First post. This blog is where I write up bugs, vulnerabilities and whatever
research I end up doing.

## Code looks like this

```python
import requests

r = requests.get("https://example.com/.git/HEAD")
print(r.status_code, r.text.strip())
```

Inline `code`, [links](https://example.com) and tables all work.

| field | value |
| ----- | ----- |
| cvss  | 9.8   |
| vendor | unresponsive |

> Quotes look like this.
