# 004_quick_save
クイックセーブ＆ロードスクリプト

## 概要
Mainより上ならば、どこに貼り付けても構いません。
（Scene_Debug 以下、Main 以上が無難です。）

Scene_Save と Scene_Load から単純なセーブ及びロードの機能を抜粋し、
quick_save でクイックセーブが、quick_load でクイックロードが可能です。
指定されたクイックセーブ用のファイルが存在しない場合、
強制ニューゲームスクリプトの force_newgame を使用し、
ニューゲームになります。

初期設定では、QuickSave.rxdata にクイックセーブ用のデータを作成します。
quick_save、quick_load のそれぞれの filename の値を変えて
セーブファイル名の変更が可能です。

通常のセーブ方式に準じているため、戦闘中など、
Scene_Map 以外でのセーブには対応していません（一応ロードは可能です）。
必要であれば、各自で改造してください。