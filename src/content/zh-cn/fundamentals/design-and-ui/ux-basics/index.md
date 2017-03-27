project_path: /web/_project.yaml
book_path: /web/fundamentals/_book.yaml
description:循序渐进的用户体验设计基础知识指南。

{# wf_updated_on:2016-10-01 #}
{# wf_published_on:2016-10-01 #}

# 用户体验基础知识 {: .page-title }

{% include "web/_shared/contributors/mustafa.html" %}

本文介绍的工作流程可以帮助团队、产品、初创企业以及公司打造一个可靠而又有意义的流程，为其客户开发更优质的用户体验。流程的不同环节可以单独使用，但在理想的情况下，将这些环节作为一系列步骤一起使用的效果最佳。


本指南深入借鉴了设计冲刺方法，Google 的多个团队就是利用这一方法来排查和解决[自动驾驶汽车](https://www.google.com/selfdrivingcar/ "Self Driving Car"){:target="_blank" .external}和 [Project Loon](https://www.solveforx.com/loon/ "Project Loon"){:target="_blank" .external} 等挑战。




### 双钻石

此流程作业基于我们用户体验圈内熟知的双钻石模型，在[英国设计协会](https://www.designcouncil.org.uk/ "British Design Council"){:target="_blank" .external}的推动下得到广泛采用，在这种模型下，团队成员各自通过研究理解某个创意，接着集思广益明确挑战，各自分别制定设计草案，分享构思，决定最佳前进路线，最后进行测试和验证。





<figure>
  <img src="images/double-diamond.png" alt="项目包括以下阶段：理解、定义、分散、决定、开发原型和验证">
  <figcaption>英国设计协会开创的“双钻石”设计流程模型，其步骤涉及以下项目阶段：<em>理解</em>、<em>定义</em>、<em>分散</em>、<em>决定</em>、<em>开发原型</em>和<em>验证</em>。</figcaption>
</figure>

## 奠定基础

首先要从当前的根本性挑战着手，像提案那样把它写出来，并且要问自己：“我实际试图解决的是什么问题？”。挑战声明是您为项目编写的简报，其中包含了您的目标。


这个挑战可能是已有的某项需要优化的产品功能，也可能是一款全新的产品。
无论是什么任务，只需调整声明的措辞，使之适合您试图达到的目标。
声明应该与团队目标相关联、以受众为中心、具有鼓舞性并且言辞简洁。


以下是我过去的一些产品设计实例：


* 设计一个管理畸形足患者的治疗和后续护理的系统。


* 开发一款能够将复杂的财务系统精简为只保留必备功能的应用。


* 设计一款既能在不同平台上保持一致性又不会牺牲品牌形象的移动应用。


### 更新挑战声明

编写了若干版本的目标后，将其提交给团队以形成共识。
最好加入一个期限，因为这有助于团队集中精力解决问题。
因此，对于以上所列的实例，可能需要做下列调整：


* 设计一个计划在今年第 1 季度发布、用于对 2 岁以下畸形足患儿进行治疗和后续护理的系统。
* 开发一款 2017 年 7 月首次发布、用户无需具备金融知识便可通过点按按钮来买卖股票的简单金融应用。
* 在今年年末前制作一份能灵活适用于多个平台并且能够让公司品牌有效进驻每个平台的设计指南。


完成挑战声明后，将其展示在醒目位置，以便工作时能够看到。
您需要不断回过头来查阅声明内容，甚至需要在整个项目进行过程中对其进行更新或修改。


## 验证问题

下一步是研究挑战和了解问题的相关情况。您需要发现的是团队对问题的理解是否有效。我们常常从自己的视角看待问题，这样做很危险，因为大多数像我们这样的科技人员实际上是超级用户，只是用户群体中的少数。我们是享有发言权的少数派，可能会愚蠢地认为存在某种问题，实际却并非如此。


以下是各种收集数据来验证挑战的方法。每一种方法都取决于团队以及是否能接触用户。
其目标是更深入地了解当前面临的问题。


### 与利益相关方进行内部面谈

<figure>
  <img src="images/stakeholder-interviews.jpg" class="attempt-right" alt="与利益相关方进行面谈可能有益于发掘公司或团队一级的洞见。">
  <figcaption>与利益相关方进行面谈可能有益于发掘公司或团队一级的洞见。</figcaption>
</figure>

面谈流程涉及对贵公司从营销到财务的每个团队成员和利益相关方进行面谈。
这有助于发现他们所认为的真正挑战和可能的潜在解决方案。我这里所说的解决方案并不是技术解决方案，而是对公司或产品而言的最佳情况设想和最终目标。以上述挑战为例，可以将“年末前让我们的畸形足软件进入 80% 的医疗机构”作为一个可以追求的宏伟目标。






有一点需要注意。这种验证方法最不受青睐，因为它妨碍团队讨论和协作，所以可能会在组织内形成一种孤立氛围。尽管如此，它的确能获得一些有关客户和设计挑战的有用信息，并且是其他方法可能无法获得的信息。


### 闪电演讲

<figure>
  <img src="images/lightning-talks.jpg" alt="闪电演讲是一种持续时间很短（几分钟）的演讲。">
  <figcaption>闪电演讲是一种持续时间很短（几分钟）的演讲。</figcaption>
</figure>

它与内部面谈类似，不同的是将每一位利益相关方集合在一个房间内。
然后从这些利益相关方中选出五六人（分别代表营销、销售、设计、财务、研究等部门）做演讲，每个演讲都要集中阐述自己对挑战的观点，持续时间不超过 10 分钟。他们在演讲中必须涵盖的主题应包括：




* 业务目标
* 他们所认为的项目挑战（这些挑战可能是技术、研究数据收集、设计创作等方面的挑战）
* 目前掌握的用户研究数据

最后留出 5 分钟时间回答问题，选出一人做全程记录。
完成后，可能需要更新挑战内容以反映掌握到的新信息。
其目标是收集一系列要点，这些要点推动的功能或流程有助于您实现产品目标。


### 用户访谈<figure>

  <img src="images/user-interviews.jpg" class="attempt-right" alt="用户访谈对了解人员执行任何给定任务时的痛点都极为有效。">
  <figcaption>用户访谈对了解人员执行任何给定任务时的痛点都极为有效。</figcaption>
</figure>

这或许是了解用户的体验之旅、痛点以及流程的最佳途径。
至少安排五个用户访谈，如果可以联系到更多用户，可以增加访谈数量。
向他们提出的问题类型应包括：

- 他们如何完成现有任务？例如，假定您想解决上文那个金融应用面临的挑战，可以问他们“您目前如何购买股票？”
- 他们对此流程的哪些方面感到满意？
- 他们对此流程的哪些方面感到不满？
- 用户目前使用哪些类似产品？
    *  他们对这些产品的哪些方面感到满意？
    *  他们对这些产品的哪些方面感到不满？
- 如果他们得到一根魔杖，可以对这个流程的一个方面做出改变，他们会改变哪个方面？


访谈的意图是让用户对其面临的挑战发表看法，
不适合您参与讨论，因此您必须尽可能保持沉默。
当用户停止说话时更须如此，务必稍等片刻，因为他们可能正在整理自己的思绪。
您会吃惊的看到，用户停顿几秒后常常会继续讲很久。


全程记录并在可能的情况下为谈话录音，以帮助您捕捉任何可能遗漏的信息。
其目标是将挑战与您收集的用户数据分析进行比较。
两者是否一致？您是否了解到任何有助于更新挑战声明的信息？


### 人种学实地研究

<figure>
  <img src="images/field-interviews.jpg" class="attempt-right" alt="观察用户在其自然环境中的行为对了解他们如何解决自己的挑战极有帮助。">
  <figcaption>观察用户在其自然环境中的行为对了解他们如何解决自己的挑战极有帮助。</figcaption>
</figure>

这是指实地观察用户在特定环境中的行为，例如观察他们如何购物、上下班的出行方式、如何发送短信等行为。

这是因为，在某些情况下，用户告诉您的只是他们认为您想听到的信息。
但如果实地观察用户自己执行操作和任务的行为，就可能看透本质。
实际上您所做的就是在不干扰用户的情况下观察用户的行为，记录他们认为容易或困难的环节以及他们可能未留意的环节。其目标是让自己沉浸在用户环境中，更设身处地地体会他们的痛点。


这种方法通常需要进行一些长期的工作，并且需要有一名研究员主导项目这一部分的工作。
但它或许最具洞察力，因为您观察的是自己正在研究的一群用户在其自然环境中的行为。



### 汇总信息

完成项目的了解阶段后，需要对挑战做最后一次审视。
前进的道路是否正确？是否需要做出任何调整？
写下您了解到的所有信息并将它们按类别分组。
根据您要解决的具体问题，这些信息可能成为功能或流程的基础。
还可以利用它们来更新和修改挑战。


获得足够的反馈和进行充分的数据分析后，运用这些知识创建项目规划图的时机就成熟了。


## 项目规划图

您尝试解决的问题通常由不同类型的人员（或参与者）组成，每一类型都与项目流程有着相应的利害关系。
您需要根据自己了解的信息列出可能的参与者。
它可能是一个用户类型或利益相关方，例如“治疗畸形足的医生”、“畸形足患者”、“照顾患者的看护者”等等。在一张纸的左侧写下每个参与者，如果有白板，可以写在白板的左侧。在右侧写下每个参与者的目标。

最后，写下每个参与者达到其目标需要完成的步骤数量。
例如，对于“治疗畸形足的医生”，其目标将是“治疗畸形足患者”，因此需要的步骤可能是“在系统中登记患者”、“启动其医疗方案”、“创建其医疗健康的复查周期”以及“执行医疗程序”。




<figure>
  <img src="images/project-map.jpg" alt="项目规划图对每个用户或参与者在流程中的主要步骤作出规划">
  <figcaption>项目规划图对每个用户或参与者在流程中的主要步骤作出规划。</figcaption>
</figure>

得到的项目规划图包含流程中的主要步骤。可以将其视为不包含过多细节的项目概览。
团队成员还可通过它来判断规划图是否与挑战声明一致。
稍后，当您分解每个步骤时，可以获得更多详情。
但项目规划图暂时只能对用户完成最终目标所需执行的步骤进行高层次分解。


## 建立设计框架和制作串连图板

### 疯狂的 8

对于这个阶段，我建议采用一种名为“疯狂的 8”的方法，采用这种方法时，需要将一张纸折叠两次得到八个面板。
然后在每个面板中根据您迄今为止了解的所有信息草拟一个创意。
给自己十分钟时间，将想出的创意填入所有八个面板。
如果给自己超过 20 分钟的时间，您可能就会开始拖延：给自己冲一杯咖啡，查看一下电子邮件，与团队闲聊，这些活动本质上就是逃避完成工作。在执行此步骤时，您需要营造出一种紧迫感，从而迫使自己快速并且更有效地工作。



如果是与团队合作，还要让每一位团队成员都完成自己的工作。这一过程让您的大脑开动起来，引发您对挑战的思考。一般而言，草案将是一个界面设计框架。



之后，您和团队的所有成员要向小组介绍自己的创意。每个人都必须详细地逐一说明其创意，以及他们为何选择沿特定道路前进。提醒每一位团队成员利用了解到的信息为其创意提供依据。
所有人介绍完毕后，便可就创意进行投票表决。
每个人都会获得两张便利贴，可投票表决任何创意。他们可以将两张选票都投给自己真正喜欢的某一个创意。



<!-- <figure>
  <img src="images/voting-ideas.jpg"   alt="您可以在便利贴上加注释，将票投给概念或草案本身">
  <figcaption>您可以在便利贴上加注释，将票投给概念或草案本身。</figcaption>
</figure> -->


<figure  class="attempt-left">
  <img src="images/crazy-8s.jpg" alt="疯狂的 8 可以非常有效地将您的所有创意落实到纸面上”。>
  <figcaption>疯狂的 8 可以非常有效地将您的所有创意落实到纸面上。</figcaption>
</figure>

<figure class="attempt-right">
  <img src="images/detailed-wireframe.jpg"   alt="现在需要根据了解到的信息进行详细设计。">
  <figcaption>现在需要根据了解到的信息进行详细设计。</figcaption>
</figure>

<div class="clearfix"></div>

### 优化设计

投票结束后根据得票最多的创意拟订最终创意。您也可以借鉴从同事那里听到的其他创意。再给自己十分钟时间完成这项任务。完成后，再次向团队介绍创意，然后像之前那样投票表决。


### 为创意制作串连图板


<figure>
  <img src="images/storyboard.jpg" class="attempt-right" alt="串连图板涉及将草案和创意合并成一个全面的流程。">
  <figcaption>串连图板涉及将草案和创意合并成一个全面的流程。</figcaption>
</figure>

有设计在手，就可以为设计与用户的互动制作串连图板。到了这个时候，您应该已经思考过用户执行的不同步骤。将同事的一种设计也纳入到流程中是相当普遍的做法。
您需要获得一个清晰的分步式流程，用户可以在其中的某些环节进入分支。
可以回过头来查阅项目规划图，以对照目标验证您的设计。


<div class="clearfix"></div>

## 创建原型

创建原型的本质并不是为完美的代码段建模，而是创造出某种可令使用者相信的东西。
用来创建原型的工具因人而异。
一些人喜欢使用 Keynote 或 Powerpoint，因为它能迫使您思考流程而不是设计细节。
您可能需要投入时间学习使用 Balsamiq、Marvel 或 Framer 之类的工具，可以通过它们进行更多行为控制。无论使用什么工具，都要确保它能让您侧重于流程，并且具有真实感。
您需要以真人为对象测试原型，因此原型的可信度要尽可能高，但同时又不应需要数个工作周才能创建完毕。



<figure>
  <img src="images/prototyping.jpg"  alt="原型需要足够逼真才具有可信性">
  <figcaption>原型需要足够逼真才具有可信性。</figcaption>
</figure>

创建原型需要在时间和逼真性之间找到平衡，因此注意不要太过倾向于任何一个极端。
无论走向哪一个极端，最终结果可能都是浪费时间。

## 易用性 - 测试您的设计

有现成的测试实验室当然好，即使没有，建立一个也并不困难，前提是切记要营造一个不使用户分心的舒适环境。测试通常需要用户和两名团队成员参与，其中一人做记录，另一人提问。
一种有效的方案是使用 Hangouts 之类的应用并记录用户的操作，如果希望其余团队成员从另一个房间观察，使用此方案同样很方便。对于我们这些应用开发者来说，亲眼见证自己设计的实测怪吓人的。这种体验可能既令人振作又发人深省。



<figure>
  <img src="images/usability-testing.jpg"  alt="串连图板涉及将所有草案和创意合并成一个全面的流程。">
  <figcaption>串连图板涉及将所有草案和创意合并成一个全面的流程。</figcaption>
</figure>

### 需要提出的问题

进行设计测试时，请用户在应用中执行任务，并鼓励他们畅所欲言，用言语表述他们的行为和原因。
这件事做起来怪怪的，但有助于您听到他们的真实想法。
尽量不要打断他们的讲话，或告诉他们在思维停顿时应该怎么做。
只需在他们完成（或未完成）特定流程后询问他们执行这个流程的原因。


您需要弄明白的是：

- 他们对原型的哪些方面感到满意？
- 他们对原型的哪些方面感到不满？
- 有哪些痛点？
      * 流程为何能发挥作用
      * 流程为何不能发挥作用
- 他们希望哪些方面做出改进？
- 总体设计/流程是否符合他们的需求？

## 重新检查设计并再进行一轮测试

您有一个能正常工作的原型并收到了反馈。现在应该修改设计，并对发挥和未发挥作用的环节进行分析。
不要为创建全新的设计框架串连图板和创建新的原型而感到畏惧。
从头开始创建新的流程可能比试图改动早期原型更有意义。
尽量不要太过珍视它，因为它不过是一个原型。


对设计感到满意后，便可再次进行测试，并做一些进一步的优化。
如果原型根本达不到标准，您或许认为项目已经失败，
实际并非如此。与实际打造设计相比，创建原型所花费的开发时间可能较少，并且您还通过创建原型对用户的真正喜好有了更多了解。我们的设计冲刺哲学是：要么一举成功，要么学习经验，因此如果创意的效果不合乎预想，也不必对自己太过苛求。



## 大功告成！

您完成了创意的测试。用户喜欢这些创意。利益相关方得到了利用，因为他们从一开始就参与进来。
现在可以实现创意了。
到目前为止，您应该已经对需要实现的创意以及体验的优先级有了清楚的了解。
在每个项目里程碑，您可能都需要引入易用性测试来帮助验证工作的效果和保持工作方向不偏离轨道。



事先尽可能多地了解情况无比重要，否则您投入大量辛劳、时间和精力完成的工作可能并非正确的解决方案。



现在，您应该已经通过本文对用户体验及其重要性有了基本的了解。不应将用户体验视为设计师或研究员的本职工作，它实际上是每个项目参与者的责任，因此我建议大家利用每一个机会参与项目。



{# wf_devsite_translation #}