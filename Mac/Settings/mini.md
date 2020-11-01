---
title: Mac mini(2018)
---

# OS

macOS Catalina バージョン 10.15.7

# システム環境設定

## 一般

- アクセントカラー
  - レッド
- 強調表示色
  - レッド

## デスクトップとスクリーンセーバ

### デスクトップ

デスクトップピクチャの1つを選択してから以下を実行。

- ピクチャを変更
  - チェック
  - 5分ごと
- ランダムな順序
  - チェック

### スクリーンセーバ

- `今日の一言` を選択
- 開始までの時間
  - 5分

## Dock

- ウインドウをしまうときのエフェクト
  - スケールエフェクト
- ウインドウをアプリケーションアイコンにしまう
  - チェック
- Dockを自動的に表示/非表示
  - チェック
- 最近使ったアプリケーションをDockに表示
  - アンチェック

## セキュリティとプライバシー

### 一般

- スリープとスクリーンセーバの解除にパスワードを要求
  - アンチェック

### FileVault

**FileVaultは有効にしない。**

## ディスプレイ

### ディスプレイ

- 使用可能な場合はメニューバーにミラーリングオプションを表示
  - アンチェック

## 省エネルギー

- ディスプレイをオフにするまでの時間
  - 15分
- ネットワークアクセスによるスリープ解除
  - アンチェック
- Power Napを有効にする
  - アンチェック

## キーボード

### キーボード

- キーのリピート
  - 最速に変更
- リピート入力認識までの時間
  - 最短に変更

1. 修飾キー
   - Caps Lock (⇪) キー
     - `^ Control` に変更

### ユーザ辞書

- `きららざか` を削除

### ショートカット

- 入力ソース
  - 前の入力ソースを選択
    - アンチェック
  - 入力メニューの次のソースを選択
    - `^\` に変更
- Spotlight
  - Spotlight検索を表示
    - アンチェック
  - Finderの検索ウインドウを表示
    - アンチェック

### 入力ソース

- 下記以外を削除
  - U.S.
  - ひらがな(Google)

## マウス

- スクロールの方向: ナチュラル
  - アンチェック
- 軌跡の速さ
  - 最速に変更
- スクロールの速さ
  - 適度に調整

## サウンド

### サウンドエフェクト

- 通知音を選択
  - `Submarine` に変更
- 通知音の音量
  - 適度に調整
- 音量を変更するときにフィードバックを再生
  - チェック
- 主音量
  - 適度に調整
- メニューバーに音量を表示
  - チェック

## iCloud

サインインしてから `iCloud Drive` のみをチェック。

## ネットワーク

- Wi-Fi
  - Wi-Fiをオフにする
  - メニューバーにWi-Fiの状況を表示
    - アンチェック

## Bluetooth

Bluetoothをオフにする。

- メニューバーにBluetoothを表示
  - チェック

## 共有

- コンピュータ名
  - baobab

## 日付と時刻

### 時計

- 秒を表示
  - チェック
- 日付を表示
  - チェック

## アクセシビリティ

### ディスプレイ

- カーソルのサイズ
  - 適度に調整

# アプリケーション

## インストール

- [Google Chrome](https://www.google.co.jp/intl/ja/chrome/)
- [ESET](https://eset-info.canon-its.jp/)
- [1Password](https://1password.com/jp/)
- [Google日本語入力](https://www.google.co.jp/ime/)
- [Firefox](https://www.mozilla.org/ja/firefox/)
- [ForkLift](https://binarynights.com/)
- [Googleのバックアップと同期](https://www.google.com/intl/ja_ALL/drive/download/backup-and-sync/)
- [FUSE for macOS](https://osxfuse.github.io/)
- [VeraCrypt](https://www.veracrypt.fr/en/Home.html)
- [AppCleaner](https://freemacsoft.net/appcleaner/)
- [DMM Player v2](http://help.dmm.com/-/detail/=/qid=46524/)
- [VLC](http://www.videolan.org/)
- [Kindle for Mac](https://www.amazon.co.jp/gp/digital/fiona/kcp-landing-page)
- [Docker](https://docs.docker.com/docker-for-mac/)

## アンインストール

- GarageBand
- iMovie
- Keynote
- Numbers
- Pages

## Dock

以下のアイコンを削除。

- Siri
- メール
- 連絡先
- カレンダー
- メモ
- リマインダー
- マップ
- 写真
- メッセージ
- FaceTime
- iTunes

## Finder

### 環境設定

1. 一般
   - 新規Finderウインドウで次を表示
     - ホームディレクトリを選択
2. サイドバー
   - サイドバーに表示する項目
     - よく使う項目
       - 下記のみを選択
         - アプリケーション
         - デスクトップ
         - ダウンロード
         - ホームディレクトリ
     - iCloud
       - iCloud Drive
         - アンチェック
3. 詳細
   - すべてのファイル名拡張子を表示
     - チェック
   - 拡張子を変更する前に警告を表示
     - アンチェック
   - フォルダを常に先頭に表示する場所
     - 名前順で表示しているウインドウ
       - チェック
     - デスクトップ
       - チェック
   - 検索実行時
     - `現在のフォルダ内を検索` を選択

### 「表示」メニュー

- パスバーを表示
- ステータスバーを表示

1. 表示オプション
   1. 任意のフォルダで表示オプションを表示(`command` + `J`)
   2. 下記の設定に変更
      file:../../images/Mac/settings/mini/001.png
   3. Finderのタブで表示項目を並べ替える
      - 名前
      - サイズ
      - 作成日
      - 変更日
   4. `デフォルトとして使用` をクリック
      この設定が適用されないフォルダでは下記を実行。
      1. 表示オプションを表示(`command` + `J`)
      2. `option` を押す `デフォルトとして使用` が `デフォルトに戻す` になる。
      3. `デフォルトに戻す` をクリック
