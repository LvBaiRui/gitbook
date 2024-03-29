## 标题

```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6
```



## 强调

```markdown
强调，又叫做斜体，使用 *星号* 或 _下划线_。

重点强调，又叫做粗体，使用 **星号** 或 __下划线__。

使用 **星号和_下划线_** 组合使用强调。

删除线使用两个波浪线。~~划掉这个~~
```



_强调_

__重点强调__

**组合_强调_**

~~删除~~



## 列表

```markdown
1. 有序列表的第一项
2. 另外一个项
..* 无序子列表
1. 事实上序号不起作用，那只是一个数字而已
..1. 有序子列表
4. 最后一个项

...你可以适当的缩紧列表项中的段落。注意上面的空行和前导空格（至少一个，但是这里我们使用三个来对齐原始的Markdown内容）。

...换行而不形成段落，你需要使用两个尾部空格。..
...注意这行是分开的，但还在同一个段落中。..
...（这个违背了不需要尾部空格的典型的GFM换行行为）。

* 无序列表可以使用星号
- 或者减号
+ 或者加号
```

1. 有序
2. 有序2

* 无序
* 无序2



## 链接

有两种创建链接的方式。

```markdown
[内嵌式链接](https://www.google.com)

[带标题的内嵌式链接](https://www.google.com "谷歌的主页")

[引用式链接][arbitrary case-insensitive reference text]

[相对引用一个库文件](../blob/master/LICENSE)

[你可以在引用式链接定义中使用数字][1]

或者空着什么都不写 [link text itself]

用来说明引用链接的文字可以放在后面。

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
```



[百度](http://www.baidu.com)



## 脚注

Markdown默认使用的脚注样式链接不会在页面中显示。有时包含一个读者可见的非超链接注脚很有用。对于这样的注脚，GitBook支持的一种简单的语法。

```markdown
Text prior to footnote reference.[^2]
[^2]: Comment to include in footnote.
```

## 图片

```markdown
内嵌式
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

引用式
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/ic
```



## 代码和语法高亮

代码块是Markdown规范的一部分，但是语法高亮不是。然而，很多渲染器，比如GitHub的和*这里的Markdown*，都支持语法高亮。支持那种语言以及语言的名字应该怎样写随渲染器的不同而变化。*这里的Markdown*支持许语言；查看完整的列表，以及如何写语言的名字





 代码块要么被包含三个反引号 ````` 的行包围，要么被四个空格缩进。推荐仅仅使用被包围的代码块，它们使用方便并且只有它们支持语法高亮。 

## 表格

表格不是Markdown规范的核心部分，但是它是GFM的一部分，*这里的Markdown*也支持它。

```markdown
冒号可以用来对其列。

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

外部的管道符 (|) 是可选的，而且不需要优雅的排列Markdown。你还可以在表格中内嵌其他Markdown。

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```

## 块引用

```markdown
> 在邮件中块引用中很方便用来仿真文本的回复。
> 这行是同一个块的一部分。

引用结束

> 当这行很长的文字被包裹的时候，它依然会被恰当的引用。让我们继续写下去来确保包裹它
```

## 内嵌HTML

You can also use raw HTML in your Markdown, and it'll mostly work pretty well.

你同样可以在Markdown中使用HTML，并且它能很好的工作。

```markdown
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
```

## 水平线

```markdown
三个或者更多...

---

连字符

***

星号

___

下划线
```

***sjanj***

## Youtube视频

视频不能被直接添加，但你可以添加一个链接至视频的图片，像这样：

```markdown
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
```

或者，使用纯Markdown，但是会丢失掉图片的大小和边框：

```markdown
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](
```

