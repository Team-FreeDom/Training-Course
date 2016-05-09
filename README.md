---
title: github协作指南
tags: github,教程,协作
grammar_cjkRuby: true
---


欢迎进入 **{思博课}(S P O C)协作模式**，github客户端图形界面用SourceTree。

### 项目文档协作示范，我这里写一个简单的流程，大家可以参考一下：
----------
1. 首先fork主持人的项目
2. 把fork过去的项目也就是你的项目clone到你的本地
3. 先在本地创建一个新分支develop，develop就是属于你的专用分支不用同步到远端
4. 然后在本地切换到新分支
5. 运行 git remote add upstream 把项目主持人的库添加为远端库
6. 运行 git remote update更新，SourceTree则用获取操作。
7. 运行 git fetch upstream master 拉取我的库的更新到本地，SourceTree则用拉取操作
8. 运行 git rebase upstream/master 将我的更新合并到你的分支
这是一个初始化流程，只需要做一遍就行，之后请一直在develop分支进行修改。


----------


**如果修改过程中主持人的库有了更新，请重复6、7、8步。**

修改之后，首先push到你的库，然后登录GitHub，在你的库的首页可以看到一个 *pull request* 按钮，点击它，填写一些说明信息，然后*提交*即可。

