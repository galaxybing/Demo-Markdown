

文本样式
=
（＝等于号，数量大于1个以上）
=
（＝等于号，上面补空行则只显示下横线）


横杠
-
（-横杠，数量大于1个以上）


#井号
##井号
###井号
####井号
#####井号
######井号

####斜体、粗体、删除线
|语法|效果|
|----|-----
|`*斜体1*`|*斜体1*
|`_斜体2_`|_斜体2_
|`**粗体1**`|**粗体1**
|`__粗体2__`|__粗体2__
|`这是一个 ~~删除线~~`|这是一个 ~~删除线~~
|`***斜粗体1***`|***斜粗体1***
|`___斜粗体2___`|___斜粗体2___
|`***~~斜粗体删除线1~~***`|***~~斜粗体删除线1~~***
|`~~***斜粗体删除线2***~~`|~~***斜粗体删除线2***~~

斜体、粗体、删除线可混合使用

布局样式
=


***
（***，3个及以上星号为粗横线）


布局换<br />行  
(换行，使用\<br />或者在上一行文本后面补两个空格)
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />


 空格布局  
(默认的文本行首空格都会被忽略，要显示空格布局,需要将输入法由半角改成全角；苹果的 Mac OS 系统自带的输入法是不具有全角半角切换的功能，请自行安装对应中文输入法)

    单行文本
(行首两个 tab 空格)

    多行文本，行一
    多行文本，行二
    
(各行首两个 tab 空格或者4个空格，且整体前后补空行后生效)
```
    多行文本，行一
    多行文本，行二
``` 
(整体前后补3个反引号)


文本行内`引用块`  
（\`\`反引号）

>缩进竖线1级
>>缩进竖线2级
>>>缩进竖线3级
>>>>缩进竖线4级
>>>>>缩进竖线5级
>>>>>>缩进竖线6级

圆点符
* 星号表示圆点符
(星号* 后面有一个空格，无空格时则仍表示普通*号符)

操作样式
=
文本超链接

|#|语法|效果|
|---|----|-----
|1|`[我的博客](http://noonteam.com "悬停显示")`|[我的博客](http://noonteam.com "悬停显示")
|2|`[我的知乎][zhihu] `|[我的知乎][zhihu] 
|2|`[zhihu]:https://www.zhihu.com/people/wang-yin-he-30/activities "我的知乎，欢迎关注"`|   

语法2由两部分组成：
- 第一部分使用两个中括号，[ ]里的标识符（本例中zhihu），可以是数字，字母等的组合，标识符上下对应就行了（**姑且称之为URL标识符**）
- 第二部分标记实际URL。

引用图片资源
使用web资源链接  
（![](http://getfirebug.com/img/firebug-large.png) ）
使用仓库内部的图片资源链接  
（![](https://github.com/galaxybing/demo-Markdown/raw/master/assets/firebug.png) ）

语法高亮

```Java
public static void main(String[]args){} //java
```

```C
int main(int argc, char *argv[]) //c
```

```Bash
echo "hello github" # bash
```

```Javascript
function person(){ // javascript
    this.name= "galaxyw";
}
person.prototype.study= function(){};
```

--------------------------------
[csdn]:http://noonteam.com "我的博客"
[zhihu]:https://www.zhihu.com/people/jellywong "我的知乎，欢迎关注"
[baidu-logo]:http://www.baidu.com/img/bdlogo.gif "百度logo"
[weibo-logo]:/img/weibo.png "点击图片进入我的微博"
[csdn-logo]:/img/csdn.png "我的CSDN博客"
[firebug]:https://github.com/galaxybing/demo-Markdown/raw/master/assets/firebug.png
