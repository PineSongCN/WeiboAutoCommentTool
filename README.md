# WeiboAutoCommentTool

微博自动评论工具。
*警告：谨慎使用，仅供学习，不要做违法乱纪的事情。*

## 使用方法

* 登录微博
* 切换到发现页面 [https://d.weibo.com](https://d.weibo.com)
* F12打开浏览器控制台，把脚本内容全部复制粘贴到控制台，按回车
* 然后执行以下代码：

```
weiboAutoCommentTool.start({
  //评论内容，不填默认当前时间
  content: '哇，不错不错，很赞！'	,
  //评论间隔时间，默认秒
  delay: 10
});
```
随机评论
```
weiboAutoCommentTool.start({
  //格式['','','']
  content: ['评论1','评论2','评论3']	,
  //评论间隔时间，默认秒
  delay: 10
});
```
## 其他工具
```
//停止自动评论
weiboAutoCommentTool.stop()
```

```
//查看评论统计
weiboAutoCommentTool.stat()
```
