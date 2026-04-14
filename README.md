# ガラス価格表アプリ - 公開手順

## 必要なもの
- GitHubアカウント（無料）→ https://github.com
- このフォルダの3ファイル：index.html / manifest.json / sw.js

---

## STEP 1：GitHubにサインアップ（アカウントがない場合）
1. https://github.com にアクセス
2. 「Sign up」からメールアドレスで無料登録

---

## STEP 2：新しいリポジトリを作成
1. GitHubにログイン後、右上の「+」→「New repository」
2. Repository name に `glass-price-app` と入力
3. 「Public」を選択（GitHub Pagesは無料枠でPublicが必要）
4. 「Create repository」をクリック

---

## STEP 3：ファイルをアップロード
1. 作成したリポジトリのページで「uploading an existing file」をクリック
2. index.html、manifest.json、sw.js の3ファイルをドラッグ＆ドロップ
3. 下の「Commit changes」ボタンをクリック

---

## STEP 4：GitHub Pages を有効にする
1. リポジトリページの「Settings」タブをクリック
2. 左メニューの「Pages」をクリック
3. Branch: 「main」を選択 → 「Save」
4. しばらくすると以下のURLでアクセスできるようになります：
   → https://【あなたのユーザー名】.github.io/glass-price-app/

---

## STEP 5：スマホのホーム画面に追加

### iPhoneの場合（Safari推奨）
1. SafariでアプリのURLを開く
2. 下の共有ボタン（四角＋矢印）をタップ
3. 「ホーム画面に追加」をタップ
4. 「追加」をタップ → アイコンがホーム画面に出現！

### Androidの場合（Chrome推奨）
1. ChromeでアプリのURLを開く
2. 右上の「⋮」メニュー →「アプリをインストール」または「ホーム画面に追加」
3. 「インストール」をタップ → 完了！

---

## ポイント
- オフラインでも動作します（一度アクセスすれば電波なしでOK）
- 価格改定時は index.html を編集して再アップロードするだけ
- URLを共有すれば他のスタッフも使えます

---

## アイコン画像について（任意）
manifest.jsonにアイコンの設定がありますが、画像がなくてもアプリは動作します。
きれいなアイコンを設定したい場合は、以下で自動生成できます：
→ https://favicon.io/favicon-generator/
生成した icon-192.png と icon-512.png を同じフォルダに置いてください。
