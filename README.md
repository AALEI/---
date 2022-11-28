<p align="center"><a href="https://github.com/AALEI/TimeSound_desktop"><img width="200" src="http://69a6abcce2ff74b954e6b7206.weitshop.com/error.jpg"></a></p>
# 时音音乐-桌面版(开源免费音乐软件)

#### 介绍
TimeSound-前端源码, 前端源码分两部分（vue, node）
音源支持：
  - 酷我 ✅
  - 后续有时间再更新

#### 软件架构
使用到的技术，electron(v13 稳定), egg(v2 框架), vue(v3 setup语法), ts(v4 js拓展), node(v16.17.0), element-plus, sass ...

#### 软件介绍
支持平台：
- windows ✅
- mac ✅
- linux ❎

#### 软件下载：
软件历史版本请查看：[更新日志](https://github.com/AALEI/TimeSound_desktop/blob/main/CHANGELOG.md)<br>
软件下载请转到(mac, win)：[云盘页面](https://www.aliyundrive.com/s/3mLaHpHn4W1) [分享码] `5b8p` <br>

#### 源码使用说明
Gitee [码云](https://gitee.com/reviee_admin/time-music-desktop-version) <br>
GitHub：[云盘页面](https://github.com/AALEI/TimeSound_desktop) <br>
检查node版本及其他依赖对应版本, 并将 vue 代码置于 frontend/ 文件夹下，安装好(node, vue)所需依赖

node:
 ```bash
# 开发模式
npm run dev

# 测试模式
npm run test

# 发布前检查
npm run start

# 构建安装包（Windows 32位）
npm run build-w

# 构建安装包（Windows 64位）
npm run build-w-64

# 构建安装包（Mac）
npm run build-m

# 构建安装包（Mac m1 芯片）
npm run build-m-arm64

# 源码加密
npm run encrypt

# 提交仓库(中厂标准模式，可配置)
npm run commit

# 其他命令参照 哆啦好梦 egg 框架
```


vue:
 ```bash
# 开发模式
npm run dev

# 发布命令
npm run build:test
npm run build:pro
npm run build:dev

# 提交仓库(中厂标准模式，可配置)
npm run commit

# 其他命令请查看源码
```


#### 默认数据存储路径
- Windows：`%APPDATA%/lx-music-desktop`
- macOS：`~/Library/Application Support/lx-music-desktop`


### 项目协议

本项目基于 [Apache License 2.0] 许可证发行，以下协议是对于 Apache License 2.0 的补充，如有冲突，以以下协议为准。

词语约定：本协议中的“本项目”指时音音乐桌面版项目；“使用者”指签署本协议的使用者；“官方音乐平台”指对本项目内置的包括酷我、酷狗、咪咕等音乐源的官方平台统称；“版权数据”指包括但不限于图像、音频、名字等在内的他人拥有所属版权的数据。

1. 本项目的数据来源原理是从各官方音乐平台的公开服务器中拉取数据，经过对数据简单地筛选与合并后进行展示，因此本项目不对数据的准确性负责。
2. 使用本项目的过程中可能会产生版权数据，对于这些版权数据，本项目不拥有它们的所有权，为了避免造成侵权，使用者务必在**24小时**内清除使用本项目的过程中所产生的版权数据。
3. 本项目内的官方音乐平台别名为本项目内对官方音乐平台的一个称呼，不包含恶意，如果官方音乐平台觉得不妥，可联系本项目更改或移除。
4. 本项目内使用的部分包括但不限于字体、图片等资源来源于互联网，如果出现侵权可联系本项目移除。
5. 由于使用本项目产生的包括由于本协议或由于使用或无法使用本项目而引起的任何性质的任何直接、间接、特殊、偶然或结果性损害（包括但不限于因商誉损失、停工、计算机故障或故障引起的损害赔偿，或任何及所有其他商业损害或损失）由使用者负责。
6. 本项目完全免费，且开源发布于 GitHub 面向全世界人用作对技术的学习交流，本项目不对项目内的技术可能存在违反当地法律法规的行为作保证，**禁止在违反当地法律法规的情况下使用本项目**，对于使用者在明知或不知当地法律法规不允许的情况下使用本项目所造成的任何违法违规行为由使用者承担，本项目不承担由此造成的任何直接、间接、特殊、偶然或结果性责任。

若你使用了本项目，将代表你接受以上协议。

音乐平台不易，请尊重版权，支持正版。<br>

若对此有疑问请 mail to: 1533936667+qq.com (请将`+`替换成`@`)
