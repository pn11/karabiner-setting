# Karabiner-setting
Karabiner の設定をエクスポートしたもの。

## エクスポート方法
設定メニューからできるものと思ってたけど見当たらなくて、調べたらコマンドを叩くみたい。

- [![](http://capture.heartrails.com/75x75/shadow?http://qiita.com/icb54615/items/9c7a5366e23496bfacd5)](http://qiita.com/icb54615/items/9c7a5366e23496bfacd5)[Karabinerの設定移行 - Qiita](http://qiita.com/icb54615/items/9c7a5366e23496bfacd5)[![](http://b.hatena.ne.jp/entry/image/http://qiita.com/icb54615/items/9c7a5366e23496bfacd5)](http://b.hatena.ne.jp/entry/http://qiita.com/icb54615/items/9c7a5366e23496bfacd5)


```
/Applications/Karabiner.app/Contents/Library/bin/karabiner export
```

とするとシェルスクリプトが出力されるので、これをリダイレクトして保存したものをこのリポジトリに置いとく。スクリプトを実行すればインポートされる。

## 設定内容
US配列の Built-in keyboard, Magic Keyboard 2 を使用。OS の System Preference で <kbd>Caps Lock</kbd> を <kbd>Control</kbd> にしてる。以下を Karabiner で設定。

- <kbd>左Command</kbd> を <kbd>英数</kbd> に 
- <kbd>右Command</kbd> を <kbd>かな</kbd> に 
- <kbd>fn</kbd> を <kbd>Command</kbd> に 
- <kbd>右Option</kbd> を <kbd>fn</kbd> に 
- <kbd>Control</kbd> + PNBF でカーソル移動 (Emacs mode)
- 円記号をバックスラッシュに
