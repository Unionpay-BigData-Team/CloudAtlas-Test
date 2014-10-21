# CloudAtlas-Test是什么

本仓库定位于`云图测试管理平台`，主要提供测试计划、测试案例以及测试问题的管理等。

# 使用说明

- 加入organization `Unionpay-BigData-Team`
- `fork`本项目
- 偏右上的Notifications选择Be Notified of all conversations
- Test case 请在自己的项目下做修改，然后发一条`pull request`，请求Merge到主分支
- 右侧是工具栏，常用的是issues，里面有测试遇到的各种问题，并且包含问题状态以及指派由谁来解决
- Wikies大家不妨有什么想法可以写写
 

# 如何更新fork后的代码
- 在本地装好github客户端，或者git客户端
- clone 自己的fork分支到本地，可以直接使用github客户端，clone到本地，如果使用命令行，命令为：<br />
  `git clone git://github.com/Unionpay-BigData-Team/CloudAtlas-Test.git CloudAtlas-Test`
- 增加源分支地址到你项目远程分支列表中(此处是关键)，命令为：<br />
  `git remote add myPro git://github.com/Unionpay-BigData-Team/CloudAtlas-Test.git`<br />
  此处可使用git remote -v查看远程分支列表
- fetch源分支的新版本到本地<br />
  `git fetch myPro`
- 合并两个版本的代码<br />
  `git merge myPro/master`
- 将合并后的代码push到github上去<br />
  `git push origin master`
  
