大标题
===
中标题
---

横线(星号减号和下划线)
***
---
___
---
标题（使用#）<br>


#一级标题 <br>
##二级标题 <br>


使用"\"转义\<br><br>
显示超链接直接输入url<br>
　　显示文本行首的空格使用全角 <br>
        单行文本 两个TAB


多行文本        
每行行首使用两个TAB
    
       文本块
       
        在连续几行的文本开头加入1个Tab或者4个空格

        使用一对三个反引号

换行
---
在上一行文本后面补两个空格，
下一行换行

或者就是在两行文本直接加一个空行。

也能实现换行效果，不过这个行间距有点大。





        
部分文字的高亮 <br>
使用`TAB 键上方的`括起来
还要注意`英文输入法`情况下<br>

文字超链接
[文字](url)<br>

鼠标悬停显示文字效果
[文字](url "悬停显示")


        
插入符号        
圆点 （*加一个空格）
* 显示圆点符
* 二级三级圆点 前多加一个两个TAB 
    * 二级圆点
        * 三级圆点  

#缩进     
>第一层

>>第二层
>>>第三层
>>>>"使用>符号 第几层缩进就用几个常用于引用 "     


        #插入图片
        
"![](url)"
[]括号里可以加入一些 标识性的信息  


![baidu](/image/360截图20171217213810966.jpg "logo")

来源于网络的图片 的URL
---
http://www.baidu.com/img/bdlogo.gif

GitHub仓库里的图片 的URL
---
 https://github.com/ 你的用户名 / 你的项目名 / raw / 分支名 / 存放图片的文件夹 / 该文件夹下的图片

 给图片加上超链接
 ---
 [![baidu]](http://baidu.com)  

[！[csdn-logo]][csdn]

起的标识可以任意但上下文一定要一致

[baidu]:http://www.baidu.com/img/bdlogo.gif


插入代码片段
===
“用三个TAB上方的\```括起来<br>
若要实现代码高亮 在开头的第一行(\```括起来 )写上语言比如C Java c++ cpp ”
```Java
public static void main(String[] args) {}//Java
```
```c
int main(int argc, char *argv[]) //C
```
```Bash
echo "hello GitHub" #Bash
```
```javascript
documen.getElementById("myH1").innerHTML="welcome";//javascript
```
```python
if a < 0:
    print("a<0") #python
```


[参考](https://github.com/guodongxiaren/README)














        











