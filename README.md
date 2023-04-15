# 4951group13
WKU Clinic Appointment & Management System

本项目使用微信开发者工具+vant组件库实现

# 如何使用
1. 请务必提前注册号微信公众平台账号(https://mp.weixin.qq.com/wxamp/home/guide?lang=zh_CN&token=374824459)
2. 由于本项目使用微信开发者工具提供的云数据库服务，因此请在注册完成后获取AppID以使用微信开发者工具中的“微信云开发”服务

![image](https://user-images.githubusercontent.com/75212308/232187344-540881b3-510f-4215-a6c0-956c87ca14ac.png)

3. 将项目中的所有文件解压到同一文件夹下后，在“创建小程序”中，将“目录”指向该文件夹路径即可打开项目

# 注意 
如果使用4951demo2（用户注册页面），则需额外安装vant weapp组件库：
1、安装 node.js
在使用 Vant Weapp 前，我们需要安装 node.js ，因为后面会用到 npm 指令。
下载网址：https://nodejs.org/zh-cn/
下载长期维护版的 node.js 安装包，然后安装一路点击Next，注意勾选上 Add to PATH 即可。
安装完成后测试node.js是否安装成功：
在cmd终端中输入 node -v 后回车显示版本号，表示安装成功！

2、通过 npm 安装
首先，在终端中打开项目根目录（注意：云开发项目要打开根目录下的 miniprogram 目录）
接着，输入初始化项目的命令：npm init -y
然后通过 npm 指令安装 Vant Weapp：npm i @vant/weapp -S --production

3. 构建 npm 包
打开微信开发者工具，点击 工具 -> 构建 npm，并勾选 使用 npm 模块 选项。
新版的微信开发者工具中，详情 -> 本地设置中没有【使用 npm 模块】选项，则不用理会, 如果有则需要勾选。

# 已完成的部分
1. 主界面，以及Appointment页面
2. 已完成的页面之间的跳转
3. Medicine页面布局以及逻辑

# 未完成的部分
1. Register Today页面
2. Pay页面
3. Expense Record页面
4. 上述页面的跳转
