# 网易云音乐PC端音乐Vue 3.0 改版

#### 项目视频效果

[哔哩哔哩](https://www.bilibili.com/video/BV1wU4y1u7MC/)

#### 介绍

墨迹了很久了，终于开始动手了。也是因为最近闲了下来！

#### 软件架构
这是对上一个《[基于网易云音乐API实现PC端音乐网站](https://gitee.com/trtst/vue_pc_music)》项目版本的改进，采用了vue3.0 组合式API，写的非常基础，也是没认真看完文档就写的。纯属误人子弟了！哈哈哈。。。
接下来会对上个项目改版完成，然后继续深度优化。在开发调试过程中，发现了不少问题及bug，也没仔细去修改！

注：非常不建议学我的代码写法，纯粹是为了快速升级重构，无脑改写而已。也欢迎大家推荐优秀的vue3项目，让我也学习学习！  :joy: 


#### 安装教程

1.  支持直接在 Vercel 下部署,不需要自己的服务器（[部署教程](https://binaryify.github.io/NeteaseCloudMusicApi/#/?id=vercel-%e9%83%a8%e7%bd%b2)）
2.  部署成功后，将图一里的DOMAINS复制到src/api/instance.js文件里的 baseURL
3.  fork 此项目，并clone到本地，npm install 安装依赖， npm run dev  运行项目

#### 使用说明

![Vercel部署成功  图一](https://images.gitee.com/uploads/images/2021/1111/165443_52120e01_5120464.jpeg "20211111165413.jpg")

#### 特点
1.  继续使用了 饿了么 plus 组件库，首页采用了饿了么骨架屏
2.  后端部署在 Vercel， 完全可以自己架构一个音乐网站（仅供学习使用，谨防侵权）
...


#### 项目效果图

##### 首页
![首页](https://images.gitee.com/uploads/images/2021/1118/181315_cff9b1fb_5120464.jpeg "首页.jpg")
##### 排行榜
![排行榜](https://images.gitee.com/uploads/images/2021/1118/181337_6db748c7_5120464.jpeg "排行榜.jpg")
##### 歌单
![歌单](https://images.gitee.com/uploads/images/2021/1118/181357_537e6089_5120464.jpeg "歌单.jpg")
##### 歌单详情页
![歌单详情页](https://images.gitee.com/uploads/images/2021/1118/181410_b5bc6cec_5120464.jpeg "歌单详情页.jpg")
##### 歌曲详情页
![歌曲详情页](https://images.gitee.com/uploads/images/2021/1118/181421_45f5781b_5120464.jpeg "歌曲详情页.jpg")
##### 歌手
![歌手](https://images.gitee.com/uploads/images/2021/1118/181437_81819761_5120464.jpeg "歌手.jpg")
##### 歌手详情页
![歌手详情页](https://images.gitee.com/uploads/images/2021/1118/181450_e3e8e250_5120464.jpeg "歌手详情页.jpg")
##### MV
![MV](https://images.gitee.com/uploads/images/2021/1118/181503_992b9e28_5120464.jpeg "MV.jpg")
##### MV详情页
![MV详情页](https://images.gitee.com/uploads/images/2021/1118/181513_a22dcad5_5120464.jpeg "MV详情页.jpg")
##### 搜索页
![搜索页](https://images.gitee.com/uploads/images/2021/1118/181527_2e09c48d_5120464.jpeg "搜索页.jpg")
