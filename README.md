# Android学习记录
------

主要用来记录学习过程中用到的工具、问题

## 速查表
### [AndroidStudio](https://github.com/markz-code/Android_Note/blob/master/cheatsheets/androidstudio.txt)

### [Git](https://github.com/markz-code/Android_Note/blob/master/cheatsheets/git.txt)

### [ADB](https://github.com/markz-code/Android_Note/blob/master/cheatsheets/adb.txt)

### Vim
Vim常见模式：

* 一般指令模式（command mode）Vim启动后的默认模式  
* 编辑模式（insert mode）编辑模式需要输入i、o、a任意一个字母之后才可以编辑文件内容。在编辑模式中，可以按ESC键回到默认模式。  
* 命令行模式（command-line mode）在命令行模式中可以输入会被解释成并执行的文本。例如执行命令（":"键），搜索（"/"和"?"键）或者过滤命令（"!"键）。在命令执行之后，Vim返回到命令行模式之前的模式，通常是默认模式。  

Vim基本操作：

* vim test.md 初始进入编辑器命令模式。
* 输入i进入编辑模式。
* 在编辑模式中，可以按ESC键回到命令模式。
* :wq保存退出。
* :q!不保存强制退出。

### Sublime Text
### Command Lines

* **pwd 命令**  
[print working directory] 查看当前所处目录的路径  
> pwd -P 目录连接链接时，显示出实际路径，而非使用连接（link）路径；  
> pwd显示的是连接路径
	
* **cd 命令**  
[change directory] 切换目录  
> cd /home 进入 '/ home' 目录'   
> cd .. 返回上一级目录  
> cd ../.. 返回上两级目录   
> cd 进入个人的主目录   
> cd ~user1 进入个人的主目录   
> cd - 返回上次所在的目录    

* **ls 命令**  
[list] 查看目录中的文件  
> ls 查看目录中的文件，不包括隐藏文件  
> ls -a 查看当前目录下所有文件(包括隐藏文件)  
> ls -al 查看当前目录下所有文件(包括隐藏文件)的详细信息   

* **mkdir 命令**  
[make directory] 创建文件夹  
> mkdir projects 创建projects文件夹  
> mkdir project1 project2 同时创建两个目录

* **touch 命令**  
创建文件
> touch readme.md 创建readme文件 

* **rm 命令**  
[remove] 删除文件  
> rm readme.md  删除readme文件  
> rm –i 删除已有文件之前先进行删除确认提示  
> rm –i test 删除一个名为test的文件  
> rm –r readme.md 这个操作可以连同这个目录下面的子目录都删除  
> rm –rf readme.md 强制删除（force），没有确认删除提示  

* **mv 命令**  
[move] 重命名或移动文件  
> mv test new1 将文件text重命名为new  

* **cat 命令**  
[concatenate] 查看文件内容  
> cat text 查看text文件中的内容 

* **cp 命令**  
[copy] 将一个或多个源文件或者目录复制到指定的目的文件或目录  
> cp file1 file2 复制一个文件  
> cp dir/* . 复制一个目录下的所有文件到当前工作目录   
> cp -a /tmp/dir1 . 复制一个目录到当前工作目录   
> cp -a dir1 dir2 复制一个目录  

* **清屏**  
> clear  || ctrl+l  

* **翻页&内容过多**
> Enter     向下n行，需要定义，默认为1行  
> Ctrl+f    向下滚动一屏  
> 空 键      向下滚动一屏  
> Ctrl+b    返回上一屏  
> =         输出当前行的行号  
> :f        输出文件名和当前行的行号  
> v         调用vi编辑器  
> ! 命令     调用Shell，并执行命令  
> q         退出more

* **Tab键补全文件名**

### [Markdown](https://www.zybuluo.com/mdeditor#)  
换行-->>两个空格  

### [Mac](https://support.apple.com/zh-cn/HT201236)
