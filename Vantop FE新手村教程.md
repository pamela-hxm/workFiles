# VantopFE新手村文档

此文档是为了让New Vantop-FE更好的入手项目所编写

> Author: Mingbiao Xiao, Hongdong Liao, Frank Wu
>
> Last Modified Time: 20200917 11:37



## 1. 账号相关

> **请按顺序执行！！！**

- **邮箱**：找运维同学@**卢斌斌**开通

- **LDAP(gitlab)**：找运维同学@**胡景光**开通

  > 开通了LDAP账号之后找@**肖名骠**开通git权限
  >
  > - ERP项目地址： http://git.nextop.cc/nextop-web/nextop-web-front
  > - BI项目地址：http://git.nextop.cc/nextop-web/nextop-bi-web

- **禅道、Confluence**：找开发经理@**刘旭东**开通

- **Yapi**: [注册链接](http://yapi.nextop.cc/login)

  > 注册后联系@**肖名骠**



## 2. 文档相关

> 在开发正式代码之前，需要将各个文档通读一遍
>
> [文档中心](http://wiki.nextop.cc/pages/viewpage.action?pageId=327993)
>
> 具体各个文档连接查看钉钉前端小组的群公告

- JS规范：http://wiki.nextop.cc/pages/viewpage.action?pageId=328066
- CSS规范：http://wiki.nextop.cc/pages/viewpage.action?pageId=328057
- HTML规范：http://wiki.nextop.cc/pages/viewpage.action?pageId=328068
- Git开发规范：http://wiki.nextop.cc/pages/viewpage.action?pageId=328081
- Git提交规范：http://wiki.nextop.cc/pages/viewpage.action?pageId=328078



## 3.流程相关

> 名词解释：
>
> - 不确定性：代表此模块是根据需求而定，存在的可能性因时而异

- **需求评审** ：

  - 解释说明：由产品经理组织的一个会议，主要用于解释新需求的功能块以及需求点
  - 参会人员：产品、开发（前后端）、测试
  - 产出：禅道上对应的需求模块，其中由需求文档和原型图组成
- **UI评审（不确定性）**：

  - 解释说明：由UI组织的一个会议，主要用于解释新需求的UI页面以及标准
  - 参会人员：产品、UI、前端
  - 产出：蓝湖上的对应的UI图
- **测试评审（不确定性）**：

  - 解释说明：由测试组织的一个会议，主要用于解释测试编写的测试用例
  - 参会人员：产品、测试、开发（前后端）
  - 产出：禅道上对应的测试用例文件
- **技术评审（不确定性）**：
- 解释说明：由开发组织的一个会议，主要用于分析需求上所拥有的技术难点以及确定开发周期、联调时间以及提测时间；
  - 参会人员：开发（前后端）
  - 产出：Confluence上对应的需求时间节点
- 前端任务拆分：
  - 解释说明：接到需求之后进行需求分析和任务拆解
  - 产出：在禅道上新建的需求任务(原则上一个任务不能超过4个小时)
- **联调**：
- 解释说明：前后端对各自所负责的模块从前端页面以用户的角度进行测试联调，修复遗漏的功能点
  
  - 验收人：开发（前后端）
- **提测**：
-  解释说明：测试根据测试用例在测试环境对需求进行测试验收
  
  - 验收人：测试
  
- **上线**:
  
  - 解释说明：测试和产品根据测试用例在生产环境对需求进行测试验收
  
  - 验收人：测试、产品、UI
  
    

## 4. 项目结构

- **文件目录说明**：

![avatar](http://39.108.115.177/11111.png)

- **API目录说明：**

  > 后台接口都写在此目录下

  ![avatar](http://39.108.115.177/22222.png)

  



## 5.前端相关

- **周会：**每周最后一个工作日的3:30AM - 4:30AM
- **开发测试相关:**
  - 新增测试路由：
    - 使用18888888888/Aa123456账号登录，进入设置/菜单管理页面
    - 点击新增按钮
      - 路由地址为浏览器url，以及项目以views为根目录的文件相对路径
      - 其他配置可参考其他页面







加油，Vantop FE!