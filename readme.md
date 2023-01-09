> リンク切れにのみ対応します。  
> 他の質問には基本的に一切応答できません。  
> 加筆修正はプルリク送ってください。  
> (応答がなければフォークしてそちらをメンテナンスしてください。)

## dophinというエミュレーターを利用したスマブラXネットプレイ(ネトスマX)の導入メモ
海外勢が既にネットプレイ環境を整備してくれているのでそれを利用します。  
これにはいくつかの利点があります。
* セーブデータを対戦相手と事前に共有するなどの面倒な作業が必要ない(同じセーブデータを使わないと同期ズレしたりします)
* ゲーム由来の入力遅延2f無効化、キャラ選択画面でキーコン編集、リザルト基本スキップなどの便利で快適な機能を利用できる
* デフォルトで5ステ3スト8分TAonに設定されている


デメリットとしては
* 海外版のisoが必要
* ゲーム内のUIが英語

などが挙げられます。

## ISOの準備
海外版(RSBE 1.01)のISOが必要です。  
違法ダウンロード、ダメ、絶対！   

> dolphin内のソフト一覧画面上でssbbを右クリックして `Properties` -> `Info` -> `MD5Checksum`の横の`Compute`を押せばISOのmd5ハッシュを確認できます。

使える(同期ズレ等が起こらない)ISOは以下のmd5ハッシュのうちのどれかと合致するものです。
- `d18726e6dfdc8bdbdad540b561051087`
- `d8560b021835c9234c28be7ff9bcaaeb`
- `5052e2e15f22772ab6ce4fd078221e96`
- `52ce7160ced2505ad5e397477d0ea4fe`
- `9f677c78eacb7e9b8617ab358082be32`
- `1c4d6175e3cbb2614bd805d32aea7311`

## 導入
> 必要なファイル(ネットプレイ用のdolphin)をダウンロードします。  
> あえてここに直リンすることはしません。(リンク切れやバージョンの問題を回避するため)

Brawl Centralという海外勢のコミュニティに参加してください。   
https://discord.com/invite/3DmJN2m

`#resources-and-guides`というチャンネルに導入ガイドがあるのでそれを開きます。
> (執筆時点では)`Brawl Netplay vA.B (20YY)`という項目の下にガイドへのリンクがあります。

ガイド内に`Brawl Netplay vA.B (20YY)`というファイルへのリンクがあるのでそこからダウンロードしてガイドに沿って導入してください。
> 認定のiso設定,BGMOff等しっかり設定しないと同期ズレしたり起動しなかったりします。

読めなければ翻訳しましょう。  
https://www.deepl.com/translator


## コントローラーの設定
`#resources-and-guides`内にガイドがあります。
> 純正GCタップ+GCコンなら接続するだけでdolphinに認識されるはず。

## 日本人向けのネトスマX専用コミュニティーはないの？
プレイヤー人口が少ないので、基本皆さん身内同士で対戦していると思います。  
身内ノリがあると新規が入りにくいので対戦募集のみのサーバーを誰かが運営してくれるとありがたいですね。

## その他
グラフィックエンジンが違うと同期ズレを起こす可能性があるので統一したほうが良い。(openglがおすすめされているので特に理由がなければそちらを使用しましょう。)

## 関連リソース
### ラグについてのガイド
https://www.ssbwiki.com/User:P.i./Lag_Guide

### テクスチャハック等
http://forums.kc-mm.com/Gallery/BrawlView.php  
https://gamebanana.com/games/5678
> モデルをいじったハックは同一のものを使用しないと同期ズレします。

### .wbfsを.isoに変換する方法
ツール
http://www.wiibackupmanager.co.uk/WiiBackupManager_Build78.html

解説
https://www.youtube.com/watch?v=m8ON63Hn6jg 

### リアルタイム巻き戻し機能やランダムマッチ機能の実装modの開発鯖
https://discord.com/invite/dzYRN32k4D

#### mod等の関連コミュニティ
https://discord.gg/GbxJhbv  
https://discord.gg/s7c8763
