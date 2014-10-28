xcdebugger
==========

使用github保存XCode的xcdebugger设置


####一. XCode的用户自定义Breakpoint保存路径:
 	
 	/Users/xxxx/Library/Developer/Xcode/UserData/xcdebugger/Breakpoints.xcbkptlist    
 XCode启动时会自动读取此文件。

###二. 如果已经将xcdebugger设置提交到了Github网站，以下步骤可以将远程xcdebugger和当前正在使用的XCode关联起来:   

1. 下载并安装Github for Mac客户端   
[http://mac.github.com/](http://mac.github.com/)   
下载完成之后将Github.app拖动到如下电脑应用目录中: Macintosh HD/应用程序,启动github程序。

2. 输入github账户及密码，可以看到github网站的远程客户端上的所有工程

3. 在alex520biao/xcdebugger工程上，点击Clone to Computer，
最终存放位置为: Macintosh HD/Users/xxxx/Library/Developer/Xcode/UserData/xcdebugger
Macintosh HD(当前盘符)，xxxx(当前用户);   
路径可以简写为: ~/Library/Developer/Xcode/UserData/xcdebugger   
~表示当前系统用户根目录;      
如果用户的资源库文件已经被隐藏,那么请参考: 显示/隐藏Mac用户的资源库目录.rtf

4. 这样xcdebugger目录中的内容就和Github网站上的对应项目联系起来了。   
XCode会从此目录中读取CodeSnippets供编程使用，我们通过XCode添加/修改/删除任何xcdebugger内容，也会保存在此目录中。

5. 打开Github程序，进入alex520biao/xcdebugger工程，我们就可以看到哪些内容将会被提交到Github网站的svn服务器上。

6. 同样，我们在Github网站上对alex520biao/xcdebugger工程的任何更改，都可以通过Github.app更新到本地。

7. 打开Github.app程序，在alex520biao/xcdebugger上选择Remove，本地文件不会被删除，只是本地文件和远程svn服务器的联系将会被终止。

####其他    
同理XCode的Templates(模板)也可以通过此方法上传到Github网站上;


