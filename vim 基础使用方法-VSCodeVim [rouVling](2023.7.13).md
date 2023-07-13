<style type="text/css">
/*提示：如果你看到了这行文字，那说明您的预览器不支持内嵌 CSS 代码，请使用 VSCode 阅读本 Markdown 文件*/

body{font-size:15px;color:#333;background:#fff;font-family:Helvetica, Arial, "PingFang SC", "Microsoft YaHei", "WenQuanYi Micro Hei", "tohoma,sans-serif";margin:0;padding:10%}h1{font-size:2.2em;font-weight:700;line-height:1.1;padding-top:16px;margin-bottom:4px}h2, h3, h4, h5, h6{line-height:1.5em;margin-top:2.2em;margin-bottom:4px}h2{color:#ffffff !important;background-color:#9c8af0;border-left:12px solid #755ceb;padding :1px 1px 1px 20px}h3{font-weight:700;font-size:1.2em;line-height:1.4;margin:10px 0 5px;padding-top:10px}h4{font-weight:700;text-transform:uppercase;font-size:1.1em;line-height:1.4;margin:10px 0 5px;padding-top:10px}h5, h6{font-size:.9em}h5{font-weight:bold;text-transform:uppercase}h6{font-weight:normal;color:#AAA}img{width:100%;border-radius:5px;display:block;margin-bottom:15px;height:auto}dl, ol, ul{margin-top:12px;margin-bottom:20px;padding-left:5%;line-height:1.8}p{margin:0 0 20px;padding:0;line-height:1.8}a{color:#f22f27;text-decoration:none}a:hover{color:#f55852;text-decoration:underline}a:focus{outline-offset:-2px}blockquote{font-size:1em;font-style:normal;padding:30px 38px;margin:0 0 15px;position:relative;line-height:1.8;text-indent:0;border:none;color:#888}blockquote:before{content:"“";left:12px;top:0;color:#E0E0E0;font-size:4em;font-family:Arial, serif;line-height:1em;font-weight:700;position:absolute}blockquote:after{content:"”";right:12px;bottom:-26px;color:#E0E0E0;font-size:4em;font-family:Arial, serif;line-height:1em;font-weight:700;position:absolute;bottom:-31px}strong, dfn{font-weight:700}em, dfn{font-style:italic;font-weight:400}del{text-decoration:line-through}pre{margin:0 0 10px;font-size:13px;line-height:1.42857;word-break:break-all;word-wrap:break-word;border-radius:4px;white-space:pre-wrap;display:block;background:#f8f8f8;padding:10px 20px;border:none;margin-bottom:25px;color:#666;font-family:Courier, sans-serif}code{color:#c7254e;background-color:#f9f2f4;border-radius:4px;font-family:Menlo, Monaco, Consolas, "Courier New", monospace;padding:2px 4px;font-size:90%}p>code{color:#c7264e;background-color:#f9f2f4;font-size:.95em;border-radius:3px;-moz-border-radius:3px;-webkit-border-radius:3px}figure{margin:1em 0}figcaption{font-size:0.75em;padding:0.5em 2em;margin-bottom:2em}figure img{margin-bottom:0px}hr{border:0;height:1px;background:#333;background-image:linear-gradient(to right, #ccc, #333, #ccc)}ol p, ul p{margin-bottom:0px}li{margin-bottom:0.75em;margin-top:0.75em}ol#footnotes{font-size:0.95em;padding-top:1em;margin-top:1em;margin-left:0;border-top:1px solid #eaeaea;counter-reset:footer-counter;list-style:none;color:#555;padding-left:5%;margin:20px 0}ol#footnotes li{margin-bottom:10px;margin-left:16px;font-weight:400;line-height:2;list-style-type:none}ol#footnotes li:before{content:counter(footer-counter) ". ";counter-increment:footer-counter;font-weight:800;font-size:.95em}@keyframes highfade{0%{background-color:none}20%{background-color:yellow}100%{background-color:none}}@-webkit-keyframes highfade{0%{background-color:none}20%{background-color:yellow}100%{background-color:none}}a:target, ol#footnotes li:target, sup a:target{animation-name:highfade;animation-duration:2s;animation-iteration-count:1;animation-timing-function:ease-in-out;-webkit-animation-name:highfade;-webkit-animation-duration:2s;-webkit-animation-iteration-count:1;-webkit-animation-timing-function:ease-in-out}a:target{border:0;outline:0}animation-iteration-count:1;-webkit-animation-timing-function:ease-in-out}a:target{border:0;outline:0}tion-iteration-count:1;-webkit-animation-timing-function:ease-in-out}a:target{border:0;outline:0}
</style>
<div align="center">
<h1><font  color="#755ceb"><svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-bookmark-check-fill" viewBox="0 0 16 16">
  <path fill-rule="evenodd" d="M2 15.5V2a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v13.5a.5.5 0 0 1-.74.439L8 13.069l-5.26 2.87A.5.5 0 0 1 2 15.5zm8.854-9.646a.5.5 0 0 0-.708-.708L7.5 7.793 6.354 6.646a.5.5 0 1 0-.708.708l1.5 1.5a.5.5 0 0 0 .708 0l3-3z"/>
</svg>
每天一个技术点</font>
</h1>
</div>

<HR>

<h3>
<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-person-fill" viewBox="0 0 16 16">
  <path d="M3 14s-1 0-1-1 1-4 6-4 6 3 6 4-1 1-1 1H3Zm5-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6Z"/>
</svg>
本文作者：rouVling
<br>
<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-calendar2-event-fill" viewBox="0 0 16 16">
  <path d="M3.5 0a.5.5 0 0 1 .5.5V1h8V.5a.5.5 0 0 1 1 0V1h1a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1V.5a.5.5 0 0 1 .5-.5zm9.954 3H2.545c-.3 0-.545.224-.545.5v1c0 .276.244.5.545.5h10.91c.3 0 .545-.224.545-.5v-1c0-.276-.244-.5-.546-.5zM11.5 7a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5h-1z"/>
</svg>
发布时间：2023.7.13
<br>

<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-book-fill" viewBox="0 0 16 16">
  <path d="M8 1.783C7.015.936 5.587.81 4.287.94c-1.514.153-3.042.672-3.994 1.105A.5.5 0 0 0 0 2.5v11a.5.5 0 0 0 .707.455c.882-.4 2.303-.881 3.68-1.02 1.409-.142 2.59.087 3.223.877a.5.5 0 0 0 .78 0c.633-.79 1.814-1.019 3.222-.877 1.378.139 2.8.62 3.681 1.02A.5.5 0 0 0 16 13.5v-11a.5.5 0 0 0-.293-.455c-.952-.433-2.48-.952-3.994-1.105C10.413.809 8.985.936 8 1.783z"/>
</svg>
内容概要：vim 的入门使用

</h3>


## 0. Vim 安装
教程使用 VSCodeVim 扩展作为例子，没有接触过vim的读者请到 vscode 搜索扩展Vim 并安装

## 1.Vim 的三种模式
vim 常用的模式有三种，normal mode，insert mode，visual mode一般进去之后就是 normal mode <br>
normal mode 下不能编辑，但是可以进行光标的移动，复制，粘贴，撤销，以及输入命令等操作<br>
insert mode 下，编辑器的行为和一般编辑器没有区别，编辑<br>
visual mode 下，编辑器进行区域选择<br>

为了防止有的读者进去后乱按切换到其他模式了，在这里顺便讲一下模式之间的切换：按下 esc 键从insert 或者 visual mode切换到 normal mode，按下 i 或 a 从 normal mode 切换到 insert mode，按下 v从normal mod 切换到 visual moode

当前的模式会在vscode 下方栏显示

## 2.normal mode 下的命令
## 2.1 - 基本的光标移动
以下操作均在normal mode 模式下生效

(<b>注意区分大小写！！！</b>，本篇大部分命令都是小写)：
$$\begin{matrix}
\text{j}&\text{向下移动一行}\\
\text{k}&\text{向上移动一行}\\
\text{h}&\text{向左移动一个字符}\\
\text{l}&\text{向右移动一个字符}
\end{matrix}$$
这是最最常用的四个按键，建议先尝试一下熟悉一下，我们再继续<br>
什么？你说移动起来太慢了不如点鼠标跳转？那我们来点快的
$$\begin{matrix}
\text{w}&\text{向右移动一个单词}&\text{可以理解为 word}\\
\text{b}&\text{向左移动一个单词}\\
\text{\$ (shift + 4)}&\text{移动到行末尾}\\
\wedge \text{ (shift + 6)}&\text{移动到一行开头}\\
\text{gg(按两下g)} & \text{跳转到文档开头}\\
\text{G}&\text{跳转到文档尾}
\end{matrix}$$
除此之外，你还可以在 h j k l 四个移动指令前面加上数字，比如输入 3 j 就可以往下移动3行，20 h 往左移动20个字符。以及也可以在 gg 命令前面输入数字，比如 3 g g 就可以跳转到第三行

会了这些后，光标移动就轻松多了。会vim 之前，我最不喜欢写完一行后用鼠标点一下定位到行末尾，在加上一个分号。现在你可以输入 \<Esc\> \$ a 直接定位行位，然后轻松愉快地补上分号了 :)

## 2.2 normal mode 切换 insert mode
前面说 normal mode 切换到 insert mode 可以按 a 或者 i ，现在我们再补充一些
$$\begin{matrix}
\text{a}&\text{进入insert mode 并定位到 normal mode 光标右侧}&\text{可以理解为 append}\\
\text{i}&\text{进入insert mode 并定位到 normal mode 光标左侧}&\text{可以理解为 insert}\\
\text{o (小写)}&\text{在当前行下面插入一行，然后定位到新行}\\
\text{O (大写)}&\text{在当前行上面插入一行，然后定位到新行}\\
\end{matrix}$$

## 2.3 normal mode 下删除
虽然是删除，也许说是剪切更好一点？<br>
d d （连按两下d）表示删除这一行，删除的内容被保存在 vim 的剪贴板里面<br>
你也可以按一下 d 然后后面再结合前面所讲的光标移动命令，比如 d w 就可以删除当前光标到当前单词尾部的所有内容，d $ 可以删除当前到行末尾的所有内容。d+j d+k d+数字+j 这些就由读者自行推理其行为吧

c 和 d 效果也差不多，只不过是删除后进入 insert mode 而已。读者可以自行体会 :) <br>

不过需要补充一下 c 还有一个很常用的用法。输入 c i w 可以完整删除当前光标所在的这个单词，即便是光标在单词的正中间。

## 2.4 normal mode 下复制
复制命令 y 类似于 d , yy 复制一行，y后加移动命令选择复制的地方。<br>
复制完之后可以在normal mode 下按 p 进行粘贴 :)
记得这里的复制用的是 vim的剪贴板，而不是系统的剪贴板

## 2.5 normal mode 下撤销
使用 u 进行撤销<br>
使用 ctrl + r 进行重做 <br>
可惜的是， ctrl + r 被 visual studio 占用了，visual studio 里面的vim插件不能正常重做 :(

## 3 insert mode
insert mode 就当普通编辑器用就好了，按esc回到normal mode前面也说过了<br>
恭喜你快速的过完了一章 :)

## 4 visual mode
visual mode 为选中模式，visual mode 里面你可以使用和 normal mode 里面相同的光标移动命令<br>
对于选中的行，你可以按 d 删除，按 y 复制

你也可以按 V（大写）进入 visual line mode, 以行为单位进行选取

你可以按 ctrl + v 进入 <b>visual block mode</b> 这下试试上下左右移动光标，你会发现选取呈块状。同样支持 d 删除， y 复制。至于 p 粘贴出来是啥样，请读者自行尝试 :)

## 5. 其他

命令：normal mode 实际上还没讲完，normal mode 下按冒号 : 可以进入命令，输入的命令会在vscode下方栏进行显示<br>

退出：命令中，输入 wq 进行保存并退出，输入 q! 不保存然后退出，保留了 linux vim 的原汁原味

搜索：normal mode下，不输入 : 直接输入 / 可以进行查找 比如搜索 insert ，就在normal mode 中输入 /inser<br>
回车确定后，可以输入 n 定位下一个，N 定位上一个

替换：命令中，输入 %s 替换，如果我想把insert 替换成 normal 我就要在normal mode 中输入 :/insert/normal<br>
这个功能vscode 做的还是很好的，请读者自行实验 :)

录制：normal mode 下，按 q后，输入一个名字后开始录制，录制的时候地下会显示 Recording @...<br>
normal mode中再按q停止录制。录制中的所有动作可以在normal mode 中输入 @ \<你定的名字\> 进行复现

## 6.杂项
vscode vim 还提供了key map,可以自定义按键映射，比如你可以将 i i 映射到 \<Esc\>(j k 这个组合可能更好一点)，这样你在编辑的时候就可以使用 i i 直接回到normal mode 而不用按esc了<br>
按 ctrl + shift + p 选择 open user settings(JSON) 进入。以下是我个人的部分配置,这里面将 j k 映射到 esc，将 s s s 映射到一个公式的代码

```json
{
    "vim.insertModeKeyBindings": [
        {
            "before": ["j", "k"],
            "after": ["<Esc>"]
        },
		{
			"before":["i", "i"],
			"after":["$"]
		},
		{
			"before":["s", "s", "s"],
			"after": ["\\", "s", "u", "m", "\\", "l", "i", "m", "i", "t", "s", " ", "_", "{", "i", "=", "1", "}", " ", "^", "n", " "]
		},
		{
			"before":["u", "u"],
			"after":["&"]
		}
    ],
    // "vim.visualModeKeyBindings":[
    //     {
    //         "before": ["j", "k"],
    //         "after": ["<Esc>"]
    //     }
    // ],
    "vim.normalModeKeyBindings": [
        {
            "before":[";"],
            "after": ["a", ";"]
        }
    ],
    "vim.statusBarColorControl": true,
    "vim.statusBarColors.visual": "#b55d02",
    "vim.statusBarColors.visualblock": "#a02236",
    "vim.statusBarColors.visualline": "#9C195B",
    "vim.statusBarColors.replace": "#6f1f45",
    "vim.statusBarColors.insert": "#6d8400",
    "vim.statusBarColors.normal": "#007575",
```
按键映射下面是状态栏颜色的设置


<br>
最后，每日音乐推荐 From The New World (来自新世界/自新大陆) - Antonín Leopold Dvořák
