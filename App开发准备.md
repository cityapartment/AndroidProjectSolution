
# 项目开发准备：


## 代码管理规范
    
    推荐使用：
    文档管理：SVN, 代码管理：Git

## 开发规范

    1.推荐《阿里巴巴Java开发手册》，链接地址：https://yq.aliyun.com/articles/69327

    2.推荐《阿里巴巴Android开发手册》，链接地址：https://edu.aliyun.com/course/813

    除了以上两个方面的规范以外，根据项目具体的情况又多考虑了几个方面。
    
## 命名规范
虽然没有强制的要求，但是好的命名能使得项目成员在项目开发过程中快速切入，达到事半功倍的效果，主要从以下几个方面来说：

1. 工程命名

    项目名：一般为公司项目,为了命名行的操作，最好全小写，以"-"分割，表达该项目的意思即可，如：fullbrain-android,fullbrain-ios
2. 模块命名

    模块命名: 一般使用全小写，以"_"分割，前缀为项目缩写或者全写，如："fb_loan_lib"


3. 包命名（可以采用域名倒置再加上自定义的包名）
    
    格式1：cn.XXX + 产品名 + 模块名 
    格式2：com.XXX + 产品名 + 模块名
    
    例如：
    基础库：cn.fullbrain.it.loan.baselib
    日志：cn.fullbrain.it.loan.log

4. 类命名

    驼峰命名，首字母大写

5. 方法命名

    驼峰命名，首字母小写

6. 资源命名
    
    为了各个模块最终打包时候避免资源冲突，必须在每个资源前面加上当前模块的前缀，如：
    格式1：XXX + 模块名 + 资源名
    例如：

    drawable: fb_loan_apply_ + agreement_layout.png

    drawable: fb_loan_apply_ + bind_card_layout.png

    drawable: fb_mine_ + coupon_icon.png

    drawable: fb_mine_ + feedback_icon.png

    layout: fb_login_ + forget_password.xml

    layout: fb_login_ + reset_password.xml


## 管理工具

    需求管理：    
    大的公司可能都会有自己搭建的项目管理需求，之前使用过的：JIRA,Rally, 一般的中小公司可能并非自己搭建这些敏捷项目管理平台，也有很多小的敏捷管理工具，使用过企业微信的TAPD，也不错。

