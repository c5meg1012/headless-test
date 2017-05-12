## つかいかた

ターミナルを2画面開いて
一つで先に

```
$ chrome-c --headless --remote-debugging-port=9222 https://chromium.org
```

特に出力はなく、入力待ちみたいな状態になります

もし`mesa library`周りのエラーが出たら`--disable-gpu`オプションをつけると良いそうです。

もう一つで

```
$ node script.js
```

https://developers.google.com/web/updates/2017/04/headless-chrome?hl=ja

に他の機能もあるよ！