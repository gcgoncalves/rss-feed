# rss-feed

feeder interface:

```javascript
let RssFeedEmitter = require('rss-feed-emitter');
let feeder = new RssFeedEmitter();

feeder.add( {...} )
feeder.remove( 'http://...' );
feeder.list();
feeder.on( 'new-item', callback);
feeder.destroy();
```
