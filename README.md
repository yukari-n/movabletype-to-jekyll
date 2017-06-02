# Import your MovableType articles into Jekyll

This is a repository forked from [holic/movabletype-to-jekyll](https://github.com/holic/movabletype-to-jekyll).  
The script has been customized for ~~me~~ Hatena Blog users.  
はてなブログから出力したMovableType形式のエクスポートファイルから変換しやすいように手を加えています。

- BASENAMEに`/`が含まれていてもエラーが出ないように修正（`-`に置き換え）
- OGP用画像があれば`<%- @meta.image %>`で利用できるように
- 時刻を日本時間に（`+0900`を追加）

## TIPS

- 変換前にエクスポートファイルの追記の区切りを`<!-- more -->`などに変えておく（そのままだと抜粋部分しか変換されません）
- テンプレートファイル（post.yml.eco）は各自カスタマイズ推奨

## TODO

- English README

---

## Original README

1. `git clone` this repo
2. `npm install` dependencies
3. Export your MovableType articles and put in `in/` directory within this repo
4. `coffee index.coffee` to convert

Feel free to open issues or fork/pull request.
