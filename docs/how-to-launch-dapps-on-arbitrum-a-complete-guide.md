# 如何在 Arbitrum 上推出 Dapps？完全指南

> 原文：<https://web.archive.org/web/https://dappradar.com/blog/how-to-launch-dapps-on-arbitrum-a-complete-guide>

## 了解如何在 Arbitrum 协议上运行您的分散式应用，以及随之而来的所有好处

在 Arbitrum 区块链上构建您的 dapps 可能会获得更好的速度、可扩展性甚至隐私。但是你是怎么做到的呢？本文将指导您在以太坊第二层协议上启动 dapps。我们开始吧！

## 目录

*   什么是仲裁？
*   【Arbitrum 对 dapp 开发者有什么好处？
*   [顶级仲裁员 dapps](https://web.archive.org/web/20221229172852/https://dappradar.com/blog/how-to-launch-dapps-on-arbitrum-a-complete-guide/#Top-Arbitrum-dapps)
*   [如何在 Arbitrum 上启动 dapps:循序渐进](https://web.archive.org/web/20221229172852/https://dappradar.com/blog/how-to-launch-dapps-on-arbitrum-a-complete-guide/#How-to-launch-dapps-on-Arbitrum:-Step-by-step)
    *   [第一步:编辑你的可靠性合同](https://web.archive.org/web/20221229172852/https://dappradar.com/blog/how-to-launch-dapps-on-arbitrum-a-complete-guide/#Step-1:-Compile-your-Solidity-contracts)
    *   [步骤 2:定义验证器来跟踪你的虚拟机的执行](https://web.archive.org/web/20221229172852/https://dappradar.com/blog/how-to-launch-dapps-on-arbitrum-a-complete-guide/#Step-2:-Define-the-validators-to-track-your-VM’s-execution)
    *   [第三步:与以太桥通信](https://web.archive.org/web/20221229172852/https://dappradar.com/blog/how-to-launch-dapps-on-arbitrum-a-complete-guide/#Step 3: Communicate with EthBridge)
*   [在 DappRadar 上提交您的 Arbitrum dapps】](https://web.archive.org/web/20221229172852/https://dappradar.com/blog/how-to-launch-dapps-on-arbitrum-a-complete-guide/#Submit-your-Arbitrum-dapps-on-DappRadar)

## 什么是 Arbitrum？

Arbitrum 旨在克服基于以太坊的智能合约的一些缺陷，是领先的区块链的第 2 层扩展解决方案。它有助于验证智能合同，防止以太坊主网堵塞。

在今年的加密熊市中，第二层也是表现最好的，在 DeFi 开发人员中特别受欢迎。

> ***“当我们查看 Arbitrum 交易数时，我们可以看到它自年初以来一直处于上升趋势，从 8 月到 9 月增长了 54.7%。”***
> 
> [*Measuring the Impact of Ethereum’s Merge on Layer-2*](https://web.archive.org/web/20221229172852/https://dappradar.com/blog/measuring-the-impact-of-ethereums-merge-on-layer-2/#Arbitrum,-like-Optimism,-a-top-performer-during-this-bear-market)

## Arbitrum 对 dapp 开发者有什么好处？

在这么多以太坊可扩展性解决方案中，Arbitrum 在 2022 年第二、三季度已经脱颖而出。

业内一些最常用的 dapp 已经集成了第 2 层，这可以解释为 Arbitrum 为 dapp 开发人员带来的好处。包括:

*   安全性；
*   易于实施；
*   性能优越；
*   防欺诈机制。

此外，由于 Arbitrum 与以太坊虚拟机兼容，任何开发人员都可以在 Arbitrum mainnet 中构建他们的 dapps，而无需学习新的编码语言——除了 Solidity。

## 顶级仲裁员

一些在阿尔比库姆最受欢迎的 DeFi dapps 包括 SushiSwap、Uniswap、GMX 和 Stargate。关于 Arbitrum 上的 NFT dapps，OpenSea、Stratos 和 tofuNFT 排名靠前。

他们的贡献使得 Arbitrum 在 2022 年 9 月(TVL)的总价值达到了 10 亿美元，比上一季度增长了 36%。

*   **阅读**:[Arbitrum 上你必须知道的流行趋势](https://web.archive.org/web/20221229172852/https://dappradar.com/blog/trending-dapps-on-arbitrum-you-must-know)

## 如何在 Arbitrum 上启动 dapps:循序渐进

无论你是在开发一个全新的 dapp，还是已经完成并想从以太坊移植过来，这个过程都非常简单并且是开源的。请遵循以下步骤。

### 第一步:编辑你的可靠性合同

假设你的 dapp 合同已经用 Solidity 写好了，接下来你需要做的就是把它们格式化成 Arbitrum 格式。这是通过 Arbitrum 编译器完成的，创建一个 Arbitrum 虚拟机(VM)。

为了将合同部署到 Arbitrum 链上，您可以使用任何以太坊开发框架，如 Truffle、Hardhat、Foundry 和 Brownie。

### 步骤 2:定义验证器来跟踪 VM 的执行

然后是时候识别你的 dapp 验证器来确保它的 VM 的执行是正确的。值得注意的是，第二层还为其开发人员提供了 AnyTrust 保证，这样，只要他们中的一个人在线并诚实行事，验证就可以顺利进行。

### 第三步:与 EthBridge 沟通

将 dapp 迁移到 Arbitrum 的最后一步包括调用 EthBridge 来通知您的 VM 在 Arbitrum 上的启动及其验证器。这个智能合同将把 Arbitrum 连接到以太坊，允许您的 dapp 向您的 VM 发送和接收以太或任何其他基于以太坊的令牌。

在这个阶段，使用你的 dapp 的人可以在他们的浏览器中启动你的前端界面——这将与你的 VM 交互并向你的验证器发送消息。欢迎来到阿比杜姆！

## 在 DappRadar 上提交您的 Arbitrum dapps

如果你已经跟随潮流，将你的基于以太坊的 dapp 迁移到 Arbitrum，你会很高兴地知道你已经可以将它列入 [DappRadar 排名](https://web.archive.org/web/20221229172852/https://dappradar.com/rankings)。

> 1/2
> 🎯 [@arbitrum](https://web.archive.org/web/20221229172852/https://twitter.com/arbitrum?ref_src=twsrc%5Etfw) 即将来到 DappRadar(全球最大的 dapp 店)！
> 
> 【➡️】如果你是 [#arbitrum](https://web.archive.org/web/20221229172852/https://twitter.com/hashtag/arbitrum?src=hash&ref_src=twsrc%5Etfw) dapp 开发者，你已经可以在这里提交你的 dapp 合约:[https://t.co/UIRvmMx0Jb](https://web.archive.org/web/20221229172852/https://t.co/UIRvmMx0Jb)[@ arbitrumdevs](https://web.archive.org/web/20221229172852/https://twitter.com/ArbitrumDevs?ref_src=twsrc%5Etfw)[@ offchainlabs](https://web.archive.org/web/20221229172852/https://twitter.com/OffchainLabs?ref_src=twsrc%5Etfw)[pic.twitter.com/NWclplBnmF](https://web.archive.org/web/20221229172852/https://t.co/NWclplBnmF)
> 
> — DappRadar (@DappRadar) [October 6, 2022](https://web.archive.org/web/20221229172852/https://twitter.com/DappRadar/status/1578128017460789264?ref_src=twsrc%5Etfw)

请务必将您的 Arbitrum dapps 提交到 dappRadar，这是一家全球 Dapp 商店，让您的 Dapp 有机会与一个令人惊叹的社区互动，并最大限度地提高其知名度。

[Submit Arbitrum Dapps To DappRadar](https://web.archive.org/web/20221229172852/https://dappradar.com/dashboard/submit-dapp)

我们希望您喜欢了解更多关于在 Arbitrum 上发布 dapps 的内容。

DappRadar 将继续密切关注 Arbitrum 及其在 Web3 中的激动人心的旅程。加入我们的 [Twitter](https://web.archive.org/web/20221229172852/https://twitter.com/DappRadar) 成为第一个听到新趋势的人。

***以上不构成投资建议。此处给出的信息仅供参考。请尽职调查并自行研究。***

## 随身携带您的 Web3 之旅

使用 DappRadar 移动应用程序，再也不会错过 Web3。查看最受欢迎的 dapps 的性能，并关注您投资组合中的 NFT。您在 DappRadar 上的帐户会与我们的移动应用程序同步，这样您很快就可以选择实时接收提醒。

[Download the DappRadar app now](https://web.archive.org/web/20221229172852/https://dappradar.app.link/blog)[](https://web.archive.org/web/20221229172852/https://play.google.com/store/apps/details?id=com.portfolio.dappradar)[![](img/a3634373d68930c5d4e8a7fce618f91f.png)<picture>![](img/2a61eaf90f053d8a56440d9ebf324440.png)</picture>](https://web.archive.org/web/20221229172852/https://play.google.com/store/apps/details?id=com.portfolio.dappradar)![](img/6d5a4a2d609c56e1a5771717e54ba759.png) NewsletterUnsubscribe at any time. [T&Cs](https://web.archive.org/web/20221229172852/https://dappradar.com/terms) and [Privacy Policy](https://web.archive.org/web/20221229172852/https://dappradar.com/privacy-policy)