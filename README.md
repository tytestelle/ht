你的链接怎么改？ 你的文件链接是： https://github.com/tytestelle/ht/blob/main/tvbox/ht/ht.json
但是注意：你给的示例是一个 raw 文件链接（raw.githubusercontent.com），可以直接获取文件内容。而你的链接是 GitHub 的网页浏览链接（github.com.../blob/...）。

如果你想直接获取 api.json 这个文件的内容，需要先把它转换成 raw 链接，再加代理前缀。

转换规则很简单：把链接里的 github.com 换成 raw.githubusercontent.com，并去掉 /blob。

你的原始链接： https://github.com/tytestelle/ht/main/tvbox/ht/ht.json

转换后的 raw 链接： https://raw.githubusercontent.com/tytestelle/ht/main/tvbox/ht/ht.json

https://gh-proxy.com/ 前缀的最终加速链接：

https://gh-proxy.com/https://raw.githubusercontent.com/tytestelle/ht/main/tvbox/ht/ht.json


