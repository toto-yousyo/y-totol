+++
title = "Org-roamを学び始める"
author = ["toto"]
tags = ["orgroam"]
draft = false
+++

{{< figure src="/ox-hugo/Screenshot from 2023-01-29 11-21-01.png" >}}

Org-roam というものがある。[&gt;Org-roam](https://www.orgroam.com/)がメモを取っていくのに役立つのなら、これを中心に記憶の宮殿を作成していく。

Org-roam についての[&gt;マニュアル](https://www.orgroam.com/manual.html)を確認しながら実行する。また、Org-roam のブログがいくつかあるので、下記のもののとおり、一旦やって理解を深めてみる。

[Boris Buliga - Task management with org-roam Vol. 1: Path to Roam](https://d12frosted.io/posts/2020-06-23-task-management-with-roam-vol1.html)

上記ブログでは、Meta-project ごとに PROPERTIES を作成し、その中でカテゴリーを分けた。

```text
:CATEGORY: Org-roam
:CATEGORY: blog
```

org-agenda-filter- by -category でこのカテゴリーごとに表示を分けていたが、"No mactch point"とでて、何も表示されなかった。

しかし、これはまず、org-agenda view で、TODO List に行き、mactch todo/prop/tags[m]を選択する必要があった。

## TODO
### org-roam のブログを見ながら同じようにやってみる
### Tangent のファイルも移行してみる
- それに ID を自動的にふる方法を探す
- ID をふっていく
### タグの使用方法を調べる
### プロジェクトはどのように設定するか
- タスクが集まったものが project
- ブログのように最終結果がないものは Meta-project とよぶ
### Resource をフォルダで作成する
- ウェブのブックマークリンクはここに入れていく
- タグをふる
