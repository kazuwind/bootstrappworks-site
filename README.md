# bootstrappworks-site

スタジオ共通のルートドメイン bootstrappworks.com を配信する静的サイトです。
AdMob の `app-ads.txt` を https://bootstrappworks.com/app-ads.txt で配信することが主な目的で、スタジオの簡単なトップページも置いています。

## DNS の前提

GitHub Pages で配信します。bootstrappworks.com の A レコードは、次の4つです。

- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

`CNAME` ファイルは、カスタムドメインの設定なので消さないでください。

## app-ads.txt を変更するとき

- パブリッシャーID（`pub-` で始まる値）は、AdMob 管理画面のものと一致させてください。一致しないと、AdMob の確認に失敗し、広告配信に影響します。
- 余計な空白や引用符を入れないでください。
- サイトのルート直下から移動しないでください。
