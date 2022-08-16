# Bing-IMG
> 基于 Vercel 构建的必应每日图片  
> 
> 请求地址：http://Location/api

| 可选参数 | 参数含义 | 可用变量 |
| :------------: | :-------------: | :------------: |
| rand | 随机显示最近8天内的图片 | **true** or **false** |
| day | 显示指定的最近图片 | -1，0，1，2，3，4，5，6，7 (0为今天，1为昨天，-1未知) |
| size | 指定获取图片大小 | 详情见下方**可用分辨率** |
| info | 获取图片JSON格式基础信息 | **true** or **false** |

## 默认参数

* rand = false
* day = 0
* size = 1920x1080
* info = false

## 可使用分辨率

* 1920x1080
* 1366x768
* 1280x768
* 1024x768
* 800x600
* 800x480
* 768x1280
* 720x1280
* 640x480
* 480x800
* 400x240
* 320x240
* 240x320

> 注意：分辨率中的 **x** 为小写英文字母 **X**.

## 获取图片JSON格式基础信息

> http://Location/api/?info=true

## 部署
准备好了吗？点击 Deploy 立即部署  
<a href="https://vercel.com/new/project?template=https://github.com/simpfun/Bing-IMG/main"><img src="https://vercel.com/button"></a>
