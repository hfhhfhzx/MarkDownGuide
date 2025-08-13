# MarkDownGuide
帮助人们学习如何写自述文件

自述文件使用markdown(以下简称为“md”)语言编写。因此此项目主要简绍如何写md

# ＂#＂号的作用

#号是一个自述文件的基石，它可以创建将一段段正文隔开的标题。

#号后面需要加一个空格，才能起到标题的作用，否则只能是个普通字符串

示例
```markdown
# 114514
1919810
```


# 换行
在md中，如果仅是按一下回车，那么上一行和下一行只会隔一段距离，并不会直接隔一行。因此，想要真正隔一行需要按两下回车

示例
```markdown
ngm
hfv

kjj

kll
```
效果

ngm
hfv

kjj

kll

# 特殊字符

  1.**号
  
这个字符串可以加粗字体，但本来用的字体就是粗体的话效果不是那么明显

示例
```markdown
**666**
```
效果

**666**

  2.~~号

这个字符串可以施加删除线的效果

示例
```markdown
~~777~~
```
效果

~~777~~

 3.```号

这个字符串可以显示代码。在第一个```后加上语言的名称可以对一些代码高亮。

示例

`` `kotlin

package hfhhfhzx.markdownguide

println(＂Hello World＂)

var tt = 3

`` `

(PS:第三个`号前我加了个空格，不然有麻烦)

效果

```kotlin
package hfhhfhzx.markdownguide

println(＂Hello World＂)
var tt = 3
```

 4.-号

这个符号与#号的机制类似，效果是一个原点

示例
```markdown
- 114
- 2145
```

效果

- 114
- 2145

 5.[]()号

这个号可以创建超链接。在小括号里输入URL可以跳转到这个URL，在小括号里输入./+文件名可以跳转到此github项目中自述文件所在目录的的文件，在小括号里输入#+标题名可以跳转到自述文件中的标题

示例
```markdown
[github](https://github.com)

[许可证](./LICENSE)

[114](#换行)
```

效果

[github](https://github.com)

[许可证](./LICENSE)

[114](#换行)

 6.>号
 
这个符号可以在文字前面加一条竖线

示例
```markdown
> 444

> [!CAUTION]
> 114

> [!Note]
>555

> [!WARNING]
>777
```

效果

> 444

> [!CAUTION]
> 114

> [!Note]
>555

> [!WARNING]
>777

# 徽标
徽标主要用于显示项目的一些基本信息

徽标由第三方驱动，我们要做的是调用它们

示例
```markdown
<a href="https://github.com/LSPosed/LSPosed/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/LSPosed/LSPosed?label=stars"></a>
<a href="https://github.com/LSPosed/LSPosed/forks"><img alt="GitHub forks" src="https://img.shields.io/github/forks/LSPosed/LSPosed"></a>
<a href="https://github.com/LSPosed/LSPosed/blob/main/LICENSE"><img alt="GitHub License" src="https://img.shields.io/github/license/LSPosed/LSPosed"></a>
<a href="https://github.com/LSPosed/LSPosed/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/LSPosed/LSPosed"></a>
<a href="https://github.com/LSPosed/LSPosed/discussions"><img alt="GitHub discussions" src="https://img.shields.io/github/discussions/LSPosed/LSPosed"></a>
<a href="https://socialify.git.ci/LSPosed/LSPosed/image?font=Rokkitt&forks=1&issues=1&language=1&name=1&owner=1&pattern=Brick%20Wall&pulls=1&stargazers=1&theme=Auto"><img alt="GitHub" src="https://socialify.git.ci/LSPosed/LSPosed/image?font=Rokkitt&forks=1&issues=1&language=1&name=1&owner=1&pattern=Brick%20Wall&pulls=1&stargazers=1&theme=Auto"></a>
<a href="https://www.star-history.com/#LSPosed/LSPosed&Timeline"> <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=LSPosed/LSPosed&type=Timeline"></a>
<a href="https://github.com/LSPosed/LSPosed/graphs/contributors"><img src="https://contrib.rocks/image?repo=LSPosed/LSPosed"></a>
<a href="https://github.com/LSPosed/LSPosed"><img alt="Repo Card" src="https://github-readme-stats.vercel.app/api/pin/?username=LSPosed&repo=LSPosed"></a>
```

(PS:由于我的项目~~无人问津~~局限性太大，所以我使用LSPosed项目示范。把＂LSPosed/LSPosed＂换为你们的仓库即可直接使用)

效果

<a href="https://github.com/LSPosed/LSPosed/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/LSPosed/LSPosed?label=stars"></a>
<a href="https://github.com/LSPosed/LSPosed/forks"><img alt="GitHub forks" src="https://img.shields.io/github/forks/LSPosed/LSPosed"></a>
<a href="https://github.com/LSPosed/LSPosed/blob/main/LICENSE"><img alt="GitHub License" src="https://img.shields.io/github/license/LSPosed/LSPosed"></a>
<a href="https://github.com/LSPosed/LSPosed/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/LSPosed/LSPosed"></a>
<a href="https://github.com/LSPosed/LSPosed/discussions"><img alt="GitHub discussions" src="https://img.shields.io/github/discussions/LSPosed/LSPosed"></a>
<a href="https://socialify.git.ci/LSPosed/LSPosed/image?font=Rokkitt&forks=1&issues=1&language=1&name=1&owner=1&pattern=Brick%20Wall&pulls=1&stargazers=1&theme=Auto"><img alt="GitHub" src="https://socialify.git.ci/LSPosed/LSPosed/image?font=Rokkitt&forks=1&issues=1&language=1&name=1&owner=1&pattern=Brick%20Wall&pulls=1&stargazers=1&theme=Auto"></a>
<a href="https://www.star-history.com/#LSPosed/LSPosed&Timeline"> <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=LSPosed/LSPosed&type=Timeline"></a>
<a href="https://github.com/LSPosed/LSPosed/graphs/contributors"><img src="https://contrib.rocks/image?repo=LSPosed/LSPosed"></a>
<a href="https://github.com/LSPosed/LSPosed"><img alt="Repo Card" src="https://github-readme-stats.vercel.app/api/pin/?username=LSPosed&repo=LSPosed"></a>
