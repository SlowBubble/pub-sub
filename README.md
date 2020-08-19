

# Usage

```
import * as pubSub from './node_modules/@clubfest/pub-sub/pubSub.js'

const [noteOnPub, noteOnSub] = pubSub.make();
noteOnSub(data => { console.log('Received: ', data); });
noteOnPub(42);  // log: 'Recieved: 42'
```