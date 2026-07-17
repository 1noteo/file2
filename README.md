# Four Photo Collage

GitHub Pages向けの4枚組み写真作成アプリです。

## 公開方法
1. GitHubで新しいリポジトリを作成
2. `index.html`、`style.css`、`app.js` をリポジトリ直下へアップロード
3. Settings → Pages
4. Sourceを `Deploy from a branch`
5. Branchを `main`、フォルダを `/ (root)` に設定
6. Save

## 機能
- 4枚を2×2に配置
- ドラッグ＆ドロップ
- 並び替え
- 各画像の表示位置調整
- 1:1、4:5、3:4、3:2、2:3、16:9、9:16
- 外側余白、写真間隔、背景色
- cover / contain
- 均等セル / 可変セル
- 角丸
- PNG / JPEG
- JPEG品質
- 出力長辺指定

## 注意
複数写真を合成するため、元画像のEXIFやICCプロファイルは出力画像へ引き継ぎません。
