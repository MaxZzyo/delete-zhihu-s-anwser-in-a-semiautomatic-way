- 声明
此脚本仅对我个人的知乎账号使用过，使用者也仅限用于自己的账号，不得在他人账号中使用！本脚本开始运行后，会自动把当前页的所有回答都删除，不支持选择性删除，谨慎使用！非开发人员、对JS一窍不通的人员请自行判断是否使用，由此脚本导致的任何问题与本人无关。
（删除过程中可以刷新页面中断脚本，但已删除的回答无法恢复！）

# -
知乎注销账号不会删除之前回答的问题，可以用这个脚本半自动删除

- 使用方法
先登录PC网页版知乎，复制自己的用户名用来替换下面的链接
打开 https://www.zhihu.com/people/用户名/answers?page=1
按下F12进入浏览器的调试工具，进入console，复制index.js里面的代码运行

P.S. 脚本是半自动的，删除完一页后需要手动翻页。（知乎自己用的异步请求，所以翻页后脚本不会断）


- Q&A
Q：为什么是半自动？
A：知乎的前端页面在你删除完一页的内容后，切换下一页会有各种各样的坑，手动翻页如果发现没有回答可以删除了，就重新F5一下，再继续重复运行一下脚本。

Q：怎么实现的？
A：主要使用标签的click方法进行模拟点击，虽然不如模拟接口请求那么快。之后也不打算再进行优化或者迭代了。

Q：为什么要做这个脚本？
A：强迫症，知乎账号要注销，从此只当百度知道来用了，但是账号注销了，你回答过的问题还在，只是回答上不显示你的账号信息，自己的知识财产我自然要带走的，知乎又不提供多选删除，找客服也回复没有这个功能，只能一个一个删。

