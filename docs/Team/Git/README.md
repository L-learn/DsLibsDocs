!>内部协同开发Git说明

### 内部Gitlub管理地址
安装在内部路由器上，访问地址:<br>
http://192.168.1.250:50000/

#### 登录注册内网Gitlab
  注意:注册完了以后 需要让maksim把你的git号加到团队组里面

###### 内部Git创建项目的代码仓库
访问上面那个链接 登录后会就能进入项目列表界面 右边有一个很明显的新建项目按钮<br>
 截图示例 <br>
##### step1
<img src="./_images/WindowGitControl/createProject.png" width = "100%" alt="" align=center />
##### step2
<img src="./_images/WindowGitControl/step1.png" width = "100%" alt="" align=center />
 

#### 内部Git项目协同开发分支约定 
  master是主分支  开发时候不同开发人员使用自己名字加 `_dev`
 master 只有主负责人可以进行合并
 各自只编辑自己的分支 <br>
 截图示例 <br>
##### step1
 <img src="./_images/WindowGitControl/2U3FTFP3`1(BT(S{U$W8H(B.png" width = "100%" alt="" align=center /> 
##### step2
 <img src="./_images/WindowGitControl/aa.png" width = "100%" alt="" align=center />
##### step3
 <img src="./_images/WindowGitControl/bb.png" width = "100%" alt="" align=center />
 到这里创建你的分支已经完成 需要拉取到本地并绑定  
 <a href="/#/Team/Git/?id=%e8%bf%9c%e7%a8%8b%e4%bb%93%e5%ba%93-%e8%ae%be%e7%bd%ae" >点击这里</a> 

### Git客户管理软件

推荐SourceTree,目前测试下来相对比较方便的Git图像客户端软件。需要安装后需要进行翻墙注册账号后方可使用。

 下载地址
https://www.sourcetreeapp.com/  <br>
Also available for Windows 这个按钮下载windows的<br>
 
#### SSH key的设置 
Mac系统或者有经验伙伴可以直接看如下帮助:<br>
http://192.168.1.250:50000/help/ssh/README.md <br>
Window用户如何配置<br> 
安装sourcetree后 打开软件点击这个
##### step1
 <img src="./_images/WindowGitControl/cs.png" width = "100%" alt="" align=center /> 
##### step2
 <img src="./_images/WindowGitControl/cc.png" width = "100%" alt="" align=center />  
##### step3
 <img src="./_images/WindowGitControl/gg.png" width = "100%" alt="" align=center /> 
##### step4
 <img src="./_images/WindowGitControl/ss.png" width = "100%" alt="" align=center /> 
##### step5
 <img src="./_images/WindowGitControl/ff.png" width = "100%" alt="" align=center /> 
 上面的步骤做完以后 重启source就可以了

### SourceTree进行项目代码仓库管理
文强补充
### 远程仓库-设置 
文强补充
### 检出指定远程分支到本地
文强补充
### 代码修改提交到远程仓库
### step1
 <img src="./_images/WindowGitControl/csz.png" width = "100%" alt="" align=center /> 
### 协同开发分支版本合并
文强补充
### 项目完成master归档
文强补充
!> `只有项目主负责人能操作` 切换到master分支把自己开发的分支（确保最终版本）合并进master 归档
