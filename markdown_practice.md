I learned a lot from my friend [Guojia Qi](https://github.com/yuan-qi5), I appreciate his guidance a lot!

**标题**


# 一级
## 二级
### 三级 

一个空格在 # 和标题之间进行分隔
======

要创建段落，使用空白行将一行或者多行文本进行分隔。

example:
I really like using Markdown.

I think I will have good luck in my research journey.

I love you.
I thinik I'll use it to format all of my documents from now on.

I love you.  
I thinik I'll use it to format all of my documents from now on.

I really like using Markdown.<br>
I find that our university support us to start doing our research at anytime.

换行
========
结尾空格（通过两个或者多个空格进行 + 回车进行换行，或者结尾添加`<br>`
> 我不知道 br 是什么的缩写唉

粗体：通过在文本前后各添加两个 星号 ** 或者 两个下划线 __，推荐使用 星号 <br>
**有什么办法能够** **快速打出`<br>`吗** __直接打好麻烦，practice makes perfect?__

斜体：在文本前后各添加一个 星号 或者 下划线<br>
*I like theorem proving* <br>
_doing something you really like is really enjoyable_

同时使用粗体和斜体的话，用三个 星号 就可以啦<br>
*我是**粗斜体*** ： 斜体在外 粗体在内
======
**引用**
======
块引用：通过 > 创建  
**多个段落的块引用通过为 空白行 添加 > 实现  
> I really like this.
>
> I will use it to document all of my work in the future.

**嵌套快引用**通过 >> 实现
> Can a language model learn and exploit?
> I need learn some neural-symbolic approaches
>> Doing research is challenging but meaningful.

**带有其他元素的块引用**  <br>
块引用可以包含其他 Markdown 格式的元素，但并非所有元素都可以使用，需要进行实验以查看那些有效 <br>
> ### 标题
> **粗体** *斜体* ***粗斜体***

**列表**
=======
**有序列表** : 在每个列表项前添加数字并紧跟一个英文句点，数字不必按数学顺序排列，但列表应以数字 1 起始<br>
example : <br>
1. first item
2. second item
3. third item

**无序列表** ： 在列表项前添加破折号 - 、星号 * 、或 加号 + 。缩进一个或多个列表项可创建嵌套列表。
- first item
- second item
- third item

或者是这样<br>
* first iterm
* second iterm

或者是这样<br>
+ you
+ and me
+ and whom?

note : 选择一种符号并坚持下去，不要混用

**在列表中嵌套其他元素** ： 要在保留列表连续性同时在列表中添加另一种元素，请将该元素缩进四个空格或一个制表符（如段落、引用块）。若要嵌入代码块、列表（本身采用四个空格或一个制表符缩进），则缩进八个空格或两个制表符。 <br>
example : <br>
1. first item
2. second item
3. third item
    - indented item
    - indented item
4. fourth item

======
要将单词或短语表示为**代码**，请将其包裹在反引号中 <br>
example : <br>
At the command prompt, type `nano`. <br>

转义反引号 ：   <br>
要表示为代码的单词或短语中包含一个或多个反引号，则可以通过将单词或短语包裹在双反引号中 <br>
example :   <br>
`` Use `code` in your Markdown file .``

代码块 ： 要创建代码块，请将代码块的每一行缩进至少四个空格或一个制表符, 用三个反引号即可  
example :  
```python
    print("hello world")   
    print("world hello")
```
example :
```C++
    int a = 1
```
example :
``` lean
    example (l : ℝ) : Tendsto (fun n : ℕ => l) atTop (𝓝 l) := by
      simpa using tendsto_const_nhds
```
> I don't know how to creat a lean4 code block.

**分隔线**
======
要创建分割线，请在单独一行上使用三个或多个 *** , 破折号 --- ，或下划线 ___ ,并且不能包含其他内容。  
为了兼容性，请在分割线前后均添加空白行。   

---

***

___

**链接**
=====
链接放在中括号内，链接地址放在后面的括号中，链接 title 可选<br> 
超链接 Markdown 语法代码 : `[超链接显示名](超链接地址 '超链接 title')`   
example :   
这是一个链接 [Markdown 语法](https://markdown.com.cn 'Markdown 教程')  

带格式化的链接    
**强调**链接 ： 在链接的语法前后增加星号    
要将链接表示为**代码**，在方括号`内`添加反引号    
example :
Here is my friend: [yuan-qi5](https://github.com/yuan-qi5 'You can also be my friend!!')  
I love deepseek **[deepseek](https://chat.deepseek.com/ 'deepseek 官网')**    
This is the gpt [`gpt`](https://chatgpt.com/ 'gpt 官网')   

