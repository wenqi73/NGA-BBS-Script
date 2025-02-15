# NGA论坛的增强型体验

[![Github](https://img.shields.io/github/stars/kisshang1993/NGA-BBS-Script?label=Star&style=social)](https://github.com/kisshang1993/NGA-BBS-Script) [![Greasy Fork](https://img.shields.io/badge/Greasy%20Fork-NGA优化摸鱼体验-brightgreen)](https://greasyfork.org/zh-CN/scripts/393991-nga%E4%BC%98%E5%8C%96%E6%91%B8%E9%B1%BC%E4%BD%93%E9%AA%8C/) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/kisshang1993/NGA-BBS-Script) ![GitHub](https://img.shields.io/github/license/kisshang1993/NGA-BBS-Script)

![NGA-Script LOGO](https://i.loli.net/2021/04/02/iyUhwTpYXm8SKN6.png)

NGA论坛显示优化，功能增强，具体功能见下面【功能列表】

功能列表中的功能是选择开启的，由于功能较多，为了可以完整的体验脚本赋予的所有功能

## 建议第一次使用请先阅读本篇文档

请按照个人喜好选择配置功能，选择开启使用功能

脚本还在完善阶段，摸鱼永无止境，如有想添加的功能或实现，欢迎提出需求![GoodJob](https://i.loli.net/2020/05/27/s2rPUJteBYOE1I7.png)

最后，如果大家觉得此脚本好用，独乐乐不如众乐乐，就请推荐给更多的人使用吧！![Yeah](https://i.loli.net/2020/05/27/aYbjDRcz2qKsZwT.png)

---

## v3.9更新 *

- 添加功能[**护眼模式**]，防止辣眼睛

    ![护眼模式预览](https://i.loli.net/2021/04/22/FeJYLNCpwI3gvXP.png)

- 添加功能[**字体大小调整**]，在高级设置中可以调整字体大小，单位为像素(px)，默认为12像素

    !![字体大小调整](https://i.loli.net/2021/04/29/dsZwFI3tQr5UG4A.png)

- Excel模式现在支持更高的分辨率

- 优化部分代码

## 安装指引

- 安装在浏览器脚本管理器：[[Tampermonkey]](https://www.tampermonkey.net/?ext=dhdg)
- 安装在广告过滤器：找到广告过滤器中的用户脚本管理页面，添加用户脚本，输入[[脚本地址]](https://greasyfork.org/scripts/393991-nga%E4%BC%98%E5%8C%96%E6%91%B8%E9%B1%BC%E4%BD%93%E9%AA%8C/code/NGA%E4%BC%98%E5%8C%96%E6%91%B8%E9%B1%BC%E4%BD%93%E9%AA%8C.user.js)安装

  *注意：此种安装方式部分脚本管理器特有的功能将不可用*

*开发及调试环境：谷歌浏览器(Chrome) + TamperMonkey浏览器油猴扩展 （也是建议环境）

## 功能列表

- 隐藏头像（默认快捷键切换显示[Q]）
- 隐藏表情，使用中文替代（默认快捷键切换显示[W]）
- 隐藏楼内图片（默认快捷键切换显示[E]）
- Excel模式（默认快捷键切换显示[R]）
- 护眼模式
- 贴内图片缩放（默认缩放至宽度200px）
- 隐藏签名
- 隐藏版头/版规/子版（使用一个按钮进行切换）
- 护眼模式
- 调整字体大小
- 帖子列表打开时使用新标签栏
- 连接直接跳转
- 自动翻页
- 折叠引用
- 楼内图像尺寸优化，每张图最大宽200px
- 独立预览图片时可以切换楼内图片（默认快捷键为左右箭头按键）
- 独立预览图片时可以缩放图片，拖拽图片
- 独立预览图片时可以旋转图片
- 高亮楼主
- 拉黑/标签
- 关键字屏蔽
- 导出/导入配置

**注意：以上功能不是默认全部开启的，初次使用请先在【插件设置面板】根据个人喜好选择开关功能，关于【插件设置面板】请继续阅读*

## 部分效果预览

### 隐藏表情，切换快捷键 [**`W`**]

隐藏前

![隐藏前预览](https://s1.ax1x.com/2020/05/27/tAIpB4.jpg)

隐藏后

![隐藏后预览](https://s1.ax1x.com/2020/05/27/tAISuF.jpg)

#### 可配置的主动隐藏图片，使用一个按钮切换，默认快捷切换键[**`E`**]

![隐藏图片预览](https://s1.ax1x.com/2020/05/27/tAI05n.jpg)

#### 论坛Excel模式，WPS风格，默认快捷切换键[**`R`**]

**使用Excel为了提升体验，最好关闭【帖子列表打开时使用新标签栏】功能*

![Excel模式预览](https://s1.ax1x.com/2020/05/27/tAIDCq.png)

**注意：如果出现图片加载失败，比如用于伪装的excel页头及页尾，请及时反馈*

#### 护眼模式

![护眼模式预览](https://i.loli.net/2021/04/22/FeJYLNCpwI3gvXP.png)

**可以与Excel混用*

#### 图片缩放功能，贴内图片宽度调整到200px，更易于浏览

![图片缩放预览](https://s1.ax1x.com/2020/05/27/tAIcKU.jpg)

#### 图片增强功能，用一个独立的遮罩来预览大图，可以通过滚轮缩放图片，鼠标左键拖拽图片，也可以旋转图片

![图片增强预览](https://s1.ax1x.com/2020/05/27/tAIyvT.jpg)

#### 标记楼主，贴内楼主会被标记出来，更容易区分

![标记楼主预览](https://s1.ax1x.com/2020/05/27/tAIo26.jpg)

**注意：必须进入主楼一次才能标记楼主。*

#### 拉黑名单与备注功能

操作面板

![操作面板预览](https://s1.ax1x.com/2020/05/27/tAIh5R.jpg)

标签功能（备注/标记）

![标签预览](https://i.loli.net/2020/07/28/GWpSbyJdCuNDZn7.jpg)

名单管理（配置入口在插件设置面板，详情请继续阅读）

![名单管理预览](https://i.loli.net/2020/07/28/D7R5Z1NFikSrcbn.jpg)

#### 关键字屏蔽

含有屏蔽内容的标题，回复，贴条等全部都会被删除
*可以在控制台中看到删除的内容*

---

## 设置

插件的全局设置，针对每一个功能的开关及对应的配置，初次使用应该先根据个人需求配置一下插件功能

### 普通模式下

[个人中心] -> [NGA优化摸鱼插件设置]

![普通模式下设置面板入口](https://s1.ax1x.com/2020/05/27/tAokZQ.jpg)

### Excel模式下

右上角 -> 点击摸鱼

![Excel模式下设置面板入口](https://s1.ax1x.com/2020/05/27/tAoJiR.png)

在开启了【自动翻页】功能后，到最后一页之前基本是点不到 [收藏]，[发表回复]，为了快捷回复，此入口会被顶置到这里

*普通模式下请使用页头的[收藏&回复]

![Excel下的收藏&回复](https://s1.ax1x.com/2020/05/27/tAoiqg.png)

### 设置面板

![设置面板预览](https://i.loli.net/2020/12/11/NWLnh1yXKoxajgV.jpg)

### 高级设置

高级设置可以对部分基础设置的功能进一步微调

![高级设置面板预览](https://i.loli.net/2020/12/11/SP28gXYHEQqcvJZ.jpg)

#### 可以手动配置快捷键，避免与其他插件冲突

![配置快捷键预览](https://i.loli.net/2020/10/29/f54OGDgeBqnLrbu.jpg
)

#### 可以选择导出配置，迁移数据到新浏览器，或者分享配置

![导出配置](https://i.loli.net/2020/07/28/bEIrcRF1f3AnhJK.jpg)

## FAQ

### Q：部分表情没有隐藏

A：那其实不是用编辑器添加的表情，是张图片

### Q：安装了后刷新没有反应

A：可能是脚本没有运行，也可能是URL没有匹配，因为NGA URL很多，出现这种情况把出现问题的URL贴给我，后续我再添加匹配

目前匹配的URL有

- \*://bbs.nga.cn/\*
- \*://ngabbs.com/\*
- \*://nga.178.com/\*

### Q：脚本也安装了URL也匹配了运行还是没有反应

A：可能是兼容性问题，请升级浏览器以及安装最新的油猴插件

### Q：部分图片没有显示出来

A：存放于图床的图片失效了，请及时联系我重新上传图片

---

## 兼容性检查

### 浏览器

| 浏览器 | Chrome | Firefox | Edge | IE   | Opera | Safari |
| ---------- | ------ | ------- | ---- | ---- | ----- | ------ |
| 最低版本号 | 51     | 53      | 25   | ×    | 32    | 10      |

### 脚本管理器

| 管理器 | Tampermonkey | Violentmonkey | Greasymonkey | 本地管理器 |
| ---- | ------------ | ---- | ---- | ---- |
| 支持度 | 完全支持 | 完全支持 | 注册菜单不支持 | 注册菜单不支持 |
| 检查版本 | 4.12 | 2.13.0 | 4.11 | - |

---

### 有问题或建议可以在脚本更新地址提交【反馈】，或者在Github上提交一个【Issues】，或者论坛私信

#### *反馈BUG时请带上浏览器名称版本+油猴插件名称版本，最好配上图文信息，方便定位与调试BUG

##### 发现问题请先查看社区内是否已经有人提出，作者是否已经修复，如作者已经修复，重新安装一下脚本即可

- Github [[Github Issue](https://github.com/kisshang1993/NGA-BBS-Script/issues)]
- Greasy Fork [[反馈](https://greasyfork.org/zh-CN/scripts/393991-nga%E4%BC%98%E5%8C%96%E6%91%B8%E9%B1%BC%E4%BD%93%E9%AA%8C/feedback)]
- NGA玩家中心  [[@kisshang1993 私信](https://ngabbs.com/nuke.php?func=ucp&uid=9034572)]
