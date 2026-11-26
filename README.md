# Body & Balance

スマートフォン対応のダイエット・ジム記録Webアプリです。

## 公開方法（GitHub Pages）
1. GitHubで `diet-tracker` という新しいPublicリポジトリを作成
2. このフォルダ内の4ファイル（`index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`）をリポジトリ直下へアップロード
3. Settings → Pages → Deploy from a branch → `main` / `/(root)` → Save
4. 数分後に `https://あなたのGitHubユーザー名.github.io/diet-tracker/` で公開

## 機能
- 体重記録・推移グラフ
- 筋トレ種目の選択、重量・回数・セット数の記録
- 有酸素運動の時間・速度・傾斜の記録
- カレンダー・トレーニング履歴
- localStorageによる端末内保存
- PWA対応（HTTPSで公開後、iPhone Safariの共有 → ホーム画面に追加）

## データについて
記録は利用中のブラウザ内に保存されます。同じブラウザ・端末で利用してください。ブラウザデータの消去や端末変更で消える可能性があり、クラウド同期はありません。
