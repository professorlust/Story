# Story
[![CircleCI](https://circleci.com/gh/MizukiSonoko/Story/tree/master.svg?style=shield)](https://circleci.com/gh/MizukiSonoko/Story/tree/master)  

This is a read-only mirror of "水樹素子の物語"

- Episode-1 [![Status](https://img.shields.io/badge/status-writing-yellowgreen.svg)]()  

# Major Release List 
- 水樹素子物語v0.1 C92(2017/8/13) [This](https://github.com/MizukiSonoko/Story/releases/tag/C92-v0.1)

# Release numbering
以下の規約でReleaseTagを切る。

----
```
1.x.x
```
本として発行する区切り

----
```
x.1.x
```
内容の更新の区切り

----
```
x.x.1
```
レイアウトの更新の区切り(内容の更新なし）

# Branch　

- master 読める程度にまとめたもの。
- snapshot　masterをpdfにしたもの。
- writing　執筆中（一般的にはdevelop）
- feature/**　特定の章等
- hotfix/**　誤字脱字。レイアウトミス

# Current working branch
[content.tex](https://github.com/MizukiSonoko/Story/blob/write/episode-1/content.tex)

# How to make
中でlatexを使用している。latexが入っている環境なら手元で製本できる。
```sh
cd C92
uplatex content.tex
dvipdfm content.tex
```

