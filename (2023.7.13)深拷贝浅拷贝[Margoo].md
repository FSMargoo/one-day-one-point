<style type="text/css">
/*提示：如果你看到了这行文字，那说明您的预览器不支持内嵌 CSS 代码，请使用 VSCode 阅读本 Markdown 文件*/

body{font-size:15px;color:#333;background:#fff;font-family:Helvetica, Arial, "PingFang SC", "Microsoft YaHei", "WenQuanYi Micro Hei", "tohoma,sans-serif";margin:0;padding:10%}h1{font-size:2.2em;font-weight:700;line-height:1.1;padding-top:16px;margin-bottom:4px}h2, h3, h4, h5, h6{line-height:1.5em;margin-top:2.2em;margin-bottom:4px}h2{color:#ffffff !important;background-color:#ff9b98;border-left:12px solid #FF7E79;padding :1px 1px 1px 20px}h3{font-weight:700;font-size:1.2em;line-height:1.4;margin:10px 0 5px;padding-top:10px}h4{font-weight:700;text-transform:uppercase;font-size:1.1em;line-height:1.4;margin:10px 0 5px;padding-top:10px}h5, h6{font-size:.9em}h5{font-weight:bold;text-transform:uppercase}h6{font-weight:normal;color:#AAA}img{width:100%;border-radius:5px;display:block;margin-bottom:15px;height:auto}dl, ol, ul{margin-top:12px;margin-bottom:20px;padding-left:5%;line-height:1.8}p{margin:0 0 20px;padding:0;line-height:1.8}a{color:#f22f27;text-decoration:none}a:hover{color:#f55852;text-decoration:underline}a:focus{outline-offset:-2px}blockquote{font-size:1em;font-style:normal;padding:30px 38px;margin:0 0 15px;position:relative;line-height:1.8;text-indent:0;border:none;color:#888}blockquote:before{content:"“";left:12px;top:0;color:#E0E0E0;font-size:4em;font-family:Arial, serif;line-height:1em;font-weight:700;position:absolute}blockquote:after{content:"”";right:12px;bottom:-26px;color:#E0E0E0;font-size:4em;font-family:Arial, serif;line-height:1em;font-weight:700;position:absolute;bottom:-31px}strong, dfn{font-weight:700}em, dfn{font-style:italic;font-weight:400}del{text-decoration:line-through}pre{margin:0 0 10px;font-size:13px;line-height:1.42857;word-break:break-all;word-wrap:break-word;border-radius:4px;white-space:pre-wrap;display:block;background:#f8f8f8;padding:10px 20px;border:none;margin-bottom:25px;color:#666;font-family:Courier, sans-serif}code{color:#c7254e;background-color:#f9f2f4;border-radius:4px;font-family:Menlo, Monaco, Consolas, "Courier New", monospace;padding:2px 4px;font-size:90%}p>code{color:#c7264e;background-color:#f9f2f4;font-size:.95em;border-radius:3px;-moz-border-radius:3px;-webkit-border-radius:3px}figure{margin:1em 0}figcaption{font-size:0.75em;padding:0.5em 2em;margin-bottom:2em}figure img{margin-bottom:0px}hr{border:0;height:1px;background:#333;background-image:linear-gradient(to right, #ccc, #333, #ccc)}ol p, ul p{margin-bottom:0px}li{margin-bottom:0.75em;margin-top:0.75em}ol#footnotes{font-size:0.95em;padding-top:1em;margin-top:1em;margin-left:0;border-top:1px solid #eaeaea;counter-reset:footer-counter;list-style:none;color:#555;padding-left:5%;margin:20px 0}ol#footnotes li{margin-bottom:10px;margin-left:16px;font-weight:400;line-height:2;list-style-type:none}ol#footnotes li:before{content:counter(footer-counter) ". ";counter-increment:footer-counter;font-weight:800;font-size:.95em}@keyframes highfade{0%{background-color:none}20%{background-color:yellow}100%{background-color:none}}@-webkit-keyframes highfade{0%{background-color:none}20%{background-color:yellow}100%{background-color:none}}a:target, ol#footnotes li:target, sup a:target{animation-name:highfade;animation-duration:2s;animation-iteration-count:1;animation-timing-function:ease-in-out;-webkit-animation-name:highfade;-webkit-animation-duration:2s;-webkit-animation-iteration-count:1;-webkit-animation-timing-function:ease-in-out}a:target{border:0;outline:0}animation-iteration-count:1;-webkit-animation-timing-function:ease-in-out}a:target{border:0;outline:0}tion-iteration-count:1;-webkit-animation-timing-function:ease-in-out}a:target{border:0;outline:0}
</style>
<div align="center">
<h1><font  color="#ff7e79"><svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-bookmark-check-fill" viewBox="0 0 16 16">
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
本文作者：Margoo
<br>
<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-calendar2-event-fill" viewBox="0 0 16 16">
  <path d="M3.5 0a.5.5 0 0 1 .5.5V1h8V.5a.5.5 0 0 1 1 0V1h1a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1V.5a.5.5 0 0 1 .5-.5zm9.954 3H2.545c-.3 0-.545.224-.545.5v1c0 .276.244.5.545.5h10.91c.3 0 .545-.224.545-.5v-1c0-.276-.244-.5-.546-.5zM11.5 7a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5h-1z"/>
</svg>
发布时间：2023年7月13日

<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-book-fill" viewBox="0 0 16 16">
  <path d="M8 1.783C7.015.936 5.587.81 4.287.94c-1.514.153-3.042.672-3.994 1.105A.5.5 0 0 0 0 2.5v11a.5.5 0 0 0 .707.455c.882-.4 2.303-.881 3.68-1.02 1.409-.142 2.59.087 3.223.877a.5.5 0 0 0 .78 0c.633-.79 1.814-1.019 3.222-.877 1.378.139 2.8.62 3.681 1.02A.5.5 0 0 0 16 13.5v-11a.5.5 0 0 0-.293-.455c-.952-.433-2.48-.952-3.994-1.105C10.413.809 8.985.936 8 1.783z"/>
</svg>
内容概要：本文将会介绍 C++ 中深拷贝与浅拷贝以及其相关的一些知识。

</h3>

## 值语义和引用语义
在介绍深拷贝、浅拷贝以前，需要先了解 C++ 中的值语义（Value Semantics）和引用语义（Reference Semantics），先来说值语义，假设有两个对象 a，b，若 a = b 以后，b 的改变不会影响到 a，则说明这两个变量具有值语义。

其实，所有的原始变量（Primitive Variable）都具有值语义（原始变量包括即类似于 int 这种数据），又称为 POD（Plain Old Data），对于一个具有值语义的原始变量，变量赋值可以转换成内存的原内存拷贝（Bitwise Copy），所谓原内存拷贝，即为类似 memcpy 这样的拷贝，原始对象不需要调用 memcpy，只需要使用等号就可以复制内存，同时注意，STL 中大部分的模板类都是由值语义的（如 std::string, std::vector, std::function 和 std::thread 除外）。

然而引用语义则变量保存的就是对值的引用，形如 a = b 的赋值不会拷贝一份新的副本，两个变量值占有一份内存空间，此时可以理解为这块内存空间的别名，或者是 a 的别名，最典型的例子就是指针。

说的更通俗一点就是，若有赋值语句 a = b 以后，b 的状态的改变依然能影响到 a 状态的改变，则说明这是一个引用语义。

## 深拷贝与浅拷贝
在上文介绍到了值语义与引用语义，现在我们再来讨论深拷贝与浅拷贝，假设有一个类 A 定义如下：

```cpp
class A
{
public:
    ~A()
    {
        delete ptr;
    }

public:
    bool Equal()
    {
        return value == *ptr;
    }

public:
    int  value;
    int* ptr;
};
```
此时并没有 A 声明构造函数与构析函数，编译器将会隐式为类 A 生成拷贝函数，一般来说，这个编译器生成的拷贝函数会把两个 A 的示例直接复制过来（注意是值上的复制），即为如下的形式：
```cpp
A(const A& Instance)
{
    value = Instance.value;
    ptr   = Instance.ptr;
}
```
那么也就是说，编译器不会去管值语义与引用语义，这个赋值有可能是具有值语义的，可能是具有引用语义的，如果有下面这一行代码：
```cpp
int main()
{
    A C;
    {
        A D;
        D.value = 1;
        D.ptr   = new int(1);

        C = D;
    }

    if (C.Equal())
    {
        return 0;
    }

    return 1;
}
```
这个时候问题就出现了，D 处于大括号内的作用域，而 A 处于大括号外的作用域，D 作为局部变量，超出作用域以后就会被销毁，因为 C = D 中，两个成员变量 ptr 之间的赋值是引用语义，而并非值语义，所以就会导致 D 调用构析函数以后销毁了 ptr 指针，而此时 C 中的 ptr 成员也受到了影响，最终就会导致 C.Equal() 返回的并不是 true 而是 false，这种拷贝形式我们就称之为浅拷贝。

那么深拷贝则就是当 C = D 的时候，C 中的 ptr 同 D 中的 ptr 指向了不同的内存，我们需要手动编写一系列构造函数如下所示：

```cpp
A(const A& Instance)
{
    value = Instance.value;
    ptr = new int(*Instance.ptr);
}
A(A& Instance)
{
    value = Instance.value;
    ptr = new int(*Instance.ptr);
}
void operator=(const A& Instance)
{
    value = Instance.value;
    ptr = new int(*Instance.ptr);
}
```
此时的 ```ptr = new int(*Instance.ptr);``` 则就是一个拷贝构造了，再次运行上面的测试代码， C.Equal() 成功返回 true。

## 为什么编译器不实现深拷贝
这是因为深拷贝不可能实现，一个指针指向的对象有可能是一个数组，也有可能是多态，也可能需要更多的操作才能实现一次拷贝，这些问题都不是编译器能预料到的，所以只能交由用户自行设计。

事实上除了深拷贝和浅拷贝，C++ 中还有移动语义和拷贝交换以及移动构造这两个操作，他们同深浅拷贝有不同的引用场景，这些我们会在日后的文章再讨论。