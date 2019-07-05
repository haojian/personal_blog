---
layout: post
title: "价值函数."
description: "human centered value function."
tags: [life, phd, cn]
---


拖了很久，终于在jason的接连催促下，把 [email++](https://arxiv.org/abs/1907.01423) 上传到了 arXiv。论文想法很简单，如何去修改已经发出去的邮件。因为SMTP protocols的关系，邮件发出去以后，就存储在了收件人的服务器，发件人就不能再修改了。我经常因为自己蹩脚的语法，发现刚发出去的邮件有时态错误。做法也很简单，把邮件里面一部分内容换成图片超链接，而图片是存在第三方服务器上的。这样只要更新第三方图片，收件人看到的邮件也会相应改变。整篇论文介绍了我做的chrome 插件，但是没做 user study。


回过头去看，email++ 是我刚入学博士的心态，想在顶级学术会议上证明自己。我想模仿的是 chris harrison 的 [http://chrisharrison.net/projects/obliqueLCD/lcdangle.pdf](A New Angle on Cheap LCDs: Making Positive Use of Optical Distortion) 和 juho kim 的 [Content-Aware Kinetic Scrolling for
Supporting Web Page Navigation](https://juhokim.com/files/UIST2014-CAKS.pdf). 我说服自己这是一个很好的锻炼，去磨练我的写作，怎么样把一个简单而可爱的想法发表。但是我功力不够。这篇论文投了两次 (UIST 2017, CHI 2018), 两次分数都是borderline, reviewer 表示愿意接收这篇论文如果我做一个user study的话。我觉得这篇论文的核心不在于user study，而在于这个想法。user study是画蛇添足。另外，更重要的是，如果做了user study，我也就没达到自己的目标：我想要探索 minmal publishable unit的初心。


我对自己很失望是我没有抓到这样的一个窍门。一直到有一天看到 david chang 的一个[访问](https://www.wired.com/2016/07/chef-david-chang-on-deliciousness/), 里面有一句话让我印象很深刻。
```
To compensate for my lack of dexterity, speed, and technique, I think about food constantly. In fact, I’m much stronger at thinking about food than I am at cooking it.
```

学术圈有很多rock star (i.e., 论文机器)，他们都非常删除

最后我也没和这篇论文达成和解，我也就没在这篇论文上花费任何时间。




学术圈有各种各样的rock star，每个人都有一个超级长的论文列表。当你在学术圈呆久了以后，你会有一种game这个system的的冲动。熟悉论文评审的规则，如果包装自己的研究，让他被别人喜欢。很长一段时间，我不能和自己和解，因为我对自己很失望是我显然没有抓住这么一个窍门。我对我的writing很担心。每次


我是一个很喜欢价值函数(value function)的人，回想起来，我的大部分论文里面都会把一个实际问题变成一个价值函数，然后去优化它，寻找最优解。

tracko 优化的是distance ressidual
elasticplay 里我定义了一个concept叫，优化的是 
wish 优化的是 shape ressidual。
microwave oven 优化的是heating residual。

这件事的起因可能是来自于16年当时我开始对machine learning fairness 感兴趣的时候，和dawei yin的讨论。从hci的角度来看，我觉得这个是一个非常有意思的问题，但是dawei也觉得这个挺有意思，显然没有我那么激动。他把这个东西描述成 另外一个value function。对他而言，他们的任务并没有任何区别，只要是有一个value function，他们就可以提供最好的办法来优化他。这让我觉得这个问题最后可能更多是hci问题，如何去定义这个价值函数。但是dawei 当是这段话给了我很大的启示，所以之后几年没当我不知道怎么解决这个问题，我就把这个问题变成一个价值函数，然后去优化他，这也成了我研究里面的一个signature。

上周六和hcii的phd去吃巴西烤肉自助，我想我终于到了一个年纪不能再费力得吃了。自助是让人感觉self fullfiling的事情，因为当你觉得你吃回票价了，你觉得完成了一个很重要的任务，他既有翻山越岭的酣畅感，又有击败对手的成就感。value function就是吃了多少价值的东西。在hci读了几年phd，我终于把value function改成了 human centered value function. it's not about the value i have consumped, it's about how happy i would be. my happiness is based on a combination of how much i have consumed, whether i have beaten the restaruant, and how comfortable i would be after that meal. 

这件事让我想起来前一阵子看到的andrew yang的human centered economy，虽然andrew yang 并不是一个scholar，但是我非常appreciate 他的reflection。社会从计划经济，到市场经济，再到社会主义最后的按需非配。但是大家其实并不是完全trust每个人的需求。因为穷有穷活法，富有富活法。按需分配的基础是在于每个人的需求。我觉得human centered economy 是一个很好的transition，between the market economy and the ultimate utopia of socialism。optimization 是一个很有意思的问题，是因为他从来基于一个资源不足的假设。而追求gdp 发展的

在早期社会，社会的optimization里面，是追求总资源的增加，而过了一定阶段以后，就应该变成质量的增加，或者是营养的吸收率，这里的第一步metric 需要发生变化，就是human centered metrics。
elasticplay里面，maximize the human perception。我们希望用户花最多的时间在这个视频浏览上。然而更好的办法，

人们总说选择要比努力要重要，大家总是喜欢用一个四象限的图来表示选择的方向。这是一个retrospective的看法。因为只有上帝视角才能看到你要走的方向。一个更真实的方向是 human-centered value function。今年我又去了glasgow，感谢老板的funding，我又没有论文去了chi。在chi我看到很多work，我发现我下意思地把work 分成四类。matrix

第一类是，特别后悔自己没做出来的。感觉自己已经那么接近了，但是我却错过了。比如equal opportunity，比如word embeding for implicit bias，比如icml那篇lasting impact，这些work我是有skill却做的，而且我也已经很接近了，但是我却没做到。

第二类是，谢谢你完成了这个work，那些work我觉得很有意思，但是我不具备这样的skill来完成这个task，你真厉害.

第三类是，你的work真有意思，虽然我有时间有技能也不一定会去做这个项目，但是我非常尊敬和欣赏你的work。

第四类，是剩下的work。有些工作我并不赞同他们的position，或者设计。


