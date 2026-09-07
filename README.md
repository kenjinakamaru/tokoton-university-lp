# トコトン 大学広報課向けLP（レビュー用プレビュー）

`tokoton.biz` の `lp/university/` を、1枚のHTMLに固めたレビュー用のコピーです。
CSSと画像はすべてファイル内に埋め込んであります。

## プレビュー

https://kenjinakamaru.github.io/tokoton-university-lp/

## 本番との違い

レビュー中の誤送信・計測汚染を避けるため、以下を外しています。

| | 状態 |
|---|---|
| HubSpot 資料ダウンロードフォーム | 位置に枠を置いただけ（送信できません） |
| Google Tag Manager | 削除 |
| jQuery | 削除。アンカーのスムーススクロールは素のJSに置き換え |

フォーム送信まで含めた確認は、ステージング環境で行ってください。

## 検索避け

このホストは `kenjinakamaru.github.io/robots.txt` で全体が `Disallow: /` になっています。
加えて、このページ自体にも `noindex,nofollow` を入れています。

ただし **robots.txt はアクセス制御ではありません。URLを知っていれば誰でも閲覧できます。**

## 元データ

`phonogram-inc/tokoton.biz` の `lp/university/`
