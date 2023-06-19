---
title: 前端开发人员专家新认证
description: 了解如何成为Adobe领域的认证Adobe Developer专家 [!DNL Commerce].
solution: Commerce
product: Magento
role: Developer
badge: label="Exam AD0-E720" type="positive"
mini-toc-levels: 1
source-git-commit: 71d01a071a98d82ef8abcd4518b4596ca6834466
workflow-type: tm+mt
source-wordcount: '1307'
ht-degree: 0%

---

# Adobe的认证历程 [!DNL Commerce] 前端开发人员专家

了解如何成为认证Adobe Developer专家。

>[!NOTE]
>
>这是最新的Adobe Commerce前端开发人员专家考试。 如果您已经开始学习或计划了 [旧版本](ac-e-fedeveloper.md) 您必须在2023年8月18日之前完成此操作。

## 最低体验

Adobe Commerce前端开发人员被视为专家级角色，在Adobe Commerce前端开发方面拥有至少1-3年的实践经验。 他们应该有能力将任务需求所表达的需求转化为技术解决方案。

候选人应能够熟练使用下列技术：

* Adobe Commerce — 版本2.4.6
* 对前端结构和布局的基本了解
* 对HTML、CSS（和预处理器）、LESS、JavaScript和UI组件、jQuery、Underscore、Require.JS、Knockout、PHP模板、数据库知识和内容管理的经验和理解
* 熟悉平台、CMS块、小组件、CMS页面、类别页面、产品页面、购物车和结账以及帐户仪表板区域
* 对管理员配置的基本了解或知识
* 具有扩展和覆盖样式、布局和JS文件的知识
* 扩展父主题/主题层次结构
* CLI命令（缓存清理、设置：升级、索引器、部署模式）和计数
* 缓存技术、客户端浏览器、了解存储（Cookie、本地存储）
* 了解响应式设计和媒体查询
* 所见即所得/页面生成器
* 了解代码包
* 实施翻译
* 了解如何使用电子邮件模板
* 了解Adobe Commerce Cloud基础架构
* 对Cloud CLI命令工具的基本了解

>[!BEGINTABS]

>[!TAB 准备就绪]

**目标受众：**

* 开发者
* 主要开发人员
* 前端开发人员

**考试详细信息：**

* 级别：专家（1-3年经验）
* 及格分数：33/50
* 时间：100分钟
* 投放：在线监护（需要访问摄像头）或测试中心监护
* 可用语言：英语
* 费用：225美元（全球）/150美元（印度）
* 考试ID：AD0-E720

**就绪性自我评估**

完成 [在线准备情况调查表](https://scorpion.caveon.com/launchpad/ad0-e710-adobe-commerce-front-end-developer-expert-copy-jtnjz6){target="_blank"} 查看您当前的体验是否与推荐的最低候选资格相匹配。

**考试目标和范围**

第1节：主题管理（主题层次结构、图像配置、翻译）(16%)

* 描述Adobe Commerce主题文件夹结构以及它如何与基于文件夹的主题相关联
* 演示创建新主题的功能（继承/回退、设计异常、主题属性）
* 演示扩展现有主题的能力
* 演示自定义事务性电子邮件的能力
* 演示应用翻译的能力
* 给定一组用例，确定何时将文件放置到应用程序/代码或应用程序/设计中

第2部分：布局XML和模板（phtml模板）(22%)

* 演示利用布局XML指令的能力
* 演示创建新页面布局的能力
* 了解扩展/合并和覆盖XML之间的区别
* 演示如何将参数传递和利用到模板
* 展示创建和自定义模板的能力
* 应用模板安全性（转义输出）

第3节：样式(18%)

* 确定样式 — m.less、样式 — l.less、print.less的目的
* 描述特定部分文件(_extends.less、_extend.less、_theme.less、_widgets.less、_module.less、)之间的区别
* 展示覆盖或扩展Magento的能力
* 说明LESS的核心概念
* 演示设置电子邮件样式的能力
* 解释样式的层次结构（库、模块、主题）
* 展示实施和自定义LESS库组件的能力
* 确定客户端编译与服务器端编译之间的区别及其工作方式

第4部分：JavaScript（图像小组件、图像库、客户数据模块、挖空模板）(22%)

* 演示初始化和调用JavaScript组件的能力
* 区分不同JavaScript组件的用例
* 演示RequireJS的用法
* 演示实施不同类型的mixin的能力
* 描述如何在JS中添加翻译
* 描述UI组件之间的交互
* 演示“挖空JS”的使用
* 演示jQuery小组件的用法
* 使用布局XML演示JS组件的用法

第5部分：管理员配置和PageBuilder (12%)

* 展示自定义页面生成器内容的能力”
* 描述前端优化
* 自定义事务性电子邮件
* 演示管理开发工具的使用

第6节：工具（CLI和Grunt）(10%)

* 演示基本bin/Magento命令的用法
* 描述Composer命令（安装、更新、需要、删除）的使用情况
* 区分部署模式的适当用例
* 定义客户群设置和使用情况
* 描述云提供的其他工具（Fastly、下载数据库、内容部署、使用UI分支）

>[!TAB 准备好]

您不必在参加考试前完成培训，仅靠培训无法为您提供通过考试所需的知识和技能。 培训与成功的在职经验相结合，对于为您提供通过考试所需的存储库至关重要。

以下是一些可帮助您准备的建议资源：

**第1部分：主题管理（主题层次结构、图像配置、翻译）**

* [主题](https://developer.adobe.com/commerce/frontend-core/guide/themes/)
* [模板](https://developer.adobe.com/commerce/frontend-core/guide/templates/)
* [添加自定义变量](https://experienceleague.adobe.com/docs/commerce-admin/systems/variables/variables-custom.html?lang=en)
* [翻译](https://developer.adobe.com/commerce/frontend-core/guide/translations/)

**第2部分：布局XML和模板（phtml模板）**

* [版面](https://developer.adobe.com/commerce/frontend-core/guide/layouts/xml-manage/){target="_blank"}
* [常见自定义任务](https://devdocs.magento.com/guides/v2.4/frontend-dev-guide/layouts/xml-manage.html){target="_blank"}
* [组件开发](https://developer.adobe.com/commerce/php/development/components/){target="_blank"}
* [安全性](https://developer.adobe.com/commerce/php/development/security/){target="_blank"}

**第3节：样式**

* [响应式网页设计](https://developer.adobe.com/commerce/frontend-core/guide/responsive-design/){target="_blank"}
* [自定义主题样式](https://developer.adobe.com/commerce/frontend-core/guide/css/quickstart/customize-styles/){target="_blank"}
* [编码标准](https://developer.adobe.com/commerce/php/coding-standards/){target="_blank"}
* [层叠样式表(CSS)](https://developer.adobe.com/commerce/frontend-core/guide/css/quickstart/customize-styles/){target="_blank"}

**第4部分：JavaScript（图像小组件、图像库、客户数据模块、去壳模板）**

* [JavaScript](https://developer.adobe.com/commerce/frontend-core/javascript/){target="_blank"}
* [UI组件简介](https://developer.adobe.com/commerce/frontend-core/ui-components/){target="_blank"}
* [自定义结帐](https://developer.adobe.com/commerce/php/tutorials/frontend/custom-checkout/){target="_blank"}
* [可观察阵列](https://knockoutjs.com/documentation/observableArrays.html){target="_blank"}

**第5部分：管理员配置和PageBuilder**

* [页面](https://experienceleague.adobe.com/docs/commerce-admin/content-design/elements/pages/pages.html){target="_blank"}
* [什么是Page Builder？](https://developer.adobe.com/commerce/frontend-core/page-builder/){target="_blank"}
* [JavaScript捆绑](https://developer.adobe.com/commerce/frontend-core/guide/themes/js-bundling/){target="_blank"}
* [Google reCAPTCHA](https://experienceleague.adobe.com/docs/commerce-admin/systems/security/captcha/security-google-recaptcha.html){target="_blank"}

**第6节：工具（CLI和Grunt）**

* [配置指南](https://experienceleague.adobe.com/docs/commerce-operations/configuration-guide/overview.html?lang=en){target="_blank"}
* [内部部署安装概述](https://experienceleague.adobe.com/docs/commerce-operations/installation-guide/overview.html?lang=en){target="_blank"}
* [生成变量](https://experienceleague.adobe.com/docs/commerce-cloud-service/user-guide/configure/env/stage/variables-build.html?lang=en){target="_blank"}
* [云基础架构上的Commerce](https://experienceleague.adobe.com/docs/commerce-cloud-service/user-guide/overview.html?lang=en){target="_blank"}

>[!TAB 获得认证]

>[!IMPORTANT]
>
> 以下部分和链接将起作用 **仅限** 之后 **成功登录** 到 [Adobe凭据管理系统](https://www.certmetrics.com/adobe){target="_blank"}.

**现在您已成功登录，可以直接访问以下链接。**

**参加练习测试**

我们建议您在开始之前参加免费的练习测试。 您将可以不受限制地访问Adobe专家级考试的所有可用练习测试。

我们的实践测试都是基于与实时测试相同的Blueprint开发的。 实践测试将帮助您了解实时测试涵盖的主题。

请记住，通过练习测试并不保证您会通过认证测试。

转到 [Adobe认证考试准备门户](https://www.certmetrics.com/adobe/candidate/gmetrix_sso.aspx){target="_blank"} 现在来参加一个练习测试。

**参加认证考试**

Adobe使用两个供应商来管理委托考试：PSI和考试。

* **PSI** 提供测试中心和日语考试选项（如果可用）
* **[!DNL Examity]** 提供远程联机选项

要安排、重新安排或取消考试，只需单击所选供应商，然后按照屏幕上提供的说明操作。 就这么简单！

您在Adobe凭据管理系统中的配置文件名称必须与您的政府ID完全匹配。 如果未能获得相同信息或出现任何不匹配情况，则采购员将终止考试，并要求您重新安排预约，同时还要支付额外的考试费用。

如果在安排的考试预约之前48小时发起，则可以取消和重新安排。 候选人必须自行修改此约会。

### 考试编号：AD0-E720

[!BADGE 考试]{type=Informative url="https://www.certmetrics.com/adobe/candidate/examity_sso.aspx?eid=AD0-E720 newtab=true"}

您可以通过凭单或信用卡支付认证考试费用。 要购买考试凭单，请转到： [Adobe认证凭证中心](https://market.xvoucher.com/adobe/global){target="_blank"}.

您可以在安排考试时应用优惠券代码。 如果您有折扣，则将在结账时应用。

>[!ENDTABS]

**问题**

查看认证 [常见问题解答](https://experienceleague.adobe.com/docs/certification/certification/faq.html){target="_blank"}.

还有其他问题吗？ [联系我们](mailto:certif@adobe.com){target="_blank"}.
