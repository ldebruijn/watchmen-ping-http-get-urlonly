# watchmen-ping-http-get-urlonly

[![Greenkeeper badge](https://badges.greenkeeper.io/ldebruijn/watchmen-ping-http-get-urlonly.svg)](https://greenkeeper.io/)

Watchmen ping plugin which performs a GET request.
The full path is built only with the `url` property of the service.
This means the following is now possible:

```
http://localhost:3010/path
```

Before, the port property would be appended to the url, resulting in the following


```
http://localhost:3010/path:3010
```
