
### [Live Demo hosted on Github pages!](https://yoav-zibin.github.io/gupshup/)


How It Works
------------
Chrome and Firefox announced recently that their WebRTC APIs now
[interoperate](http://www.webrtc.org/interop). The
[original demo](https://code.google.com/p/webrtc-samples/source/browse/trunk/apprtc/)
uses Google App Engine to exchange the WebRTC offer and answer blobs, whereas
Gupshup uses Firebase to do the same - eliminating the need to write any server
logic at all.


Known Issues with WebRTC
------------------------
* The remote video can sometimes take up to 10 seconds to appear.
* There may be other rough edges around WebRTC.
