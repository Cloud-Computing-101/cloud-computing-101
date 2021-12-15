# Cloud Computing 101 创作背景

随着云计算技术与服务逐渐变成我们生活中的“水”和“电”，并且开源催生了非常多的基础设施软件，让任何人都可以快速在自己的本地环境尝试，这让云计算技术的普及变得更加“平民化”，为不计其数企业与个人带来了便利。

然而，云计算领域的技术概念与软件生态非常庞杂，云计算产品与服务也层出不穷，对于非技术与科班出身的人士理解起来并非易事。即使是全球最为流行的容器技术 Kubernetes 与 Docker，在大多数专业技术从业人士来看，[复杂度也依然是最大的挑战](https://www.cncf.io/wp-content/uploads/2020/11/CNCF_Survey_Report_2020.pdf)。

最近我身边也有越来越多的新同事初入云计算行业，面对专业和复杂的云计算与云原生相关产品与技术，在自学过程中也会有些许地感到无从入手，网上找到的文档与视频学习资料大多是面向工程师人群，而对于从事云计算行业的运营、市场、文档、销售、渠道等角色，或是萌新实习生来说，这些资料很难系统地帮助到非技术人士入门和了解云计算产品与技术，大部分官方文档对于非技术背景出身的人群通常较为晦涩难懂。

## 什么是 Cloud Computing 101

Cloud Computing 101 旨在面向上述背景中提到的**非技术背景的云计算从业者，以及对云计算与云原生产品与技术感兴趣的同学**。作者希望以**在线视频会议、原创图文以及动手实验**的方式，尽可能地将晦涩的产品技术以更加通俗的语言传达给受众，并搜集与汇总内外网相关的优质学习资源，给目标受众提供自学方向的引导。

此次系列教程受 [self-taught-guide-to-cloud-computing](https://github.com/madebygps/self-taught-guide-to-cloud-computing) 的启发，教程内容将围绕以下的几个目标进行协作输出：

### Goal

- 整理与总结云计算领域的知识图谱，重点聚焦到云原生领域的开源项目与技术
- 帮助目标受众了解云计算与云原生领域常见的概念、术语，了解最基本的使用场景
- Talk is cheap，本教程将通过互动实验的形式帮助初学者快速上手与实践
- 通过类似 [100 Days of Kubernetes](https://100daysofkubernetes.io/overview.html) 的形式打卡完成学习路线
- 希望通过开源与开放协作的方式输出教程内容（欢迎讲师自愿加入）

### Non-goal

- 本系列教程的目标并非将目标受众培养为专业的工程师
- 本系列教程不提供一对一的技术支持（遇到实际问题可以在此仓库的 GitHub issue 提出）

## 开始前

对于非计算机专业出身的同学来说，你可以根据个人时间与兴趣先对大学计算机基础补补课，提前了解一下大学计算机相关专业必修的四门课程涉及的内容，实际上还有《数据结构与算法》这门课程。如果你的发展方向不是专业的工程师，那么这些大学计算机基础课程非 100% 必须项，你可以把它们当做“字典”，在遇到相关概念或问题时，自行查阅相关教材与书籍📚，或在[中国大学慕课网](https://www.icourse163.org/)观看各大名校计算机专业教授的课程。

> 注：此图出自[大学计算机知识要点总结_思维导图](https://www.processon.com/view/61162a510e3e7407d39eeee5?fromnew=1)。

![大学计算机知识要点总结](/images/computer-science-fundamentals.jpg)

## 知识图谱

我们将对以下知识图谱中涉及到的云计算与云原生相关技术产品和开源项目的基本概念、应用场景、使用示例进行讲解，此知识图谱主要根据[青云公有云](qingcloud.com)和 [KubeSphere](kubesphere.io) 涉及的产品与生态软件进行归类，目前还是一份初稿，后续将会横向与纵向地延展，欢迎大家对内容提供建议与反馈。后期的使用教程也会主要使用[青云公有云](qingcloud.com)与 [Katacoda](katacoda.com) 这两个平台作为示例来演示。

![云计算与云原生](/images/cloud-computing-mind-map.jpg)

## 如何参与

目前暂定每周一次或两次，将于周三和周五下午 6:00 ~ 6:30 使用腾讯会议的方式进行，双周则每周两次，单周仅周三一次。例如 11 月 22 日是 [2021 年的第 48 周](http://www.rili163.com/dijizhou.html)即双周，因此会有周三和周五两次会议。若遇到临时的会议冲突，可能会调整时间。

### 每周三的会议信息

- 腾讯会议地址：https://meeting.tencent.com/dm/NRiK4Of6m6nj
- 会议号：783 3647 5206

### 每双周周五的会议信息

- 腾讯会议地址：https://meeting.tencent.com/dm/K1UmYqwxXODx
- 会议号：：750 4735 1399

## 历史回放

### 第一期：云计算基础 - 什么是 IaaS、PaaS 和 SaaS

分享时间：2021 年 11 月 24 日 

- [视频回放](https://yunify.anybox.qingcloud.com/s/0AkMO2LvjreQJV1KsQUSnNTaHMXmiIcZ)
- [PPT](https://docs.google.com/presentation/d/1dIKQQPvRuTxwcgfLKtU1rtnckkddrJhPZj4Hf7PNkBE/edit?usp=sharing)

### 第二期：云计算基础 - Docker 与 Kubernetes 容器云

分享时间：2021 年 12 月 1 日

- [视频回放（此次会议忘录屏了）](https://yunify.anybox.qingcloud.com/s/PhhMhS81MKw3IJOKeaufswL23QzfGshF)
- [PPT](https://yunify.anybox.qingcloud.com/s/PhhMhS81MKw3IJOKeaufswL23QzfGshF)

### 第三期：计算 - 了解虚拟化技术

分享时间：2021 年 12 月 3 日

- [视频回放](https://yunify.anybox.qingcloud.com/s/A3IWwiz5RJrhixpodmT44Lbp7WB0uAIp)

### 第四期：计算 - CPU、GPU、云服务器

分享时间：2021 年 12 月 8 日

- [视频回放](https://yunify.anybox.qingcloud.com/s/A3IWwiz5RJrhixpodmT44Lbp7WB0uAIp)
- [PPT](https://docs.google.com/presentation/d/1dIKQQPvRuTxwcgfLKtU1rtnckkddrJhPZj4Hf7PNkBE/edit?usp=sharing)

### 第五期：存储 - 文件存储、对象存储、块存储、集中存储与分布式存储

分享时间：2021 年 12 月 15 日

- [视频回放](https://yunify.anybox.qingcloud.com/s/WyTTKWJvIk4iopFx9wtQkYMTIOZU1LCY)
- [PPT](https://yunify.anybox.qingcloud.com/s/K4i7oJhl3htj78AECAYhBLkdOcgaJKDA)

## 贡献者讲师（欢迎加入）

- [Feynman Zhou](https://github.com/FeynmanZhou/)
- 相东
- 朱波

