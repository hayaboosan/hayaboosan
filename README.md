# hayaboosan

**Web制作 — クリーンでアクセシブルなLP・小規模サイトを、フレームワークなしで。**

個人でWeb制作をしています。React等のフレームワークに頼らず、**素のHTML / CSS / JavaScript** で軽快に動く、読みやすく崩れにくいサイトを作るのが得意です。
**LP制作 / 小規模サイト / 既存サイトの修正・改修** を承っています。お気軽にご相談ください。

---

## 制作できるもの

- **ランディングページ（LP）** — 商品・サービス・キャンペーン向けの1枚完結ページ
- **コーポレート小規模サイト** — 店舗・個人事業・小さな会社向けの数ページ構成サイト
- **既存サイトの修正・改修** — 表示崩れの修正、スマホ対応、文言・デザインの差し替え、ちょっとした機能追加
- **WordPress の修正・機能追加（コード層）** — 子テーマでのCSS調整・レイアウト修正、functions.php での機能追加（カスタム投稿・ショートコード）、カスタムブロック、コード層の表示速度改善。※Elementor 等ページビルダーでの構築・ゼロからのデザイン制作は対象外

---

## 技術スタック

- **HTML5 / CSS3 / vanilla JavaScript** — フレームワーク・ライブラリ不使用。ビルド工程なしでそのまま動く構成
- **WordPress（子テーマ・コード層）** — 子テーマ・functions.php のフック・ビルド不要の動的ブロック・速度改善。親テーマ無改変のアップデート耐性を重視
- **レスポンシブ対応** — スマートフォンからワイド画面まで、CSS Grid / Flexbox で柔軟に
- **アクセシビリティ（WCAG AA を目安に）** — キーボード操作、ARIA属性、`prefers-reduced-motion` への配慮
- **Git / GitHub Pages / Vercel** — バージョン管理と、すぐ確認できる公開環境
- **AI（Claude Code）を活用した実装・改修** — AIとの協働で、見積りからリリースまでのスピードと品質を両立します

<p>
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black">
  <img alt="WordPress" src="https://img.shields.io/badge/WordPress-21759B?logo=wordpress&logoColor=white">
  <img alt="Responsive" src="https://img.shields.io/badge/Responsive-2EA44F">
  <img alt="Accessibility" src="https://img.shields.io/badge/A11y%20WCAG%20AA-0A7B83">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white">
  <img alt="GitHub Pages" src="https://img.shields.io/badge/GitHub%20Pages-222222?logo=githubpages&logoColor=white">
  <img alt="Vercel" src="https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white">
  <img alt="Claude Code" src="https://img.shields.io/badge/Claude%20Code-D97757?logo=anthropic&logoColor=white">
</p>

---

## ポートフォリオ

フレームワークを使わず、vanilla な HTML / CSS / JavaScript のみで制作した作品をまとめています。静的なLPから、状態を持つインタラクティブなツール、データ駆動の一覧UIまで、表現の幅を示しています。

- 🌐 **デモサイト**: https://hayaboosan.github.io/portfolio/
- 📁 **リポジトリ**: https://github.com/hayaboosan/portfolio

収録内容：

- **LP 5作品** — オンラインスクール／コーヒー焙煎所／美容サロン／パーソナルジム／歯科クリニック（明るい清潔系まで配色のレンジを用意）
- **サイト改修ビフォーアフター事例 2件** — 整骨院・個人食堂の「2008年当時の作り → 現行標準（スマホ対応・WCAG AA・`tel:`・予約フォーム）」を、Before→After対応表つきで比較
- **WordPress 子テーマ改修デモ** — 既存WPサイト（Lightning）を子テーマ・functions.php・自作ブロックだけで改修（tel:化＋固定CTA・診療時間表・お知らせ機能・**JS 96%削減の実測つき速度改善**）。コードは [lightning-child-demo](https://github.com/hayaboosan/lightning-child-demo) で公開し、WordPress Playground の blueprint 同梱で**1コマンドで改修前後を手元再現**できます
- **よくある小修正デモ集** — スマホ崩れ・フォーム設置・画像最適化・コントラスト・`tel:`リンク化・レイアウト崩れを、実際に触れる Before→After で実演
- **検索エンジン対応・Q&A設置デモ** — `title` / `meta description` で検索結果の見え方がどう変わるかの Before→After、「検索に出ない」ときの確認7項目（noindex・Search Console・サイトマップ等）、JS無効でも動くQ&A実装と **FAQPage 構造化データ（JSON-LD）**。リッチリザルトの現状も含め「できること・できないこと」を正直に書いた構成
- **見積もりWebアプリ（インタラクティブツール）** — リフォーム見積もりシミュレーター。箇所×グレード×オプション×広さからリアルタイムで明細・税込合計を計算し、選択内容をURLに保存して共有・復元できる1画面完結UI
- **賃貸物件検索UI（データ駆動の一覧）** — 家賃・間取り・面積・駅徒歩・こだわり条件などの多軸絞り込み（ファセット検索）＋並べ替え＋件数の即時更新。URL保存・お気に入りの `localStorage` 永続化つき。JS無効でも全件一覧できるプログレッシブエンハンスメント設計

> 掲載しているブランド・店舗・サービス・お客様の声・実績数値は、すべて**架空のサンプル**です。

---

## お仕事のご相談

LP制作・小規模サイト・既存サイトの改修など、**クラウドワークス**または**ランサーズ**よりお気軽にご相談ください。
内容の整理からご一緒しますので、「何を頼めばいいか分からない」段階でも大丈夫です。

- 💼 **クラウドワークス**: https://crowdworks.jp/public/employees/3919155/
- 💼 **ランサーズ**: https://www.lancers.jp/profile/busa8823
