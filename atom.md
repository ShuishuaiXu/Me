9.29
### 学习使用atom
### 目标：
1. 搞清楚atom是什么，为什么要用atom，atom和其他代码编辑器有什么区别和优势
> atom是一个代码文本编辑器+众多各种功能的库和插件。既极简高效，又可以通过安装第三方库和插件来丰富自己的功能，还支持markdown,内置git版本控制器。应该这样说，atom既可以是像Vim,Sublime Text这样的纯粹的编辑器，也可以通过插件变成全能的IDE.

> 其实atom有点类似于chrome，只提供简单的功能，然后自己去搭配适合自己的插件
2. 看一下atom的文档，熟悉atom的用法
  - [介于纯粹的文本编辑器和臃肿的IDE之间](https://sspai.com/post/43674)
3. 常见的文本编辑器：
> `vim`,`emacs`,`Sublime Text`, `Atom`, `VS Code`和`Notepad++`
4. 问题1：atom上面修改过的文档怎么直接推送到github上面
> 现在好像解决了，只有保存之后才会显示git提交的命令，但是又遇到了一个新的问题，这样的话github desktop还有用没有
5. 问题2：好像右下角的undo不能都用，否则会把之前的记录也会提交上去
>好像已经解决了

>到底解决了没有呀

>在github上做的改变

>在atom上做的改变

>第二次在github上做的改变

>这一次好像真的懂了，以前都摁错了，undo是撤销之前的提交，而commit master里面是要写这一次做了什么改变

6. **总结：atom配合github的使用**
> 在atom上面每次先要fetch一下，看看github上面有什么修改没有，如果有，则pull一下，如果没有，则自己在atom上面写好之后CTRL+s保存，然后把改版从unstaged changes放到staged changes，在commit message的栏里简短的写上这一次的改变，然后点击commit to master，最后点击push

7. 好像还可以撤销之前提交的修改
>这个现在用处还不是太大，了解就行

8. atom有很多很好的插件或者叫库，以后可以尝试找几个用用
