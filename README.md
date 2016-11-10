
### [Live Demo hosted on Github pages!](https://yoav-zibin.github.io/gupshup/)


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

Known Issues with WebRTC
------------------------
* The remote video can sometimes take up to 10 seconds to appear.
* There may be other rough edges around WebRTC.
