# studytype-shindan

GitHub Pages で公開する **StudyType 勉強診断** 専用サイトです。

## ページ

| ファイル | 内容 |
|---------|------|
| `index.html` | トップ（`studytype.html` へリダイレクト） |
| `studytype.html` | StudyType 勉強診断（24問・ペン選択式） |
| `assets/` | 16タイプのキャラ画像（JPEG） |

## 公開URL（設定後）

- トップ: `https://taichiadi.github.io/studytype-shindan/`
- 診断: `https://taichiadi.github.io/studytype-shindan/studytype.html`

## 更新のしかた

1. `studytype.html` を編集
2. コミット → **push**（下記「初回の公開」参照）
3. 数分後にサイトが自動更新されます

## 初回の公開（GitHub に上げてサイトを出す）

ローカルには最新版があるが GitHub に push できないときは、**ブラウザだけ**でも公開できます。

### 1. ファイルを GitHub に上げる

1. https://github.com/taichiadi/studytype-shindan を開く（`taichiadi` でログイン）
2. **Add file** → **Upload files**
3. このフォルダからドラッグ＆ドロップ:
   - `studytype.html`
   - `index.html`
   - `README.md`
   - `assets` フォルダ（中の jpg 16枚ごと）
4. 下のメッセージ例: `StudyType診断を公開`
5. **Commit changes**

※ Cursor のターミナルで `git push` が失敗する場合は、**Mac の「ターミナル」アプリ**で同じフォルダから `git push` を試す（Cursor の認証エラーを避けられることがあります）。

### 2. GitHub Pages をオンにする

1. リポジトリの **Settings** → 左 **Pages**
2. **Build and deployment** → Source: **Deploy from a branch**
3. Branch: **main**、Folder: **/ (root)** → **Save**
4. 1〜3分待つと URL が表示される

### 3. 公開URL

- https://taichiadi.github.io/studytype-shindan/
- https://taichiadi.github.io/studytype-shindan/studytype.html

ブラウザで **スーパーリロード**（Mac: `Cmd + Shift + R`）すると最新が見えます。
