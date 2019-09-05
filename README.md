# mybook

我收藏和喜欢的书，以及一些文档笔记什么的

这个仓库的存在是因为我终于解决了github访问速度慢的问题

前前后后使用了ssr做git的 http代理，因为输入密码麻烦又使用了ssh协议，在配置ssh协议的时候废了好多时间，最悲催的是自建的ssr被封了，购买机场被坑了，唉😔

最近发现http协议可以通过这个配置实现记住密码的功能

``` bash

git config --global credential.helper store

```
