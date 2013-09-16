irc-replies
===========

No need to re-write the wheel! This repo contains the reply codes defined
by [RFC 1459 section 6](https://tools.ietf.org/html/rfc1459#section-6) and
[RFC 2812 section 5](http://tools.ietf.org/html/rfc2812#section-5) as a
simple JSON object so you can use them in whatever IRC thingy you are building.

Use as a node.js module:
```
npm install irc-replies
```


```javascript
var reply = require('irc-replies');

console.log(reply['372']);
//RPL_MOTD
```


### license
MIT
