# KarabinerElementsの設定

## ファイルの配置場所

`~/.config/karabiner`にクローンすればOK。（`~/.config/karabiner/karabiner.json`となるような形にする）

## 設定したキーバインド

+ mouse button 5 + mouse button 3 => screen shot
+ mouse button 5 => left_alt
+ Ctrl+u => PageUp
+ Ctrl+v => PageDown
+ Ctrl+a/e => Home/End
+ 英数/かなキーにワンショットモディファイアを設定（それぞれCtrl/Commandに対応）

## 詳細

### mouse button 5 => left_alt

「マウスボタン5 + 右クリック」でデスクトップ表示をするために設定。

システム環境設定 => MissionControlにて「Option + マウス副ボタン」でデスクトップ表示する設定も必要。


### Ctrl+a/e => Home/End

Macではデフォルトでこのショートカットで行頭・行末に移動するが、一部エディタでは「Ctrl+Shift+a/e」で「行頭・行末まで選択」がされない。

こちらを設定すればそれらのエディタでも上記処理が可能になるので設定。
