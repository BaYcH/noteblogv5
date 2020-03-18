
## 项目已重构，此项目不在维护！，[点我前往](https://github.com/miyakowork/notepress_free)
## 获取最新版本及更新日志请前往：[点我前往](https://wuwenbin.me/article/u/noteblogv5_updates)
开源版本：v5.0.0（2019/10/01日提交，此仓库只更新至5.0）<br/>
最新版本：v5.9.1（2019/11/01日更新）（为了保持持续的更新，后续的更新都放在私有仓库中，需要的请前往[此处](https://wuwenbin.me)查看）

---
点击链接加入群聊，获取 v5.0.0版 SQL文件【[笔记博客 ~ 交流反馈：697053454](https://jq.qq.com/?_wv=1027&k=5ZEGGl8)】

---
## noteblogv4 -> noteblogv5 的一些升级优化和BUG修复
+ 从jpa换成mybatis-plus，更易上手
+ 升级前端框架layui版本
+ 全面删除内嵌使用的vue部分功能，纯净js+html模板
+ 简化一些不必要的代码（包含java部分和js）
+ 更简单的发布配置以及更简洁的配置说明
+ 后台一些配置管理更加清晰易上手
+ 增加添加页面模板的功能（可能放到小版本上）
+ 增加隐藏内容（提供回复可见、登录可见以及购买可见）
+ 支持emoji的评论
+ 新增用户中心模块
+ 首页多种排版风格配置
+ 网页的多种动画过渡效果的优化
+ 支持QQ、Github第三方用户登录以及普通用户名登录
+ 支持留言、评论邮件提醒的功能
+ 优化卡片的显示样式
+ 更多的功能等待你去发现...

---
## 截图预览
[请查看](https://gitee.com/wuwenbn/noteblogv5/tree/master/screenshot)

## 二次开发文档（持续更新中...）
[点我前往](https://wuwenbin.me/article/5db02858e4b01c32641159c0)

## 部署教程（持续更新中...）
[点我前往](https://wuwenbin.me/article/u/noteblogv5_updates)

---
## 更新日志
### v5.9.1
[√] 修复文章评论出回复的一处可能会造成评论失败的BUG<br/>

### v5.9
[!!!]此版本升级需要升级SQL，脚本如下（可能因为条目过多，需等待一会）
[+] 新增seo优化配置，包含关键字和描述<br/>
[^] 优化访问量的统计PV和UV<br/>

### v5.8.7
[√] 修复添加下载资源标题时长度提示的错误<br/>
[√] 修复编辑下载资源时，密码/提取码为必填的提示<br/>
[√] 修复一个页面多个编辑器ID冲突的问题<br/>
[√] 修复检查更新的跨域问题<br/>

### v5.8.3
[^] 优化卡密的生成操作<br/>
[^] 优化七牛云上传的空间配置代码<br/>
[^] 优化代码规范<br/>

### v5.8
[!!!] 注意：此版本由上一版本升级的时候需要升级SQL脚本
[+] 新增网站欢迎页，提供4个卡片进行配置 <br/>
[+] 新增检测更新的功能，请前往管理后台控制台右上方进行操作 <br/>
[+] 新增云文件分享下载的功能的页面模块 <br/>
[+] 新增用户被回复时，可根据用户的邮箱进行邮件提醒 <br/>
[+] 新增留言榜和评论榜的显示 <br/>
[^] 优化文章卡片日期的显示（由创建日期改为更新日期）<br/>
[^] 优化数据库链接URL配置，现在可以自定义url链接 <br/>
[^] 优化网站背景图显示 <br/>
[^] 优化html的页面代码，采用片段插入 <br/>
[^] 优化文章的评论楼层显示 <br/>
[^] 优化添加/编辑文章的分类数目的判断 <br/>
[^] 优化添加文章页面的排版显示 <br/>
[^] 优化本地服务器上传文件夹位置的处理，现在可以有默认配置了，默认在jar的同级文件夹下 <br/>
[√] 修复添加隐藏内容是总是插入文章末尾的BUG <br/>
[√] 修复更新文章时候文章的日期不更新的问题 <br/>
[√] 修复用户中心用户头像上传失败的BUG <br/>

### v5.3.11.8
[√] 修复更新文章时，重复插入隐藏内容的BUG <br/>
[√] 修复文章详细页面评论总数显示错误的BUG <br/>

### v5.3.11.6
[+] 新增首页的分类查询显示 <br/>
[^] 优化登录界面和注册界面的LOGO文字，显示为网站LOGO的相同文字 <br/>
[√] 修复更新文章时自定义url清空的BUG <br/>

### v5.2.10.5
[+] 新增文章时候，可以直接新增分类 <br/>
[+] 新增定时删除无效多余的上传文件/图片 <br/>
[^] 优化上传代码，简化上传代码逻辑 <br/>
[^] 优化设置的提交功能，现在可以多个项目一起提交 <br/>
[^] 优化后台管理移动手机模式侧边栏 <br/>
[^] 优化safari浏览器顶部导航栏的动画效果 <br/>
[^] 优化后台统计图的显示，地域名字优化 <br/>
[^] 优化移动端的后台管理的界面排版 <br/>
[^] 优化文章添加时二维码的提醒 <br/>
[^] 优化站长认证标识的显示位置 <br/>
[^] 优化微调编辑器选项提示的位置 <br/>
[^] 优化文章设置中打赏功能的提示 <br/>
[√] 修复文章的评论功能设置无效的BUG <br/>
[√] 修复修改文章的自定义url会被覆盖不会更新的BUG <br/>
[√] 修复文章数量较少时侧边static栏错位的BUG <br/>
[√] 修复某些情况下参数缓存实效的BUG <br/>
[√] 修复提交个人设置时会影响邮箱设置的BUG <br/>
