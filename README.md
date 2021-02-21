# Reading-Report
关于五篇基于区块链的物联网安全相关论文的学习笔记和心得
# 基于区块链技术的物联网安全和隐私相关论文读书报告 
寒假期间，我主要是针对五篇基于区块链技术的物联网安全和隐私相关论文进行了学习`:blush:`，包括在校时看的一篇中文研究综述，以及回家后阅读的三篇英文研究综述、一篇具有针对性研究方案的论文。这几篇都是基于区块链的物联网安全相关具有代表性的论文，无论是从论文的叙述风格还是内容质量都是非常值得我学习`:smiley:`。同时，我对论文内容也有一些个人的思考，并结合论文的研究背景、核心思想、解决的问题或未来的方向，以及读书总结整理成读书报告。该读书报告大致分为以下三个部分，包括**写作背景**、**主要内容**和**读书总结**。 
## 一、写作背景 
选读这几篇论文的初衷，我是为了进一步了解区块链和物联网结合的技术瓶颈和应用场景，以及基于区块链技术的物联网解决方案存在主要的安全和隐私问题，为后期的论文撰写打下理论基础、提供研究背景和明确技术路线。 
为了更好的了解读完的几篇论文，本读书报告分别将相关论文的标题、作者、年份、来源和简要内容进行了汇总并制成表格，如表1所示。 
<p align="center">  
表1 相关论文的基本情况  
</p>   

| 论文名称 | 作者 | 来源 | 年份 | 简要内容 |  
| --- | --- | --- | --- | --- |  
| [1] [区块链技术驱动下的物联网安全研究综述](https://github.com/Cryptocxf/Reading-Report/blob/main/%5B1%5D-2017-zhao.pdf "zhao") | 赵阔(吉林大学计算机与科学技术学院) | 信息网络安全 | 2017 | 介绍了IoT存在问题，对结合区块链后的安全性进行分析。 |  
| [2] [Blockchain Technologies for the Internet of Things: Research Issues and Challenges](https://github.com/Cryptocxf/Reading-Report/blob/main/%5B2%5D-2019-Mohamed.pdf "mohamed") | Mohamed Amine Ferrag(Guelma University) | IEEE Internet of Things Journal | 2019 | 提出了IoT安全和隐私方面的威胁模型，并进行分类。 |  
| [3] [Blockchain-Based Solutions to Security and Privacy Issues in the Internet of Things](https://github.com/Cryptocxf/Reading-Report/blob/main/%5B3%5D-2018-Yu.pdf "yu") | 禹勇(陕西师范大学密码学国家重点实验室) | IEEE Wireless Communication | 2018 | 针对IoT的问题，开发了一个区块链与IoT集成的应用框架。 |  
| [4] [IoT security: Review, block-chain solutions, and open challenges](https://github.com/Cryptocxf/Reading-Report/blob/main/%5B4%5D-2018-Minhaj.pdf "minhaj") | Minhaj Ahmad (Bahauddin Zakariya University) | Future Generation Computer Systems | 2018 | 概述IoT的安全需求，并对IoT分层架构的安全问题进行了分类。 |  
| [5] [Towards Secure Industrial IoT: Blockchain System with Credit-Based Consensus Mechanism](https://github.com/Cryptocxf/Reading-Report/blob/main/%5B5%5D-2019-Huang.pdf "huang") | Junqin Huang(电子科技大学) | IEEE Transactions on Industrial Informatics | 2019 | 面向工业IoT，提出了一种基于信用的共识机制的区块链系统 |  

* 通过阅读论文[1]了解到，虽然物联网给我们的日常生活带来了巨大变革，但是由于物联网的***拓扑结构***和***资源的约束***，传统的安全技术也已经不在完全适用于物联网，物联网将面临着严重的***安全隐私问题***。以此为写作背景，作者通过分析区块链技术特点来解决物联网应用中的安全问题，并对区块链技术与物联网结合后的安全性问题做出了探讨。  

* 通过阅读论文[2]了解到，由于物联网设备的***计算***、***存储***和***带宽受限***，大量数据流量成为满足所需服务质量的瓶颈，许多研究人员将区块链技术应用于物联网中。以此为写作背景，作者对物联网网络现有的区块链协议进行了全面的综述，并提出了物联网中区块链协议所考虑的***威胁模型***的分类。  

* 通过阅读论文[3]了解到，物联网引领学术界和工业界的数字革命，它给人们的生活带来了方便，也存在***安全***和***隐私***问题亟待解决。以此为写作背景，作者开发了一个将区块链与物联网集成的***系统框架***。  

* 通过阅读论文[4]了解到，大多数物联网设备***容易被黑客攻击***和***破坏***，以及在计算、存储和网络***容量***方面***受限***。以此为写作背景，作者提出并调查了物联网的主要安全问题，并对物联网分层架构的***安全问题***进行了***分类***。  

* 通过阅读论文[5]了解到，现有工业物联网系统容易出现***单点攻击***和***恶意攻击***，它不能提供稳定的服务，传统区块链是***强耗电-低输出***的，并不适用能力受限的物联网设备。以此为写作背景，作者提出了一种***基于信任的共识机制的区块链系统***。  

综上，以上五篇论文的写作背景都是基于物联网现存的***安全***和***隐私***问题，如常见的***威胁模型***和***攻击手段***，以及一些设备的***计算***、***存储***和***资源受限***等挑战，通过分析物联网中的安全和隐私问题，对威胁模型和攻击手段进行***分类***或提供***解决方案***，全面探讨最新一些解决方案的优劣势，并撰写成文献综述或是具有针对性研究方案的论文。  

## 二、主要内容  
这部分将详细介绍以上5篇论文的**研究背景**、**核心思想**、**解决的问题**或**潜在的方向**等。  
### 2.1 论文[1]—“区块链技术驱动下的物联网安全研究综述”  
#### (1) 研究背景  

本篇论文指出物联网主要在应用层、网络层和感知层中存在隐私保护、认证与访问控制和数据安全等安全问题。首先，用户隐私和信息安全传输方面有许多不足，信道安全不能满足一对多、多对多环境下抵抗密钥共享攻击。其次，身份认证中密钥被窃取，会话数据被攻击者窃取，消息认证中攻击者可通过穷举、数据流监听等方法伪装。最后，物联网处理的是流式数据，是实时的、连续的，物联网中海量数据的存储和处理面临巨大的安全挑战。  

#### (2) 核心思想  

本篇论文指出点对点网络下存在较高网络延迟，需要设计一种机制，对在差不多时间段内发生的事务的先后顺序进行共识，这种机制使物联网设备之间传递的数据的隐私安全得到保证，然而区块链的特点能给物联网安全提供共识机制，其可实现**去中心化、去信任化、时序数据、数据加密和智能合约**等5个特点。  

  *   区块链技术对于物联网的中心化结构有较好的优化作用，可以改善数据存储中心化、物联网结构中心化的现状，减少物联网对中心机构的依赖，防止由于中心结构的损坏导致的整个系统的瘫痪。  
  *   区块链去信任化的特点能够在物联网的互信机制中，使用户之间的交易更加透明化。  
  *   时间戳方法不仅能保证数据的安全，也降低了交易追溯的成本。  
  *   时序数据强化了信息的不可篡改性，对保障物联网中的物品流通安全起到了很大的作用。  
  *   非对称加密能够保证物联网中交易数据的安全，降低交易数据丢失的风险。  
  *   椭圆曲线数字签名算法（ECDSA）表明签名人的身份以及对这项交易数据内容的认可。  
  *   智能合约强化了物联网中用户之间的互信机制，能够实现物联网中的去信任化。
   
#### (3) 解决的问题  
 
 本篇论文提到，将区块链技术的特点应用在物联网安全中，能够推动物联网的发展，降低物联网应用的成本。表2为采用区块链技术解决物联网相关领域安全的实例。  
 <p align="center">  
表2 采用区块链技术改善物联网相关领域安全的实例  
</p>  
 
| 物联网相关领域 | 面临的安全问题 | 区块链技术对其作用 |  
| --- | --- | --- |  
| 金融经济 | 信息伪造、银行信用、骗货挪用、异地监管等 | 区块链去信任化以及数据加密的特点能够用来改善金融领域的安全问题，实现货运金融一体化等 |  
| 中介机构 | 虚假信息、用户隐私安全等 | 利用区块链中的智能合约实现双方互信、保证用户信息的安全，削弱中介机构的控制 |   
| 数据存储 | 存储中心化、数据安全等 | 利用区块链的去中心化改善大数据存储的中心化现状，利用区块链数据加密技术保证文件安全 |  
| 公共服务 | 食品安全、医疗安全、交通拥堵等 | 利用区块链时序数据标记食品的产地、日期且不可更改；对医疗数据加密，保证用户隐私；利用区块链技术实现交通信息实时共享 |   

区块链技术能够实现真正的去中介化，在没有第三方的干预下实现点对点的支付，其**去信任化**以及**智能合约**的特点来保证用户双方的**相互信任**。另外，数据加密来保证数据的安全性，以及每个节点都存储数据的特点使其适用于存储和处理这些**隐私数据**，并有效防止因中心机构被攻击而导致的数据丢失损坏。  

``总体来说，本篇论文概括了物联网的相关特征和存在的问题还比较全面，能够分层次的阐述主要的问题，针对性的用区块链的特性解决问题。但是，感觉区块链在物联网中的应用特点讲的比较浅，没有详细讲述细节，还需要自己查资料。``  

### 2.2 论文[2]—"Blockchain Technologies for the Internet of Things: Research Issues and Challenges"  
#### (1) 研究背景  

本篇论文指出由于物联网设备的计算、存储和带宽受限，大量数据流量成为满足所需服务质量的瓶颈，许多研究人员将区块链技术应用于物联网中，因此本篇论文全面调查了现存的区块链应用于物联网领域的例子，包括车联网、能源互联网、互联云和边缘计算等。  

#### (2) 核心思想  

这是一篇研究区块链技术在物联网中存在的问题和挑战的综述，指出了物联网许多的领域可以用区块链技术来**解决安全和隐私问题**，同时也指出物联网领域并不是都必须用区块链，并提供了一种判断是否必须用区块链的方法，如图1所示。  
.<img src="https://github.com/Cryptocxf/Reading-Report/blob/main/picture1.png" width="600" height="900" />
 <p align="center">  
图1 判断是否必须利用区块链技术的方法流程图  
</p>  

然后，作者将目前对物联网的威胁模型大致分了两大类和五小类，两大类为依赖应用程序的攻击和无需应用程序的攻击，五小类分别为**基于身份的攻击**(攻击者伪造身份伪装成授权用户，以便访问系统并操纵它)、**基于操纵的攻击**(涉及未经授权的访问和数据篡改)、**密码分析攻击**(目标是破解密码算法并公开密钥)、**基于声誉的攻击**(一方通过把他的名声变成积极的声誉来操纵他)和**基于服务攻击**(目的要么是使服务器不可用，要么是使服务的行为不同于其规范)。  

另外，论文提出了基于物联网链的体系结构实现需要四个主要阶段：  
  *  创建智能合约并部署到区块链中；
  *  发送交易到合同地址；
  *  客户端请求加密密钥来解密密钥服务器上的资源；
  *  客户端可以直接从资源服务器下载加密后的资源。  

#### (3) 潜在的方向  
 作者概述了可以提高物联网+区块链的能力和有效性的开放问题和研究挑战，并提出如下潜在的研究方向。
 
  * **对联合攻击的弹性**：可设计一种安全解决方案，即能抵抗组合的无应用程序攻击，又能考虑到解决方案的实现可行性，特别是在资源约束较低的物联网设备的情况下。
  * **动态和可适应的安全框架**：如何为物联网链体系结构设计一种动态的、适应性强的安全框架是未来应该受到更多关注的挑战之一。
  * **节能的“挖矿”**：设计一种高效节能的共识协议是物联网结合区块链技术的重大研究挑战之一。
  * **社交网络和信任管理**：假新闻可能是网络攻击的一部分，大规模的谣言传播会对一个组织或一个国家造成严重的社会和经济损失，尤其是使用在线社交网络。
  * **特定区块链基础设施**：支持大型区块链区去中心化存储的区块链专用设备成为一个具有挑战性的问题。此外，计算资源丰富的设备之间的可信度需要在区块链基础设施中建立。
  * **车载云广告传播**：如何设计一个基于区块链技术的单属性访问控制协议来保护车载云广告广播中的交易隐私？如何设计一个基于区块链技术的隐私保护的秘密共享方案来确定选定车辆参与交易？
  * **Skyline查询处理**：这已经成为数据库研究中的一个重要问题，如集中式数据库、分布式数据库和相似度搜索。调查方案还没有研究在区块链中使用skyline查询的可能性。
 
 ``总体来说，本篇论文还是非常详细的对物联网中的威胁模型进行分类，大概有十几种攻击都能详细归类，并且讲的也比较细致，适合仔细阅读。特别是一种判断是否必须利用区块链技术来解决物联网问题的方法流程图非常有意思，对于铺天盖地的利用区块链技术的论文起到很好的警醒作用。``  

### 2.3 论文[3]—"Blockchain-Based Solutions to Security and Privacy Issues in the Internet of Things"  
#### (1) 研究背景  
本篇论文指出物联网已经在我们的日常生活中得到了广泛应用，其安全级别较低的设备会成为**恶意敌手**的**攻击目标**，且智能设备之间的连接也会招致许多恶意敌手的攻击。此外，这些系统中产生的数据若保存不当，可能会**暴露隐私**，给用户带来担忧。因此，新兴的区块链可以在物联网安全方面引发新的机遇。  

#### (2) 核心思想  

作者研究了传统物联网架构，并分析其中的安全和隐私问题，包括**数据完整性、数据共享、身份验证和访问控制**。另外，作者论证了区块链如何与物联网集成，描述了区块链和物联网**协同工作**的框架，并指出了区块链如何从物联网系统中受益。最后，论文展示了一些可能的解决方案，以解决基于区块链和**以太坊**的物联网系统中的安全和隐私问题。另外还考虑了更多基于区块链的潜在解决方案，以展示区块链在物联网中的强大功能。 

.<img src="https://github.com/Cryptocxf/Reading-Report/blob/main/picture2.png" width="600" height="500" />  

 <p align="center">  
图2 基于区块链的物联网数据完整性框架  
</p>  

  * **数据完整性**：采用以太坊和智能合约来解决分布式系统中数据的完整性，如图2所示。  
    * 点对点(peer-to-peer, P2P)系统中的节点需要通过生成空间证明(proof of space)来提交它们所拥有的空间，以证明他们的claims并进行deposits。这是在同行注册到系统中以生成交易Tregist时实现。  
    * 矿工通过验证空间证明方程来验证这笔交易和链接有效交易在区块链中。然后，物联网用户宣布在P2P网络中的交易Tstore、索赔的claim和涉及的费用。矿工为用户匹配交易的需求、服务和提供存储。
    * 当物联网用户需要检查外包数据的完整性时，会生成一个新的交易Tchal。然后，存储数据的矿工计算一个证明，并将其放在区块链上，由用户验证。
    * 若验证未通过，交易Tregist的deposit将奖励给用户，作为对承载数据的矿工的惩罚。若矿工想撤销存储空间，他们需要产生一个交易Tcancel，并在交易Tregist中撤销deposit。

  * **数据共享**：基于以太坊区块链提供了一个可能的解决方案。假设数据所有者收集物联网系统中生成的数据，并以d BTC的价格作为收入共享数据。为保证交易双方的公平，买方需要支付一定的deposit，且不低于d BTC，如图3所示。  
    * 预定义一个时间t的时间承诺，卖方在t时间内诚实地向卖方付款后，就可以赎回deposit。否则，deposit可以在交易熔断(Fuse)签字后转寄给卖方。
    * 如果卖方在时间t之前签署了Fuse交易，它是无效的。因为它不能再交易时间tlock内通过矿工的验证。这确保了恶意买家再获得预期数据时不会损害卖方利益。
    * 如果买方也需要受到公平交易的保护，卖方也需要产生一笔交易来支付deposit。  
 
.<img src="https://github.com/Cryptocxf/Reading-Report/blob/main/picture3.png" width="450" height="400" />
 <p align="center">  
图3 基于区块链的物联网数据共享框架  
</p>  

  * **身份验证和访问控制**：以太坊可以为智能设备、服务器和物联网中的数据提供*身份认证*和*访问控制*。用户可以在智能合约中预定义访问策略，并生成多种交易，如Tpolicy、Taccess和Tquery。这个交易Tpolicy包括预定义访问策略，Taccess是为了访问管理，Tquery是为了访问查询。当新实体第一次注册到物联网系统时，将确定新生成的公钥和相应的访问权限，并将其放入区块链上的交易Taccess中。随后，当实体需要访问物联网系统时，通过构造和签名交易Tquery生成查询。 
 
  * **隐私**：可以结合多种加密技术来实现**完全匿名**。可链接环签名非常适合于自发环中隐藏发送者身份的交易签名。***同态承诺***可以隐藏账单交易中的货币金额。***零知识证明和零知识论证***是将交易中的任何信息转为随机信息的完美工具，可以防止任何第三方获取一丁点的信息。当涉及到物联网系统中的数据隐私时，为了提高效率，使用了***对称加密，如AES加密***。  

#### (3) 潜在的方向  
最后，基于区块链的安全和隐私问题之外，还提出了更多可能的解决方案，例如***GHOST协议***，一种在主分类账中用树形结构修改了的区块链，以及一种基于***有向无环图(DAG)***的加密货币模型。  

``本篇论文研究的是基于区块链技术在物联网中解决安全和隐私问题，重点描述了区块链与物联网协同工作的框架，为了便于读者理解，采用了一个实例描述了基于区块链的身份验证和访问控制过程。最后，作者也提供了几种解决隐私问题可能的方向，包括一种基于DAG结构的区块链，对后面的研究具有重要的参考意义。``  

### 2.4 论文[4]—"IoT security: Review, block-chain solutions, and open challenges."  
#### (1) 研究背景  
本篇论文指出物联网设备在计算、存储和网络容量方面受到限制，他们比其他端点设备更易受到黑客攻击和破坏。因此，需要保护整个部署架构免受可能阻碍物联网提供的服务以及可能对数据的**隐私、完整性**或**机密性**构成威胁的攻击，安全解决方案需要适应受约束的体系结构。  

#### (2) 核心思想  
在本篇论文中，作者通过分析**安全威胁**及其对物联网可能解决方案的映射的参数，并对物联网安全问题进行了分类和分层，以及给出了解决这些问题的对策。然后，讨论基于区块链的安全解决方案的基本特征，并分析其在保护物联网方面的**有效性**。最后，提出了未来强调开放的可能解决物联网安全问题的方向。  

首先，作者总结了物联网的安全需求：  
  * **数据私密性**、保密性和完整性：物联网数据在网络中需要经过多个跃点，需要适当的服务、设备和网络的多样化集成，存储在设备上的数据很容易受到侵犯隐私的侵害，危及网络中的节点;
  * **认证、授权和计费**：为了保证物联网通信的安全，双方需要进行身份验证。授权机制确保将对系统或信息的访问提供给被授权的人。对资源使用的核算，审计和报告提供了可靠的机制确保网络管理安全;
  * **可用性的服务**：针对物联网设备的攻击可能会通过传统的拒绝服务攻击阻碍服务的提供;
  * **能源效率**：物联网设备资源通常有限，具有低功耗、低存储的特点。针对物联网架构的攻击可能会导致网络的泛滥，并通过冗余或伪造的服务请求耗尽物联网资源，从而增加能源消耗;
  * **单点故障**：基于物联网基础设施的异构网络的持续增长可能暴露大量单点故障，这可能反过来恶化通过物联网设想的服务。它需要为大量物联网设备开发防篡改环境，并为容错网络的实现提供替代机制。

基于智能合约的区块链有望在管理、控制、最重要的是保护物联网设备方面发挥重要作用。总结了区块链解决物联网安全的几种方向。  

  * **地址空间**：区块链的地址空间为160位，可以为物联网设备离线生成和分配地址，且无需注册或唯一性验证，区块链是一个比IPv6更可扩展的物联网解决方案。  
  * **事件的身份和管理**：区块链能够轻松、安全、高效地解决物联网设备所有权和身份关系变化的挑战。区块链已被广泛用于提供可信和授权的身份登记，所有权跟踪和监控产品、商品和资产。  
  * **数据验证和完整性**：链接到区块链网络的物联网设备传输的数据进行加密验证和签名，从而保证传输数据的身份验证和完整性。此外，通过物联网设备进行的所有交易在区块链分布式账本上，可以安全的跟踪。  
  * **身份验证、授权和隐私**：区块链智能合约能够提供去中心化的认证规则和逻辑，从而能够为物联网设备提供单方和多方认证。此外，智能合约可为链接提供更有效的授权访问规则与基于角色的访问管理。通过使用智能合约，可以设置访问规则、条件和时间，允许特定的个人或组用户或机器拥有、控制或访问静止或传输中的数据，从而确保数据的隐私性。  
  * **安全通信**：物联网应用通信协议，如HTTP、MQTT和路由相关协议都不安全，都必须封装在其他安全协议中。使用区块链，密钥管理和分发完全被消除，因为一旦安装并连接到区块链网络，每个物联网设备都将拥有自己的唯一GUID和非对称密钥对。  

论文指出物联网安全性和区块链的研究工作大部分集中在利用区块链技术使物联网总体受益，包括不可变的事件日志、数据访问控制管理、收集物联网数据的交易和物联网设备的对称和非对称密钥管理。这些挑战主要包括**所有权**和**身份关系**、**身份验证**和**授权**、**数据治理**和**隐私**。  

#### (3) 潜在的方向  
  * **资源受限**：物联网的资源约束架构一直是定义安全机制的主要障碍。与传统范式相反，密码算法必须限制在这些约束条件下工作。对于交换密钥或证书所需的任何广播或多播，需要处理存储和能源需求，以便为物联网成功实现安全和通信协议。  
  * **异构设备**：从传感器的小型低功耗设备到高端服务器的异构设备，都需要实现一个动态适应的多层安全框架。在向最终用户提供任何服务之前，该框架应首先适应现有资源，就物联网层安全机制的选择做出决策。
  * **安全协议的互操作性**：为了标准化物联网的安全机制，在不同层次实现的协议需要通过提供转换机制进行互操作。在全局机制中，可以通过考虑体系结构约束来定义每一层安全标准的有效组合。 
  * **单点故障**：对于异构网络、架构和协议，物联网范式比其他范式更容易受到单点故障的影响，还需要进行大量的研究工作，以确保足够的可用性物联网元件，特别是关键任务应用。它需要机制和标准来引入冗余，同时考虑到成本和整个基础设施的可靠性之间的权衡。
  * **硬件和固件的漏洞**：在部署物联网之前，还需要验证硬件中的安全算法、路由和包处理机制的实现。任何在部署后被利用的漏洞都很难被发现和缓解。因此，标准的验证协议是控制物联网安全性的必要条件。
  * **受信任的更新和管理**：，区块链技术可以成为未来物联网设备所有权、供应链和数据隐私的安全可信治理相关问题的解决方案的推动者。然而，区块链技术本身在可扩展性、效率、仲裁/规则和密钥冲突等方面提出了研究挑战。
  * **区块链漏洞**：依赖矿工散列能力的共识机制可能会被破坏，从而允许攻击者宿主区块链。类似地，具有有限随机性的私钥可以被利用来危害区块链账户，还需要定义有效的机制来确保交易的隐私性，避免在交易过程中可能导致双重开销的种族攻击。

``总体来说，本篇论文对物联网各个特性和存在的问题讲述的比较全面，就是感觉前面偏向更底层的通信协议和地址生成问题，比较难理解，引用了许多的参考文献。论文的后半部分指出了许多的几种方向，以及建议的潜在方向，为后面的学习探索提供了更多的选择。``  

### 2.5 论文[5]—"Towards Secure Industrial IoT: Blockchain System with Credit-Based Consensus Mechanism"  
#### (1) 研究背景  
本篇论文指出现有的工业物联网系统容易出现**单点故障**和**恶意攻击**，它不能提供稳定的服务。物联网目前主要需要面对三个主要的挑战：**效率和安全之间的权衡**、**透明度和隐私共存**和**高并发性和低输出**之间的矛盾。  

#### (2) 核心思想  
作者提出了一种基于信任的共识机制的区块链系统，同时能保证系统安全和交易效率。为了保护敏感数据的机密性，作者设计了一个数据权限管理方法去控制对传感器数据的访问。另外，本论文建立基于**有向无环图(Directed Acyclic Graph, DAG)架构的区块链**—tangle，在性能上比传统区块链更高效。  

在tangle网络中，它消除了区块的概念，每笔交易都是链接在分布式分类中的单个节点。在提交一个新交易之前，它必须验证两个已经附加在一起的前交易(在tangle中未验证的交易)，这称为tips。然后，通过工作量证明(POW)算法，新交易与前两个交易捆绑在一起，新的交易可以广播到tangle网络。每笔新交易都将在以后由其他更新的交易进行验证。传统链结构的区块链采用同步共识，而tangle采用了异步共识。DAG结构的区块链并不是一直被单一的主链和分叉所约束，交易之间的关系看起来就像一个错综复杂的网络。这种新颖的体系结构和共识机制可以从理论上提高网络吞吐量和系统响应时间，如图4所示。  
.<img src="https://github.com/Cryptocxf/Reading-Report/blob/main/picture4.png" width="550" height="250" />
 <p align="center">  
图4 基于有向无环图结构的区块链（白色代表验证了的交易，灰色代表tips）  
</p>  

本论文从**系统体系结构**、**基于信用的POW机制**和**数据权限管理**方法三个方面介绍。  

  * **系统体系结构**：根据功能划分为轻节点和全节点。轻节点为功率受限的设备，不存储区块链信息，可验证、运行POW算法和发送新的交易到全节点。全节点为更强大的设备，如网关和服务器，主要维护整个区块链网络。
  如图5所示，为基于区块链的工业物联网系统架构。无线传感器节点初始化生成区块链账号，即一对公开秘密密钥(PK, SK)，作为系统中唯一的标识符。网关作为全节点接收来自各种传感器的请求，并在tangle中广播交易，并只处理来自合法的，经过授权的传感器交易。管理者为一个特定的全节点，负责管理物联网设备。管理器的公钥编码到网关中的软件中，只有管理器有权发布设备的授权列表，并管理物联网设备的添加/删除。tangle网络为公共的区块链网络，任何一方都可以访问该网络。网关保证了网络的安全，并通过广播交易和保留区块链的副本来保持稳定。 
 <img src="https://github.com/Cryptocxf/Reading-Report/blob/main/picture5.png" width="400" height="350" />
 <p align="center">  
图5 基于区块链的工业物联网系统架构  
</p>  

  * **基于信用的POW机制**：定义具有信用值Cr属性的节点i，其信用值会根据节点的行为实时变化。正常行为会增加信用价值，异常行为会降低信用值。POW机制的难度根据每个节点的信用值自适应调整，信用值越低，运行时间越长。因此，该机制将使诚实节点消耗更少的资源，同时迫使恶意节点增加攻击代价。tangle网络是透明的，可以从DAG网络中获取所有传感器的交易信息和它们之间的关系。该系统中POW的难度与信用评分成反比，信用评分在整个系统周期内动态调整。
  * **数据权限管理**：作者提出了一种数据权限管理方法来支持系统中传感器数据的访问控制，和一种无需中央信任方的密钥分发方案。因此可以利用公开密钥加密来分发对称密钥，一次密钥分发分为三个步骤，如图6所示。 

.<img src="https://github.com/Cryptocxf/Reading-Report/blob/main/picture6.png" width="400" height="350" />  

 <p align="center">  
图6 对称密钥分发过程  
</p>  

TS为时间戳，M为消息，生成对称密钥只执行一次，每条消息都使用发送方的密钥签名，以确保接收到的消息不被篡改或损坏。每个消息中的TS标识消息的时效性，用于抵抗重放攻击。  

``总体来说，本篇论文从引言部分就详细的阐述了相关属性之间权衡的挑战，这是目前所有解决方案必须面对的问题，我觉得这种特性权衡的问题也是一个小亮点，以及后面基于信用的POW机制也是比较新颖，但是感觉缺少对其可行性的验证。``  

## 三、读书总结  
本篇读书报告主要围绕了这五篇论文展开学习，分别从**写作背景**、**写作目的**、**主要内容**和**未来前景**等几个方面进行陈述。前四篇为综述型文献，主要概括了物联网、区块链的基本概念和存在的**安全与隐私**问题，以及对比了多种基于区块链技术的物联网方案之间的**优劣势**，指出**未来开放式**的**研究方向**。最后一篇论文为具有**针对性**解决方案的论文，基于工业物联网系统容易出现**单点故障**和**恶意攻击**等问题，提出了一种**高效、安全、低耗**的解决方案。  

  * 论文[1]：作者基于物联网应用层、网络层和感知层的**安全威胁**，指出传统的安全技术已不再适用于物联网，从而提出区块链技术能解决物联网应用中的安全问题，并对结合后的安全性问题做出来了探讨。这篇论文使我对物联网、区块链有了更清晰的认识，特别是认识到物联网处理的是实时的、连续的流式数据，这将是一个影响安全和效率的重要因素。
  * 论文[2]：作者指出了物联网许多的领域可以用区块链技术来解决**安全**和**隐私**问题，也指出了一种判断是否必须用区块链的方法流程，然后对目前的**威胁模型**进行了**分类**。这篇论文几乎对大部分攻击方法进行了**分析**和**汇总**，具有很好的参考意义，且提出了一种判断是否用区块链来解决物联网问题的方法特别新颖，这是其他论文中没有的部分。
  * 论文[3]：作者围绕解决物联网中**安全**和**隐私**两个重要的属性，描述了区块链和物联网**协同工作的框架**，最后作者在隐私方面提出了几种可考虑的技术，例如可链接环签名、同态承诺、零知识证明和AES加密等，以及GHOST协议和有向无环图(DAG)结构的区块链。正好与最后一篇论文用的DAG一样，这类结构的区块链应该是比较流行的方向，需要重点学习。
  * 论文[4]：作者基于物联网底层协议、通信协议的安全问题做出了分析和分类，这些比较偏底层较难理解，后面指出了基于**智能合约**的区块链可以在管理、控制和保护物联网设备方面发挥重要作用，这部分是本篇论文的关键。整体来看，这篇论文的前半部分可以不用细看，都是偏底层比较难懂，只需挑选后半部分阅读即可。
  * 论文[5]：作者基于工业物联网的**安全问题**，提出了一种基于信用的共识机制的**区块链系统**，利用基于DAG结构的区块链实现该系统的体系结构以提高系统的吞吐量，基于信用的POW机制有效防御恶意攻击和降低诚实节点的功耗，以及数据权限管理方法有效地保证一个透明系统中数据的保密性。从这篇论文开始，我是首次认识了基于DAG结构的区块链，然后前面的论文结尾也有提到这种结构，猜想应该是比较适用物联网系统的一种区块链结构，需要我进一步了解，加强这方面的学习，以便寻找到突破点。
