
# TradingView JS API集成教程(一)：简介

> **这个系列教程中，我将完成本集成指南，涵盖很多TradingView功能，以及增进的文章。我希望每个人都能轻松完成这个过程，并且非常欢迎各位读者的反馈！**

[TradingView](http://www.tradingview.com/)是最受欢迎的数字货币图表工具，许多交易所和网站集成了他们免费的[图表库](https://www.tradingview.com/HTML5-stock-forex-bitcoin-charting-library/)以提供交易者熟悉而强大的图表界面。

但是，将TradingView图表库放入网页的过程让人困惑并且开发文档写的不够清晰明了。在官方项目上提交的大量相似问题证明了这一点。

**本系列教程的目标是向您展示如何使用CryptoCompare作为免费的数据源来使用图表库。**

-   [第1部分](https://www.jianshu.com/p/603d671400da)重点介绍如何设置图表库Widget，向您介绍TradingView JS API以及如何设置静态图表。

[**TradingView图表库加密的JS API设置：第1部分**  
_查看本教程系列的简介（如果您还没有）。这是一个令人费解的过程，所以请...](https://www.jianshu.com/p/603d671400da)

-   第2部分扩展了第1部分，并使用websockets实现了对图表数据的实时更新

[**TradingView图表库加密的JS API设置：实时图表更新**  
_在TradingView JS API示例指南的第2部分中，我们将在图表上实现实时价格更新。制作..._medium.com](https://medium.com/@jonchurch/tv-part-2-b8c2d4211f90 "https://medium.com/@jonchurch/tv-part-2-b8c2d4211f90")[](https://medium.com/@jonchurch/tv-part-2-b8c2d4211f90)

### 在开始之前

图表库虽然可以免费用于商业和公共用途，但它是一个私人github项目，您必须申请访问。

在本教程中，我没有向您提供图表库文件，因为他们的许可协议禁止我这样做😭😭

**要自己实际实现本教程，您需要**[**申请访问**](https://www.tradingview.com/HTML5-stock-forex-bitcoin-charting-library/)**图表库，然后将其复制到**`/public/`**目录中。**

在此期间，您可以了解所涉及的内容。遗憾的是，即使是开发文档也仅提供给授权用户访问[图表库github资源](https://github.com/tradingview/charting_library)。如果您未获得授权，您将看到404

> **译者注：虽然英文开发文档非授权用户不可以访问，但是可以访问我翻译的[中文开发文档](https://zlq4863947.gitbooks.io/tradingview/)**

### 代码在哪里？

您可以在此处查看本教程所涉及的代码资源：

[**jonchurch / tradingview-js-api-tutorial**  
_通过在GitHub上创建一个帐户来参与tradingview-js-api-tutorial开发。_github.com](https://github.com/jonchurch/tradingview-js-api-tutorial "https://github.com/jonchurch/tradingview-js-api-tutorial")

----------

### 关于译者

我是一名现就职于[日本最大数字货币交易所bitbank](bitbank.cc)的全栈开发人员，住在东京。如果您需要加快将TradingView放入到您的网站或交易网页，我可以付费帮忙。

**您可以联系我：zlq4863947@gmail.com**

**您也可以加入开发交流qq群：313839516**

### 关于本篇译文

#### 英文原文地址： [TradingView JS API Integration Tutorial: Introduction](https://medium.com/@jonchurch/tradingview-js-api-integration-tutorial-introduction-5e4809d9ef36)