# 说明 #

## 申请API Key ##
> http://t.sina.com.cn/11051/3f4cXR5Tej

## 关于sinaAPI库的功能 ##
  1. 基于OAuth认证.
  1. 已经实现upload图片
  1. 适合desktop应用和web应用
  1. sample清晰展示oauth协议过程

## 使用教程 ##

  1. 对于web应用：请到项目Oauth4web的Web.config里面修改app\_key和app\_secret为你自己的appKey和appSecret。
  1. 对于Desktop应用：请到项目Oauth4desktop的app.config里面修改app\_key和app\_secret为你自己的appKey和appSecret。
## 支持的方法 ##
### 获取下行数据： ###

  * public\_timeline()
  * friends\_timeline()
  * user\_timeline()
  * mentions()
  * comments\_timeline()
  * comments\_by\_me()
  * comments()
  * counts()
### 微博 ###

  * statuses\_show()
  * statuses\_update()
  * statuses\_id()
  * statuses\_upload()