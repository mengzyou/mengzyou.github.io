---
title: "一体化CI/CD平台"
date: 2021-01-25T14:22:16+08:00
categories: ["DEVOPS"]
hero: single-application-cicd.png
tags: ["gitlab", "cicd"]
menu:
  sidebar:
    name: "一体化CI/CD平台"
    identifier: single-application-cicd
    parent: devops
    weight: 10
---

## 前言

匆匆忙忙结束了2020年，想着还是要在2021年的第一个月要写一篇文章。在看了[Gitlab]推送的文章之后，自己也比较认同在DevOps实践中如果使用一个一体化的CI/CD平台或者工具所能带来的好处。  

不过每个组织或者团队有自身的一些考量和实际情况，就比如的当前我在工作中也使用了多个工具来实现整个CI/CD流程，似乎是分离了CI和CD的过程，因为公司更加考量了做交付的稳定性和安全性考量，并没有做到完全的持续发布。  

所以这篇文章仅仅是探讨一些一体化CI/CD平台可以带来的优势。

## CI/CD

持续继承和交付（CI/CD）改变了我们构建，测试和部署软件应用的方式。CI/CD工具自动化这些流程，减少错误率，并且优化了整个工作流。代码在整个开发阶段中进行自动化测试，已确保在错误到达生产之前就将其捕获并修复。  

CI/CD工具的使用将持续增加并改善软件开发的方式，应的部署也不再需要是每年一次，每个季度一次，甚至每个月一次。通过CI/CD，开发运维团队可以一天内部署多次。  


![devops-cycle](https://images.mengz.dev/posts/devops01.png)  

## 10个CI/CD的优点

上面说了什么是CI/CD，那接下来我们看看其有哪些优点。  

**1. 更少的交接**  
在开发管道中更多的交接，那将带来更多的故障点和更多的复杂性。  

**2. 增加开发速度**  
通过CI/CD，开发的所有阶段都更快，整个过程中更快的迭代速度使每个团队的工作效率更高，开发人员也可以更有信心地转移到其他项目。  

**3. 更多的部署**  
每两周或更长时间发生一次的发布，现在可以每天推送多次。  

**4. 更快的测试**  
开发工作流程中一个比较耗时的部分被移除，开发人员可以从事其他高价值的项目。自动化测试让团队可以更快速地获得反馈，并尽早失败，而不是在生产中产生这些错误，或者更糟糕地将错误带到最终的发布版本中。  

**5. 更少的代码缺陷**  
通过开发流程中引入自动化测试，在代码缺陷发生时就能及时捕获，并避免代码合并入主分支。这样可以确保整体上的具有更高的代码质量，并且每个发布版本都能按预期工作。  

**6. 增强合规性**  
合规性任务可以纳入开发生命周期，减少发布不合规应用的风险。自动化合规检查使得更容易完成审核，并可以防止高代价的错误。  

**7. 更多的创新时间**  
花费在集成维护的时间越少，IT支出不变，也就意味着可以更多的时间投入到其他地方。  

**8. 更开心的开发者**
开发人员能够更有自信地工作和快速地修复缺陷，而不是等上几个星期来了解错误发生在哪里。  

**9. 减少管理费用**  
组织中开发人员的时间是有限的，开发时间是可计费时间的很多倍，而手动测试和部署代码可能会破坏整个IT预算。自动化的工作流程减少了手动任务，可以使预算更加有效。  

**. 流程一致性**  
开发流程中具有更高的自动化程度意味着没人会忘记该过程中执行的步骤，也使得构建更加一致。这样更容易培训新的开发人员，组织也可以更加容易控制如何构建，以及何时进行发布。  

## 一体式CI/CD优势

上面概述了CI/CD可以带来的好处，然而在实际的实践中，如何真正地衡量生产力速度，需要评估整个软件开发生命周期（SDLC），而不仅仅是点点滴滴。  

无缝地持续集成和交付应具有使应用程序为部署做好准备所需的一切，不幸的是，很多使用CI/CD的组织由于使用的工具而陷入了无法达到最佳工作流程的困境。  

一个可以在整个软件开发生命周期提供可见性的应用程序是确保和优化每个开发阶段的最佳方法，当一切都在一个屋檐下时，就容易发现流程的瓶颈，以及评估影响开发速度的每一个元素。  

在单个DevOps平台下的每个步骤都提供了一条信息，可就是否准备好合并代码做出明智的决定。当然，所有这些步骤可以在没有一体式CI/CD的解决方案的情况下执行，但是功能全面的工具可以创建单一的事实来源，在此情况下，可以更快地监视每个步骤，并减少遗漏错误的可能性。  

一体式CI/CD平台带来以下好处：  

- 整个软件开发生命周期的可见性  
- 所有开发阶段的单一真实来源  
- 无需登陆多个应用程序  
- 在一个界面上导航更简单  
- 只需要安装，维护，扩展，备份一个应用程序  
- 更容易的授权管理  
- 降低运营费用  

![devops-cicd-process](https://images.mengz.dev/posts/devops-cicd-process.png)

因此，推荐在组织或团队中构建单一的CI/CD平台来加速应用创新，例如选择使用 [Gitlab](https://about.gitlab.com)，[Github](https://github.com)，以及各大公有云提供商发行的DevOps平台及工具来优化整个CI/CD流水线。  