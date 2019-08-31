# 多扩展接入项目

## 设计目的
* 可以处理多供应商，商户，渠道，产品线，第三方接入 的可扩展性
* 可插拔式，业务可以配置化
* 


## 业务架构设计

* 核心可扩展化
* 业务逻辑自动化/配置化
* 



## 设计点 [问题点]
* 目前的拦截器都是全局拦截器【不能针对身份做不对的拦截】
* 参考spring cloud gateway 做【某个身份的】局部拦截器 [fix]
* GlobalInterceptor 全局拦截器 --- 

## 要支持内部服务调用 [fix]
* 支持http
* 支持rpc
* 等

## 逻辑处理查找【支持自定义注解】[fix]

* @BizUnit()