# Rep RSS

* Repository: https://github.com/kamocyc/rep-rss
* Hosted at: https://ancient-shelf-27599.herokuapp.com/
* 仕様: https://github.com/kamocyc/rep-rss/wiki

![screenshot](screenshot.gif)

記事をTwitter検索して、ツイート数とコメントを表示するRSSリーダを作りました。

### 主な機能

* RSS中の記事のURLをTwitterで検索し、URLが含まれるツイート数を取得
* ツイート数と記事の公開時間を考慮してソート
* Twitterからコメントを取得して一覧表示
* はてなブックマークからも同様に件数とコメントを取得して表示

### 注意点

* Twitter APIの制限によく引っかかります。15分経つと解消されます。
* Herokuの無料サーバを使っているのでかなり重いです。おそらく同時アクセスは2~3人が限度です。
