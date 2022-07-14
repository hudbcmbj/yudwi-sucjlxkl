
0.给本项目个stars

1.将本项目fork至自己仓库修改`Deploy to app`按键指向地址为自己仓库地址

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/hudbcmbj/yudwi-sucjlxkl) 

2.点击上面紫色`Deploy to app`，会跳转到heroku app创建页面，应用程序名无需填写也能创建，名字会由heroku随机生成，选择节点（美国或者欧洲），新用户只需要自定义UUID码和CADDYIndexPage（参考：[Caddy主页配置](https://github.com/DaoChen6/IF-XTW/blob/master/README.md#5caddy%E4%B8%BB%E9%A1%B5%E9%85%8D%E7%BD%AE))，其他建议保持默认，点击下面deploy，几秒后搞定！   

3.若出现`We couldn't deploy your app because the source code violates the Salesforce Acceptable Use and External-Facing Services Policy.`提示，则返回仓库，>`Setting`>`Repository name`修改仓库名。

4.若执行了第3步修改仓库名的操作，则必须修改app.json中的name和description，十分重要，切记！！！！

5.注意`repository`必须留空以免项目被禁

6.再修改`Deploy to Heroku`按键指向地址为自己仓库地址，重复`2`的操作

7.带有删除线的部分表示已经废弃或不适用


