Gupshup
=======
Gupshup is a simple [WebRTC](http://webrtc.org) based video calling demo.
It uses [Firebase](https://www.firebase.com) to perform signaling, thereby
requiring **no servers at all**!

In fact, we hosted a live version on Github pages,
**[check it out](http://firebase.github.com/gupshup)**.

How It Works
------------
Chrome and Firefox announced recently that their WebRTC APIs now
[interoperate](http://www.webrtc.org/interop). The
[original demo](https://code.google.com/p/webrtc-samples/source/browse/trunk/apprtc/)
uses Google App Engine to exchange the WebRTC offer and answer blobs, whereas
Gupshup uses Firebase to do the same - eliminating the need to write any server
logic at all.

All the important code is in
[chat.js](https://github.com/firebase/gupshup/blob/gh-pages/js/chat.js). Many
thanks to Eric Rescorla for providing a ton of help with porting the interop
logic to JavaScript!

Known Issues
------------
The remote video can sometimes take upto 10 seconds to appear.

License
-------
[BSD 3-Clause](http://opensource.org/licenses/BSD-3-Clause).
