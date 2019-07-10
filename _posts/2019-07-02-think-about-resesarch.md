---
layout: post
title: "想."
description: "I’m much stronger at thinking about research than I am at doing it."
tags: [life, phd, cn]
---


拖了很久，终于在jason的接连催促下，我把 [email++](https://arxiv.org/abs/1907.01423) 上传到了 arXiv。email++ 的想法很简单：如何去修改已经发出去的邮件。因为SMTP protocols的关系，邮件发出去以后，会存储在了收件人的服务器，发件人就不能再修改了。我经常因为蹩脚的语法，发现刚发出去的邮件有时态错误，想修改发出去的邮件。做法也很简单，把邮件里面一部分内容换成图片超链接，而图片是存在第三方服务器上的。这样只要更新第三方图片，收件人看到的邮件也会相应改变。整篇论文介绍了我们的chrome插件，但是没做user study。

<iframe width="560" height="315" src="https://www.youtube.com/embed/HlFFL0eH3sc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br/>
回过头去看，email++ 是我刚入学博士的心态，想在顶级学术会议上证明自己。我想模仿的是 chris harrison 的 [A New Angle on Cheap LCDs](http://chrisharrison.net/projects/obliqueLCD/lcdangle.pdf) 和 juho kim 的 [Content-Aware Kinetic Scrolling for
Supporting Web Page Navigation](https://juhokim.com/files/UIST2014-CAKS.pdf). 我说服自己这是一个很好的锻炼机会，可以练习写作，学习怎么样把一个简单而可爱的想法发表。这篇论文投了两次 (UIST 2017, CHI 2018), 两次分数都是borderline, 两次审稿意见都是希望我去做一个user study。我觉得这篇论文的核心不在于user study，我不想画蛇添足来讨好审稿人。

> 我命硬. 学不来弯腰.        - [Gai 沧海一声笑](https://www.youtube.com/watch?v=06urMzpGxko)

很长一段时间，我对自己感到很失望，因为这一次小实验我没有抓到发表论文的精髓。这个精髓在于很多方面: 想法，执行，以及写作。可能每个地方差一点，导致我最后不能把它发表。一直到有一天看到 david chang 的一个[访问](https://www.wired.com/2016/07/chef-david-chang-on-deliciousness/)。david chang 是一个厨艺界的明星，做过几个很有名的美食纪录片(如The Mind of a Chef)。他谦虚说自己做饭的技巧很差，为了弥补技巧上得不足，他需要不停地去思考食物的可能性。


>To compensate for my lack of dexterity, speed, and technique, I think about food constantly. In fact, I’m much stronger at thinking about food than I am at cooking it. - [David Chang’s Unified Theory of Deliciousness](https://www.wired.com/2016/07/chef-david-chang-on-deliciousness/)


因为这句话，我成了david chang的小粉丝。研究和做饭很像。学校里有很多天赋异禀的stellar scientists，他们一路顶级学霸，非常好的数学功底和编程能力，就像那些手指灵巧的厨师。可能我写一天的程序，大佬们坐下来一小时就写完了。相比于他们，我的特长可能是在“想”这件事上了。匹兹堡并不是一个娱乐生活丰富的城市，这让我把大部分时间都丢进了读书和空想。事实上，我对每个项目想的时间要比做的时间多很多。时间久了，我反而觉得这种局限是一种特别的优点。


当我开始看更大更远的地方的时候，我觉得email++这篇论文有些不值得我的时间，我最后决定不在这个项目上继续投入任何时间。差不多同一时间，我还砍掉了好几个类似的论文项目。<b>并不是我再不需要证明自己，而是我觉得发这些论文也证明不了自己。</b>这篇essay记录了自己这几年想法的变化: 神棍-》工程师-》高立意低视角，这些变化其实并不是顺序发生，只是类似的事情重复发生，我今天回过头去看，才觉得这是我想要的研究风格。

#### 1. 神棍

<img src="/resources/phd_self_expect.gif" width="700px" alt="fallingwater"/>

一开始是飘在天上，我像个神棍。那一阵子我脑子里的关键字应该都是 humanity，universe 之类，觉得只有这样宏大的想法才能证明自己。society，social good这些词我都嫌太小。看问题基本上时间维度是百年起步，空间维度是银河系。现在打开overleaf，还能看到那个时期的一个论文草稿，研究输入法和人类语言演变的关系。

我觉得输入法的自动提示和修改会对每个用户的词汇量产生影响。用户会越来越少打第二页的词组，而很多词汇和单词如果不经常用就会慢慢忘记。以中文为例，我们从手写到打字，从五笔到拼音，算下来也就几十年的时间。如果继续今天这样打字到2050年，可能很多词汇会因为输入法的关系渐渐消失。维特根斯坦说“语言的界限就是思想的界限”。那这样，整个人类的思想就会自己创造出来的echo chamber给限制住。

作为实验手段，我从淘宝买了人民日报1940年到2017年的数据集，去分析里面汉字的频率。可以看到很多90年代的低频字和2010年的低频字有不一样的特点。90年代的低频字更多字形简单，而2010年的低频字发音简单。我觉得这是因为输入法从拼音到五笔的转变。

我有一个满满小本子的类似想法，大部分都无疾而终。这些想法有两个共同点，1) 都让我非常激动，2) 最后发现都很难找到好的切入点。时间久了，有些想法就淡掉了，但有些想法却腻在脑子里不肯去。最近我就捡起了一年级时心心念的一个项目重新开始做。

<!-- 等缘分到了，总会有机会重新捡起。 -->

#### 2. 工程师

有一句玩笑说：“当科学家快要攀登到真理的顶峰时，他们发现神/佛/哲学家已经在那里等候多时了”。我在天上没飘多久，很快就被哲学的书吸引过去了。17年的时候，[scott klemmer](https://d.ucsd.edu/srk/) 来hcii给talk，一起吃了一顿午饭。scott的气质让我非常羡慕，我也想像他那么优秀，活得非常spiritual。scott 安利了达赖的鸡汤书 [The Art of Happiness](https://www.amazon.com/Art-Happiness-10th-Anniversary-Handbook-ebook/dp/B002UK6NO0), 读完以后，我思考了一年“人为什么活着”，“我为什么在这里读博士”。再之后，我又开始看youtube上的各种介绍Jeremy Bentham，Michel Foucault的视频。

另外一方面，jason可能觉得我不着四六，一入学就想让我去做ai fairness。jason的网站上现在还介绍我是做“ai/ethics”的。16年的时候，一张平等&正义的meme很火，我一开始想做的想法类似于[Equality of Opportunity in Supervised Learning](https://papers.nips.cc/paper/6374-equality-of-opportunity-in-supervised-learning)。做到一半，Moritz Hardt这篇论文就发出来了。我非常喜欢这篇论文，Moritz的文章像庖丁解牛，把“公平”这个混乱的观念变成了一个非常具体的数学描述。我想那个时候的自己即便手更快一点，也写不出这么好的论文。

<img src="/resources/justice-fairness.jpg" width="700px" alt="fallingwater"/>

告别神棍是因为两个契机。一个是当我读越来越多的哲学书以后，发现Equality of Opportunity 原来是一个由来已久的概念。哲学家们很早就开始讨论这些，只是没有跟机器学习结合在一起。另外相比于Moritz论文里的简化，哲学家的描述更加精妙，而且充满禅意。然后我带这个问题去问jason，jason给了我一个大智慧的回答。

我问：为什么nsf不把钱给哲学家和社会学家来解决这些问题，他们在这个问题上比我们走得远多了。jason说：他们这条路走了几百年了，已经被证明很难解决这个问题。从计算机的角度看这些问题，现在虽然比较浅薄，但是是一条新路。这个回答让我开始把研究分成“成年的兔子”和“幼年的老虎”，而论文发表是按体积 (i.e., contributions)来算的。email++比较惨，是一只幼年的兔子，可能做了user study才能成年。

另外一个契机是[The Information: A History, A Theory, A Flood](https://www.amazon.com/Information-History-Theory-Flood/dp/1400096235/ref=sr_1_1?keywords=information&qid=1562442151&s=gateway&sr=8-1)，书里面有一段关于牛顿的论述特别精彩。

> The new discipline of physics could not proceed until Isaac Newton appropriated words that were ancient and vague—force, mass, motion, and even time—and gave them new meanings....
For Aristotelians, motion covered a far-flung family of phenomena: a peach ripening, a stone falling, a child growing, a body decaying. That was too rich. Most varieties of motion had to be tossed out before Newton’s laws could apply and the Scientific Revolution could succeed.

牛顿开拓现代物理的第一步其实是定义几个核心观念，比如质量和移动。在很多哲学家眼里，很多广义的变化都可以叫motion，比如小孩长大，桃子成熟。但是现在的“motion”定义更加狭隘，就是从一个位置“移动”到另外一个位置。一句题外话，我非常好奇100年前，中文开始接受现代物理学改造的时候，“移动”是怎么从“运动”中分离出来。

所有这些都把我引向神棍的另外一面：一个好的观点应该有简洁的文字和明快的思想，晶莹剔透，清楚明确。<b>虽然拎清想法是一件很吃力的事情，但是含糊的想法没有价值。因为不清不楚的话，别人也没办法明确指出想法的错误。</b> 我应该是个工程师，既不是设计师也不是哲学家。15年在uist套瓷hiroshi ishii的时候，hiroshi问我“喜欢design么？” 我中二地说了句，“不，我喜欢engineering”。虽然这成了一个非常失败的套瓷，但是未尝不是一件好事。


总之，一方面发现自己想不过那些哲学家，另外一方面觉得自己还是想做解决准确问题而不是创造模糊问题的人，我花了差不多3年才明白自己想走的路。


#### 3. 高立意，低视角

几乎我所有的研究都不是科技driven的research。我很少刻意地去看现在有什么新技术，虽然大部分时候我必须把自己沉浸在这些技术开发里。

所以我所有研究的idea其实都来自于那些让我激动人心的想法，而我找的是一个小角度去切入进去。
过去两年，我看了很多政治的书，作为一个不爱政治的人，我从这里面学到一点。就是每个人都有自己的立场，每个人需要为自己的立场发声。
冯小刚拍《芳华》的时候讲了一句话让我触动很大，每一代导演要服务一个时代的人，这是那一代导演的责任。因为后面或者前面那一代导演都没有经历过这一代人所经历的。

日常研究最多的隐私问题上，我的立场也非常极端。我当时最喜欢的书是David Brin的[The Transparent Society](https://www.amazon.com/Transparent-Society-Technology-Between-Privacy/dp/0738201448)。这本书讲的是未来世界里，监控设备越来越便宜。当各种摄像头部署以后，整个社会变得透明，每个人都没有隐私。

> "If we're free and powerful as citizens, privacy is something we'll be able to negotiate among ourselves." The key is reciprocal accountability...that we have the power to watch the watchers. 

我觉得大家不需要隐私，需要的是权利。透明的世界可以让这个世界运行地更好，我们只是需要每个人都有权利去反向监管管理者。


#### 结尾
交掉mobicom camera ready的浮生半日闲来写这篇小随笔，写着写着，发现写成了读书笔记。有一本书叫[Made to Stick: Why Some Ideas Survive and Others Die](https://www.amazon.com/Made-Stick-Ideas-Survive-Others/dp/1400064287)，这里的很多书都是好几年前看的，书里的想法确实是stick to my mind。趁现在写下来，好过以后忘却。

>悟已往之不谏，知来者之可追。
实迷途其未远，觉今是而昨非。
舟遥遥以轻飏，风飘飘而吹衣。
问征夫以前路，恨晨光之熹微。

我每天想很多无聊的问题，不仅仅。
我也很爱“想”这件事。



<!-- 
有点像Frank Lloyd Wright设计fallingwater时，压低了窗口处天花板的高度，为了促使住户看向窗外的景色。

<img src="/resources/fallingwater_ceiling.jpg" width="700px" alt="fallingwater"/>
 <i>Fallingwater 是一座建筑史上特别有名的住宅, 建立在匹兹堡附近的一处瀑布旁边。Frank Lloyd Wright 在设计这座住宅时，提倡了一种不同的建筑理念：住宅要完全融入自然之中。每个房间靠近窗口处的天花板都会拉低，强迫房间里的人看向窗外的自然环境。</i> 
 
 
 


我非常不喜欢“奇葩说”里面那样翻来覆去的文字游戏。

“移动”这个词语的意义对于传播物理的概念非常有利。



每一个问题都要顺着纹理去切开。


今天各种媒体和直播飞速发展，有很多人在媒体上讨论。这里面我最讨厌的应该是“奇葩说”。




再到最近读Stu Card的[The PhD Thesis Deconstructed](http://hci.stanford.edu/~cagatay/StuCard-WinPrizesGloryPhD.pdf)，讲从混乱到有序是科学研究的本质。
> Think of a PhD professional, her desk surrounded by a little potential energy well of lower entropy relative to the universe, the air cooler, even brisk. Her job is to reduce entropy for others as well by inventing methods, algorithms, and theories usable by them to create order out of chaos. 



这两年我特别讨厌那些把比喻应用在论证里面。
读James Gleick这本书的时候，让我感觉到很庆幸自己是一个工程师而不是哲学家。我不需要去纠结那些飘渺的问题，我可以去直接解决那些已经确定的问题。




作为一个工程师的好处是我不需要去纠结那些虚无的问题，


思考那些悖论不能带来

Reducing entropy 是一件很重要的事。

好的想法应该有简洁的文字和明快的思想。科学的进步伴随的是降低复杂度。


是把一个复杂的问题重新解析，


虽然未必能成功，我还是有“make a difference”的野望，不想从混沌里来到混沌离去。好的科学工作或者产品应该是把一个复杂的问题重新解析，用更简单的方法去四两拨千斤。

薛兆丰的经济学通识里面有一段话



 
 -->