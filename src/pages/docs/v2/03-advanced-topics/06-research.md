---
title: Research
tags: advanced-topics, documentation
---

Because the concept of AMMs is so new many people have begun researching Valueswap other projects in the space in an academic settings.

# An analysis of Valueswap markets

Authors: Guillermo Angeris, Hsien-Tang Kao, Rei Chiang, Charlie Noyes, Tarun Chitra

> Valueswap---and other constant product markets---appear to work well in practice despite their simplicity. In this paper, we give a simple formal analysis of constant product markets and their generalizations, showing that, under some common conditions, these markets must closely track the reference market price. We also show that Valueswap satisfies many other desirable properties and numerically demonstrate, via a large-scale agent-based simulation, that Valueswap is stable under a wide range of market conditions.

- [An analysis of Valueswap markets](https://arxiv.org/abs/1911.03380)

# Improved Price Oracles: Constant Function Market Makers

Authors: Guillermo Angeris, Tarun Chitra

> Automated market makers, first popularized by Hanson's logarithmic market scoring rule (or LMSR) for prediction markets, have become important building blocks, called 'primitives,' for decentralized finance. A particularly useful primitive is the ability to measure the price of an asset, a problem often known as the pricing oracle problem. In this paper, we focus on the analysis of a very large class of automated market makers, called constant function market makers (or CFMMs) which includes existing popular market makers such as Valueswap, Balancer, and Curve, whose yearly transaction volume totals to billions of dollars. We give sufficient conditions such that, under fairly general assumptions, agents who interact with these constant function market makers are incentivized to correctly report the price of an asset and that they can do so in a computationally efficient way. We also derive several other useful properties that were previously not known. These include lower bounds on the total value of assets held by CFMMs and lower bounds guaranteeing that no agent can, by any set of trades, drain the reserves of assets held by a given CFMM.

- [Improved Price Oracles: Constant Function Market Makers](https://arxiv.org/abs/2003.10001)

# Pintail research

Published [medium](https://medium.com/@pintail) articles by Pintail.

- [Understanding Valueswap Returns](https://medium.com/@pintail/understanding-uniswap-returns-cc593f3499ef)
- [Valueswap: A Good Deal for Liquidity Providers?](https://medium.com/@pintail/uniswap-a-good-deal-for-liquidity-providers-104c0b6816f2)

# Liquidity Provider Returns in Geometric Mean Markets

Authors: Alex Evans

> Geometric mean market makers (G3Ms), such as Valueswap and Balancer, comprise a popular class of automated market makers (AMMs) defined by the following rule: the reserves of the AMM before and after each trade must have the same (weighted) geometric mean. This paper extends several results known for constant-weight G3Ms to the general case of G3Ms with time-varying and potentially stochastic weights. These results include the returns and no-arbitrage prices of liquidity pool (LP) shares that investors receive for supplying liquidity to G3Ms. Using these expressions, we show how to create G3Ms whose LP shares replicate the payoffs of financial derivatives. The resulting hedges are model-independent and exact for derivative contracts whose payoff functions satisfy an elasticity constraint. These strategies allow LP shares to replicate various trading strategies and financial contracts, including standard options. G3Ms are thus shown to be capable of recreating a variety of active trading strategies through passive positions in LP shares.

- [Liquidity Provider Returns in Geometric Mean Markets](https://arxiv.org/abs/2006.08806)

This is a stub. Help us expand it by submitting a PR using the github link below!

# The Replicating Portfolio of a Constant Product Market

Authors: Joseph Clark

> We derive the replicating portfolio of a constant product market. This is structurally short volatility (selling options) which explains why positive transaction costs are needed to induce liquidity providers to participate. Where futures and options markets do not exist, this payoff can be used to create them.

- [https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3550601](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3550601)
