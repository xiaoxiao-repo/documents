# 如何帮助前端新人入门和提高？

## http://www.zhihu.com/question/19862294
我来谈一下我的感受吧，@Gino 所言极是，谁都希望招一个有经验的前端人员，那样也可以减少公司的培训成本。但目前中国整个大的环境是没有一所高校开设了前端相关的专业，前端的被重视程度还不够，很多公司和很多人都还对前端这个职位停留在“美工”或者“页面仔”的认知程度上，这样一来前端的价值就不足以很好的被体现，真正做的比较优秀的前端也就少之又少，所以公司需要招一些热爱但不怎么熟练的前端回来培养，谁刚开始不是这样过来的对吗？
新人都是从最基本的html css神马的开始摸索的，我记得我在高中那会还在用frontpage拖table来做网页，自己只是兴趣所趋，<div> css这些概念当时全然不知。说实话，如果不是自己对前端这个行业感兴趣，自己也不会选择了计算机专业，毕业后也不会一直从事着前端行业，也不会对html css js神马的喜欢到一种偏爱的程度。前端入门容易，但说实话精通真的很难，无论哪个大牛都不敢说自己是精通，因为前端知识体系不仅有广度还要有深度，每天跟代码在一起生活，唯一能支持下去的动力恐怕就是兴趣了吧。如果你不爱一个东西，那么永远也不会做好。

好吧，前面YY了一下。下面讲讲具体的如何帮助新人入门和提高吧：

去年在前一家公司培养过2个实习生，现在的一个已经当了小组的leader，但另一个放弃了这个职业，去考研去了。当时我是接到上面leader的通知，让我来培养今年进来的2个实习生。2个实习生刚来时我出了一些题目测试了一下他们对前端基本知识的掌握程度，当时我就泪奔了。。可以说他们是一张白纸，啥也不会。。唯一有的好像就是兴趣。。好吧，公司既然把这个任务给我了，再难也要迎难而上，也不应该打击2位实习生的信心。

Leader给我下了硬性指标，三个月内要让他们能参与到项目中来，我粗略算了下 有点紧，但如果他们有学习的动力还是没什么问题的。首先我为他们制定了一个三个月的学习计划，大致上分为第一个月、第二个月、第三个月，然后每个月再划分到每个星期，每个星期划分到每天。每天学习的东西做日报，每周一次周报并且我会出一些测试题给他们做，每月一次综合测试。三个月之后让他们参与一个项目测试并做三个月的总结。（是不是很像大学期间的写论文报告？但工作了之后有时总结真的很重要，能够正视自己的不足）

当然，学习所有的基本知识之前，第一天需要培养的是“思想”！要让他们知道什么是前端以及当前前端业界的一个趋势，不然在不清楚自己定位的情况下去学东西永远会在迷茫，只有清楚自己想要的才会更好地去努力。我特别传达给他们的概念就是永远不要把自己当做一个代码机器，不然自己以后真的走上前端之路会得抑郁症，在前端工作中享受前端所带来的乐趣是最高的境界。
前端不是页面仔，不是美工，前端直接面向了最终用户，前端是针线活，需要细心和耐心，前端需要不断地学习新知识，前端需要不断研究出现的问题，前端需要关注用户体验，前端需要了解用户心理，前端也需要了解程序员的心理，前端还需要了解设计师天马行空的想法 : )

第一个月主要让他们对一些专业术语和前端整体的知识体系做了概览（包括html、css、js、dom、bom等），当然这里必须要去了解的是W3C的诞生以及它的发展历程，还有各大浏览器厂商的发展历程以及当今不断变化的市场格局。前半个月对html所有的标签做一个系统的学习，并对常用的标签(div\p\h1-h6\span\img\ul\dl\ol\li)做重点的理解和DEMO书写，这里我特别传达了语义化的概念给他们希望他们合理的使用标签，而不是根据自己的心情随意的使用标签。后半个月对css的所有属性做通览，并对常用的CSS属性做重点理解和实战，这里我没有让他们对所有的CSS属性做很详细的了解（有些CSS属性可能我们自己一辈子都不会用到，以后遇到的时候学会查API即可）。这过程中还传达了hack这个概念给他们，以及对待hack的态度和常用实例。

第二个月主要是JS的学习（话说一个月学习JS真的是太难太难了，虽然是个脚本语言但要注意的地方特别多），首先对JS基础的一些东西的学习（词法结构、数据类型和值、变量、表达式和运算符、语句等等一些基础知识），在学JS期间我发现他们明显比第一个月学习html和css来的烦躁，但好得他们有学过编程，有些基础。基础学好之后，就是客户端的一些知识的学习，dom\bom等等，如何对dom操作，关于性能这方面的东西暂时没有传达给他们，等他们达到一定知识程度上我希望他们学习如何优化。后半个月就是让他们接触一个JS框架，并学会高效快速的写出页面交互代码。

第三个月基本就是实战，html+css+js，每周基本都要写好几个页面，然后我会带他们一起去review，并指出所存在的问题，顺便让他们自己记录下，总结，下次再写页面时避免。

当然这三个月期间，他们还需要学会前端工具的使用(svn\dw\notepad++\vim\zen-coding\ps等等)，工具我没有过多的去教他们，这个纯粹是一个使用熟练度的问题，只要自己多操作即可。

最后再这三个月的学习过程中我发现其中一个（是个女孩子）每天下班后经常留在公司，把白天遇到的一些问题代码实战，然后发现了她的一个本本，上面记录了遇到的问题，另外一个男孩子也偶尔会留下来，但几乎很少。三个月之后男孩子说自己要考研了，走了，我想他可能真的不适合前端，也许是有自己的理想，女孩子留了下来，并且迅速的融入了项目团队。（这里我对我这个徒弟还是比较自豪的，前端没有性别之分，女孩子也可以很出色）

说到底，前端新人，如果你是一个导师，要学会去传达一个正确的观念 ，并让他们永远保持着学习的激情，不要小看一张白纸，如果给他一支水笔，他也会描绘出一幅美好的蓝图。

## 