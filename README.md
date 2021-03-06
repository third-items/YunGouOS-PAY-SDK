# YunGouOS-PAY-SDK

![https://yungouos.oss-cn-shanghai.aliyuncs.com/YunGouOS/logo/merchant/logo.png](https://yungouos.oss-cn-shanghai.aliyuncs.com/YunGouOS/logo/merchant/logo.png)

# 相关地址

官网地址：[https://www.yungouos.com](https://www.yungouos.com "https://www.yungouos.com")

在线体验：[https://www.yungouos.com/#/demo](https://www.yungouos.com/#/demo "https://www.yungouos.com/#/demo")

接口文档：[https://open.pay.yungouos.com](https://open.pay.yungouos.com "https://open.pay.yungouos.com")


# 解决什么问题

1、为个人用户提供官方的支付商户签约和支付接口

2、为企业用户提供更低的签约费率、统一API、自动分账等其他服务

YunGouOS支付平台是为更多开发者、个体户、个人创业者、小微企业提供正规的官方支付接口。基于微信/支付宝官方授权的服务商模式为中小商家提供便捷的支付接入服务。

# 产品优势

个人：个人用户也可以在微信/支付宝官方签约正规的商户，享受来自微信官方的商户相关的API接口和资金能力

个体户/企业：通过YunGouOS签约更低费率、使用YunGouOS统一API和SDK以及订单报表、分账、聚合支付等技术服务


# 用户疑惑

1、问：为什么你们可以给个人用户签约，实现原理是什么？

    我们是微信、支付宝官方服务商，官方对外个人是不开放的，
    个人这块给部分有权限的合作伙伴从事，我们刚好有相关权限可以给个人用户签约。

2、重要：交易款先到你们账户，然后由你们再支付给我？

    这是我们与市面上不同的地方！！
    用户交易款由微信官方直接清算你申请时候的银行卡账户。
    YunGouOS只负责技术信息流，资金流一概由微信负责。

3、交易款如何提现？到账时间？

    不需要提现，微信支付会在每日自动把前一日的交易款项自动打款到您的结算银行卡。

4、交易额达到多少才可以提现，有限制吗？

    没有限制，微信支付自动打款

5、交易怎么查询、如何查看资金？

    微信：使用微信商户助手小程序进行交易查询、资金管理等操作，https://pay.weixin.qq.com/guide/miniapp_assistant.shtml
    
    支付宝：打开支付宝APP，登录你的支付宝账户->我的->账单里面可以查询，资金实时到支付宝余额

6、交易收手续费吗？

    按照申请时候选择的费率扣除，申请支付时候可以选择支付费率

7、银行入账显示的付款方名称是什么？

    根据微信支付官方公告，银行入账显示的付款方将可能是下述两种之一：
    
    【财付通支付科技有限公司客户备付金】、【财付通支付科技有限公司】

# 产品介绍

![产品介绍](https://images.yungouos.com/YunGouOS/merchant/images/product-desc.png)



# 签约流程图

![开户流程](https://yungouos.oss-cn-shanghai.aliyuncs.com/YunGouOS/merchant/images/step.png)

# 如何使用

### 方式一：使用SDK（推荐）

- [JAVA](https://gitee.com/YunGouOS/YunGouOS-PAY-SDK/tree/master/YunGouOS-JAVA-SDK)
- [PHP](https://gitee.com/YunGouOS/YunGouOS-PAY-SDK/tree/master/YunGouOS-PHP-SDK)
- [JS](https://gitee.com/YunGouOS/YunGouOS-PAY-SDK/tree/master/YunGouOS-JS-SDK)
- [Node](https://gitee.com/YunGouOS/YunGouOS-PAY-SDK/tree/master/YunGouOS-Node-SDK)
- [uniapp](https://gitee.com/YunGouOS/YunGouOS-PAY-SDK/tree/master/YunGouOS-UniApp-SDK)
- [微信小程序](https://gitee.com/YunGouOS/YunGouOS-PAY-SDK/tree/master/YunGouOS-WxApp-SDK)

### 方式二：按照API文档调用

接口文档：[https://open.pay.yungouos.com](https://open.pay.yungouos.com "https://open.pay.yungouos.com")


# 示例代码

<a href="https://gitee.com/YunGouOS/YunGouOS-PAY-SDK/tree/master/YunGouOS-SpringBoot-Demo" target="_blank">springBoot接入微信、支付宝、回调方法示例</a>

<a href="https://gitee.com/YunGouOS/YunGouOS-PAY-SDK/tree/master/YunGouOS-UniApp-Demo" target="_blank">uniapp项目接入SDK微信、支付宝方法示例</a>

<a href="https://gitee.com/YunGouOS/YunGouOS-PAY-SDK/tree/master/YunGouOS-WxApp-SDK" target="_blank">微信原生小程序调用微信个人支付接口示例</a>

# 视频教程

<a href="https://www.bilibili.com/video/BV1GU4y1W7HQ" target="_blank">第一章：30分钟详细了解微信支付宝账户体系和支付接口业务流程</a>

<a href="https://www.bilibili.com/video/BV1Wv411Y719" target="_blank">第二章：微信支付宝支付接口接入开发工具安装与环境配置（Java）</a>

<a href="https://www.bilibili.com/video/BV1Bb4y1R7gg" target="_blank">第三章：手把手教你对接微信支付宝接口收款JAVA语言编码实战（附源码）</a>

<a href="https://www.bilibili.com/video/BV1di4y1N7VJ" target="_blank">第四章：springBoot支付宝支付接口接入实战演练（附源码）</a>

<a href="https://www.bilibili.com/video/BV17Z4y1A7zL" target="_blank">第五章：uniapp开发微信小程序接入个人微信支付接口实战演练（附源码）</a>

<a href="https://www.bilibili.com/video/BV1j64y1m7w2" target="_blank">第六章：uniapp开发APP接入个人微信支付、支付宝接口实战演练（附源码）</a>

<a href="https://www.bilibili.com/video/BV1wQ4y1d79U" target="_blank">第七章：uniapp开发公众号网页接入微信个人支付接口（附源码）</a>