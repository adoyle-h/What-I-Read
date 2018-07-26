# 每日所读 - 技术

## [左耳朵耗子 - 拖累开发团队效率的困局与解决之道](http://mp.weixin.qq.com/s/PQYbtbU_lRle3G4x7oG2uw)


1. 分工不是让人永远只做一件事，而是把工作内容拆解从而让整体工作并行推进。
2. 一个程序员应该能够掌握多个语言，也能够负责多个模块甚至不同的职责。如果一个程序员觉得多学习一门语言，多掌握一个模块是件很困难的事，那么这个程序员本质上是不合格的。
3. 软件架构上要松耦合，团队组织上要紧耦合。

## [Vim Koans](https://sanctum.geek.nz/arabesque/vim-koans/)

Wq 大师，幽默又深邃

## [Makefile概念入门](https://zhuanlan.zhihu.com/p/29910215)

《Makefile概念入门》
虽然题目是 Makefile，但实际上更多的是解说要解决什么问题，怎么解决的思路。从现实需求出发不断演进，能感受到一种设计美学。作者的文笔和分析思路让我叹为观止


## [I’m harvesting credit card numbers and passwords from your site. Here’s how.](https://hackernoon.com/im-harvesting-credit-card-numbers-and-passwords-from-your-site-here-s-how-9a8cb347c5b5)

这篇文章简直就是核弹，把开源生态炸为平地。
总之就是除了自己写的，其他第三方都不要信任，最好用都不要用。否则就要做好被攻击的心理准备。
开源生态就是基于信任建立的体系，只要有一点恶意，这体系就崩溃了。这样的体系太脆弱了。

[作者另一篇反套路的文章](https://hackernoon.com/part-2-how-to-stop-me-harvesting-credit-card-numbers-and-passwords-from-your-site-844f739659b9)，但是治标不治本，而且只能拯救部分数据，而且还大大增加了开发的负担。
引入开源依赖包是引入恶意代码的根本途径，简直就是给攻击者开的后门。

## 关于数据结构

https://softwareengineering.stackexchange.com/questions/163185/torvalds-quote-about-good-programmer

> Bad programmers worry about the code. Good programmers worry about data structures and their relationships.

> Worry about the data structures first, and your code will naturally be cleaner.

> 数据决定一切。如果选择的数据结构能很好的管理数据，算法部分往往不言自明。记住，数据结构，而非算法，才是编程的关键。
https://www.wikiwand.com/zh-hans/Unix%E5%93%B2%E5%AD%A6

最近才意识到数据结构的设计原来这么重要。数据结构是最稳定的，而算法逻辑是易变的。数据结构是程序的根基。
