capture-image
=============

Cross-platform screenshots for emacs    
跨平台截图插件

# 安装
### 安装jre.
  程序为java,需要jre的支持.这里不再详述安装方法.  
  linux可以参考: http://iyf.cc/archives/253
 
  可以通过`java -version)`来检查是否安装.
### 安装capture-image
直接`git clone https://github.com/iyf/capture-image.git`到你的load-path.    
然后在.emacs中加入  

        (require 'capture-image)
        ;;bind hot key
        (global-set-key (kbd "C-c C-h") 'iyf-screenshot);;

快捷键可以自定义.  
默认情况下:  
  `C-c C-h`  
即可启动截图,屏幕会出现十字形,左键拉动即可选择返回,释放左键就完成.  
会自动保存文件并插入当前位置.

# 使用
  执行后会出现十字行，点击左键后拉动即可选取范围，松开左键就自动保存，在选择界面按ESC可以取消。
# 注意
必须要安装jre才能使用.  

# 其他
java截图程序来自于: https://github.com/iyf/CaptureImage  
其他即将加入的功能请查看该项目.

我的blog:http://iyf.cc
