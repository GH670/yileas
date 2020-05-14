# yileas
hexo-theme-yileas🎈
基于[yilia主题](https://github.com/litten/hexo-theme-yilia)的个性化定制——**yileas**  
> 欢迎访问我的博客：[wblog.tech](https://wblog.tech/) 查看效果。
## **yileas → 注重准确,崇尚简洁**  
目前仅仅对原主题进行了 _魔改_ .  
后续会**慢慢地**对其进行更改  
欢迎各位的PR.  
[说明](#说明)  

## 魔改：  

### 更改：
- 不定期优化
1. 简单化的内容修改
2. 增加网站运行时间
3. 增加访问量统计功能(不蒜子)
4. 添加代码复制功能
5. 添加天气功能模块duigoucha
6. 添加版权声明
7. 添加valine评论系统
8. 修复部分bug,修复微信分享，添加文章访问量统计
9. 添加字数、阅读时长统计（博客根目录：npm i -save hexo-wordcount）
10. 实现文章内容的加密（博客根目录：npm install hexo-blog-encrypt）   
需加密文章的Front-matter中添加：  
password: 是该博客加密使用的密码  
abstract: 是该博客的摘要，会显示在博客的列表页  
message: 这个是博客查看时，密码输入框上面的描述性文字  
11. 实现文章的置顶功能  ①更改插件 ②修改源码 （均在博客根目录有修改）
修改博客根目录下的_config.yml → index_generator（order_by: top: -1 date: -1 ）  
在需要置顶的文章的Front-matter中加上top选项即可  
top后面的数字越大，优先级越高。
12. 添加"说说"功能，可动态实时发布说说。(博客根目录下：hexo new page shuoshuo)  
博客根目录下的操作，简化版教程:[https://wblog.tech/hexo-shuoshuo.html](https://wblog.tech/hexo-shuoshuo.html) (建议查看官方文档！)  
官方文档:[https://artitalk.js.org/](https://artitalk.js.org/)  

### 注意
1. 博客根目录下的_config.yml需按照自己所需更改。
2. 主题根目录下的_config.yml按照所给'框架'填写即可，可自行按照所需更改。
3. 。。。

### 待续...
1. 优化..
2. Fork me on GitHub
3. ...

### 其他：
~~1. DaoVoice在线聊天~~  
~~2. live2d看板娘~~  
~~3. 飘雪特效~~  
~~4. 页面点击小红心效果~~  
~~5. 网易云音乐插件~~  
~~6. 头像旋转功能~~   
~~7. 文字输入特效~~  
~~8. 添加悬停预览图片效果~~  
**均会拖慢加载速度，非必需，未更改**

### 说明：
1. 能力欠缺，完善中...
2. yileas为yilia的个人魔改版。因yilia作者已停止对其主题的维护更新，故对此进行深度修改定制，形成自己特有的主题风格。
3. yileas为吸取各路大神经验总结而成，感谢开源、感谢互联网🌏
4. 不定时→偶尔更新维护
5. 依然存在很多的bug,欢迎大家提出issue.