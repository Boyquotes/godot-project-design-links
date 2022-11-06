# godot-project-design-links

Design all Godot editor items. Godot4 addon.
 
もう設計書ツールとGodotエディタとの間で往復をする必要はありません。
 
Godotエディタ内でプログラムファイルの関連設計図を作成したり（すぐジャンプできる！）、キャラクター相関図を作ることもできます。

Godot4 プロジェクト内の（シーン、リソース、ファイル、ディレクトリ）といったアイテムを好きなように配置して管理することができます。

![image](https://user-images.githubusercontent.com/32963227/200152885-cd65ccfa-8bd3-44d0-94d7-bf41459ef674.png)

---

各アイテム

## メインの機能

* [x] Godotファイルシステムからのドラッグドロップによる各アイテム追加
* [x] グループ・ラベル・テキスト・接続のアイテム追加（ヘッダーメニュー）
* [x] キャンバス内のアイテムへジャンプできるリンク作成
* [x] 整列

---

### Godotファイルシステムからのドラッグドロップによるアイテム追加　基本！

Godotのファイルシステムのところからアイテムをドラッグしてキャンバスに追加します。

追加したアイテムのアイコンをクリックするとGodotエディタでそのファイルが開きます。

シーンなら2D・3Dに対応したメイン画面、スクリプトファイルならスクリプト画面になる、などです。

各アイテムでできること

### グループ・ラベル・テキスト・接続のアイテム追加（ヘッダーメニュー）

ヘッダーメニューから管理系のアイテムを追加してアイテムをうまくまとめることができます。

グループ・ラベル・テキスト・接続の使い方・できること

### キャンバス内のアイテムへジャンプできるリンク作成

各アイテム上で右クリックからコピーできる「リンク」アイテムを使えば、広いキャンバスで迷うことなく管理することができます。

---

### キャンバス

#### コピー　（Ctrl+C）

右クリックメニューにもあります。

選択中のアイテムをコピーします。

#### ペースト　（Ctrl+V）

右クリックメニューにもあります。

選択中のアイテムをマウスカーソルの位置へ貼り付けます。

#### 削除　（Delete）

右クリックメニューにもあります。

#### 元に戻す、進む　（Ctrl+Z,Shift+Ctrl+Z）

アンドゥリドゥ機能です。

保存をすると履歴は削除されます。

簡易的なものなので、あまり過信しないでください。

---

### 管理系のアイテム　ヘッダーメニュー

ヘッダーメニューのボタンを押して、キャンバスをクリックするとクリック地点に管理系のアイテムが作成されます。

#### グループ（Alt+C）

アイテムをつないでコネクトアイテムを作ることができます。

2つのアイテムを選択した状態でAlt＋Cまたは「接続」ボタンを押すとコネクトアイテムが間にできます。

#### 

#### 接続（Alt+C）

アイテムをつないでコネクトアイテムを作ることができます。

2つのアイテムを選択した状態でAlt＋Cまたは「接続」ボタンを押すとコネクトアイテムが間にできます。

---

## 各アイテムについて

* [x] アイテム共通
* [x] シーン (.tscn)
* [x] リソース(.tres)
* [x] 画像 (.pngなど、Texture2Dとして読み込んだリソース)
* [x] 音楽
* [x] テキストファイル
* [x] ディレクトリ
* [x] ラベル（1行のみのテキスト）
* [x] テキストドキュメント
* [ ] Dialogic2.0 タイムライン 未実装
* [ ] Dialogic2.0 キャラクター 未実装

### アイテム共通

#### ロック

#### リンクコピー

#### パスのコピー

#### コピー

#### 削除

### シーン (.tscn)

クリックするとそのシーンが開きます。

2Dか3DかはそのシーンのNodeで判断されます。

右クリックからシーン再生ボタンを表示させることができます。

### リソース(.tres)

クリックするとインスペクタが開きます。

### 画像

クリックするとインスペクタが開きます。

画像


### テキストファイル


### ディレクトリ

クリックするとGodotのファイルシステムでそのディレクトリの位置を開きます

### ラベル（1行のみのテキスト）




### テキストドキュメント

---

## 設定ファイル

すべてのres://addons/godot-graphnode-document 下に
