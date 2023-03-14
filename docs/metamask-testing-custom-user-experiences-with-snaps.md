# 元蒙版测试使用快照的自定义用户体验

> 原文：<https://web.archive.org/web/https://dappradar.com/blog/metamask-testing-custom-user-experiences-with-snaps>

## Snaps 是一个允许任何人安全地扩展 MetaMask 功能的系统

随着 Snaps 的到来，领先的区块链和 Web3 钱包 MetaMask 本周向社区开放了其未来的发展。Snaps 是一个允许任何人在测试环境中扩展 MetaMask 功能的系统。值得注意的是，用户需要安装 MetaMask Flask:这是一个开发人员的实验平台，新的或提议的功能可以在部署到更广泛的公众之前进行推广和测试。

snap 是在隔离环境中运行的程序，用于定制钱包体验。例如，快照可以向元掩码添加新的 API，支持不同的区块链，或者使用内部 API 修改现有功能。MetaMask 希望 Snaps 通过以以前不可能的方式改变 MetaMask，成为创建 web3 最终用户体验的新方式。

Snaps 是 Flask 环境中推出的第一个特性，使元掩码对开发人员来说更具可扩展性，允许他们专门构建他们的 dapp 所需的内容。此外，MetaMask 是第一个为开发人员提供这种灵活性的钱包。

[https://web.archive.org/web/20221007151208if_/https://www.youtube.com/embed/2iUUwA5BmsI?feature=oembed](https://web.archive.org/web/20221007151208if_/https://www.youtube.com/embed/2iUUwA5BmsI?feature=oembed)

## 快照是如何工作的？

快照在隔离环境中运行，可以访问有限的一组功能，这由用户在安装期间授予的权限决定。与 MetaMask 的[以太坊提供者 RPC API](https://web.archive.org/web/20221007151208/https://docs.metamask.io/guide/rpc-api.html) 一样，快照使用 JSON-RPC 与 MetaMask 通信。以太坊提供者 JSON-RPC API 中添加了新的 RPC 方法，它被记录为 [Snaps RPC API](https://web.archive.org/web/20221007151208/https://docs.metamask.io/guide/snaps-rpc-api.html) 的一部分。这些新方法允许捕捉修改元遮罩的功能。此外，它们还允许网站安装单个快照并与之通信。更多细节参见[快照 RPC API 文档](https://web.archive.org/web/20221007151208/https://docs.metamask.io/guide/snaps-rpc-api.html)。

随着时间的推移，MetaMask 将会以 RPC 方法的形式公开更多的内部功能，从而为快照提供更多的功能。目前，捕捉不能直接修改元遮罩 UI。如果快照需要 UI，该 UI 必须完全存在于网站上，以便与快照通信。

[](https://web.archive.org/web/20221007151208/https://dappradar.com/blog/4-tips-on-blockchain-cybersecurity-stay-safe-in-crypto)[![](img/87befc4a1e42119d30e207f259589417.png)<picture>![](img/194973b661f1487e3eb736060d435127.png)</picture>](https://web.archive.org/web/20221007151208/https://dappradar.com/blog/4-tips-on-blockchain-cybersecurity-stay-safe-in-crypto)[](https://web.archive.org/web/20221007151208/https://dappradar.com/blog/how-to-start-using-defi-dapps-and-crypto-wallets-on-solana)[![](img/87befc4a1e42119d30e207f259589417.png)<picture>![](img/a54054d7fb13df07cb7ace1e174bb9df.png)</picture>](https://web.archive.org/web/20221007151208/https://dappradar.com/blog/how-to-start-using-defi-dapps-and-crypto-wallets-on-solana)[](https://web.archive.org/web/20221007151208/https://dappradar.com/blog/best-cryptocurrency-wallets-for-2022)[![](img/87befc4a1e42119d30e207f259589417.png)<picture>![](img/c179fc3f4109cb843ea2ec14dcde382a.png)</picture>](https://web.archive.org/web/20221007151208/https://dappradar.com/blog/best-cryptocurrency-wallets-for-2022)

## 安装 MetaMask 烧瓶

MetaMask Flask 是一个独立的开发者扩展，它提供了对其他不稳定 API 的访问。Flask 的目标是最大化开发人员的控制，以便 MetaMask 可以了解开发人员想用 MetaMask 做什么的全部范围，并结合这些经验。

*   首先，在 Firefox 或 Chrome 浏览器中，创建一个新的浏览器配置文件或禁用任何已安装的 MetaMask 版本。
*   在同一个浏览器配置文件中运行 MetaMask 的多个实例将会中断 dapp 交互。
*   接下来，下载[烧瓶](https://web.archive.org/web/20221007151208/https://metamask.io/flask)
*   并将其添加到您选择的浏览器中。

要继续探索 Snaps 和 Flask，[请点击此处获取完整说明](https://web.archive.org/web/20221007151208/https://docs.metamask.io/guide/snaps.html#serving-a-snap-to-your-local-environment)。

## 区块链和加密钱包

区块链钱包将有助于发送、接收和存储数字资产，它将保护你的密码，在某些情况下，NFT 资产的安全。然而，并不是所有的钱包都是一样的，有些钱包在质量、安全性和所提供的功能方面非常突出。

随着越来越多的人被 crypto 和 web3 吸引，钱包领域的竞争最近越来越激烈。可以说，MetaMask 可以被指责为在过去几年变得肥胖和懒惰，因为它在 crypto 和区块链钱包上享有主导地位。许多人很快指出 MetaMask 正在考虑的开发或用户功能的缺乏——例如现在标准的黑暗模式，MetaMask 仍然没有。

MetaMask 向社区开放开发以增强运营的消息应该在业内反响不错。此外，看看开发人员构建了什么功能来使使用他们的 dapps 更容易将会很有趣。

![](img/6d5a4a2d609c56e1a5771717e54ba759.png) NewsletterUnsubscribe at any time. [T&Cs](https://web.archive.org/web/20221007151208/https://dappradar.com/terms) and [Privacy Policy](https://web.archive.org/web/20221007151208/https://dappradar.com/privacy-policy)

***以上不构成投资建议。此处给出的信息仅供参考。请行使尽职调查，做你的研究。作者持有多种加密货币的头寸，包括 BTC、ETH 和 RADAR。***