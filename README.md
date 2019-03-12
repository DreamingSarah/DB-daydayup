![Alt "Trackio Audio Player"](http://img.imgur.com/rECNn8j.png "Trackio Audio Player")

代码说明  ：

   	1. 源码在src文件夹，大家在这里面写代码，外面的文件不用动
   	2. model包是整个项目的模型
          	1. track：音乐对象
          	2. trackList：播放列表对象
   	3. util包包含播放器的逻辑，暂时没摸清楚
   	4. view包放置前端配置文件和控制器类（控制器类的概念参考javaFx教程）
   	5. （前端同学注意） .fxml文件是 javaFx 的前端配置文件，用SceneBuilder打开后就能修改图形界面
   	6. （前端同学注意） 后缀名为controller的类都是控制器类，前端组件传递的参数可以在这里获得

  源码在src文件夹，整个项目使用Ant部署  




安装配置教程（IDEA 版）  

  1.环境需求  
    	jdk8 
   	 javaFx SceneBuilder  
    	Ant

  2.本地运行步骤  
      （1）clone这个包到本地，并在IDEA中打开  
      （2）在IDEA配置javaFx，JDK，和Ant  
      （3）打开IDEA的Ant界面（右上角），点＋号，在文件目录里找build.xml，然后添加。  
      （4）在Ant界面找到  jfx-project-run 点击运行

​	

