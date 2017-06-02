# About

This is a repository forked from holic/movabletype-to-jekyll.  
The script has been customized for me.  
はてなブログから出力したMovableType形式のエクスポートファイルから変換しやすいように手を加えています。

-

## TIPS

- 変換前にエクスポートファイルの追記の区切りを`<!-- more -->`などに変えておく（そのままだと抜粋部分しか変換されません）

# Import your MovableType articles into Jekyll

1. `git clone` this repo
2. `npm install` dependencies
3. Export your MovableType articles and put in `in/` directory within this repo
4. `coffee index.coffee` to convert

Feel free to open issues or fork/pull request.

### TODO:

- Better README
