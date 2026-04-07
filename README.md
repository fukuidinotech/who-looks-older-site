# GitHub Pages サイト

公開先: https://fukumone.github.io/who-looks-older-site/
リポジトリ: https://github.com/fukumone/who-looks-older-site

## ファイル

| ファイル | 公開URL |
|---------|---------|
| index.html | https://fukumone.github.io/who-looks-older-site/ |
| privacy-policy.html | https://fukumone.github.io/who-looks-older-site/privacy-policy.html |
| terms-of-service.html | https://fukumone.github.io/who-looks-older-site/terms-of-service.html |

## デプロイ

```bash
make deploy-site
```

このコマンドで `site/` 内のHTMLファイルが `fukumone/who-looks-older-site` にpushされます。
`gh auth token --user fukumone` が必要です。

## 注意

- ストアボタンのURL（index.html内の `href="#"`）はリリース後に実際のストアURLに差し替えること
- App Store Connect / Google Play Console に登録するURLは上記の公開URL
