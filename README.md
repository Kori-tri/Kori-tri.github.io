# 研究者サイト（Minimal Mistakes + Jekyll）スターター

## 使い方（最短手順）
1. GitHub で `USERNAME.github.io` という **Public** リポジトリを作成
2. この一式をアップロードして Commit
3. リポジトリの **Settings → Pages** を開き、
   - Source: Deploy from a branch
   - Branch: `main` / `/ (root)` を選択して Save
4. 数分後、 `https://USERNAME.github.io/` で公開

## ローカルでプレビュー（任意）
- Ruby をインストール（Windows の場合は RubyInstaller with DevKit 推奨）
- ターミナルで `bundle install` → `bundle exec jekyll serve`
- http://127.0.0.1:4000 で確認

## 編集箇所
- `_config.yml` の `url`, `repository`, `author` を自分の情報に変更
- `_data/navigation.yml` でナビメニュー編集
- 近況は `/_news/` に Markdown を追加（`YYYY-MM-DD-title.md`）
- `assets/` にプロフィール画像やPDFを置く
