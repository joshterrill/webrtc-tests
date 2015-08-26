# webrtc-tests
a hacky edit of the webrtc-experiment broadcast page. Run using ```node index.js``` or just put the ```index.html``` file in a directory. Open ```index.html``` and enable ```getUserMedia```. Now every peer that connects to that page afterwards will see what thew first peer is broadcasting. If there are no peers broadcasting, ```getUserMedia``` will prompt until one does.
