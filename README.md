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