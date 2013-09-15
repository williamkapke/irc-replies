irc-replies
===========

No need to re-write the wheel! This repo contains the reply codes defined
by [RFC 1459 section 6](https://tools.ietf.org/html/rfc1459#section-6) as a
simple JSON object so you can use them in whatever IRC thingy you are building.

Use as a node.js module:
```
npm install irc-replies
```


```javascript
var reply = require('irc-replies');

console.log(reply.number[372]);
//RPL_MOTD

console.log(reply.code.RPL_MOTD);
//372
```


### license
MIT
