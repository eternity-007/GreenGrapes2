# GreenGrapes2
一款有科技感颗粒、自定义头像的、功能丰富的、好看的标签云的typecho绿色主题
修改自[https://github.com/hongweipeng/GreenGrapes](https://github.com/hongweipeng/GreenGrapes "https://github.com/hongweipeng/GreenGrapes")

![](http://i.imgur.com/dD8mg7T.png)

## 使用方法 ##
1. 下载Typecho主题，得到一个文件夹
2. 重命名整个文件夹为`GreenGrapes2`并上传至`usr/themes/`目录下
3. 登陆自己的博客后台，在“控制台”的下拉菜单中选择“外观”选项进入已安装主题列表
4. 在相应的主题点击“启用”即可使用

**注意：请在/usr/uploads新建一个权限足够的名为`avatarCache`的目录用来存放头像缓存。
所谓权限足够就是PHP有足够的权限写入文件，一般也就是www:www/755或者干脆777**

## 增加的功能与特色 ##
* 增加了分享功能（插件来自于[river](https://github.com/revir/need-more-share2)）
* 页面和文章访问量统计（不需要插件）
* 改变协议为CC-BY-NC-SA4.0
* 去除页面最下方的备案信息、改成动态的颜文字
* 增加`meta theme color`使Chrome变色
* 增加侧边后台管理
* 启用侧边分类
* 启用页脚加载耗时
* 启用页脚运行时间
* 增加编辑按钮
* 增加字数统计
* 增加最后更新时间
* 增加文章数量统计
* 增加评论框特效
* 增加网站运行时间（需要修改`functions.php`第43行为你的建站时间）
* 评论头像QQ邮箱和Gravatar同时启用

优先QQ头像，然后是Gravatar，再之后是默认。已经启用了gravatar和QQ头像的缓存策略，所以基本上不会对网站速度有太大影响
* 主题增加设置缓存时间、设置建站日期



## To do ##
- [ ] 点赞
- [ ] 集成各种插件

## 演示 ##
[奔跑的蜗牛壳](https://www.mingyueli.com)

## 更多说明 ##

[戳我](https://www.bennythink.com/greengrapes2.html)来获得更多说明
