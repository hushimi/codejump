# Reset CSS

- [destyle.css](https://github.com/nicolas-cusan/destyle.css)
- [modern.css](https://github.com/Andy-set-studio/modern-css-reset)
- [ress.css](https://github.com/filipelinhares/ress)

---

# 手順

- デザインからセクションを分ける
- セクションでなんのタグ使うか決める
- ***

# Memo

## Beginner01

[picture tag](https://zero-plus.io/media/html-picture/)

- レスポンシブに画像を切り替えるために使用する
  [Google Photos link](https://theblueback.com/post-20230115172246)
- Google Photos から共有リンク作成

## Beginner02

- HERO イメージ
- 画像と文章を隣り合わせにする

---

## First commit

```bash
git init
git add -A
git commit -m ''
git remote add origin git@github.com:hushimi/codejump.git
# localブランチの上流を origin masterに移動
git push -u origin master
```

## create branch

```bash
# list branch
git branch
git branch -r

# create branch
git branch beginner01
git checkout beginner01

# merge branch to HEAD
git merge beginner01

# delete branch
git branch -d localBranch
git push origin --delete remoteBranch
```
