# Markdown语法
## 一、标题
# HelloWorld 1
> 一个“#”可以把一行变成大标题
## HelloWorld 2
> 两个“#”可以把一行变成次级标题，以此类推

你好世界！这是我的**第一个**Markdown文档

<br>

## 二、链接和图片
[百度](https://www.baidu.com "官网主页")


> [百度](https://www.baidu.com "官网主页"）可以生成超链接

[百度][1]

[1]: https://www.baidu.com  "官网主页"

[百度][1]

>参考式链接  
>```  
>[Baidu][1]
>
>[1]: https://www.baidu.com  "官网主页"
>
>可以生成参考式链接
>复用格式:[百度][1]
>```  
<br>


![Image](https://github.com/orchidblessing/ChinaMobile_BillingSystem/blob/master/bilibili.png)

>```![Image](https://github.com/orchidblessing/ChinaMobile_BillingSystem/blob/master/bilibili.png)可以插入网络图片  ```

![Image](bilibili.png)

> ```![Image](bilibili.png)```把图源放在本地同目录，可以直接导入。
<br>

<www.baidu.com>

>自动链接

## 三、代码块分割线和着重表示
">"
>">"可以生成代码块

Horizontal Rule

---
>"---"空行三横线分割线

**加粗**

>四个“*”括住的字加粗

这个文档*体现了* 如下几点:

>两个“*”括住的字斜体

***混合嵌套斜体加粗***

>六个 * 或者四个 * 和两个_ ，即**_ _**都可以实现斜体加粗。

`Inline code` with backticks
>"`"两个Tab键上方的点，加亮

* ```六个点可以整块加亮文字部分```  
    对齐
 >Tab键可以和上标题对齐  

<br>

## 四、列表
无序列表：
* 做一些事
* 做另一些事
    + 第一步
    + 第二步
    + 第三步
        - 第一步
* 结束  
>用*和+等生成无序列表，符号后要加空格

有序列表：
1. 第一步
2. 第二步
3. 第三步  

>数字加点和空格，生成有序列表。四个空格或一个Tab，文字将原样输出

~~这段不要了~~  
~~**_这段不要了_**~~
>双波浪线是删除线~~ ~~
可以和粗体斜体叠加

<br>

## 五、转义字符  
* \\\
* \\#
* \\*  
显示为:
* \\
* \#
* \*

## 六、引用块
>此为引用块

在文字前加“> ”即可

>     代码块

五个空格在引用框中生成黑色代码块

>引用中嵌套引用
>>二级引用  
 
## 七、代码段落  

```
public class HelloWorld{
    public static void main(String[] args){
        System.out.println("Hello world!");
    }
}
```

> 采用\```代码```的方式原样输出代码。

## 八、表格
|Left-aligned|Center-aligned|Right-aligned|
|:---        |     :---:    |     ---:    |
|git status  |git status    |git status   |
|git diff    |git diff      |git diff     |

>```
>        |Left-aligned|Center-aligned|Right-aligned|
>        |:---        |     :---:    |     ---:    |
>        |git status  |git status    |git status   |
>        |git diff    |git diff      |git diff     |
>```

## 九、公式
$$\cos(2\theta)=\cos^{\lim_{x\to\infty}\exp(-x)}\theta-\sin^2\theta+\sum^n_{i=1}\phi^{2^{z_1}}_i$$
$$\begin{bmatrix}1&2&3\\4&5&6\\7&8&9\end{bmatrix}$$

>导出方式ctrl+p >clip  

<br>

## 十、插件：  

1. Name: Auto-Open Markdown Preview
Id: hnw.
2. Name: Markdown Checkbox
Publisher: Philipp Kief
3. Name: Markdown Shortcuts
Id: mdickin.
4. Name: Markdown+Math
Id: goessner.mdmath
5. Name: Paste Image
Id: mushan.
