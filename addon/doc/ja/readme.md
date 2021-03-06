# Emoticons #

* 作者: Chris Leo, Noelia Ruiz Martínez, Mesar Hameed
* ダウンロード [安定版][1]
* ダウンロード [開発版][2]

このアドオンを使うと、エモーティコン文字列を含むテキストを読み上げるときに人間がもっと理解しやすい読み方に置き換えます。86種類のエモーティコンを定義しています。

例えば ":)" は「ほほえんでいる顔文字」になります。また ":D" は「笑っている顔文字」になります。

次のような機能があります:

## 顔文字の挿入 ##

特定の顔文字のためにどの文字を使えばよいか分からない場合に、このアドオンを使うと、顔文字を選択してチャットなど編集中のテキスト領域に入力できます。
NVDA+I を押すか、メニューから 設定 → エモーティコンの管理 → 顔文字の挿入 を選択してください。
ダイアログが表示され、登録されている顔文字から選択できます。OK ボタンを押すと、選択された顔文字の文字列がクリップボードにコピーされます。テキストエディットに入力するには貼り付けの操作をしてください。


## エモーティコンの編集 ##

NVDAメニューの 設定 → エモーティコンの管理 → エモーティコンの編集 から、設定のダイアログが表示されます。ここでエモーティコンの追加と、登録済みのエモーティコンの編集ができます。
このダイアログから NVDA の読み上げ辞書の形式で、あなたが編集した内容を保存できます。

「辞書を保存してエクスポート」ボタンを押すと、NVDAユーザー設定フォルダーの speechDicts サブフォルダーにファイル名
emoticons.dic で保存されます。


## 設定の有効化 ##

NVDA を起動したときにエモーティコンの読み上げを有効にするかどうかを選択できます。既定では無効になっています。この設定は保存することができます。

## キーコマンド: ##

*	NVDA+E: テキストを書かれた文字のまま読み上げるか、エモーティコンを理解しやすい読み方に置き換えるかを切り替えます。
*	NVDA+I: 貼り付けをしたい顔文字を選択するダイアログを表示します。


## 4.0 での変更点 ##

* 他の設定ダイアログが開いている状態で「顔文字の挿入」ダイアログを開くとエラーメッセージが表示されるようになりました。


## 3.0 での変更点 ##

* エモーティコンの編集ダイアログにおいて、パターンを単語全体にだけ適用するかどうかを指定できるようになりました。これは NVDA 2014.4
  の読み上げ辞書で追加された機能です。


## 2.0 での変更点 ##

* アドオンマネージャーからアドオンのヘルプが利用できるようになりました。


## 1.1 の変更点 ##

* 重複したエモーティコンを消去しました。
* 顔文字を追加しました。

## 1.0 での変更点 ##

* 最初のバージョンです。

[[!tag dev stable]]

[1]: http://addons.nvda-project.org/files/get.php?file=emo

[2]: http://addons.nvda-project.org/files/get.php?file=emo-dev
