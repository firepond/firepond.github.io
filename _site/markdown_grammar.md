# Markdown语法

 From Typora, by [firepond](firepond.github.io)



## [1.标题](#headings)

使用```## title```来表示标题， #的数量表示标题级别。

注意#与标题之间的空格。


```# 一级标题```
# 一级标题 

```## 二级标题```
## 二级标题

```### 三级标题```
### 三级标题

```#### 四级标题```
#### 四级标题

```##### 五级标题```

##### 五级标题

```###### 六级标题```

###### 六级标题



或者在标题的下一行加入一些 == 表示一级标题，加入一些--表示二级标题。

```
一级标题
======================
```

一级标题
======================
```
二级标题
-----------------------
```

二级标题
---------------------------------------------------------





## [2.引用](#quote)

在行首使用">"符号表示引用。

```
> To be or not to be, that is the question 
```
> To be or not to be, that is the question



可以使用多个">"嵌套引用。

```
> 引用
> >嵌套引用
> > > 多层嵌套
```
> 引用
> >嵌套引用
> >
> >> 多层嵌套



## [3.列表](#list)

列表项目标记通常放在行首，项目标记后面需要有一个空格。
### 无序列表
在行首使用 + , - 或 * 作为无序列表的标记。
```
- list element 1
+ list element 2
* list element 3
```


- list element 1
+ list element 2
* list element 3

  

### 有序列表

在行首使用数字和一个 . 表示有序列表。注意，渲染结果中的序号与源代码中的数字无关。

```
1. list element
2. list element
4. list element
```

1. list element
2. list element
4. list element



### 待办列表

使用```- [ ] todo```表示未勾选项目 

使用```- [x] done```表示已勾选项目

```
- [ ] learn golang
- [ ] python blog
- [x] CUDA test
```

- [ ] learn golang
- [ ] python blog
- [x] CUDA test



## [4. 强调](#emphasize)

使用 * 或 _ 表示强调



一个*或_表示斜体

```
*斜体*
_斜体_
```

*斜体*
_斜体_




两个 * 或 _ 表示加粗
```
**加粗**
__加粗__
```

**加粗**
__加粗__




## [5. 代码](#code)

使用```包裹文本来表示这是一段代码

行内代码:

```
​```System.out.println("Hello, world!");```
```

效果：```System.out.println("Hello, world!");```



代码块：

```
​```java
//代码块
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
​```
```

效果：

```java
//代码块
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```



## [6. 链接](#link)

```[firepond](https://firepond.github.io/ "my home page")```    [firepond](https://firepond.github.io/ "my home page")



## [7. 分割线](#split-line)

使用连续三个或更多的*, - 或 _表示分割线

```
***

---

_________________
```

***

---

_________________



## [8.图片](#picture)

```
![Jil](Jil.jpg "The famous bartender from va11-hall-a")
```
![Jil](Jil.jpg "The famous bartender from va11-hall-a")







## [9. 表格](#chart)



```
First Header | Second Header | Third Header
------------ | ------------- | ------------
Content Cell | Content Cell  | Content Cell
Content Cell | Content Cell  | Content Cell
```

First Header | Second Header | Third Header
------------ | ------------- | ------------
Content Cell | Content Cell  | Content Cell
Content Cell | Content Cell  | Content Cell



```
First Header | Second Header | Third Header
:----------- | :-----------: | -----------:
Left         | Center        | Right
Left         | Center        | Right
```

First Header | Second Header | Third Header
:----------- | :-----------: | -----------:
Left         | Center        | Right
Left         | Center        | Right



## [10. 公式](#math-expression)

```
$$
E=mc^2
$$
```





$$
E=mc^2
$$





## [11. 流程图](#diagram)


```
​```flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end

st->op->cond
cond(yes)->e
cond(no)->op
​```
```



```flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end

st->op->cond
cond(yes)->e
cond(no)->op
```

## [12. 锚点](#anchor-point)



