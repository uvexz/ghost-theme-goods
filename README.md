# Ghost Theme Goods

A lite theme for [Ghost](http://github.com/tryghost/ghost/).

To download, visit the [releases](https://github.com/ygbhf/ghost-theme-goods/releases) page.

## About

Ghost-Theme-Goods is a minimalist Ghost blog theme inspired by [Goods.wtf](https://goods.wtf) and built on the Bootstrap 5 CSS framework. In order to achieve faster loading speeds in Mainland China, the subscription feature of Ghost blogs was abandoned, and the loading of Ghost-related framework JS was reduced.

Ghost-Theme-Goods 是一款极简风格的 Ghost 博客主题，设计灵感来自于 [Goods.wtf](https://goods.wtf)，基于 Bootstrap 5 CSS 框架制作，为了在大陆地区更快的加载，舍弃了 Ghost 博客的订阅功能，减少加载了 Ghost 相关框架 JS。

The theme comes with Artalk comments, and you must add the following code to `Settings` - `Code Injection` - `Site Footer`.

主题自带 Artalk 评论，须在 `Settings` - `Code Injection` - `Site Footer` 加上以下代码。

```
<script>
    Artalk.init({
        el:        '#comments',
        server:    'https://[your.server.domain]',
        site:      '[Your Site Name]',
    })
</script>
```

---

** When enabling this theme, you need to click "Active with errors".**

** 启用本主题时，需点击 `Active with errors`。**

## Screenshot 

![desktop](https://raw.githubusercontent.com/uvexz/ghost-theme-goods/main/assets/screenshot-desktop.png)

## Copyright & License

```
DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
Version 2, December 2004 

Copyright (C) 2023 YJK.

Everyone is permitted to copy and distribute verbatim or modified 
copies of this license document, and changing it is allowed as long 
as the name is changed. 

      DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION 

0. You just DO WHAT THE FUCK YOU WANT TO.
```
