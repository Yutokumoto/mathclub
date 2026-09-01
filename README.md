# 数学研究部 模試解答サイト

GitHub Pagesで公開する前提の静的サイトです。

## 設計
- 模試ごとに推測しにくい独立URL
- 各ページから他模試へのリンクなし
- ルートURLから各解答ページへのリンクなし
- `noindex, nofollow, noarchive` を設定
- `robots.txt` でも全体をクロール拒否
- 将来、各解答ページ → 公式サイト の片道リンクを追加可能

## 2026年度の秘密パス
- α: `2026-alpha-ezS1VO88yebb`
- β: `2026-beta-hCb6ZK9hfzDc`
- γ: `2026-gamma-JmG2MjeiqnKi`
- 合同: `2026-joint-A3HybQV2Ch99`

## PDFを入れる
各秘密フォルダに、対応する完成版PDFを `answer.pdf` という名前で配置してください。

例:
`2026-alpha-ezS1VO88yebb/answer.pdf`

## GitHub Pages
1. GitHubで新しいリポジトリを作成
2. このフォルダの中身をリポジトリ直下にアップロード
3. Settings → Pages
4. Deploy from a branch を選択
5. Branch: main / root を選択して保存
6. 公開URLが決まったら、各秘密パスを末尾につけたURLをQRコード化

例:
`https://ACCOUNT.github.io/REPOSITORY/2026-alpha-ezS1VO88yebb/`

## 重要
GitHub Pagesは厳密な認証ではありません。
秘密URLを知っている人はアクセスできます。
ただし通常のサイト導線や検索結果からは見つけにくい構造です。

印刷後は秘密フォルダ名を変更しないでください。
中の `answer.pdf` やHTMLを更新しても、QRコードのURLはそのまま使えます。
