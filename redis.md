title: redis
level: basic

Redis is a popular in-memory datastore.

Redis is often used as a cache because its in-memory nature -- accessing memory is much faster than operations requiring disk access.

### example

    :::bash
    redis> GET mykey
    (nil)
    redis> SET mykey "1"
    "OK"
    redis> GET mykey
    "1"
    redis> INC mykey
    "OK"
    redis> GET mykey
    "2"

### resources
* [redis official website](https://redis.io/)
