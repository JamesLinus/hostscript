# hostscript
My first Bash&amp;Python script to access google for Mainland Chinese users.

Running this script needs wget & Python3 installed.


Download from here：https://www.python.org/ftp/python/3.6.1/python-3.6.1-macosx10.6.pkg


Hosts file from：

https://github.com/racaljk/hosts 

credit to racaljk

使用方法：
不写E文了，这玩意儿估计老外也用不着，看了三页python书，写的脚本，解决下自己一直手动在替换的hosts，每次搞好麻烦有木有。
使用这个脚本电脑里要有Python3，mac自带Python2。但是3要自己装，readme第一个链接就是下载链接，下载双击安装即可。

还必须要有wget来下载远程文件安装办法：在终端里输入，以下依次两行代码并分别回车

ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

brew install wget

1.下载h.sh和hosts_edit.py两个文件，把它们放到用户文件夹里~，“/Users/你的用户名”

2.首次使用：打开你原来的hosts文件“/etc/hosts”，数一数有几行，然后用文本编辑器打开hosts_edit.py,请把

“while i < 23:”

这句里的23换成你的原来hosts的行数,一劳永逸，以后就不要改了。

3.运行直接在终端里输入sudo sh h.sh,然后输入密码回车即可。

PS：这个脚本比较适合盗版软件比较多的大陆用户，比如我LOL，之前用了好多hosts屏蔽一些软件的验证服务器。
代码风格比较烂，看看笑笑就可以啦，有需求的用户自取自用，谢谢~

谷歌的正确访问方式和常见问题看这里：

https://github.com/racaljk/hosts/wiki/The-hosts-FAQ

理论支持所有装有python3的Unix/Linux系统，我用mac，其他用户自己测试吧~
