## つかいかた

ターミナルを2画面開いて
一つで先に

$ chrome-c --headless --remote-debugging-port=9222 https://chromium.org
特に出力はなく、入力待ちみたいな状態になります
もしmesa library周りのエラーが出たら--disable-gpuオプションをつけると良いそうです。
もう一つで

$ node script.js
