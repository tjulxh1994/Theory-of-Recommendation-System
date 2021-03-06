# Theory of Recommendation System
*A great tutorial that gives you a sufficient understanding of the recommendation system.*

*From Xing Wudao.*

时至今日，推荐系统已然成了一门显学，个性化推荐成了互联网产品的标配。好学的你肯定在收藏着朋友圈里流传的相关文章，转发着微博上的相关讨论话题，甚至还会不断奔走在各种大小行业会议之间，听着大厂职工们讲那些干货。这样碎片化的吸收，增加了知识的同时，也增加了焦虑。因为技术的不平等广泛存在于业界内，推荐系统也不例外。

推荐系统从搜索引擎借鉴了不少技术和思想，比如内容推荐有不少技术就来自搜索引擎， 由 Amazon 发扬光大的，基于用户（ User-based ）和基于物品（ Item-based ）的协同过滤将推荐系统技术从内容延伸到协同关系，超越了内容本身。

后来 Netflix 搞了一个瓜分百万美元的土豪比赛，以矩阵分解为代表的评分预测算法如雨后春笋般出现。至此，机器学习和推荐系统走得越来越近，最近十年，深度学习和强化学习又将推荐系统带向了新的高度。

推荐系统也是现在热门的 AI 分支之一，但凡 AI 类的落地，都需要具备这几个基本元素才行：数据、算法、场景、计算力。推荐系统也不例外，而刚好，现在的时代，这些元素的获得成本相比十年前已经小了很多。未来随着各种硬件设备越来越智能，万物互联得越来越紧密，人们的个性化需求、场景的多样性、数据的复杂性都对推荐系统提出了更高的要求。

有一个趋势我是确信无疑的：世界在向网状发展，万事万物倾向于相互连接构成复杂网络。复杂网络具有无尺度特点，表现是：少数节点集聚了大量连接。这个现象不陌生，叫做马太效应，社交网络粉丝数、网页链接引用量、电商网站商品销量等等，无不如此。推荐系统的使命，就是要用技术来对抗这种不平等。

在复杂网络中，雄踞顶端的节点无法体会长尾的疾苦。推荐系统的技术应用现状也如此，大厂们一骑绝尘，感觉分分钟就要达到奇点的节奏，然而更普遍的是：太多中小厂、工程师们还不知道一个推荐系统如何才能从 0 到 1 诞生，这需要去了解哪些知识？

这样的知识鸿沟，需要有人去填平，需要让成熟的技术走进每一个可以采用的产品中和愿意学习的人大脑中，让整个社会一起提高效率，享受时代赐予的技术红利。

**``面临现状，你其实需要这样的知识``：**

* 能解决系统起步阶段 80% 的问题；

* 已被无数产品验证过有用的东西；

* 遇到问题能够找到人或者社区交流，而非曲高和寡的前沿技术；

* 知识之间有层次递进关系，也有分门别类的整理。

**``本系列共包含 36 篇文章，分成五个模块详细介绍推荐系统的相关知识。``**

* **概念篇**：介绍一些推荐系统有关的理念、思考、形而上的内容，虽然务虚但是必要。
> * [【概念篇】你真的需要个性化推荐系统吗](https://github.com/Alluka-L/Theory-of-Recommendation-System/blob/master/%E6%A6%82%E5%BF%B5%E7%AF%87/1.%E4%BD%A0%E7%9C%9F%E7%9A%84%E9%9C%80%E8%A6%81%E4%B8%AA%E6%80%A7%E5%8C%96%E6%8E%A8%E8%8D%90%E7%B3%BB%E7%BB%9F%E5%90%97%EF%BC%9F.md)
> * [【概念篇】个性化推荐系统那些绕不开的问题](https://github.com/Alluka-L/Theory-of-Recommendation-System/blob/master/%E6%A6%82%E5%BF%B5%E7%AF%87/2.%E4%B8%AA%E6%80%A7%E5%8C%96%E6%8E%A8%E8%8D%90%E7%B3%BB%E7%BB%9F%E9%82%A3%E4%BA%9B%E7%BB%95%E4%B8%8D%E5%BC%80%E7%9A%84%E9%97%AE%E9%A2%98.md)
> * [【概念篇】这些你必须具备的思维模式](https://github.com/Alluka-L/Theory-of-Recommendation-System/blob/master/%E6%A6%82%E5%BF%B5%E7%AF%87/3.%E8%BF%99%E4%BA%9B%E4%BD%A0%E5%BF%85%E9%A1%BB%E5%85%B7%E5%A4%87%E7%9A%84%E6%80%9D%E7%BB%B4%E6%A8%A1%E5%BC%8F.md)
* **原理篇**：推荐算法的原理介绍，是俗称的干货。知道推荐系统背后技术的基本原理后，你可以更快地开发自己的系统，更好地优化自己的系统，并且更容易去学习专栏中未涉及的内容。
> * [【内容推荐】画鬼容易画人难：用户画像的“能”和“不能”](https://github.com/Alluka-L/Theory-of-Recommendation-System/blob/master/%E5%8E%9F%E7%90%86%E7%AF%87/01.%E3%80%90%E5%86%85%E5%AE%B9%E6%8E%A8%E8%8D%90%E3%80%91%E7%94%BB%E9%AC%BC%E5%AE%B9%E6%98%93%E7%94%BB%E4%BA%BA%E9%9A%BE%EF%BC%9A%E7%94%A8%E6%88%B7%E7%94%BB%E5%83%8F%E7%9A%84%E2%80%9C%E8%83%BD%E2%80%9D%E5%92%8C%E2%80%9C%E4%B8%8D%E8%83%BD%E2%80%9D.md)
> * [【内容推荐】从文本到用户画像有多远](https://github.com/Alluka-L/Theory-of-Recommendation-System/blob/master/%E5%8E%9F%E7%90%86%E7%AF%87/02.%E3%80%90%E5%86%85%E5%AE%B9%E6%8E%A8%E8%8D%90%E3%80%91%E4%BB%8E%E6%96%87%E6%9C%AC%E5%88%B0%E7%94%A8%E6%88%B7%E7%94%BB%E5%83%8F%E6%9C%89%E5%A4%9A%E8%BF%9C.md)
> * [【内容推荐】超越标签的内容推荐系统](https://github.com/Alluka-L/Theory-of-Recommendation-System/blob/master/%E5%8E%9F%E7%90%86%E7%AF%87/03.%E3%80%90%E5%86%85%E5%AE%B9%E6%8E%A8%E8%8D%90%E3%80%91%E8%B6%85%E8%B6%8A%E6%A0%87%E7%AD%BE%E7%9A%84%E5%86%85%E5%AE%B9%E6%8E%A8%E8%8D%90%E7%B3%BB%E7%BB%9F.md)
> * [【近邻推荐】人以群分，你是什么人就看到什么世界](https://github.com/Alluka-L/Theory-of-Recommendation-System/blob/master/%E5%8E%9F%E7%90%86%E7%AF%87/04.%E3%80%90%E8%BF%91%E9%82%BB%E6%8E%A8%E8%8D%90%E3%80%91%E4%BA%BA%E4%BB%A5%E7%BE%A4%E5%88%86%EF%BC%8C%E4%BD%A0%E6%98%AF%E4%BB%80%E4%B9%88%E4%BA%BA%E5%B0%B1%E7%9C%8B%E5%88%B0%E4%BB%80%E4%B9%88%E4%B8%96%E7%95%8C.md)
> * [【近邻推荐】解密“看了又看”和”买了又买“](https://github.com/Alluka-L/Theory-of-Recommendation-System/blob/master/%E5%8E%9F%E7%90%86%E7%AF%87/05.%E3%80%90%E8%BF%91%E9%82%BB%E6%8E%A8%E8%8D%90%E3%80%91%E8%A7%A3%E5%AF%86%E2%80%9C%E7%9C%8B%E4%BA%86%E5%8F%88%E7%9C%8B%E2%80%9D%E5%92%8C%E2%80%9C%E4%B9%B0%E4%BA%86%E5%8F%88%E4%B9%B0%E2%80%9D.md)
> * [【近邻推荐】协同过滤中的相似度计算方法有哪些](https://github.com/Alluka-L/Theory-of-Recommendation-System/blob/master/%E5%8E%9F%E7%90%86%E7%AF%87/06.%E3%80%90%E8%BF%91%E9%82%BB%E6%8E%A8%E8%8D%90%E3%80%91%E5%8D%8F%E5%90%8C%E8%BF%87%E6%BB%A4%E4%B8%AD%E7%9A%84%E7%9B%B8%E4%BC%BC%E5%BA%A6%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B.md)
> * [【矩阵分解】那些在Netflix Prize中大放异彩的推荐算法](https://github.com/Alluka-L/Theory-of-Recommendation-System/blob/master/%E5%8E%9F%E7%90%86%E7%AF%87/07.%E3%80%90%E7%9F%A9%E9%98%B5%E5%88%86%E8%A7%A3%E3%80%91%E9%82%A3%E4%BA%9B%E5%9C%A8Netflix%20Prize%E4%B8%AD%E5%A4%A7%E6%94%BE%E5%BC%82%E5%BD%A9%E7%9A%84%E6%8E%A8%E8%8D%90%E7%AE%97%E6%B3%95.md)
> * [【矩阵分解】Facebook是怎么为十亿人互相推荐好友的](https://github.com/Alluka-L/Theory-of-Recommendation-System/blob/master/%E5%8E%9F%E7%90%86%E7%AF%87/08.%E3%80%90%E7%9F%A9%E9%98%B5%E5%88%86%E8%A7%A3%E3%80%91Facebook%E6%98%AF%E6%80%8E%E4%B9%88%E4%B8%BA%E5%8D%81%E4%BA%BF%E4%BA%BA%E4%BA%92%E7%9B%B8%E6%8E%A8%E8%8D%90%E5%A5%BD%E5%8F%8B%E7%9A%84.md)
> * [【矩阵分解】如何关注排序效果，那么这个模型可以帮到你](https://github.com/Alluka-L/Theory-of-Recommendation-System/blob/master/%E5%8E%9F%E7%90%86%E7%AF%87/09.%E3%80%90%E7%9F%A9%E9%98%B5%E5%88%86%E8%A7%A3%E3%80%91%E5%A6%82%E6%9E%9C%E5%85%B3%E6%B3%A8%E6%8E%92%E5%BA%8F%E6%95%88%E6%9E%9C%EF%BC%8C%E9%82%A3%E4%B9%88%E8%BF%99%E4%B8%AA%E6%A8%A1%E5%9E%8B%E5%8F%AF%E4%BB%A5%E5%B8%AE%E5%88%B0%E4%BD%A0.md)
> * [【MAB问题】简单却有效的Bandit算法](https://github.com/Alluka-L/Theory-of-Recommendation-System/blob/master/%E5%8E%9F%E7%90%86%E7%AF%87/13.%E3%80%90MAB%E9%97%AE%E9%A2%98%E3%80%91%E7%AE%80%E5%8D%95%E5%8D%B4%E6%9C%89%E6%95%88%E7%9A%84Bandit%E7%AE%97%E6%B3%95.md)
> * [【MAB问题】结合上下文信息的Bandit算法](https://github.com/Alluka-L/Theory-of-Recommendation-System/blob/master/%E5%8E%9F%E7%90%86%E7%AF%87/14.%E3%80%90MAB%E9%97%AE%E9%A2%98%E3%80%91%E7%BB%93%E5%90%88%E4%B8%8A%E4%B8%8B%E6%96%87%E4%BF%A1%E6%81%AF%E7%9A%84Bandit%E7%AE%97%E6%B3%95.md)
> * [【MAB问题】如何将Bandit算法与协同过滤结合使用](https://github.com/Alluka-L/Theory-of-Recommendation-System/blob/master/%E5%8E%9F%E7%90%86%E7%AF%87/15.%E3%80%90MAB%E9%97%AE%E9%A2%98%E3%80%91%E5%A6%82%E4%BD%95%E5%B0%86Bandit%E7%AE%97%E6%B3%95%E4%B8%8E%E5%8D%8F%E5%90%8C%E8%BF%87%E6%BB%A4%E7%BB%93%E5%90%88%E4%BD%BF%E7%94%A8.md)
* **工程篇**：推荐算法的实践内容。系统落地时需要一些纯工程上的大小事情，架构、选型、案例等。
* **产品篇**：推荐系统要成功，还要考虑产品理念及其商业价值，因此这部分介绍一些产品知识和一点浅显的商业思考。
* **团队篇**：从个人来说，就是该怎么学习和成长；从团队来说，就是该招多少人，该有哪些人，以及产品经理和工程师该如何合作等问题。