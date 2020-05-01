# yileas
hexo-theme-yileas🎈
基于[yilia主题](https://github.com/litten/hexo-theme-yilia)的个性化定制——**yileas**  
目前仅仅对原主题进行了 _魔改_ .  
后续会**慢慢地**对其进行修改  
[说明](#说明：)  

## 魔改：  

### 更改：
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

### 可选：
~~1. DaoVoice在线聊天~~  
~~2. live2d看板娘~~  
~~3. 飘雪特效~~  
~~4. 页面点击小红心效果~~  
~~5. 网易云音乐插件~~  
~~6. 头像旋转功能~~  
~~7. 文字输入特效~~


### 说明：
1. 能力欠缺，完善中...
