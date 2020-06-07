---
title: Style a form
date: 2020-06-07T16:46:07.616Z
tags:
  - CSS
---
做了一个Design Technologist的面试题。要求style一个form，给了HTML，只写CSS，不改动HTML。最终要实现的效果是这样的：

![final form](images/contact-us-mock.png)

我写的CodePen是这样的：

<p class="codepen" data-height="265" data-theme-id="light" data-default-tab="css,result" data-user="jimmieego" data-slug-hash="VwLVmPY" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Form style">
  <span>See the Pen <a href="https://codepen.io/jimmieego/pen/VwLVmPY">
  Form style</a> by Tao Zhang (<a href="https://codepen.io/jimmieego">@jimmieego</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

一些经验：
- Layout用了flexbox
- 应该要用CSS variable把颜色，spacing等先定义好，这样将来更新方便
- 把label放到input里面要用`position: relative`
- Custom的radio button是用CSS的shape