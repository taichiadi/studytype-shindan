# studytype-shindan

GitHub Pages で公開する **studyType診断** 専用サイトです。

## ページ

| ファイル | 内容 |
|---------|------|
| `index.html` | トップ（`studytype.html` へリダイレクト） |
| `studytype.html` | studyType診断（24問・ペン選択式） |
| `assets/` | 16タイプのキャラ画像（JPEG） |

## 公開URL

リポジトリ名が `studytype-shindan` のとき、GitHub Pages の URL は次の形になります。

- トップ: `https://<GitHubユーザー名>.github.io/studytype-shindan/`
- 診断: `https://<GitHubユーザー名>.github.io/studytype-shindan/studytype.html`

※ サイト内のシェア URL は **開いているドメインから自動で決まります**（特定ユーザー名はコードに書いていません）。

独自ドメインを使う場合は `studytype.html` の `SITE_URL_OVERRIDE` に URL を指定してください（末尾 `/` 推奨）。

## 更新のしかた

1. `studytype.html` を編集
2. コミット → **push**
3. 数分後に GitHub Pages が更新されます

## 初回の公開

### 1. ファイルを GitHub に上げる

1. 自分の GitHub でリポジトリ `studytype-shindan` を開く（または新規作成）
2. **Add file** → **Upload files**
3. このフォルダからドラッグ＆ドロップ:
   - `studytype.html`
   - `index.html`
   - `README.md`
   - `assets` フォルダ（jpg 16枚）
4. **Commit changes**

### 2. GitHub Pages をオンにする

1. リポジトリの **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main**、Folder: **/ (root)** → **Save**
4. 表示された URL を確認（1〜3分かかることがあります）

### 3. 確認

ブラウザで **スーパーリロード**（Mac: `Cmd + Shift + R`）して表示を更新してください。
