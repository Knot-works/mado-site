# mado-site

[Mado — Markdown Reader](https://apps.apple.com/jp/app/) の公式サイト。

GitHub Pages で公開しています：

- 🏠 **トップ**: https://knot-works.github.io/mado-site/
- 🔒 **プライバシー**: https://knot-works.github.io/mado-site/privacy/
- 💬 **サポート**: https://knot-works.github.io/mado-site/support/

## 構成

```
mado-site/
├── index.html              # ランディング
├── privacy/index.html      # プライバシーポリシー
├── support/index.html      # サポート・FAQ
├── style.css               # 共通スタイル
├── icon.png                # 大サイズアプリアイコン
├── icon-256.png            # 256×256
└── favicon.png             # 64×64
```

## ローカル確認

```bash
cd mado-site
python3 -m http.server 8000
# http://localhost:8000 をブラウザで開く
```

## GitHub Pages 設定

リポジトリ Settings → Pages → Branch: `main` / `/ (root)` → Save

数分後に上記 URL で公開されます。

---

© 2026 [Knot Works](https://github.com/Knot-works)
