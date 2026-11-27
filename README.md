# Goose Egg Rush Manager

Goose Egg Rushの効果・ショートカット、TikTok LIVE連携、配信用カウンターHUDを管理するWindowsアプリです。

[最新版のダウンロード](https://github.com/yuuhaar2/goose-egg-rush/releases/latest)

## 初めて使う場合

1. Releasesから `GooseEggRushManager-vバージョン-win-x64.zip` をダウンロードします。
2. ZIPを「すべて展開」し、書き込み可能な場所へ保存します。
3. フォルダー内の `GooseShortcuts.exe` を起動します。

Windows 10 / 11の64bit（x64）に対応します。.NETとNode.jsは同梱済みです。ゲーム本体は各自で用意してください。詳しい操作は同梱の「はじめに.txt」にあります。

## 更新方法

v2.15.0以降は、アプリ左下の **アップデート → 最新版を確認 → ダウンロード → 更新して再起動** で更新できます。設定とカウンターは引き継ぎます。

v2.14.0から移行する初回は、このページのZIPをダウンロードし、既存の「アップデート」から選択してください。v2.13以前は新しいZIPを展開し、終了した旧アプリから設定JSONをコピーしてください。

## 配布ファイル

配布物は署名付きです。アプリは更新情報とファイル内容を検証します。署名検証はWindowsの発行元認証（Authenticode）とは異なります。個人の接続先・APIキー・カウンター設定は配布物に含みません。

ライセンスと対応ソースは配布ZIPの `licenses`、`source` に含まれます。

TikTokおよびゲームの公式アプリではありません。
