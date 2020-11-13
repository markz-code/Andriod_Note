# Command Lines

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

* **open 命令**
打开文件

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

* **其他**
> Ctrl + d        删除一个字符，相当于通常的Delete键  
> Ctrl + h        退格删除一个字符，相当于通常的Backspace键  
> Ctrl + u        删除光标之前到行首的字符  
> Ctrl + k        删除光标之前到行尾的字符  
> Ctrl + c        取消当前行输入的命令，相当于Ctrl + Break  
> Ctrl + a        光标移动到行首（Ahead of line），相当于通常的Home键  
> Ctrl + e        光标移动到行尾（End of line）  
> Ctrl + f        光标向前(Forward)移动一个字符位置  
> Ctrl + b        光标往回(Backward)移动一个字符位置  
> Ctrl + l        清屏，相当于执行clear命令  
> Ctrl + p        调出命令历史中的前一条（Previous）命令，相当于通常的上箭头  
> Ctrl + n        调出命令历史中的下一条（Next）命令，相当于通常的上箭头  
> Ctrl + r        显示：号提示，根据用户输入查找相关历史命令（reverse-i-search）  
> Ctrl + w        删除从光标位置前到当前所处单词（Word）的开头  
> Ctrl + y        粘贴最后一次被删除的单词  
> Command + K     清屏  
> open .          用Finder打开当前的位置  
> Tab键补全文件名

