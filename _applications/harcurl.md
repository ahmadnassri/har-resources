---
layout: post
title: HARcURL
license: LGPL License
link: http://andydude.github.io/harcurl/
source: https://github.com/andydude/harcurl
---

The HTTP archiving (HAR) file transfer tool.

The harcurl tool accepts requests on stdin, and prints responses to stdout. The format of the request and response are both specified in the HAR-1.2 specification. Obviously, almost every property is optional on input, even though the HAR spec says it is required, since one of the jobs of harcurl is to fill in the rest of the data from the response. The only 2 properties that are required are method and url.

The recommended usage is to build a JSON file either by hand, or by generating one with your favorite programming language, then feed that to harcurl on stdin.

```shell
echo '
{
  "request" {
    "method": "GET",
    "url": "http://httpbin.org/get"
  }
}' | harcurl
```

The simplest way to use harcurl is to call it with the shell command:

```shell
harcurl < req.json > resp.json
```
