---
layout: post
title: "LambdaChip：廉价Lisp/Scheme Machine发布"
date: 2021-03-02T05:43:18.000Z
author: Solidot
from: https://www.solidot.org/story?sid=67074
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1614663798000-->
[LambdaChip：廉价Lisp/Scheme Machine发布](https://www.solidot.org/story?sid=67074)
------

<div>
<a href="http://https://citypw.blogspot.com/">Shawn the R0ck</a> 写道 "Tuwei技术有限公司近日发布了一款<a href="https://lambdachip.com/" target="_blank">基于自由软件和硬件设计的商业产品LambdaChip</a>，硬件是一款STM32的开发板，运行其上的是<a href="https://lambdachip.com/articles/docs/3" target="_blank">LambdaChip VM</a>，而配套的编译器则是用Scheme语言编写的<a href="https://lambdachip.com/articles/docs/articles/docs/2">Laco</a>，受到了<a href="http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=383F36BFE702A0C1918C9C2AE51A9FBB?doi=10.1.1.57.736&amp;rep=rep1&amp;type=pdf" target="_blank">Lisp/Scheme machine</a>的启发，用户可以使用Scheme语言高效的完成各种工作，而Tuwei的创始人之一是消失了近9年的黑叔叔，很荣幸近日和黑叔叔继续了<a href="https://www.solidot.org/story?sid=29008" target="_blank">9年前因为神经元校正中断的话题</a>：<p></p><i><p></p><p>Shawn：黑叔叔，好久不见，我非常兴奋的看到一个现代版本的Scheme machine，这年头要么是Nix/Rust宗教狂热的存在要么就是基于商业化的吹牛逼，很少能看到<a href="https://raw.githubusercontent.com/DNFWAH/DNFWAH/master/3/d3_0x06_hacker_nsa_free-software.txt" target="_blank">老派黑客</a>风格的产物，请你简单介绍一下LambdaChip是什么？ </p><p></p><p>黑叔叔：首先，面对着<a href="https://rust-gcc.github.io/" target="_blank">gcc-rust</a>的开发者之一，请停止吐槽Rust宗教，不过你可以继续吐槽基于LLVM的rustc。LambdaChip是一个为<a href="http://www.iro.umontreal.ca/~feeley/papers/StAmourFeeleyIFL09.pdf" target="_blank">物联网和嵌入式优化的虚拟机</a>，老派黑客的减少并不影响产业的发展，他们会写一些这样的东西帮助new school的年轻人少加班。 </p><p></p><p>Shawn：宗教问题先放一边，你的意思是说LambdaChip的目的是为了解放年轻一代的程序员，除此之外还有其他的险恶动机吗？另外，你可以介绍一下LambdaChip VM和Laco编译器吗？ </p><p></p><p>黑叔叔：说解放年轻人那就太年轻了，不如说为了让年轻人在内卷的情况下能多个选择，将来有机会也许不用花十年时间去学习C语言就能在物联网产业混饭吃。LambdaChip VM跟JVM一样是stack VM，它实现了函数式语言的大部分特性，这使得相关编译器的工作量减少，利于函数式语言编译器为它写后端。Laco编译器的实现有个小插曲，它使用的是古老的CPS作为中间形式，这种方式曾一度被认为已经淘汰，直到2007年微软一名研究员在ICFP上发表论文表示这个世界应该再给CPS一次机会，它能在编译优化的品质和实现复杂度之间获得比其他中间形式更好的折衷。Laco编译器就是在这样的流派重新兴起的情况下进行的一次实践。 </p><p></p><p>Shawn：帮助混饭吃的产品应该有不错的市场潜力，至少这对于痴迷SICP不可自拔的年轻一代可以在fun and profit之间更容易平衡，虽然我高度怀疑最近几年还有多少人有深陷<a href="https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/" target="_blank">SICP泥潭</a>的经历。LambdaChip支持Zephyr这样的RTOS倒不奇怪，这也是Scheme machine的初衷，可以谈谈支持GNU/Linux的意图吗？这里面是否有不可告人的阴谋？ </p><p></p><p>黑叔叔：SICP在国内也许还不够狂热，不过国外的粉丝甚至把MIT的原版书都全部重新排版精雕细琢以供各个平台阅读，连我都被打动了，平时我只推荐这个粉丝重制版而不是MIT的版本。支持GNU/Linux当然是为了以后支持<a href="https://www.gnu.org/software/hurd/" target="_blank">GNU/Hurd</a>...噢不，我们是实用主义者，我们思考的是如何帮助年轻人早回家，一个物联网软件项目怎么能让年轻人加班测试呢，当然是要在CI上测，一个支持GNU/Linux的版本自然是需要的，不过对于硬件的模拟测试也许会是今后的收费项目之一，毕竟天下没有免费的午餐肉罐头。 </p><p></p><p>Shawn：赚钱是必须的，基于自由软件/硬件的商业模式必然是以盈利为基础，但我对于GNU/Hurd这类阴谋论更有兴趣，最后一个问题，真没有其他阴谋了？</p><p></p><p>黑叔叔：绝对没有了，连GNU/Hurd都不要太在意，因为我们要用GCC-Rust写个更好的...唔那个总之我们的宗旨就是为了让老板多赚钱，年轻人少加班，这不就是技术革新的意义所在吗，这个世界根本没什么阴谋论，不要整天瞎想，赚钱才是正道！ </p><p>Shawn：听起来好像很有道理，不管怎么样，为了GNU和Scheme machine的荣耀，祝LambdaChip好运！"</p></i><p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
