---
layout: post
title: "Jenkins Introduction"
date: 2015-07-26 23:07:31 +0800
comments: true
categories: 
---

>     Jenkins is an extensible open source continuous integration server
这是Jenkins官网的slogan。一个可扩展的开源CI server。但其实他究竟是干嘛的呢？首先你要明白什么是CI. 
##CI
CI是continuous integration，即持续集成。开发人员都明白，项目的开发不是一个人的战斗，大家的工作都组成一个整体才是项目产出，这就叫集成。那么持续集成，大家的工作都会通过版本控制软件提交到代码库中，那么就需要保证你提交的代码不仅需要在你本地跑得了，还要保证大家的代码都提交进来后整个项目的状态是稳定的。要避免莫个人的改动而导致整个项目运行不了，影响到整个项目组的开发，就必须在代码库更新的过程中持续的做集成，而Jenkins，就是做集成的最好的一个工具。

##Why Jenkins
###Open source
这很重要，开源是整个Java生态链中相对其他语言很有优势的地方。
第一，免费。不管老板或者公司有钱没钱，Jenkins都可以上。
第二，正所谓众人拾柴火焰高，正是由于人人都能为Jenkins做贡献。所以Jenkins这个项目才能源源不断的汲取大家提供的养分和贡献而保持不断进步。
###extensible
Jenkins有很多扩展插件，这些扩展基本上可以cover到日常开发或维护所需要用到的场景。如果没有cover到或者扩展插件有bug，由于他是开源的，你随时能为开源社区贡献自己的力量。

##Jenkins有什么用
说了这么多，如果不举几个有说服力的例子，大家肯定会觉得看了这篇文章，然而并没有什么卵用。我还是没看到为什么要花时间精力去整这么个东西来做个摆设。下面我就举几个实际的例子。
