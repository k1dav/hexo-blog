---
title: Hello World
excerpt: "先放點與 Hexo 與 Redefine Theme 有關的資料..."
---
先放點與 [Hexo](https://hexo.io/) 與 [Redefine Theme](https://redefine-docs.ohevan.com/) 有關的資料


## Redefine Block Demo
### Notes
{% notel default fa-info 訊息 %}
長訊息
長訊息
{% endnotel %}

{% note  %}
短訊息
{% endnote %}

### Buttons
{% btn center::Google::https://google.com.tw::fa-brands fa-google %}

```
center, regular, large, center large, center regular
```

### Folding
{% folding blue::藏起來了 %}

被發現了
 
{% endfolding %}

```
yellow, blue, green, red, orange, pink, cyan, white, black, gray
```

### Tabs
{% tabs First unique name %}
<!-- tab First Tab-->
**This is Tab 1.**
<!-- endtab -->
 
<!-- tab Second Tab-->
**This is Tab 2.**
 
This is Tab 2.
<!-- endtab -->
 
<!-- tab Third Tab-->
**This is Tab 3.**
 
This is Tab 3.
 
This is Tab 3.
<!-- endtab -->
{% endtabs %}

### [Mermaid](https://mermaid.js.org/)
```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```


## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)
