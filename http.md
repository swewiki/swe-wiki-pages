title: http (hypertext transfer protocol)
level: basic

HTTP is the dominating applicaiton protocol for the Web.

By default, HTTP protocol uses port `80`.

HTTP uses scheme: `http://`

Secure version of HTTP is (HTTPS)[/https].

### versions

* HTTP/1.0
* HTTP/1.1
* HTTP/2
* HTTP/3

### examples

Example request:

    GET /hello HTTP/1.1
    Host: swe.wiki

Example response:

    HTTP/1.1 200 OK
    Connection: keep-alive
    Server: gunicorn/20.0.0
    Date: Sat, 16 Nov 2019 01:13:43 GMT
    Content-Type: text/html; charset=utf-8
    Content-Length: 12

    Hello World!

### resources

* [rfc3986](https://tools.ietf.org/html/rfc3986)
