# 003_force_newgame
強制ニューゲームスクリプト

## 概要
Mainより上ならば、どこに貼り付けても構いません。
（Scene_Debug 以下、Main 以上が無難です。）

Scene_Title からニューゲームに必要な処理を抜粋して使用し、
force_newgame をスクリプトエディタ上及び、イベントのスクリプト上などから
呼び出すことにより、強制的にニューゲームと同じ状態にします。

応用として、$game_xxxx の一部だけ削除して、
「xxxxを引き継いでニューゲーム」なども恐らく可能です。