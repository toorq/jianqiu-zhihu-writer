---
title: "Linode 里为什么 Ubuntu 最火呢？"
question_id: 21421588
answer_id: 610393707
url: "https://www.zhihu.com/question/21421588/answer/610393707"
created: "2019-02-28 11:27"
updated: "2019-03-31 21:52"
voteup: 0
comments: 0
type: answer
---

# Linode 里为什么 Ubuntu 最火呢？

> 回答：2019-02-28 11:27｜更新：2019-03-31 21:52｜赞同：0｜评论：0
> 原文：https://www.zhihu.com/question/21421588/answer/610393707

---

我司服务器，现在大概40多台，主要都是我在维护。

原来用Ubuntu比较多，现在用Centos多。

我是15年以上的老Linuxer，从Redhat6.x版本一路走来。

我上大学的时候是03~07年，当时我是学校Linux板的版主。最喜欢的是Debian，03年钱我高中那会，用的是Redhat，还是光盘装的。我现在家里还收藏着Redhat 7.x的一套光盘，里面还有rpm源码盘。

Ubuntu的开发环境配置方便，对开发人员来说很友好。拿bitcoind的C++代码来说，Ubuntu一个apt全部搞定。

CentOS的话因为GCC版本太老4.x，需要先用scl弄要给新版本的GCC，boost版本也太老，还需要自己编译一个boost，boost的LD_CONFIG问题都让小白头疼。

而线上服务器的话，我还是选择用CentOS，因为Ubuntu的update实在是太多了，特别是security的。不升不安心，不知道新的update改了什么bug。升也不安心，不知道新的update会不会引入什么bug。还是不要动比较好。

Linode的话，自己要部署个服务什么的Ubuntu方便一点。严肃的服务海外还是上AWS的，Linode大多数还是小站，当然ubuntu随便撸一下就好了。都什么年代了，docker随便弄的飞起。
