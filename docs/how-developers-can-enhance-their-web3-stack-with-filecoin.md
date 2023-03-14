# 开发者如何用 Filecoin 增强他们的 Web3 堆栈

> 原文：<https://web.archive.org/web/https://dappradar.com/blog/how-developers-can-enhance-their-web3-stack-with-filecoin>

## 建立更好的互联网体验，为用户提供 dapp 主权和安全。

越来越多的开发者希望为 Web3 的建设做出贡献。然而，由于 web3 生态系统的庞大，开发者很难迅速上手。如果你也有类似的困惑，不用担心。本文简要概述了 Web3 领域最流行的技术栈和开发环境。

随着去年元宇宙的流行，Web3 已经成为最近最热门的领域之一。根据 DappRadar 的最新元宇宙报告，2021 年，参与元宇宙的区块链公司筹集了 40 亿美元。投资者和公司的持续兴趣也导致更多的开发者加入了 web3 领域的创业公司。

[Read the full Metaverse report](https://web.archive.org/web/20230116191857/https://dappradar.com/blog/metaverse-report-2-demand-for-metaverse-remains-amidst-crypto-turmoil)

在 Web2 时代，网络服务主要集中在科技巨头的手中。相反，Web3 创造了一种可访问的、完全自主的体验。它的特性包括分散的、不可信的 web 基础设施、数据和身份主权、开放的公共技术架构等等。

如果你是一个接受 web3 概念的开发人员，并想将你的想法付诸实践，请加入我们，探索 web3 栈。

## 目录

*   [首先，Web3 是什么？](https://web.archive.org/web/20230116191857/https://dappradar.com/blog/how-developers-can-enhance-their-web3-stack-with-filecoin/#web3)
*   [Web3 堆栈概述](https://web.archive.org/web/20230116191857/https://dappradar.com/blog/how-developers-can-enhance-their-web3-stack-with-filecoin/#stack)
    *   [区块链](https://web.archive.org/web/20230116191857/https://dappradar.com/blog/how-developers-can-enhance-their-web3-stack-with-filecoin/#blockchain)
    *   [节点](https://web.archive.org/web/20230116191857/https://dappradar.com/blog/how-developers-can-enhance-their-web3-stack-with-filecoin/#nodes)
    *   [智能合约开发环境](https://web.archive.org/web/20230116191857/https://dappradar.com/blog/how-developers-can-enhance-their-web3-stack-with-filecoin/#smart)
    *   [前端框架](https://web.archive.org/web/20230116191857/https://dappradar.com/blog/how-developers-can-enhance-their-web3-stack-with-filecoin/#front)
    *   [以太坊 web 客户端库](https://web.archive.org/web/20230116191857/https://dappradar.com/blog/how-developers-can-enhance-their-web3-stack-with-filecoin/#library)
    *   [钱包](https://web.archive.org/web/20230116191857/https://dappradar.com/blog/how-developers-can-enhance-their-web3-stack-with-filecoin/#wallet)
    *   [存储](https://web.archive.org/web/20230116191857/https://dappradar.com/blog/how-developers-can-enhance-their-web3-stack-with-filecoin/#storage)
    *   [索引和查询](https://web.archive.org/web/20230116191857/https://dappradar.com/blog/how-developers-can-enhance-their-web3-stack-with-filecoin/#indexing)
*   [今天在 Web3 堆栈上构建，塑造我们的未来](https://web.archive.org/web/20230116191857/https://dappradar.com/blog/how-developers-can-enhance-their-web3-stack-with-filecoin/#build)

## 首先，什么是 Web3？

Web3 设想了新一代的万维网。它融合了去中心化、区块链技术和基于令牌的经济学等概念。

在 Web3 中，最终用户直接与分散式应用程序(dApps)交互。这些 dApps 受益于分布式基础设施，同时给予用户对其身份、个人数据和财务的更多控制。许多人认为，Web3 将为用户提供更好的数据安全性、可扩展性和隐私，并对抗大型科技公司的垄断和控制。

分散存储系统为企业和个人提供了无数的优势。例如，分布式存储系统利用对等技术来消除对不必要资源的需求，并保证服务始终可用。此外，它使用数据加密来提高用户数据的安全性和隐私性，防止不道德的访问。

这些只是它众多优点中的一部分。因此，选择一个强大的存储提供商对项目的成功至关重要。

Filecoin 和 IPFS 是在分布式网络上存储和共享数据的互补协议。许多项目同时使用这两种网络来实现分散存储的最佳效果。

[Learn more about Filecoin and IPFS](https://web.archive.org/web/20230116191857/https://filecoin.io/)

## Web3 堆栈概述

让我们从开发人员的角度来简单看看 web3 技术栈的组件。接下来的内容将帮助开发人员理解在区块链上进行构建需要哪些步骤。

### 区块链

区块链是一种分布式公共分类账，利用独立的计算机(或节点)来记录、共享和同步网络中的交易。与集中式网络不同，区块链不需要中央管理员，因此不会出现单点故障。

[Learn more about blockchain](https://web.archive.org/web/20230116191857/https://dappradar.com/blog/what-is-a-blockchain-dappradars-ultimate-guide)

在区块链上运行的应用程序被称为分散式应用程序，简称 dapp。值得注意的是，当前的 dapp 生态系统已经蓬勃发展，并拥有多个并排运行的区块链。

第 1 层区块链充当区块链体系结构的基础层，它们在没有其他网络支持的情况下验证和执行事务。

例如，以太坊是一个开源的、去中心化的第一层网络，它允许用户通过智能合约相互交易。它拥有市值第二大的加密货币，并在其生态系统中托管各种各样的分散应用程序。

另一个突出的第一层网络是 Polygon，它是目前区块链拥有最多 UAV 的网络之一。它是第一个结构良好、易于使用的以太坊扩展和基础设施开发平台。此外，其模块化、灵活的框架和 EVM 兼容特性使其成为开发人员构建 dapps 的首选区块链之一。

[Explore Polygon’s ecosystem](https://web.archive.org/web/20230116191857/https://dappradar.com/rankings/protocol/polygon)

其他流行的第 1 层网络包括 Solana、Near、Flow、Polkadot、Aptos 等。

#### 兼容 EVM 与不兼容 EVM

当开发人员选择一个区块链网络来构建 dapps 时，他们有两个主要选择，兼容以太坊虚拟机(EVM)的区块链和不兼容 EVM 的区块链。

随着以太坊越来越受欢迎，它也强调了解决其拥堵问题和高交易成本的紧迫性。为此，许多项目开发了完全兼容 EVM 的网络，让用户参与到广阔的以太坊生态系统中。

此外，这些 EVM 兼容的区块链允许开发人员利用所有相同的工具、文档和专门为 EVM 连锁店构建的社区，从而节省时间并缩短学习曲线。

非 EVM 网络的出现是因为工程师们认为 EVM 链太受以太坊框架的约束，选择通过设计新的结构来创新。

#### Filecoin 的 FVM 是什么

Filecoin 推出了一款与 e VM 兼容的原生虚拟机。这是一项重大创新，旨在为 Filecoin 带来链上可编程性，并提高 Filecoin 上数据的分散计算效率。

FVM 演员(又名。智能合同)可以代理计算资源，激励计算执行，在可用的存储提供商之间分配工作负载，并证明计算结果的有效性，以便申请奖励。

FVM 开启了无限的可能性，其中一些列举如下。

*   可编程存储原语(如存储边界、拍卖等)
*   跨链互操作性桥(例如，将 Filecoin 与以太坊、Solana、NEAR 等无信任地连接起来)
*   以数据为中心的分散自治组织(Dao)
*   第 2 层解决方案(如信誉系统
*   数据可用性采样、计算结构
*   激励一致的内容交付网络)

[Learn more about FVM](https://web.archive.org/web/20230116191857/https://fvm.filecoin.io/)

### 节点

区块链或 P2P 网络由许多分布式计算机组成，也称为节点，类似于小型服务器。节点的职责包括验证事务、验证网络状态以及保存区块链的历史记录。

节点使 dapps 能够连接到区块链，访问其数据，并与智能合约进行交互。将 dapp 连接到节点时，主要有两种方法。

*   运行您自己的节点
*   使用节点提供程序

运行和维护一个节点通常需要花费大量的时间和精力。然而，对于希望专注于构建 dapps 的开发人员来说，区块链节点提供商是一个选择。像 Infura、Quicknode、Chainstack、Alchemy、Getblock、RunNode 和 Pocket Network 这样的公司允许开发者使用他们的节点。

### 智能合同开发环境

开发环境允许您部署智能合约、运行测试和调试代码，而无需处理实际环境。我们来看看目前以太坊开发可用的主流环境有哪些。

#### 建筑工人

安全帽是最常用的一种。它帮助开发人员在开发 dapps 和智能合约时管理和自动化常见任务。Hardhat 的一些强大功能包括可靠性调试、失败事务的错误消息和显式堆栈跟踪。

#### 松露

Truffle 是一个基于 JavaScript 的框架，用于构建智能合约，是以太坊开发者最古老的开发工具之一。除了作为开发和测试框架，它还可以通过使用以太坊虚拟机作为 dapps 的资产管道。

#### 其他值得注意的 Web3 开发环境

*   铸造
*   布朗尼
*   锚
*   从事
*   华夫饼

### 前端框架

开发人员有多种框架可以用来构建 Web3 项目的前端界面。

React 在客户端构建的开发者中非常受欢迎。它是一个轻量级、高效且灵活的 JavaScript 库，有助于开发流畅且用户友好的 web 应用程序。

Next.js 和 React 在人气上不分上下。它被广泛接受有许多原因。例如，在加载时间方面，它具有出色的性能。它还创造了一个奇妙的用户体验，并提供了伟大的搜索引擎优化结果。

此外， [web3ui kit](https://web.archive.org/web/20230116191857/https://github.com/web3ui/web3uikit) 变得流行，因为它为 web3 开发者带来了轻量级 ui 组件。这个 UI 库将加速开发者的 dapp 开发，无论他们构建在哪个链上。

### 以太坊 web 客户端库

[ethers.js](https://web.archive.org/web/20230116191857/https://github.com/ethers-io/ethers.js/) 库提供了一个完整而紧凑的库，用于与以太坊区块链及其生态系统进行交互。最初，它是为了支持 ethers.io 的使用而构建的，但现在它已经扩展为一个更通用的库。

[web3.js](https://web.archive.org/web/20230116191857/https://github.com/web3/web3.js) 库是以太坊基金会在 2015 年建立的开源 JavaScript 库。由于它提供了与 Ethereum 节点通信的函数和良好的 API 参考，因此被许多项目采用。

开发者也可以有 [ethjs](https://web.archive.org/web/20230116191857/https://github.com/ethjs/ethjs) 作为选项。这是一个基于 web3.js 的高度优化的敏捷 JS 工具，但是更轻便，只支持异步，并且使用 bn.js。

### 钱包

在 web3 中，身份验证呈现出完全不同的模式。在 web2 中，验证几乎总是基于用户的个人信息。然而，在 web3 中，身份围绕着钱包和公钥加密技术。作为开发人员，您必须了解如何以各种方式访问用户的钱包和地址并与之交互。

此外，你必须记住，不同的区块链可能需要不同的钱包。例如，最受欢迎的钱包之一 MetaMask 支持以太坊、BNB 链、多边形、雪崩等网络。

另一个流行的解决方案是 WalletConnec，这是一个分散的 Web3 消息层，也是连接区块链钱包和 dapps 的标准。它致力于通过为钱包提供易于使用的工具和基础设施来增强 Web3 空间的互操作性，从而提供流畅的用户体验。

### 储存；储备

网络上的数据必须存在于某个地方。在 Web2 中，几乎所有的用户数据，如视频、图像和帐户信息，都使用集中式数据库进行数据存储。

不幸的是，这种存储模式带来了几个问题。最大的问题之一是泄露重要的个人信息和未经授权的访问。

数据权是一项人权，因此维护用户数据主权是 Web3 的关键任务之一。凭借其内置的安全性、不可信赖性和透明性，区块链可以在数字化用户和他们的真实身份之间形成一道屏障，从而保护他们的隐私。然而，在链上存储大量数据目前需要大量的工作。

令人欣慰的是，分散式存储网络，如 Filecoin 和 IPFS，可以解决这个问题。分散式存储平台将文件分布在分布式系统上，保持文件的安全性和不可更改性。

[Learn more about Filecoin](https://web.archive.org/web/20230116191857/https://filecoin.io/)

### 索引和查询

该图是一个分散的协议，用于索引和查询来自区块链的数据，从以太坊开始。它支持对难以直接查询的数据进行查询。

Graph 技术的突出之处在于，它使 dapps 能够访问所有类型的区块链数据，而不局限于特定数据提供商提供的信息。

## 今天在 Web3 堆栈上构建，塑造我们的未来

Web3 领域的发展速度比以往任何时候都快，开发人员必须不断学习以提高他们的技能。随着更强大的技术解决方案变得可用，开发人员可以更高效地创建最适合其用户的系统和产品。

如果开发人员希望使用许多开箱即用的工具最大限度地实现顺畅的一站式开发流程，Filecoin 的分散存储解决方案和强大的 FVM 是满足他们需求的最佳组合。

通过下面的链接了解如何利用 Filecoin 来增强您的 dapp 安全性和用户体验。

*   [网站](https://web.archive.org/web/20230116191857/https://filecoin.io/)
*   [经济论文](https://web.archive.org/web/20230116191857/https://filecoin.io/2020-engineering-filecoins-economy-en.pdf)
*   [推特](https://web.archive.org/web/20230116191857/https://twitter.com/Filecoin)
*   [博客](https://web.archive.org/web/20230116191857/https://filecoin.io/blog/)

**免责声明** —这是一篇赞助文章。DappRadar 不认可本页面上的任何内容或产品。DappRadar 旨在提供准确的信息，但读者应该在采取行动之前总是自己做研究。DappRadar 的文章不能被认为是投资建议。