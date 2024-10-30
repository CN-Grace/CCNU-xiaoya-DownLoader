> [!Warning]\
> 目前已弃用，请转至[python版](https://github.com/CN-Grace/CCNU-xiaoya-DownLoader-py)

# CCNU-xiaoya-DownLoader
## 关键词
- 华中师范大学
- 小雅平台
- 课程资源下载
- TamperMonkey脚本
## 简介
本脚本可使用TamperMonkey加载，为CCNU的小雅平台提供资源下载按钮  
目前仅支持word、ppt、excel、zip、pdf等格式  
暂不支持视频
## 使用方法
进入到课程资源页面预览后，点击页面上部banner的下载按钮会弹出新页面下载当前资源  
### 按钮位置
顶部banner栏内  
![Alt text](image.png)
### 链接
可使用本脚本的链接格式一般如下
```
https://ccnu.ai-augmented.com/app/jx-web/mycourse/***/resource/***/***
```
## 画饼- 
- [ ] 获取文档树(进入课程界面时的导图)———应该会做成树结构
- [ ] 一键下载课程中的所有资源
- [ ] ~~下载视频资源~~(由于脚本限制无法下载m3u8文件合并)

~~可能会出一个python爬虫以实现以上功能~~  
目前由于小雅前端界面有所改变，hook点无法正常使用，请使用python版  

> [!NOTE]\
> [python版在这](https://github.com/zhouxinghua001/CCNU-xiaoya-DownLoader-py)
