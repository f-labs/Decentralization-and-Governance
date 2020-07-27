# DAO:A Decentralized Governance Layer for the Internet of Value
# DAO：价值互联网的去中心化治理层
Author：George Samman & David Freuden，2020年5月

## content

- [简介](#简介)
- [关键要点](#关键要点)
- [什么是DAO？](#什么是DAO？)
- [DAO是一种误称吗？](#DAO是一种误称吗?)
- [DAOs的技术层](#DAOs的技术层)
- [DAOs与分布式金融（DeFI）](#DAOs与分布式金融（DeFI）)
- [DAO的三角对立关系](#DAO的三角对立关系)
- [治理——权力下放](#治理--权力下放)
- [权力下放——个人](#权力下放--个人)
- [个人——治理](#个人--治理)
- [治理](#治理)
- 常见的DAO治理问题
- DAO仲裁服务
- DAO和公司
- 最后的想法和结论
- DAO生态系统
- 参考文献

## Authors
- **George Samman**
Website:www.sammantics.com
Email:georgesamman42@gmail.com
Twitter:@george_samman
Linkedin:https://www.linkedin.com/in/georgesamman

  George can be found roaming through the crypto-verse. His current headspace is dedicated to decentralized governance, crypto-finance and investing in the ecosystem.
  乔治漫游于加密世界各处。他目前的顶部空间是致力于去中心化治理、加密金融和投资生态系统。
  

- David Freuden
Website:www.monsterplay.com.au
Email:dfreuden@monsterplay.com.au
Twitter:@MonsterplayAus
Linkedin:https://www.linkedin.com/in/davidfreuden

  David is principal at Monsterplay, working with entrepreneurs and their teams to commercialise and scale their businesses. Since 2016 he has been investing, advising and writing about blockchain and cryptocurrencies.
  大卫是Monsterplay的负责人，与企业家及其团队合作，将他们的业务商业化和规模化。自2016年以来，他一直从事区块链和加密货币的投资、咨询和写作。
  
----------------------------------------

## Acknowledgments 致谢

Sarah Miles, PeterPan, Marie Leaf, Kirill Gourov, Alex Kampa, Alex Masmej, Julien Bouteloup, Kain Warwick, Akseli Virtanen, Mark Roddy, Omar Hannoun, Charlie Smith, Dorjee Sun, Kevin O’Hara, Colin Platt, Daniel Bar, Ron Quaranta, Fran Strajnar, James Zaki,Steven McKie, Matt Prewitt


“Under any economic, social, or political system, individuals, business firms, and organizations in general are subject to lapses from efficient, rational, law-abiding, virtuous, or otherwise functional behavior. No matter how well a society's basic institutions are devised, failures of some actors to live up to the behavior which is expected of them are bound to occur, if only for all kinds of accidental reasons. Each society learns to live with a certain amount of such dysfunctional or misbehavior; but lest the misbehavior feed on itself and lead to general decay, society must be able to marshal from within itself forces which will make as many of the faltering actors as possible revert to the behavior required for its proper functioning.”[1]

“In the place of nation-states you will see at first, smaller jurisdictions at the provincial level, and ultimately smaller sovereignties, enclaves of various kinds like medieval city-states surrounded by their hinterlands. As strange as it may seem to people inculcated with the importance of politics, policies of these new ministates will in many cases be informed more by entrepreneurial positioning than political wrangling. These new, fragmented sovereignties will cater to different tastes, just as hotels and restaurants do, enforcing specific regulations within their public spaces that appeal to the market segments from which they draw their customers.”[2]

“The view that state improves the functioning of the economy by massive reallocation of resources is an anachronism….it should not be forgotten that governments waste resources on a large scale. Wasting resources makes you poor. A dramatic improvement in the efficiency of resource use will arise when revenues historically engrossed by governments come to be controlled instead by persons of genuine talent.”[3]

"在任何经济、社会或政治制度下，个人、企业公司和一般组织都有可能出现与高效、理性、守法、良性或其他功能行为相悖的失误。无论一个社会的基本制度设计得多么完善，一些行为者未能达到人们对他们的期望的行为，即使只是出于各种偶然的原因，也必然会发生。每个社会都学会了忍受一定数量的这种功能失调或行为失范；但为了避免行为失范自食其果，导致普遍的衰败，社会必须能够从自身内部调动力量，使尽可能多的失范行为者恢复到正常运作所需的行为。

"在民族国家的位置上，你一开始会看到省一级的小辖区，最终会看到更小的主权国家，像中世纪城邦一样的各种飞地，被其腹地包围。虽然对于那些被灌输了政治重要性的人来说可能会觉得很奇怪，但在很多情况下，这些新的部族国家的政策更多的是通过企业定位而不是政治角力来实现的。这些新的、支离破碎的主权国家将迎合不同的口味，就像酒店和餐馆一样，在其公共空间内执行具体的规定，以吸引其顾客的市场阶层。

"国家通过大规模的资源重新分配来改善经济运行的观点是不合时宜的......不应该忘记，政府大规模地浪费资源。浪费资源会使你变得贫穷。当历史上由政府吞噬的收入转而由真正有才干的人控制时，资源使用效率就会有极大的提高。"

>"Reciprocity is one of the main forms of human sociality and is defined as: cooperation for mutual benefit. The most complex and far reaching examples of reciprocity are market interactions: trading, buying, selling, producing and other economic activities.”
>
> —— Olson,Mancur

>"互惠 "是人类社会性的主要形式之一，它的定义是：互利合作。互惠最复杂、影响最深远的例子是市场互动：交易、买卖、生产和其他经济活动。"
>
>—— 奥尔森、曼库尔(1987)


---------------------------------

[1]. Hirschman, Albert “Exit, Voice And Loyalty” 1971    
[2]. Davidson and Moog “The Sovereign Individual”     
[3]. Olson, Mancur (1987) ‘Diseconomies of Scale and Development’    
   https://www.cato.org/sites/cato.org/files/serials/files/cato-journal/1987/5/cj7n1-5.pdf

---------------------------------

## INTRODUCTION
## 简介

There are many misconceptions around what Decentralized Autonomous Organizations (DAOs) are and their purpose. A DAO at its core is a simplistic organizational structure and governance process that allows for the collective management of common goods which can be economic or non-economic.[4] The future of DAOs, while simplistic now, has the potential to re-create and re-shape the way organizations are structured. It is still very early days being barely 4 years (30 April 2016) since the first DAO was launched. This first DAO aimed to operate as a venture capital fund for investing in cryptocurrency projects and was an unexpected success securing 12.7M Ether (worth $USD 250M at the time). The space has seen significant development and growth since then and has subsequently sprouted many DAOs and seen a broadening in the scope of use cases. This growth is producing a fertile platform for learning, evolution and various forms of adoption.

There are many definitions, assumptions and new terminologies associated with DAOs, and they vary significantly depending on which group you are communicating with. That being said, one of the key assumptions that still warrants clarification is the relationship between decentralized and centralized organizational frameworks. These frameworks are not static points at opposite ends of a spectrum. Rather, the different functions of an organisation operate on a centralization scale.

Another interesting development is how blockchain technology is becoming a platform for capital formation. Decentralized finance uses applications built on open, public blockchains (like Ethereum or Bitcoin) to facilitate financial services to anybody, anywhere without the need for traditional financial intermediaries. Cryptocurrencies and digital assets can be moved directly within the DAO itself. While DAOs have been discussed and experimented with for the last four years, only now have they become the logical extension of the capital formation piece. This extension was first realized with Ethereum and MakerDao,[5] which was one of the first DAOs and Decentralized Finance (DeFi) projects to be built on Ethereum. Decentralized Finance (DeFi) has the potential to spur growth in the formation of DAOs, particularly investment/for-profit DAOs. Despite the potential that DAOs present, they face challenges from legal, governance and security perspectives.

DAOs are as diverse as humanity itself. There are many different categories and feature sets. However, there is one key similar feature amongst DAOs: the collective management of common goods via decentralized governance. The opportunities ahead will be in the formation of new types of organizations based around the interactions between token holders and decentralized governance. 

DAOs make interaction, collaboration, revenue sharing and risks (organization, community) programmable for the first time. This is allowing for an entirely new design space. The first generation internet protocols were stateless (like HTTP) so they needed a data layer for any application functionality. The organization of the “state” of the data layer was provided by the winners of yesterday: Google(for search), Facebook (for social), eBay (for commerce). This allowed them to capture value and drive centralization of the internet. But now the value capture model based on centralized control of the data layer is becoming obsolete: one can not have a competitive advantage based on control of data anymore when we know how to keep a "state" in a decentralized way. Alternatives are now available for people to govern themselves, belong, interact, participate, share ownership, create value, take risks and invest together. The structure of a DAO and the way the community comes together forms the value creation layer.

围绕着什么是分散式自治组织(DAO)及其目的，人们有很多误解。DAO的核心是一种简单化的组织结构和治理过程，它允许集体管理共同的物品，这些物品可以是经济的，也可以是非经济的[4]。 DAO的未来虽然现在很简单，但有可能重新创造和重塑组织的结构方式。自第一个DAO启动以来，距离仅仅4年（2016年4月30日）的时间，现在还处于非常早期的状态。这第一个DAO旨在作为投资加密货币项目的风险投资基金来运作，并取得了意想不到的成功，获得了1270万以太币（当时价值2.5亿美元）。从那时起，该领域得到了显著的发展和增长，随后萌生了许多DAO，并看到了用例范围的扩大。这种增长正在产生一个肥沃的学习、进化和各种形式的采用平台。

与DAO相关的定义、假设和新的术语有很多，而且根据你与哪个群体交流，它们有很大的不同。尽管如此，其中一个关键的假设仍然值得澄清，那就是分散式组织框架和集中式组织框架之间的关系。这些框架并不是处于光谱两端的静态点。相反，一个组织的不同职能是在集中化的范围内运作的。

 另一个有趣的发展是区块链技术如何成为资本形成的平台。去中心化金融使用建立在开放的公共区块链（如Ethereum或比特币）上的应用程序，为任何人、任何地方提供便利的金融服务，而不需要传统的金融中介机构。加密货币和数字资产可以直接在DAO本身内移动。虽然DAO在过去四年里一直在讨论和实验，但直到现在才成为资本形成这一块的逻辑延伸。这种延伸最早是在Ethereum和MakerDao上实现的，它是第一批建立在Ethereum上的DAO和去中心化金融（DeFi）项目之一。去中心化金融（DeFi）有可能刺激形成DAO的增长，特别是投资/盈利性DAO。尽管DAO具有潜力，但它们面临着法律、治理和安全方面的挑战。

DAO就像人类本身一样多种多样。有许多不同的类别和特征集。然而，DAO之间有一个关键的相似特征：通过分权治理对共同物品进行集体管理。未来的机会将是围绕代币持有者和分散式治理之间的互动而形成的新型组织。

DAO第一次让交互、协作、收益分享和风险（组织、社区）可编程。这是一个全新的设计空间。第一代互联网协议是无状态的（如HTTP），所以它们需要一个数据层来实现任何应用功能。数据层的 "状态 "的组织是由昨天的赢家提供的。Google（搜索）、Facebook（社交）、eBay（商务）。这使得他们能够获取价值，推动互联网的中心化。但现在，基于数据层中心化控制的价值获取模式已经过时了：当我们知道如何以去中心化的方式保持 "状态 "的时候，就不可能再有基于数据控制的竞争优势了。现在，人们可以有替代方案来管理自己、归属、互动、参与、分享所有权、创造价值、承担风险和共同投资。DAO的结构和社区聚集的方式构成了价值创造层。

--------------------
[4]. These can be political systems, donations, cultural works, natural resources, investing, lending etc.    
[5]. https://makerdao.com/en/whitepaper

---------------------


## KEY TAKE-AWAYS
## 关键要点

- The key feature that changed organizations over the years has been: reducing transaction costs to coordinate. This is reflected in Coase’s Theory of the Firm. You can achieve marginal improvements, such as applying decision support systems within an organization, but every once in a while, a large systemic change occurs that at first looks like a marginal benefit, but in essence enables wholly new types of organizations to exist.
  
- DAOs not only allow for the reduction of transaction costs, but new organizational forms and compositions to be created.

- In order to have a highly functional DAO, members must:
  - Have equal access to the same information for decision-making
  - Face the same costs for transacting their preferred choices
  - Base their decisions on self-interest and the best interest of the DAO (not on coercion or fear)
  
- DAOs attempt to solve coordination problems by solving problems associated with collective actions by aligning individual incentives with globally optimal outcomes (for people or corporations). By pooling funds and voting on fund allocation, stakeholders share the costs and incentivize coordination so the entire ecosystem benefits.

- DAOs are performing the biggest experiment in new forms of alternative governance. These experiments are not in the form of giant nation-states but applied on a local community level. This comes at a time where peak globalization is in the rear-view window and the world is retreating to a more local model.

- It is important to note, Bitcoin was the first DAO. It is run without a central authority by a core team of developers who propose decisions on the future direction of the project, mainly through Bitcoin Improvement Proposals (BIPs) which need consensus from all network participants (though mainly miners and exchanges) for changes in the code to be made.

- There will be a growing number of DSaaS (DAO Software as a Service) providers, such as OpenLaw, Aragon and DAOstack, designed to accelerate the growth of DAOs as a category. They will provide on-demand specialized resources such as legal, accounting, and third party auditing for compliance services.

- In a DAO a triangle of tensions exists. This lexicon of the triangle is based on the treatise “Exit, Voice & Loyalty” by Albert Hirschman. These must be balanced to find an optimal outcome which allows the DAO to achieve its mandate:
  - Exit (Individual)
  - Voice (Governance)
  - Loyalty (Decentralization)

- 这些年来，改变组织的关键特征是：降低协调的交易成本。这在科斯的《公司理论》中得到了体现。你可以实现边际改善，比如在组织内部应用决策支持系统，但每隔一段时间，就会发生一次大的系统性变革，起初看起来像是边际效益，但从本质上讲，它使全新的组织形式得以存在。
  
- DAO不仅可以降低交易成本，而且可以创造新的组织形式和组成。

- 为了拥有一个高功能的DAO，成员必须。
  - 平等地获得相同的决策信息
  - 面对同样的成本来处理他们喜欢的选择
  - 以自身利益和DAO的最大利益为基础做出决定(而不是以胁迫或恐惧为基础)；

- DAO试图通过解决与集体行动相关的问题来解决协调问题，使个人激励与全局最优结果（对人或企业而言）保持一致。通过汇集资金并对资金分配进行投票，利益相关者分担成本并激励协调，从而使整个生态系统受益。  

- DAO正在以一种可替代的新的治理形式进行一项伟大的试验。这些实验不是以巨大的民族国家的形式，而是应用在地方社区层面。这是在全球化高峰期已经过去，世界正在向更加地方化的模式撤退的时候出现的。

- 需要注意的是，比特币是第一个DAO。它是在没有中央权威机构的情况下运行的，由一个核心的开发者团队对项目未来的发展方向提出决策建议，主要是通过比特币改进提案（BIPs），需要所有网络参与者（虽然主要是矿工和交易所）达成共识，才能对代码进行修改。

- 将会有越来越多的DSaaS（DAO软件即服务）提供商，如OpenLaw、Aragon和DAOstack，旨在加速DAO这个类别的发展。他们将提供按需的专业资源，如法律、会计和第三方审计的合规服务。

- 在一个DAO中，存在一个三角对立关系。这个三角关系的词汇是基于Albert Hirschman的论文 "Exit, Voice & Loyalty"。必须平衡这些因素，以找到一个最佳结果，使DAO能够实现其任务。
  - 叛出（个人）
  - 抗议（治理）
  - 忠诚度(权力下放)


- DAOs challenge the traditional hierarchical and exclusive organizational structure as seen in many facets of the world today. Through “wisdom of the crowds” it is possible to have better collective decision making and therefore better-run organizations.

- New products are being made at the intersection of DAOs and Decentralized Finance[6] (DeFi). As DAOs become more decentralized and digitized using DeFi products as the payment/distribution methods, DAOs will increase and lead to new and more DeFi products being formed to interact with DAOs. This will be most powerful where the DeFi implementations allow the token holders to use governance to customize and optimize the design of the parameters of the application creating a better, tailored user-experience. It can also be used for time locking and creating different types of fee structures.

- DAOs allow for capital to be pooled, that pooled capital to be allocated and to create an asset-backed by that capital. They also allow for non-financial resource allocation. 

- Using DeFi enables DAOs to bypass, if they choose, the traditional banking sector, along with their inefficiencies. This is significant as it creates a Trustless, Borderless, Transparent, Accessible, Interoperable & Composable[7] corporation.

- DAO community and governance is very complex and difficult to get right, yet is crucial to the success of the DAO. Coordination processes and incentive measures need to be balanced so that all community members feel that their contributions matter.

- Many DAOs will be looking to wrap a legal structure with underlying smart contract code around the entity so as to comply with regulations, provide legal protection and limited liability to their participants and allow for easier deployment of capital.

- DAO is a Misnomer. DAOs today are not fully decentralized, nor are they fully autonomous and in some cases, they may never aspire to be either. Most DAOs will start centralized, then start adopting smart contracts to automate simple internal processes and limit centralized governance. With an aligned purpose, good design, and luck they can grow towards being a truer version of a DAO in time.This misnomer has led to a lot of hype around the distributed autonomy of DAOs versus the reality of what they are today.

- DAOs are not radical or unique to blockchain technology. There is a long history of DAOs to improve governance structures, decentralized decision making, improve and enforce transparency, and enable membership voting and active participation in decision making.

- DAO participation currently targets a niche within a niche within a niche. Many DAOs require minimum staking for participation in a cryptocurrency. This limits participation to the crypto participants who are wealthy, tech-savvy enough, and interested enough to participate in a DAO.

- DAO挑战的是传统的等级制和排他性的组织结构，这在当今世界的许多方面都可以看到。通过 "众人的智慧"，可以有更好的集体决策，从而有更好的组织运行。

- 在DAO和去中心化金融[6]（DeFi）的交叉点上，新的产品正在诞生。随着使用DeFi产品作为支付/分配方式的DAO变得更加分散和数字化，DAO将增加，并导致新的和更多的DeFi产品被形成，以与DAO互动。这将是最强大的地方，DeFi实现允许代币持有者使用治理来定制和优化应用的参数设计，创造更好的、量身定制的用户体验。它还可以用于时间锁定和创建不同类型的收费结构。

- DAO允许汇集资本，对汇集的资本进行分配，并创建由该资本支持的资产。它们还允许进行非金融资源分配。

- 使用DeFi使DAO能够绕过传统的银行部门，以及他们的低效率，如果他们选择的话。这一点非常重要，因为它创造了一个无信任、无边界、透明、可访问、可互操作和可组合的公司。[7]

- DAO社区和治理是非常复杂和难以做好的，但对DAO的成功至关重要。协调过程和激励措施需要平衡，以使所有社区成员感到他们的贡献很重要。

- 许多DAO将寻求在实体周围包裹一个带有底层智能合约代码的法律结构，以便遵守法规，为其参与者提供法律保护和有限的责任，并允许更容易地部署资本。

- DAO是一个误称。今天的DAO并不是完全去中心化的，也不是完全自治的，在某些情况下，它们可能也永远不会渴望成为这样的组织。大多数DAO会从中心化开始，然后开始采用智能合约来自动化简单的内部流程，限制中心化治理。如果有一个一致的目的，良好的设计和运气，他们可以在一段时间内成长为一个更真实的DAO版本.这个错误的名称导致了围绕DAO的分布式自治与今天的现实进行了大量的炒作。

- DAO不是激进的，也不是区块链技术所独有的。DAO在改善治理结构、去中心化决策、提高和执行透明度、实现会员投票和积极参与决策方面有着悠久的历史。

- DAO参与目前针对的是小众中的小众。许多DAO要求参与加密货币的最低赌注。这就限制了那些有钱、懂技术、有兴趣参与DAO的加密参与者的参与。


----------------------------------
[6]: Decentralized finance uses applications built on open, public blockchains (like Ethereum) to facilitate financial services to anybody, anywhere.     
[7]: Creating services with other existing projects by plugging existing projects into your project.

-----------------------------------

## WHAT IS A DAO?
## 什么是DAO？

A Decentralized Autonomous Organization (DAO) is an organization where the rules of operation and organizational logic are encoded as a smart contract on a blockchain. The characteristics of a DAO are decentralization, transparency, and independence. The end goal is non-centrally controlled decision making and governance[8]. Note that the rules of operation can include mechanisms to change the rules themselves.

DAOs are currently formulated as a cross-section of a real-world and digital corporation. This formulation combines blockchain technology, organizational structures, legal entities, workflow execution, governance/voting, incentive structures, and contribution/work. Their decentralized and autonomous elements create the opportunity to realign, streamline and automate organizational structure and operational requirements such as governance, voting, asset/wealth distribution, membership/participation, participant contribution, incentives, financial and legal contracts.

DAOs can also be described as an entity that lives on the internet and exists autonomously. Something (be it record keeping, policy voting, and/or money management) must happen on-chain, or at least through some kind of smart contract(s). For example, driverless cars using toll roads could pay fees, automatically schedule and pay for servicing, or even operate as an Uber collecting fees and deriving revenue.

A DAO is essentially a composition of smart contracts built on decentralized infrastructure. Smart contracts are simply programmable transactions.[9] DAO transactions are programmed to execute when the majority of the voters (voters who hold tokens) find consensus and a pre-programmed outcome is activated as a result of the consensus. DAOs may program different voting thresholds for triggering an action or outcome. (e.g. 75% need to agree not just a 50/50 split, or differing levels of quorum in order to pass voted actions.)

去中心化自治组织(DAO)是一种组织，其运作规则和组织逻辑被编码为区块链上的智能合约。DAO的特点是去中心化、透明和独立。最终目标是非中心化控制的决策和治理[8]。需要注意的是，操作规则可以包括改变规则本身的机制。

DAO目前的表述是现实世界和数字公司的交叉。这种表述结合了区块链技术、组织结构、法律实体、工作流执行、治理/投票、激励结构和贡献/工作。它们的去中心化和自治元素创造了重新调整、简化和自动化组织结构和运营要求的机会，如治理、投票、资产/财富分配、成员/参与、参与者贡献、激励、财务和法律合同。

DAO也可以被描述为一个生活在互联网上并自主存在的实体。一些事情（无论是记录保存、政策投票和/或资金管理）必须在链上发生，或至少通过某种智能合约。例如，使用收费公路的无人驾驶汽车可以支付费用，自动安排和支付服务费用，甚至像Uber一样收取费用并获得收入。

DAO本质上是建立在去中心化基础设施上的智能合约的组成。智能合约就是简单的可编程交易[9]，DAO交易被编程为当大多数投票者（持有代币的投票者）发现共识时执行，并因共识而激活一个预先编程的结果。DAO可以编程不同的投票阈值来触发行动或结果。(例如，需要75%的人同意，而不仅仅是50/50的比例，或不同的法定人数水平，以通过表决的行动。)

-------------------------
[8]. One of the main benefits of Ethereum is that it enables a community of strangers to pool value together and execute on their shared goals with less need for trust or organizational overhead. Disparate groups of people online can organize by relying on the predictability of blockchain-based “smart contracts” to execute on their group decisions and transfer value according to hard-coded rules in a highly “tamper proof” digital environment. [From OpenLaw]

[9]. For a comprehensive overview of smart contracts see:
   https://bitsonblocks.net/2016/02/01/gentle-introduction-smart-contracts/

----------------------------

#### Differences
#### 差异性

Let's first focus on the features that make a DAO different from traditional organizations. The first difference is the fact that the rules are housed within an immutable computer program. The advantage is that the rules cannot be easily changed, only upgraded, making it resistant to direct attacks on the governance rules. History has shown that one of the ways a democratic country can shift towards dictatorship is by perverting the rules of democracy. A DAO aims to solve these problems but is not there yet. For example, some dictators have been elected or given powers democratically - even Hitler ascended to be Chancellor of Germany through the democratic process. This would also be possible in a DAO as they are presently constructed.

There are also downsides and risks to this, including:
- The program could include bugs.
- Except for simple organizations, it is not easy to write rules that reflect the complexity that characterizes human decision-making.
- There is some rigidity in the system, for example, in unforeseen situations rules cannot be quickly changed.
- Code compatibility can be an issue as new code is added with the evolution of DAOs
  
Note, however, that in the same way as no democratic system is resistant to dictatorship, no DAO is resistant to a change of rules that would essentially give control of the DAO to one person or entity. An example of this has been the global response to COVID-19, where many nation-states have moved to states of exception. In the case of Hungary, the Prime Minister, Victor Orban used the situation to introduce a special state of powers where he will govern by decree for an indefinite period of time. All it takes is a sufficient majority of stakeholders to game the voting process or exploiting/deploying malicious code. Another issue is that the voters will not always be experts in the subjects they are voting on which could lead to poor decisions compared to trusting those decisions to be made (still with governance in place) by executives who have deep subject matter expertise.

Another difference is the decision-making process in centralized versus decentralized corporations. In centralized organizations, decision making power is delegated to a few elected individuals (e.g. board or politicians) governed by a traditional governance system (e.g. separation of powers) In decentralized organizations, decision making is distributed and power is given to all interested parties (e.g. shareholders) as governed by pre-defined rules that exist on decentralized infrastructure.

让我们首先关注一下使DAO不同于传统组织的特点。第一个不同之处是，规则被安置在一个不可改变的计算机程序中。其优点是规则不能轻易改变，只能升级，这就使得它能抵御对治理规则的直接攻击。历史表明，一个民主国家转向独裁的方式之一，就是歪曲民主规则。DAO旨在解决这些问题，但目前还没有达到这个目的。例如，一些独裁者是通过民主选举或赋予权力的--甚至希特勒也是通过民主程序成为德国总理的。在目前构建的民主发展组织中，这也是可能的。

这里也有缺点和风险，包括： 

- 程序可能会有bugs。
- 除了简单的组织，要写出反映人类决策复杂性特点的规则是不容易的。
- 系统有一定的刚性，例如，在不可预见的情况下，规则不能迅速改变。
- 代码兼容性可能是一个问题，因为随着DAO的发展，新的代码不断增加。

然而，请注意，正如任何民主制度都无法抵御独裁一样，没有一个DAO能够抵抗规则的改变实质上是将DAO的控制权交给一个人或实体。这方面的一个例子是全球对COVID-19的反应，许多民族国家已经转为异常状态。在匈牙利，总理 Victor Orban 利用这种情况推出了一种特权状态，他将通过法令无限期地进行执政。所需要的是足够多的利益相关者参与投票过程或利用/部署恶意程序。另一个问题是，相比于信任那些由拥有深厚专业知识的高管（仍在治理中）做出的决策，选民并不总是他们所投票的领域的专家，这可能导致糟糕的决策。

另一个区别是集权式公司与分权式公司的决策过程。在集权式组织中，决策权被授予少数经选举产生的个人(如董事会或政治家)，由传统的治理制度(如分权)来管理。 在分权式组织中，决策权被打散，权力被赋予所有相关方(如股东)，由存在于分权式基础设施上的预定规则来管理。


#### Anonymity
#### 匿名性

Depending on the blockchain, DAO “shareholders” may be able to remain anonymous or pseudonymous. Some proponents have seen that as an advantage, protection from influence from each other or to prevent factions from occurring. Some participants may also want to remain anonymous due to privacy concerns from certain entities (e.g. government authorities). The downside is legal uncertainty, de facto impossibility to enter into contractual agreements. Another risk is one person or entity secretly gaining control of the DAO (e.g. a potential Sybil attack).


依赖于区块链的特性，DAO 的"股东"可能会保持匿名或假名。一些支持者认为这是一种优势，可以保护自己不受对方的影响，或防止派别的发生。一些参与者也可能因为某些实体（如政府当局）的隐私考虑而希望保持匿名。缺点是法律上的不确定性，事实上不可能签订合同协议。另一个风险是一个人或实体秘密获得对DAO的控制权（如潜在的 Sybil 攻击）。

#### Similarities
#### 相似性

In the end, any organization is run by humans, and this applies for the governance of DAOs also. Because human decision-making is typically very complex, encoding this into formal rules is difficult, if not impossible. In other words, even in a DAO most of the decision process will be done off-chain anyway. Think of a democracy, and compare the time spent in debates and discussions to the time spent actually voting. The hope that by encoding an organization’s governance in blockchain smart contracts this will magically solve governance problems was, of course, an illusion. This is not the only issue with DAOs. In contrast with the world-changing ambitions of blockchain / DAO enthusiasts, the governance rules that have been developed for DAOs so far are generally rather simple and lack significant innovation. DAOs are the first iteration of the transition to a programmable medium for both organizations and the economy. Over time this will allow for a greater heterogeneity of organizational and economic structures.

As governance and technology evolve one can be certain that the DAO of today will be very different from the DAO of tomorrow. As DAOs grow and become more common and accepted outside of just the blockchain ecosystem, they may also impact existing organizations as they may see a DAO as a mechanism to improve their own governance and stakeholder engagement.

归根结底，任何组织都是由人管理的，这也适用于发展DAO组织的治理。由于人的决策通常是非常复杂的，将其编码为正式的规则是困难的，甚至是不可能的。换句话说，即使在DAO中，大部分的决策过程也会在链外完成。想一想民主制度，比较一下辩论和讨论的时间与实际投票的时间。希望通过将一个组织的治理编码在区块链智能合约中，这将神奇地解决治理问题，当然，这只是一种幻想。这不是DAO的唯一问题。与区块链/DAO爱好者们改变世界的雄心壮志相比，迄今为止为DAO制定的治理规则普遍比较简单，缺乏重大创新。DAO是组织和经济向可编程媒介过渡的第一次迭代。随着时间的推移，这将使组织和经济结构更加异质化。

随着治理和技术的发展，可以肯定的是，今天的DAO将与明天的DAO截然不同。随着DAO的发展，并在区块链生态系统之外变得更加普遍和被接受，它们也可能会影响现有的组织，因为它们可能会将DAO视为改善自身治理和利益相关者参与的机制。


![](./assets/dao-ecosystem.png)

1) **Tech-Related Developer Grants**: These DAOs give grants to teams building out technology and infrastructure on existing platforms. They incentivize developers to build out projects to improve existing protocols/organizations.
2) **Non-Tech Grants**: Giving out grants for social, economic, political and community-based activities.
3) **Investment DAOs (for-profit)**: DAOs that invest capital into projects.
4) **Decentralized Governance**: These companies are specifically working on building out tools and infrastructure to enable decentralized governance capabilities to be built into DAOs.
5) **DDeFI DAOs (for-profit)**:These DAOs are building out different parts of the Decentralized Finance stack aka “money legos”.
6) **Protocols / Organizations**:These are the underlying protocols DAOs are being built on top of. Organizations/Companies are also creating DAOs for token holders.
7) **DSaaS (DAO Software as a Service)**:Software platforms that provide infrastructure to build out DAOs.

_Copyright © 2020 George Samman and David Freuden_


## IS DAO A MISNOMER?
## DAO是一种误称吗？

For a DAO to be created it requires human decision-making to identify the opportunities, validate the need, possibly find co-collaborators, and to map out the processes that can be automated and built into smart contracts. These are all activities of centralized[10] or distributed teams as coordination, contribution, and communication are key elements to building a DAO.

要创建一个DAO，就需要人的决策，以确定机会，验证需求，可能找到共同合作者，并规划出可以自动化和建立在智能合约中的流程。这些都是集中式[10]或分布式团队的活动，因为协调、贡献和沟通是建立DAO的关键要素。

####How do you bootstrap a decentralized system without being in charge  
——DAO Founder:Christoph Jentzsch - AraCon 2019

####如何在不用全面负责的情况下引导一个去中心化的系统？
——DAO 创始人：Christoph Jentzsch - AraCon 2019

Other centralized elements:
- Nearly every DeFi smart contract that's capable of holding your funds has an admin key. Some of those admin keys can be used maliciously if they fall into the wrong hands. It's very hard to find out how these keys are protected - some products that live on the blockchain have a kill function, while others have a pause function or a master key to stop and making it difficult from the onset to decentralize. By design, others may disable such functionality after a period (incremental decentralisation), or library contracts.
- The protocol should only be upgraded through the consensus of representative stakeholders. The original team which developed the protocol should not be able to arbitrarily upgrade the logic of the smart contracts.
- A DAO must have a source of funds and a process for allocating those funds for development in a way which is secure.

One of the most interesting and pertinent questions is whether or not DAOs can be integrated into traditional business models to improve operations, reduce operational costs and timeframes, create transparency and streamline automated processes that require transparency. This approach and direction bring with it many challenges, including the logistics of how to decentralize with controlled risk, defining what decentralization means to this specific organization and the scale and speed that this decentralization will take. These decisions are made by a centralized body. There are examples of entities with DAO-like structures that have operated successfully, albeit not with technological structures and benefits of DAOs, these include Coop Unions, Credit Unions, Guilds and even the Green Bay Packers, a publicly held non-profit corporation that owns the Green Bay Packers football franchise of the National Football League (NFL).

其他集中的要素：

- 几乎每一个能够持有你资金的DeFi智能合约都有一个管理密钥。其中一些管理密钥可能会被恶意使用，如果他们落入坏人之手。很难找出这些密钥是如何被保护的——一些存在于区块链上的产品具有终止功能，而另一些产品则具有暂停功能或主密钥来停止，从一开始就很难分散。根据设计，其他产品可能会在一段时间后禁用这种功能（增量去中心化），或者库合同。

- 协议应该通过有代表性的利益相关者的共识才能升级。开发协议的原团队不应该能够任意升级智能合约的逻辑。

- DAO必须有一个资金来源，以及以安全的方式分配这些资金用于开发的程序。

最有趣和相关的问题之一是dao是否可以集成到传统的业务模型中，以改进操作、降低操作成本和时间框架、创建透明度并简化需要透明度的自动化流程。这种方法和方向带来了许多挑战，包括如何在风险可控的情况下下放权力，界定权力下放对这一特定组织意味着什么，以及这种权力下放将采取的规模和速度。这些决定是由一个中央机构作出的。有一些具有类似DAO结构的实体成功运作的例子，尽管它们没有DAO的技术结构和好处，这些例子包括合作社联盟、信用社、行会，甚至包括绿湾包装工队，这是一家上市的非营利性公司，拥有美国国家橄榄球联盟（NFL）绿湾包装工队的特许经营权。

Because of this centralized to decentralized approach, the definitions around the decentralized component varies greatly DAO to DAO, subsequently, the ease and adoption of greater decentralization is still a long way from becoming a reality.

The construct of Autonomous (in DAO) is challenging, as the definition begets the question, Autonomous from whom? Organizations still need to operate within the legal framework of jurisdictions of its own structure, as well as the jurisdiction of its participants and members. For example, when a not-for-profit employs people, those people are required to pay the tax within the jurisdiction in which they are citizens. There is also evolving SEC (or other financial regulatory body) guidance on whether governance or operational tokens will be defined as securities, currencies, or commodities. This varies greatly as different DAOs need to prove a certain threshold of decentralization.

Many DAO standards are more iterative than revolutionary. They wish to maintain existing legal and social structures of organizations and implement blockchain for transparency-related tasks such as record keeping, yet still maintain the capacity to use traditional methods if required. From a technological standpoint, DAO forks are also an iterative approach which allow members to take existing code and use it for their expressed purposes in building a DAO which is different from the original DAO. An example of this is Moloch DAO.[11] The code has been forked by other DAO’s in the Ethereum ecosystem.[12] Other smart contract platforms like Kadena have upgradeable code. Pact, which is Kadena’s smart contract language is non-Turing complete (no recursive attacks)[13] and includes formal verification[14] of the code which allows for correctness in the code to be found before smart contracts go live. These iterative technological approaches introduce the transparency and trust layers of blockchain and DAO into an organization’s corporate structure but do not necessarily reduce the legal and technical costs of developing DAOs, nor remove jurisdictional and legal uncertainty.

由于这种从集中到分散的方法，围绕分权部分的定义在DAO到DAO之间有很大的差异，因此，距离更大程度的分权变得容易和被采用,仍然还有很长的路要走。

自治（在DAO中）的构建是具有挑战性的，因为该定义产生了一个问题：自治来自谁？各组织仍然需要在其自身结构的司法管辖区以及其参与者和成员的管辖权的法律框架内运作。例如，当一个非营利组织雇用人员时，这些人必须在其公民管辖范围内缴纳税款。此外，美国证券交易委员会（或其他金融监管机构）也在就治理或运营代币是否定义为证券、货币或商品制定指导意见。由于不同的DAO需要证明一定的去中心化门槛，这一点差别很大。

许多DAO标准更多的是迭代而不是革命性的。他们希望维持组织现有的法律和社会结构，并实施区块链以执行与透明度相关的任务，如记录保存，但仍保持在需要时使用传统方法的能力。从技术的角度来看，DAO分叉也是一种迭代的方法，允许成员获取现有代码并将其用于其表达的目的，从而构建与原始DAO不同的DAO。Moloch DAO[11]就是一个例子。该代码已经被Ethereum生态系统[12]中的其他DAO所分叉。其他智能合约平台，如Kadena，也有可升级的代码。Pact是Kadena的智能合约语言，它是非图灵完备的（没有递归攻击）[13]，并且包括对代码的正式验证[14]，允许在智能合约生效之前发现代码的正确性。这些迭代的技术方法将区块链和DAO的透明度和信任层引入组织的企业结构中，但并不一定能降低开发DAO的法律和技术成本，也不能消除管辖权和法律的不确定性。


---------------------
[10]. https://bzx.network/blog/introducing-bzxdao

[11]. https://concourseopen.com/blog/moloch-dao-explained/

[12]. It’s important to note this not only applies to DAOs. See the recent Steemit/Hive fork. Hive forked from Steemit after the takeover. The community left Steemit to form Hive. https://hackernoon.com/inside-trons-steem-takeover-attempt-and-the-birth-of-the-hive-blockchain-ya1g63249

[13]. Note: This how the DAO was hacked.

[14]. https://runtimeverification.com/blog/how-formal-verification-of-smart-contracts-works/

---------------------


## TECHNOLOGY LAYER FOR DAOs
## DAO的技术层

The Base Layer used for DAOs is based on blockchain technology provided by protocols like but not limited to Ethereum, EOSDac (decentralized autonomous corporation), Tezos, Cosmos, Decred, Dash, Enigma and Colony to name a few. At the platform level, you have companies like Aragon and DAOstack which use solidity and can be considered DSaaS (DAO software as a service) models. DAOs built using Aragon and DAOstack sit at application level. It is important to note that you don’t need to use Aragon or DAOstack to build DAOs and that you can fork existing DAOs to create a specific DAO for your needs.

**he diagram below shows how The DAO ecosystem is built using Ethereum.**

![](./assets/build-dao-using-ethereum.png)

Other technology pieces for DAOs come from the underlying protocol (but can be forked) such as the core consensus mechanism and Improvement Proposals/software upgrades. Synthetix is taking a slightly different approach to this problem, they are deploying “governance by exception” approach.[15]

Governance by exception appoints a council of experts to manage protocol upgrades but allows tokenholders to veto any specific change. This approach focuses on protocol iteration as being critical in the early stages of development. Synthetix is working on this structure with Aragon.

![](./assets/governance-by-exception.png)

DAOs exist as part of the Layer 2 ecosystem built on top of Ethereum as an example.
See the image below:

![](./assets/layer2-on-ethereum.png)


DAO使用的基础层是基于协议提供的区块链技术，如但不限于Ethereum、EOSDac（去中心化自治公司）、Tezos、Cosmos、Decred、Dash、Enigma和Colony等。在平台层面，你有像Aragon和DAOstack这样的公司，它们使用solidity，可以被认为是DSaaS（DAO软件即服务）模式。使用Aragon和DAOstack构建的DAO处在应用层面。需要注意的是，你不需要使用Aragon或DAOstack来构建DAO，你可以fork现有的DAO来创建一个特定的DAO来满足你的需求。

**下图显示了如何使用以太坊构建DAO生态系统。**

![](./assets/build-dao-using-ethereum.png)

DAO的其他技术部分来自底层协议（但可以分叉），比如核心共识机制和改进提案/软件升级。Synthetix对这个问题采取了一种稍微不同的方法，他们正在部署 "异常（exception）治理 "的方法[15]。

异常（exception）治理任命一个专家委员会来管理协议升级，但允许代币持有人否决任何具体的变化。这种方法侧重于协议迭代，因为在开发的早期阶段，协议迭代是至关重要的。Synthetix正在与Aragon一起研究这种结构。

![](./assets/governance-by-exception.png)

以Ethereum为例，DAO是作为建立在Ethereum之上的第二层生态系统的一部分而存在的。

见下图：

![](./assets/layer2-on-ethereum.png)


------------------
[15]. https://github.com/Synthetixio/SIPs/issues/98

[16]. McKie, Steven ‘The Year of the DAO Comeback’ (2019)
    https://medium.com/amentum/the-year-of-the-dao-comeback-9c888b44980
    
_governance by exception,异常治理，应该是指针对一些异常的、非一般性的状况进行的治理_ 

------------------

## DAOs AND DECENTRALIZED FINANCE (DeFI)
## DAOs与分布式金融（DeFI）

Decentralized finance uses applications built on open, public blockchains (like Ethereum or Bitcoin) to facilitate financial services to anybody, anywhere without the need for traditional financial intermediaries. Cryptocurrencies and digital assets can be moved directly within the DAO itself. This is accomplished through a feature called composability (aka money legos). Composability allows for protocols and applications to be selected and assembled in combinations. An example is how Ethereum is a protocol which MakerDAO, another protocol, is built on top of. MakerDAO is used by many other DeFi applications and those applications use others themselves. DAOs are using these pieces for the treasury function and network value transfer.

The two core pieces that make DeFi flourish in networks are liquidity and collateral. Liquidity is about the state, the banking system it superintends, and the money it issues. DeFi challenges the centrality of the states and the banking system as the source of money issuance, proposing instead p2p reciprocal issuance amongst agents in a network. In normal times, free markets determine what is acceptable as collateral and what is not, and how they can be utilized for leverage. A worker’s primary asset is their capacity to work and earn money. In the context of work, the employer (owner) can use the worker as collateral; yet the worker cannot use themselves as collateral. The collateral question is the financial version of ‘class’. In DAO+DeFi compositions, all agents can issue assets to be used as collateral.

去中心化金融使用建立在开放的公共区块链（如Ethereum或比特币）上的应用程序，为任何人、任何地方提供便利的金融服务，而不需要传统的金融中介机构。加密货币和数字资产可以直接在DAO本身内移动。这是通过一种称为可组合性（又称货币乐高）的功能来实现的。可组合性允许选择协议和应用，并进行组合组装。一个例子是Ethereum是如何作为一个基础协议，令MakerDAO、以及其他协议建立在其之上。MakerDAO被许多其他DeFi应用使用，这些应用本身也使用其他应用。DAO证是使用这些组件来实现财政功能和网络价值转移。

使DeFi在网络中蓬勃发展的两个核心部分是流动性和抵押品。流动性是关于国家、它所监管的银行系统和它所发行的货币。DeFi挑战了国家和银行系统作为货币发行源头的中心地位，而提出了网络中代理人之间的p2p互惠发行。在正常情况下，自由市场决定什么是可接受的抵押品，什么是不可接受的抵押品，以及如何利用它们来做杠杆。劳动者的主要资产是其工作和赚钱的能力。在工作的情况下，雇主（所有者）可以把工人作为抵押品；但工人却不能把自己作为抵押品。抵押品问题就是金融版的 "阶级"。在DAO+DeFi构成中，所有代理人都可以发行资产作为抵押品。


>DAO+DeFi allows expanding the grammar of finance - freeing it from its narrow use right now - to making intangible, informational, relational values (native to the internet) recognizable and economically expressible - and thus exchangeable, liquid, consumable, spendable and stakeable - without necessarily reducing their information into one index of price and one measuring unit of profitability, without restricting their use by proprietary ownership, without hiding their source code, without needing to monetize them via advertising.   
> ——Akseli Virtanen, ECSA
                          
>DAO+DeFi允许扩展金融语法--将其从目前的狭隘使用中解放出来--使无形的、信息性的、关系性的价值（互联网的原生价值）可以被识别和经济地表达出来--因此是可交换的、可流动的、可消费的、可花费的和可押注的--而不一定要将它们的信息缩减为一个价格指数和一个衡量盈利能力的单位，不通过所有权限制它们的使用，不隐藏它们的源代码，不需要通过广告将它们货币化。  
>
>--Akseli Virtanen, ECSA


## DAO TENSION TRIANGLE
## DAO的三角对立关系

### What is a Tension Triangle

In the instance of a DAO, the tension triangle can be considered a balancing act between three distinct yet equally important components. This is not a traditional trilemma as much as a triangle of tensions. As you slide around, there are tensions that need to be ameliorated between all sides. While it is difficult at times, an optimal mix can be achieved if the dynamics are right. This sliding scale is not a static point in time so moving towards one side and away from another gives different degrees of interaction with each other. It is a balancing act which if approached properly will lead to the long term success of the DAO. Most DAOs use trial and error and gradual adjustment to move toward what the participants feel is optimal. It must be noted that this tension triangle may not hold in the long run existence of the DAO.

A trilemma is different from a tension triangle in that with a trilemma difficult choices must be made between the implementation of three different design options, where one is limited to picking two of the three options. The act of designing a system to implement all three goals is axiomatically impossible, as the combination of their existence counteracts one another. These options can all be unacceptable or unfavorable or they can all be favorable, depending on different contexts or towards different subsets of the affected demographic. Regardless, difficult choices need to be made. All systems have tradeoffs and using a triangle helps map these out.

The three sides of DAO Tension Triangle are based on Albert Hirschman’s book “Exit, Voice, and Loyalty.” For Hirschman, organizations take shape based on how stakeholders/ members/ citizens respond to perceived declines in the value of products, services, or political representation.
 
在DAO的例子中，三角对立关系可以被视为三个不同但同样重要的组成部分之间的平衡行为。这不是一个传统的三难问题（三元悖论），而是一个对立三角。当你滑来滑去的时候，各方之间都有需要改善的紧张关系。虽然有时很难，但如果动力合适，就可以达到最佳的组合。这个滑动的尺度并不是一个静态的时间点，所以向一边移动和远离另一边会给彼此带来不同程度的互动。这是一个平衡的过程，如果处理得当，将使DAO获得长期的成功。大多数DAO采用试错和逐步调整的方法，向着参与者认为最佳的方向发展。必须指出的是，这种紧张的三角关系在DAO的长期存在中可能无法维持。

三难问题与对立三角不同，在三难问题上，必须在实现三种不同的设计方案之间做出艰难的选择，其中一种方案仅限于从三种方案中选择两种方案。设计一个系统来实现这三个目标是不可能的，因为它们的存在相互抵消。这些选择可能都是不可接受的或不利的，也可能都是有利的，这取决于不同的环境或对受影响人口的不同子集。无论如何，都需要做出艰难的选择。所有系统都有折衷，使用三角关系有助于解决这些问题。

DAO的三角对立的三个方面是基于Albert Hirschman的《叛出、抗议和忠诚》一书。对于Hirschman来说，组织的形成是基于利益相关者/成员/公民对产品、服务或政治代表性价值下降的反应。

- Exit takes form whenever one either:
  - (1) leaves circumstances one finds disagreeable,
  - (2) withdraws one’s consumer faith in a line of commercial products,
  - (3) departs an organization for another better representing one’s interests,or
  - (4) in the extreme, forsakes the nationality to which one had pledged allegiance.

- Voice is the articulation of discontent with a product, service, or policy position under conditions. If an individual’s voice is not heard, exit becomes a viable option.

- Loyalty to a firm, mission, or policy platform inhibits leaving or complaining about a bad situation; it thereby effectively suppresses tendencies for both exit and voice.[17]

So as Charles Tilley observed: ‘Voice is more effective and likely when the exit is possible but not too easy. Some loyalty is necessary to voice opposition. If there’s no loyalty and exit is impossible, people will have no choice but to suffer in silence. If there is absolute loyalty, no one will voice opposition.’[18]

- 当出现下列情况之一时，叛出即形成：
  - (1)离开自己不喜欢的环境；
  - (2)撤销对商业产品的消费信心。
  - (3)离开一个组织，到另一个更能代表自己利益的组织去，或
  - (4)在极端情况下，放弃自己曾经效忠的国籍。

- 抗议是在一定条件下表达对产品、服务或政策立场的不满。如果一个人的抗议听不见，叛出就成了一个可行的选择。

- 对公司、任务或政策平台的忠诚抑制了离开或抱怨糟糕的情况；从而有效地抑制了叛出和抗议的倾向[17]。

因此，正如 Charles Tilley 所观察到的：“当叛出是可能的，但不太容易的时候，抗议更有效，也更有可能。有些忠诚是表达反对意见的必要条件。如果没有忠诚，叛出是不可能的，人们将别无选择，只能默默忍受。如果有绝对的忠诚，就不会有人发出反对的声音。”[18]


A DAO, like any organization, must balance the forces of voice, exit, and loyalty. The extent to which a DAO respects the sovereign nature of the individual is the extent to which it permits exit. The Individual is all about **autonomy in participation**. The Individual can choose when to join a DAO and when to leave a DAO as well as choose to participate and vote in all other decisions of the DAO (use their voice). It maps to free will. The Individual is Exit. Governance mechanisms are the DAO specific design space associated with Voice. Participating in governance and attempting to improve the DAO by being active is governance. This is the Individual using his voice for the greater good. To strengthen governance requires strengthening the voice and weakening incentives for the exit. Decentralization is like Hirschman's concept of loyalty. Decentralization not only describes the technology platform but the attributes and ethos of those who choose to participate in the DAO. It is loyalty which influences whether participants in a DAO will lean towards voice or exit, all else being equal. For DAOs, decentralization along with the people and their motives behind the DAO are the major factors influencing the credibility of the project.

一个DAO，与任何组织一样，必须平衡发言权、退出和忠诚的力量。一个DAO在多大程度上尊重个人的主权性质，就在多大程度上允许退出。个人就是要**在参与中实现自主性**。个人可以选择何时加入DAO，何时退出DAO，也可以选择参与DAO的所有其他决策并投票（使用他们的发言权）。它映射到自由意志。个人就是退出。治理机制是与发言权相关联的DAO特定设计空间。参与治理并试图通过活跃的方式改善DAO就是治理。这就是个体利用自己的发言权为更大的利益服务。要加强治理，就要强化话语权，弱化退出的激励机制。去中心化就像赫希曼的忠诚概念。去中心化不仅描述了技术平台，还描述了选择参与DAO的人的属性和精神。在其他条件相同的情况下，正是忠诚度影响着DAO的参与者是倾向于抗议还是叛出。对于DAO来说，权力下放和DAO背后的人及其动机是影响项目可信度的主要因素。


**"Decentralization is neither binary nor costless. It involves tradeoffs. It's about achieving enough decentralization to meet the demands of your use case at whatever scale you're aiming for." - Reserve Protocol**

**"权力下放既不是二元的，也不是无代价的。它涉及到权衡。它是关于实现足够的分散化，以满足你的用例的需求，无论您的目标规模是什么。”—Reserve Protocol**

Highly centralized organizations engender disloyalty and skepticism (e.g. XRP). Decentralized ones gain a passionate following that may lean towards voice rather than simply leaving, even though it is possible (e.g. MakerDAO). Voice and exit come at the expense of one another. If it is easier to exit, the mechanisms of voice lose some of their importance. If the mechanisms of voice become more binding, it is harder to exit. Loyalty and decentralization influence how these mechanisms are implemented. Decentralization makes mechanism design more difficult, whether it is a voice or exit mechanism, but engenders greater loyalty to the DAO as a whole.[19]

高度集中的组织会引起不忠诚和怀疑(如XRP)。分散的组织会获得热情的追随者，他们可能倾向于发出抗议，而不是简单地离开，尽管这是有可能的(如MakerDAO)。抗议和叛出是以牺牲对方为代价的。如果退出更容易，抗议机制就会失去一些重要性。如果话语权机制变得更有约束力，退出就更难。忠诚度和分权会影响这些机制的实施方式。不管是话语权机制还是退出机制，分权都会使机制设计更加困难，但会使人们对整个DAO产生更大的忠诚度[19]。

The components of the DAO Tension Triangle are:

- **Decentralization (Loyalty)**
  - In the context of a DAO decentralization is not just a technical aim but a political one. Decentralization becomes a belief system by which members maintain their loyalty to the DAO. Specifically, how many individuals or organizations ultimately participate in the DAO.
  - The degree of decentralization also differs for every DAO and is governed by their purpose, capabilities, and costs of participation.

- **Individual (Exit)**
  - A person who believes in rights and power for the individual. The individual is often someone who believes in self- governance and the greater good but wants individual rights to be upheld, and who is willing to do things for his/her self. The definition can also extend to include registered or unregistered corporations that operate under the jurisdiction of their lands and are legally treated and defined as individuals.
  
- **Governance (Voice)**
  - Governance rules relate to organization legal structure, operations, purpose, membership, onchain and off-chain voting, and all facets that enable its existence and dismantling.

DAO对立三角的组成部分是：

- **权力下放（忠诚）**

  - 在DAO的背景下，权力下放不仅仅是一个技术目标，而且是一个政治目标。分权成为一种信仰体系，成员通过这种信仰体系保持对DAO的忠诚。具体来说，有多少个人或组织最终参与到DAO中。

  - 每一个DAO的分权程度也不尽相同，受其目的、能力和参与成本的制约。

- **个人（叛出）**

  - 这里的个人，是相信个人权利和权力的人。个人往往是相信自我治理和更大利益，但希望维护个人权利，愿意为自己做事的人。这个定义还可以扩展到包括在其土地管辖范围内经营的注册或未注册的公司，并在法律上作为个人对待和界定。
  
- **治理（抗议/发言权）**。

  - 治理规则涉及组织的法律结构、运作、宗旨、成员、链上和链下投票，以及使其存在和解散的所有方面。
  

  
### DAO Tension Triangle 
### DAO的三角对立关系

![](./assets/DAO-tension-triangle.png)  

- DECENTRALIZATION: LOYALTY

  Loyalty to a firm, mission, or policy platform helps mitigate against leaving or complaining about a bad situation; it thereby effectively reduces the likelihood of tendencies for both exit and voice

- THE INDIVIDUAL: EXIT
  
  Exit takes form whenever one leaves circumstances that they find disagreeable; withdraws one’s consumer faith in a line of commercial products; departs an organization for another better representing one’s interests; or, in the extreme, forsakes the nationality to which one had pledged allegiance.

- GOVERNANCE: VOICE

  Voice is the articulation of discontent with a product, service, or policy position under conditions when exit is not considered a viable option.

To better understand the DAO Tension Triangle it’s important to understand both the individual definition of Loyalty (decentralization), Exit (the Individual) and (Voice) Governance as well as the relationship each of these have with each other.
  
- 权力下放：忠诚
  
  对公司、任务或政策平台的忠诚度有助于缓解离开或抱怨糟糕的情况；从而有效地降低了叛出和抗议两种倾向的可能性。
 
- 个人：叛出

  每当一个人离开自己不喜欢的环境，撤销对某一商业产品的消费信心，离开一个组织而选择另一个更能代表自己利益的组织，或者极端地放弃自己曾经效忠的国籍时，就会形成叛出。 
  
- 治理：抗议

  抗议是指在退出不被认为是一种可行的选择的情况下，表达对产品、服务或政策立场的不满。
  
为了更好地理解DAO的三角对立，既要理解忠诚（分权）、叛出（个人）和（抗议）治理的个人定义，也要理解它们各自之间的关系。 


-------------
[17]. Matthew T. Witt (2011) Exit, Voice, Loyalty Revisited, Public Integrity, 13:3, 239-252

[18]. Charles Tilly (1977) “From Mobilization To Revolution”

[19]. Inspirations from this came from conversations with Charlie Smith from Reserve.

-------------


## GOVERNANCE - DECENTRALIZATION
## 治理--权力下放

Decentralization is challenged and limited by centralized elements of governance (discussed below). Allowing for centralized pieces of governance to be modified over time leads to greater decentralization. There are many forms of governance that exist and there are varying degrees of decentralization amongst different projects.

Governance deals with many issues which relate to the community as opposed to the individual. It makes solving them challenging:

1. Arbitration & Conflict resolution
2. Taxation
3. Law of Land or Lands (multiple)
4. Off-chain compliance and transparency
5. Membership process
6. Profit vs Non-Profit
7. Dividend Distribution
8. Fund repatriation (Profit or Loss) of funds impact on tax – DAO or individual?
9. DAO Dissolution
10. DAO break-up value greater than DAO value (if ETH value goes up)
11. Contracting or hiring staff to do work – who and how is this done, recorded, records stored
12. Legally compliant – record keeping, lodging and storing

DAOs have varying degrees of governance “on-chain” and have governance rules for which members can vote and how.

Depending on the importance of the issues, the governance rules of the DAO may limit the ability to vote on the issue, such as funding grants (e.g. cannot vote for your own proposal or sponsored proposals) or the need to activate a pause / kill-switch in event of funding breach,[20] such as the recent BzX attack.[21] If controlled by a few people, this limits decentralization.

Governance activities that happen external to the protocol are called “off-chain” governance, They include: negotiating and entering third party contracts, hiring/firing, and voting (can be on-chain or offchain).

The complexities between stakeholders and their bargaining power makes designing blockchain governance mechanisms difficult and can challenge the decentralization objectives of the DAO.

权力下放受到中心化治理要素的挑战和限制（下文讨论）。允许随着时间的推移对中心化的治理部分进行修改，会导致更大的权力下放。现有的治理形式很多，不同项目的权力下放程度不同。

治理涉及许多与社区而非个人有关的问题。因此，解决这些问题具有挑战性：

1. 仲裁和解决冲突 
2. 税收
3. 土地法或复合土地法规
4. 链外合规性和透明度
5. 会员制度
6. 盈利与非盈利
7. 股息分配
8. 资金回流（盈亏）对税收的影响--DAO还是个人？
9. 解散DAO
10. DAO的分解价值（残值）得大于DAO的价值（如果ETH值上升）。
11. 承包或雇用工作人员工作 -- -- 由谁来做，如何做，如何记录，如何储存记录。
12. 合法合规性----记录保存、寄存和储存。

DAOs有不同程度的 "链上 "治理，并有关于成员可以投票和如何投票的治理规则。

根据问题的重要性，DAO的治理规则可能会限制对问题进行投票的能力，例如资金补助（例如不能对自己的提案或赞助的提案进行投票），或者在资金违规的情况下需要启动暂停/终止开关[20]，例如最近的BzX攻击[21]。如果由少数人控制，这就限制了去中心化。

发生在协议外部的治理活动称为“链外”治理，它们包括：协商和签订第三方合同、雇佣/解雇和投票（可以是链上或链下）。

利益相关者之间的复杂性及其讨价还价能力使得区块链治理机制的设计变得困难，并可能挑战DAO的去中心化目标。

---------------
[20]. This applies to a singularly controlled pause-switch, but not if it were a collective super-majority vote. Similarly the constraint to not vote on your own proposal doesn't necessarily mean it's less decentralised, but merely the rules of the DAO individuals vote into. This is similar to quadratic voting.

[21]. https://haseebq.com/flash-loans-why-flash-attacks-will-be-the-new-normal/

---------------

## DECENTRALIZATION - INDIVIDUAL
## 权力下放--个人

The larger a decentralized structure becomes the lower the participation rate tends to be. In larger DAOs, the individual may be more marginalized and choose not to participate or be passive, particularly if proxy voting or staking coins through an exchange or pool whereby an individual gives up voting power and the right to participate in governance. If the DAO has a controlling voting entity this has a similar effect, reducing the incentive to participate in DAO governance for individuals. The most recent example of this at the time of writing is the Steemit/Tron hardfork.[22]

The larger the DAO gets, the less influence the individual exercises as their perception of their voting power becomes diminished or inconsequential once the individual becomes a smaller part of a large group. This can be seen via Dunbar's Rule and the Ringelmann Effect, which states that members of a group become lazier, disenfranchised, and more detached as the size of their group increases. This stems from the assumption that “someone else is probably taking care of that.” In the real world, this occurs in every election cycle in countries where voting is optional, where everyone has the right to vote but only a small percent of people actually do vote.

The MetaCartel (MCV) Whitepaper highlights these tradeoffs:

“MCV’s goal is to facilitate a DAO with a focus on open participation where its members are enabled to have a radical level of flexibility in their continued involvement, all while having a right to participate in the management of the DAO (investment decisions, asset management, membership admissions). These goals are naturally in tension: If MCV becomes too open too quickly, the community runs a high risk of either lapsing into a traditional leader/follower org structure or fragmenting into dysfunctional cliques. If MCV is too rigid, it will miss critical opportunities to build the community. MCV will carefully consider all such social, legal, and technical factors to enable a continuous, dynamic readjustment of this delicate balance.[23]

分散式结构越大，参与率往往越低。在规模较大的DAO中，个人可能会被更多地边缘化，选择不参与或被动参与，特别是如果通过交易所或资金池进行代理投票或押币，个人放弃了投票权和参与治理的权利。如果DAO有一个控股的投票实体，这也会产生类似的效果，降低个人参与DAO治理的动力。在编写本报告时，最近的例子是 Steemit/Trond 的硬分叉。[22]

DAO越大，个人的影响力就越小，因为一旦个人成为一个大群体的小部分，他们对自己投票权的认识就会减弱或变得无足轻重。这一点可以通过邓巴规则和林格尔曼效应看出，随着群体规模的扩大，群体成员会变得更懒惰、失去权利、更加疏离。这源于 "可能有其他人在处理"的假设。在现实世界中，这种情况在每个选举周期都会发生，在那些投票是可选的国家，每个人都有投票权，但只有一小部分人真正投票。

MetaCartel（MCV）白皮书强调了这些权衡：

“MCV的目标是促进DAO的开放式参与，使其成员能够在继续参与的过程中拥有激进的灵活性，同时有权参与DAO的管理（投资决策、资产管理、成员准入）。这些目标自然而然地处于紧张状态：如果MCV过于开放，社区面临着很高的风险，要么陷入传统领导/追随者组织结构，要么分裂成功能失调的集团。如果MCV过于僵化，它将错过建设社区的关键机会。MCV将仔细考虑所有这些社会、法律和技术因素，以便持续、动态地调整这种微妙的平衡。[23]

-------------
[22]. https://cointelegraph.com/news/steem-community-resists-takeover-hard-fork-launches-hive-network

[23]. From the Metacartel Whitepaper: https://github.com/metacartel/MCV/blob/master/Whitepaper.pdf

--------------

## INDIVIDUAL - GOVERNANCE
## 个人--治理

Decentralization is a sliding scale of how open the DAO is. Fully decentralized would mean anyone can participate and vote/make decisions and become involved in the DAO, but in practice, it doesn't work like this. There would be a tremendous scalability problem for most DAOs as they get bigger or need everyone to vote on and approve every decision. This would make decentralized governance impractical. If you require too little attention from members the decision making could not be in the best interest of most DAO members and lead to collusion and misrepresentation of the majority. If members feel they aren’t being represented or their voice isn’t being heard they will “ragequit” and take their assets out of the DAO.

Instead, there are many centralizing elements particularly around who can join, how they can join and/or an economic contribution via a staking requirement. This is done through a group of insiders vetting who can join based on reputation, sought-after domain expertise or bank account (whales are always welcome).

For example, the LAO is a member-directed venture capital fund and a registered LLC in the US. They have limited membership to only 100 members in compliance with US Securities law with a 120ETH minimum staking contribution.

去中心化是DAO开放程度的一个滑动尺度。完全去中心化意味着任何人都可以参与和投票/决策，并参与到DAO中，但在实践中，它并不是这样工作的。对于大多数dao来说，当它们变得更大或者需要每个人投票和批准每个决策时，会有一个巨大的可扩展性问题。这将使分散式治理不切实际。如果你对成员的关注度要求太低，那么决策就不可能符合大多数DAO成员的最大利益，并导致大多数人的串通和歪曲。如果成员觉得他们没有被代表，或者他们的声音没有被听到，他们就会 "愤怒地退出"，并把他们的资产从DAO中拿出来。

相反，有许多中心化的因素，特别是围绕谁可以加入，他们如何加入和/或通过一个质押要求作出经济贡献。这是通过一个内部审查小组来完成的，他们可以根据声誉、受追捧领域的专长或银行账户（鲸鱼总是受欢迎的）。

例如，LAO是一个由会员指导的风险投资基金，是在美国注册的有限责任公司。根据美国证券法，他们的成员人数限定为100人，最低出资额为120ETH。

![](./assets/Elements-of-DAO-Tension-Triangle.jpg)


## GOVERNANCE
## 治理

Governance is the central piece of a DAO. Since DAOs operate on smart contracts or executable programs/protocols mainly created on Ethereum, DAOs do not have a centralized and conventional management structure. The code for DAOs is often open-source. The governance of this structure gives privileges and the right to vote to participants in the DAO who are geographically distributed but want to participate in the governance process and help the DAO better achieve its goals. All members, unless deferred to a central authority, have a say in the DAO’s direction. The purpose of DAO(s) is to code governance and enable participation while minimizing the operations requirements of a corporation to function effectively.

治理是DAO的核心部分。由于DAO主要是在Ethereum上创建的智能合约或可执行程序/协议上运行，因此DAO没有一个中心化的传统管理结构。DAO的代码通常是开源的。这种结构的管理赋予DAO的参与者特权和投票权，这些参与者虽然分布在不同的地理位置，但都希望参与管理过程，帮助DAO更好地实现目标。除非交由中央机关管理，否则所有成员对DAO的发展方向都有发言权。DAO(s)的目的是规范治理和促进参与，同时最大限度地减少公司有效运作的业务要求。

### Why Corporations Need Governance
### 为什么企业需要治理

Corporations are not private enterprises. Private enterprises are businesses where the owner, usually a sole owner, family, partnership or private company, are also the managers and in direct control of the business. Corporations are usually public, private-public partnerships, or public-private entities, that are composed of many shareholders and the corporation relies on managers to operate profitably, distribute dividends, and grow the corporation value. Corporations and private enterprises are structurally, operationally, and legally different. This is an important definition to make as governance is primarily focused on corporations, not private enterprise.

When referring to governance this refers to modern corporate governance, which is based on the foundation of the separation of ownership and control, together with dispersed shareholding. This separation resulted in the need to put protections in place so that those controlling the corporation did not steal from those owning the corporation, especially as almost none of the shareholders individually have any insight or influence into the business operations.

In 'The Modern Corporation and Private Property', by Adolf Berle and Gardiner Means, they argue that it was the structure of corporate law in the 1930s that enforced the separation of ownership and control. They also explore the divergence of interest between ownership and control.

>“The economic power in the hands of the few persons who control a giant corporation is a tremendous force which can harm or benefit a multitude of individuals, affect whole districts, shift the currents of trade, bring ruin to one community and prosperity to another. The organizations which they control have passed far beyond the realm of private enterprise - they have become more nearly social institutions.”

公司不是私营企业。私营企业是指企业主(通常是独资企业主、家庭、合伙企业或私营公司)同时也是管理者并直接控制企业的企业。公司通常是公共的、公私合营的或公私合营的实体，由许多股东组成，公司依靠经理人经营盈利、分配红利、增长公司价值。公司和私营企业在结构上、经营上、法律上都是不同的。这是一个重要的定义，因为治理的重点主要是公司而不是私营企业。

当提到治理时，这指的是现代公司治理，其基础是所有权和控制权的分离，以及分散的持股。这种分离的结果是，需要制定保护措施，使控制公司的人不会偷窃拥有公司的人的东西，特别是几乎没有一个股东单独对企业经营有任何了解或影响。

在Adolf Berle和Gardiner Means的《现代公司与私有财产》一书中，他们认为是20世纪30年代的公司法结构强制了所有权和控制权的分离。他们还探讨了所有权和控制权之间的利益分歧。

>"控制巨无霸公司的少数人手中掌握的经济力量是一种巨大的力量，它可以伤害或造福许多人，影响整个地区，改变贸易潮流，给一个社区带来毁灭，给另一个社区带来繁荣。他们所控制的组织已经远远超出了私营企业的范畴，它们已成为更接近社会的机构。”


It is important that DAOs are structured to ensure that management is correctly incentivized to operate for the long term good of the DAO and all their stakeholders. Otherwise, they risk enabling the Principal Agent problem that has grown in many corporations.

The Principal Agent problem occurs, and recurs, when one person or central entity (the "agent"), is able to make decisions and/or take actions on behalf of, or that impact, another person or entity: the "principal".[1] This dilemma exists in circumstances where agents are motivated to act in their own best interests, which are contrary to those of their principals, and is an example of moral hazard. One example of this behaviour has been the recent and widespread share buybacks of public companies so that agents can benefit disproportionately through bonuses and incentives, at the cost of the long term health of the corporation, such as having cash-on-hand to manage economic downturns.

For DAO governance, even if record keeping is the only function utilizing blockchain tech via a digital registry, this is still a great transparency improvement over existing infrastructure. Individual voting decisions about corporate affairs can be more efficiently implemented if proxy advisory services can advise individual investors directly, and advisory services can provide oracle services to the smart contracts (smart votes) in order to automate individual voting.

The governance rules that have been developed for DAOs so far are generally rather simple and lack innovation. This is not just a DAO problem but a problem in global democracies. Using blockchain technology, new approaches to the problems surrounding democratic governance can be designed to improve:

- Types of voting (eg majority voting, consensus voting, simultaneous voting, multi-stage voting, futarchy.[24])

- When to vote, and when to use sortition (random choice)
- Leaders (term limits?)/ Leaderless / Delegation
- Participation incentives to draw voter turnout
- Education and Information around what needs to be voted on and how to vote
- Identity and weight of voting

DAOs, as they exist now, will not be able to change how dispute resolution occurs, however, they will reduce a lot of the possible circumstances in which it will be required.


重要的是，DAO的结构应确保管理层得到正确激励，以便为DAO及其所有利益相关者的长期利益而运作。否则，它们就有可能引发委托代理问题，而委托代理问题已在许多公司中蔓延开来。

当一个人或中央实体("代理人")能够代表另一个人或实体(即 "委托人")作出决定和/或采取行动，或影响到另一个人或实体时，就会出现并反复出现委托人代理问题[1]。这种两难的情况存在于代理人为了自己的最大利益而行事的情况，而这种利益与其委托人的利益相悖，是道德风险的一个例子。这种行为的一个例子是，最近上市公司普遍回购股票，使代理人可以通过奖金和奖励获得不成比例的利益，而代价是公司的长期健康发展，例如拥有手头的现金来管理经济衰退。

对于DAO治理，即使记录保存是通过数字注册使用区块链技术的唯一功能，这仍然是对现有基础设施的一个巨大的透明度改进。如果代理咨询服务可以直接为个人投资者提供建议，咨询服务可以为智能合约（智能投票）提供谕旨（智囊）服务，以实现个人投票的自动化，那么有关公司事务的个人投票决策就可以更有效地实施。

到目前为止，已经制定的DAO的治理规则普遍比较简单，缺乏创新。这不仅是DAO的问题，也是全球民主制度的问题。利用区块链技术，可以设计新的方法来改善民主治理的问题。

- 投票的类型（如多数投票、共识投票、同步投票、多阶段投票、futarchy. [24]）
- 何时投票，何时使用排序（随机选择）？
- 领导人(任期限制?)/无领导人/授权制。
- 参与激励措施吸引选民投票
- 围绕需要投票的内容和如何投票进行教育和宣传。
- 投票的身份和权重

目前存在的DAO将无法改变解决争端的方式，但是，它们将减少许多可能需要解决争端的情况。

------------------------
[^footnote24]: A form of government proposed by economist Robin Hanson, in which elected officials define measures of national wellbeing, and prediction markets are used to determine which policies will have the most positive effect.

[^footnote25]: Sortition is a way to obtain both scalability and resistance to "demagogues"

------------------------