<ol>标签是一个有序列表容器（ordered list），会在内部的列表项前面产生数字编号。列表项的顺序有意义时，比如排名，就会采用这个标签。

```
<ol>
  <li>列表项 A</li>
  <li>列表项 B</li>
  <li>列表项 C</li>
</ol>
```

<ol>标签内部可以嵌套<ol>标签或<ul>标签，形成多级列表。

该标签有以下属性。

（1）reversed

reversed属性产生倒序的数字列表。

（2）start

start属性的值是一个整数，表示数字列表的起始编号。

（3）type

type属性指定数字编号的样式。目前，浏览器支持以下样式。

* a：小写字母
* A：大写字母
* i：小写罗马数字
* I：大写罗马数字
* 1：整数（默认值）
