---
title: github协作指南
tags: github,教程,协作
grammar_cjkRuby: true
---


欢迎进入 **协作分享联盟**。
### 一、工具软件推荐：
----------
1. github本地客户端推荐用图形界面的[SourceTree](https://www.sourcetreeapp.com/)
2. 文档撰写不要用word，用支持markdown的网络文档工具，推荐用[小书匠](http://soft.xiaoshujiang.com/)
3. mardown[入门教程](http://www.jianshu.com/p/1e402922ee32/)、[官方教程](http://daringfireball.net/projects/markdown/syntax).

----------

### 二、共享协作范围：
----------
1. 任何团内成员均可发起项目，项目主持人需搭建初级框架。请先书写需求和协作方式，告之给大家。
2. 任何人都可参与项目，哪怕是修改一行也有贡献，请项目主持人实时更新主要贡献名单。
3. 团内目前有各高校各专业的教师，也有教育公司的技术骨干，还有有能力的学生，请大家自由发挥，思博课团队专业能力有限不负责引导。
4. 组织里所有的项目，均遵守开源精神，个人免费使用，商业请联系项目主持人。
5. 欢迎各位在协作过程中，技术人员自由组团队，公司也可猎人才，这里完全无政府无组织。
6. 大家在项目中上传图片时，请处理下大小，尽量用文档交流，视频就不要上传了，可发链接共享。

----------
### 三、协作示范，我这里写一个简单的流程，请不熟悉的用这个项目作为测试：
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

----------
### 四、github视频使用教程
----------
1. [为什么要使用github](http://v.youku.com/v_show/id_XMTU4MzY2NTEwNA==.html?f=27319436&from=y1.2-3.4.1)
2. [初识github](http://v.youku.com/v_show/id_XMTU4NDI1ODI1Ng==.html?f=27319436&from=y1.2-3.4.2)
3. [不同行业在github上发布项目的经验](http://v.youku.com/v_show/id_XMTU4NDMwODc3Ng==.html?f=27319436&from=y1.2-3.4.3)
4. 在github上参与项目
5. 在github上主持和管理项目
6. 常见操作错误

