
(Ugly) fork from [akpoff](https://github.com/akpoff/spfwalk) to work on
Linux with glibc.

This a tool to query a domain to get all the hosts (or netblocks)
included in the SPF records. E.g.:

~~~
$ ./spfwalk conostix.com
176.31.113.162
2a02:6f00:c0::d00:91a5
31.22.120.20
2001:41d0:8:38a2::1035
~~~

# Building

You need a BSD make (`bmake` on Debian). The depencies are *libasr* (`libasr-dev` on
Debian) and *libevent* (`libenvent-dev` on Debian).
