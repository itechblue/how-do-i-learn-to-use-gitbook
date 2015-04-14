# 到底我是怎么做到可以用GitBook的呢
## 参考
[用 Github、Markdown 和 GitBook 写开源书](http://my.oschina.net/waylau/blog/355179)<br/>
这个看了有一点感觉，主要是知道了要去注册[GitBook帐号](https://www.gitbook.com)

[Gitbooks & GitHub](http://tomjn.com/2014/06/25/gitbooks-github/)<br/>
这个人的遭遇和我一样，就是没什么文档看，一头雾水。所以他写的操作步骤是比较有用的。
## 试验
尽管有了参考，还是一个试错的过程。
一开始我是先建gitbook再关联github项目，但有问题。
后来学乖了，先创建好github项目，在里面创建两个必须文件：
```
README.md
SUMMARY.md```
然后去到Github Intergration，写上项目名称，点上webhook。接着就可以了啊！
确实有点莫名其妙。<br/>
还去下载了编辑工具，[GitBook Editor](https://github.com/GitbookIO/editor/releases)。一开始竟然找不到，太白痴了，只能搜出来。
## 其它
1.用GitBook Editor增加目录时用中文会有问题，但先是其它名字，再改回来就可以。<br/>
2.MarkDown换行还是靠< b r/ >

