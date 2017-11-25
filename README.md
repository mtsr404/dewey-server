# dewey-local-server

- start-dewey-server.shでローカルのサムネイル生成サーバーを起動
- dewey-chrome-extensionをchromeの拡張機能に追加

## Powered by

- [nodejs](https://nodejs.org/)
- [bottleneck](https://github.com/SGrondin/bottleneck) - for limiting number of
    concurrent screenshot
- [express](http://expressjs.com) - for powering nodejs server app
- [image-native](https://github.com/elad/node-imagemagick-native) - for
    resizing screenshots
- [morgan](https://github.com/expressjs/morgan) - for writing logs about
    requests
- [webshot](https://github.com/brenden/node-webshot) - for generating
    screenshots
