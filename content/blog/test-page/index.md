---
title: プロジェクトのドキュメントの作成
date: "2022-02-10T22:12:03.284Z"
description: "ドキュメント作成のコツ。<br> エキスパートPythonプログラミング改訂3版　より"
---

テンプレを少しずつ変更しながら作っています（2022/02/10）!

構築環境はDockerを利用して、node環境を立ち上げ、Gatsbyを入れて使っています。あとnetlifyでホスティングしています。
[netlifyはこちら](https://www.netlify.com/).

以下で引用形式で記述できる様子。
> A salted duck egg is a Chinese preserved food product made by soaking duck
> eggs in brine, or packing each egg in damp, salted charcoal. In Asian
> supermarkets, these eggs are sometimes sold covered in a thick layer of salted
> charcoal paste. The eggs may also be sold with the salted paste removed,
> wrapped in plastic, and vacuum packed. From the salt curing process, the
> salted duck eggs have a briny aroma, a gelatin-like egg white and a
> firm-textured, round yolk that is bright orange-red in color.
> 私はわたしが好きなあなたが好きだ。←できた！

![DockerでGatsby環境の構築](./sample.png)

コードも以下のように書ける！↓

```js
const saltyDuckEgg = "今日は大雪注意報が発令されていて、関東でも積雪があった日"
```

| Number | Title                                    | Year |
| :----- | :--------------------------------------- | ---: |
| 1      | ハリーポッターと賢者の石 | 2001 |
| 2      | ハリーポッターと秘密の部屋  | 2002 |
| 3      | ハリーポッターとアズカバンの囚人 | 2004 |

[View raw (TEST.md)](https://raw.github.com/adamschwartz/github-markdown-kitchen-sink/master/README.md)

段落構成は以下の用な感じ！

    This is a paragraph.

# Header 1

## Header 2


# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6

    # Header 1
    ## Header 2
    ### Header 3
    #### Header 4
    ##### Header 5
    ###### Header 6


# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6

    # ヘッダー 1 #
    ## Header 2 ##
    ### Header 3 ###
    #### Header 4 ####
    ##### Header 5 #####
    ###### Header 6 ######

> Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

    > Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> ## This is a header.
>
> 1. リストはこんなかんじ～.
> 2. This is the second list item.
>
> Here's some example code:
>
>     Markdown.generate();

>これはどう
>以下、変換されないで書くことができる




    > ## This is a header.
    > 1. This is the first list item.
    > 2. This is the second list item.
    >
    > Here's some example code:
    >
    >     Markdown.generate();

- Red
- Green
- Blue

* Red
* Green
* Blue

- Red
- Green
- Blue

```markdown
- Red
- Green
- Blue

* Red
* Green
* Blue

- Red
- Green
- Blue
```

- `code goes` here in this line
- **bold** goes here

```markdown
- `code goes` here in this line
- **bold** goes here
```

1. Buy flour and salt
1. Mix together with water
1. Bake

```markdown
1. Buy flour and salt
1. Mix together with water
1. Bake
```

1. `code goes` here in this line
1. **bold** goes here

```markdown
1. `code goes` here in this line
1. **bold** goes here
```

Paragraph:

    Code

<!-- -->

    Paragraph:

        Code

---

---

---

---

---

    * * *

    ***

    *****

    - - -

    ---------------------------------------

This is [an example](http://example.com "Example") link.

[This link](http://example.com) has no title attr.

This is [an example][id] reference-style link.

[id]: http://example.com "Optional Title"

    This is [an example](http://example.com "Example") link.

    [This link](http://example.com) has no title attr.

    This is [an example] [id] reference-style link.

    [id]: http://example.com "Optional Title"

_single asterisks_

_single underscores_

**double asterisks**

**double underscores**

    *single asterisks*

    _single underscores_

    **double asterisks**

    __double underscores__

This paragraph has some `code` in it.

    This paragraph has some `code` in it.

![Alt Text](https://placehold.it/200x50 "Image Title")

    ![Alt Text](https://placehold.it/200x50 "Image Title")
