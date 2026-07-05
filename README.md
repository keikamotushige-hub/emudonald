# エムドナルド — バーガー大乱闘

McDonald's風店舗で、店員（ゆい・兄タクヤ）と配達員（ケン・ソウ）がバーガーを投げ合うブラウザゲーム。

## 遊び方

- 画面をクリック → 近いキャラがバーガーを投げる
- 命中で COMBO・スコアアップ
- 緑ボタン / 配達エリア → Uber Eats 配達員登録（招待コード `zzzxa28`）

## ローカル

`index.html` をブラウザで開くだけ（ビルド不要）。

## 公開 URL

| サービス | URL |
|---------|-----|
| **Vercel（本番）** | https://emudonald.vercel.app |
| **GitHub** | https://github.com/keikamotushige-hub/emudonald |

スマホ・PC のブラウザからそのまま遊べます。

## 構成（GitHub + Supabase + Vercel）

- **GitHub** … ソースコード管理
- **Supabase** … 同一アカウントのプロジェクト連携（スコアは現状 localStorage）
- **Vercel** … インターネット公開（Virtual）
