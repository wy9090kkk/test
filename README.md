2018.1.24
1.初步学习yii框架，主要内容如下
  （1）创建动作
       1.在controllers目录下的SiteController文件中SiteController类中创建一个新的方法，actionSay()用来加载页面中的hello字样
  （2）创建视图
       1.在views目录下的site目录下创建一个say文件，用来接受控制器的内容并加载模板
  （3）试运行
       1.输入http://localhost/basic/web/index.php?r=site/say&message=Hello+world来访问新创建的方法，页面会显示一个Hello world字样
  （4）总结
       1.学习到了controller层在创建的时候，是以控制器ID+Controller后缀形式去命名
       2.每一个控制器内的方法是以action+操作ID形式来命名
       3.访问时是在对应目录下 r（路由） = （控制器ID/操作ID）site/say&（参数）message=？？？形式来访问的