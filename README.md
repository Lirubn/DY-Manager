# DY-Manager

![banner](/logo.png)

###### 基于 AutoJs 的抖音自动评论脚本

###### Auto.js\-based ant forest energy auto-collect script

******


[![GitHub top language](https://img.shields.io/github/languages/top/SuperMonster003/Ant-Forest?color=eb8031)](https://github.com/topics/javascript)
******
### 使用说明
******

1. 检查设备环境

- 操作系统: Android 7.0+

2. 下载并安装 Auto.js

- [4.1.1 Alpha2](https://github.com/SuperMonster002/Hello-Sockpuppet/raw/master/%5Bauto.js%5D%5B4.1.1_alpha2%5D%5Barm-v7%5D(b69a4e23).apk?raw=true) (`免费版本`)
- [Pro 7.0.4-1](https://github.com/SuperMonster002/Hello-Sockpuppet/blob/master/%5Bauto.js%5D%5Bpro_7.0.4-1%5D(31b16c93).apk?raw=true) (`付费版本`)
- [Pro 8.3.16-0](https://github.com/SuperMonster002/Hello-Sockpuppet/blob/master/%5Bauto.js%5D%5Bpro_8.3.16-0%5D(9a414abf).apk?raw=true) (`付费版本`)

3. 下载并部署项目 (任意一种方式)

- [下载项目部署工具](http://doc.autoxjs.com/) (`*.js`)
    1. 将部署工具 (脚本文件) `保存` 或 `另存为` 至本地存储
    2. 用 `Auto.js` 直接运行 (或导入后运行) 脚本文件完成部署
    3. 部署后可能需要关闭并重启 `Auto.js` 才能看到项目目录
- [下载最新项目数据包](https://tianfukeji.lanzoui.com/b01hremtg) (`*.zip`)
    1. 将项目数据包解压到本地存储
    2. 定位到设备的内部存储目录 如:  
       `/内部存储/` `/Internal Storage/` `/sdcard/` `/storage/emulated/0/` 等
    3. 在此目录下找到 `Auto.js` 默认工作目录  
       · 中文系统默认目录 `./脚本/`  
       · 英文系统默认目录 `./Scripts/`
    4. 若不存在则需手动建立工作目录  
       或在 `Auto.js` 软件中设置工作目录
    5. 将解压后的项目文件夹放置在工作目录中

4. 使用 Auto.js 运行项目

- 运行 `main.js` 启动项目

******
### 使用指南
******
* [编译器文档](http://doc.autoxjs.com) (`文字`)
******
### 功能简介
******

* 自动判断评论
* 自动点赞/监测城市
* 收取结果统计/展示/数据筛查
* 悬浮窗消息提示  
  · 详细/简略  
  · 开发者测试日志 (默认关闭)
* 自动解锁屏幕  
  · 提供解锁密码录入等配置
* 定时任务与循环监测  
  · 直播榜单样本复查  
  · 同城城市循环监测  
  · 定时任务自动管理
* 多任务自动排队
* 脚本运行安全  
  · 运行失败自动重试  
* 事件监测与处理  
  · 账户登出  
* 项目管理  
  · 在线更新项目  
  · 本地备份项目  
  · 本地或服务器还原项目  
  · 项目更新提示
* 账户功能  
  · 防止其他账户意外收取 (需录入主账户信息)  
  · 主账户操作完毕可自动回切之前登录的账户
* 统计功能
* 适应恶劣条件  
  · 脚本在网络条件较差时仍可正常运行或识别异常
* 图形化配置工具  
  · 基于UI的配置工具 可详细配置项目参数

******
### 版本历史
******

[comment]: <> (Version history only shows last 3 versions)

# v1.2.2
###### 2021/08/02
* `新增` 断网提醒
* `修复` 模块交叉引用导致部分模块独立引用失败的问题
* `修复` 榜单搜索失效问题
* `优化` 新的抖音控件值获取方法的代码方案 (试优化)
* `优化` 同城页面滚动速度
* `优化` 直播时防止重复进入同一用户

## 下载
https://tianfukeji.lanzoui.com/b01hremtg
