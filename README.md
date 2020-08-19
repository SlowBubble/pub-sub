

Usage:

```
const [noteOnPub, noteOnSub] = pubsub.make();
noteOnSub(data => { console.log('Received: ', data); });
noteOnPub(42);  // log: 'Recieved: 42'
```