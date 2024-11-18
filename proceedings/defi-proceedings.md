---
layout: "multilevel_navbar"
background: '/img/bg-index.jpg'
---

<html xmlns:bkstg="http://www.atypon.com/backstage-ns" xmlns:urlutil="java:com.atypon.literatum.customization.UrlUtil" xmlns:pxje="java:com.atypon.frontend.services.impl.PassportXslJavaExtentions"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="Content-Style-Type" content="text/css"><style type="text/css">
            #DLtoc {
            font: normal 12px/1.5em Arial, Helvetica, sans-serif;
            }

            #DLheader {
            }
            #DLheader h1 {
            font-size:26px;
            }

            #DLcontent {
            font-size:16px;
            }
            #DLcontent h2 {
            font-size:20px;
            margin-bottom:5px;
            }
            #DLcontent h3 {
            font-size:16px;
            padding-left:20px;
            margin-bottom:0px;
            }

            #DLcontent ul{
            margin-top:0px;
            margin-bottom:0px;
            }

            .DLauthors li{
            display: inline;
            list-style-type: none;
            padding-right: 5px;
            }

            .DLauthors li:after{
            content:",";
            }
            .DLauthors li.nameList.Last:after{
            content:"";
            }

            .DLabstract {
            padding-left:40px;
            padding-right:20px;
            display:block;
            }

            .DLformats li{
            display: inline;
            list-style-type: none;
            padding-right: 5px;
            }

            .DLformats li:after{
            content:",";
            }
            .DLformats li.formatList.Last:after{
            content:"";
            }

            .DLlogo {
            vertical-align:middle;
            padding-right:5px;
            border:none;
            }

            .DLcitLink {
            margin-left:20px;
            }

            .DLtitleLink {
            margin-left:20px;
            }

            .DLotherLink {
            margin-left:0px;
            }

</style><title>DeFi'22: Proceedings of the 2022 ACM CCS Workshop on Decentralized Finance and Security</title></head><body><div id="DLtoc"><div id="DLheader"><h1>DeFi'22: Proceedings of the 2022 ACM CCS Workshop on Decentralized Finance and Security</h1><a class="DLcitLink" title="Go to the ACM Digital Library for additional information about this proceeding" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/proceedings/10.1145/3560832"><img class="DLlogo" alt="Digital Library logo" height="30" src="https://dl.acm.org/specs/products/acm/releasedAssets/images/footer-logo1.png">
Full Citation in the ACM Digital Library
</a></div><div id="DLcontent"><h2>SESSION: Session 1: MEV</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560832.3564259">Improving Proof of Stake Economic Security via MEV Redistribution</a></h3><ul class="DLauthors"><li class="nameList">Tarun Chitra</li><li class="nameList Last">Kshitij Kulkarni</li></ul><div class="DLabstract"><div style="display:inline">
<p>Maximal Extractable Value (MEV) has generally been viewed as a negative, parasitic aspect of economic transactions on blockchains that increases costs for non-strategic users. Recent work has shown that MEV is not always bad for social welfare in crypto networks. In this note, we demonstrate that if rational validators in Proof of Stake (PoS) protocols are able to earn a portion of MEV revenue, by a process we call MEV redistribution, they are disincentivized to unstake and lower economic security. We construct a joint staking-lending dynamical system in which a fraction of MEV revenue is used to increase staking returns. We formally show that this MEV redistribution can avoid bad competitive equilibria between staking and lending in which no users stake under benign conditions on the reward inflation schedule of the protocol, and conduct numerical simulations that demonstrate this. This represents another potentially positive externality of MEV, provided that the mechanism for redistribution is well-designed.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560832.3563440">Strategic Peer Selection Using Transaction Value and Latency</a></h3><ul class="DLauthors"><li class="nameList">Kushal Babel</li><li class="nameList Last">Lucas Baker</li></ul><div class="DLabstract"><div style="display:inline">
<p>Many blockchains utilize public peer-to-peer networks to communicate transactions. As activity on blockchain-based DeFi protocols has increased, there has been a sharp rise in strategic behaviour from bots and miners, commonly captured by the notion of Maximal Extractable Value (MEV). While many works have focused on MEV arising from the smart contract layer or consensus layer, in this work we study how a strategic agent can maximise realisable MEV through the optimal choice of network peers. Specifically, we study how existing definitions and algorithms for latency optimization can be augmented with information about the transactions themselves in order to optimize peering algorithms. We formally model this optimization objective for two classes of consensus protocols : 1) time-based ("fair ordering") protocols and 2) single leader-based protocols. We present an efficient local algorithm for choosing peers strategically, and evaluate our algorithm on real world data to show that it outperforms benchmark algorithms that either choose peers randomly or do not exploit information about blockchain transactions.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560832.3563433">Price of MEV: Towards a Game Theoretical Approach to MEV</a></h3><ul class="DLauthors"><li class="nameList">Bruno Mazorra</li><li class="nameList">Michael Reynolds</li><li class="nameList Last">Vanesa Daza</li></ul><div class="DLabstract"><div style="display:inline">
<p>Maximal (also miner) extractable value, or MEV, usually refers to the value that privileged players can extract by strategically ordering, censoring, and placing transactions in a blockchain. Each blockchain network, which we refer to as a domain, has its own consensus, ordering, and block-creation mechanisms, which gives rise to different optimal strategies to extract MEV. The strategic behaviour of rational players, known as searchers, lead to MEV games that have different impacts and externalities in each domain. Several ordering mechanisms, which determine the inclusion and position of transactions in a block, have been considered to construct alternative games to organise MEV extraction, and minimize negative externalities; examples include sealed bid auctions, first input first output, and private priority gas auctions. However, to date, no sufficiently formal and abstract definition of MEV games have been made. In this paper, we take a step toward the formalization of MEV games and compare different ordering mechanisms and their externalities. In particular, we attempt to formalize games that arise from common knowledge MEV opportunities, such as arbitrage and sandwich attacks. In defining these games, we utilise a theoretical framework that provides groundwork for several important roles and concepts, such as the searcher, sequencer, domain, and bundle. We also introduce the price of MEV as the price of anarchy of MEV games, a measure that provides formal comparison between different ordering mechanisms.</p>
</div></div>

<h2>SESSION: Session 2: Game Theory and Mechanism Design</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560832.3563442">To EVM or Not to EVM: Blockchain Compatibility and Network Effects</a></h3><ul class="DLauthors"><li class="nameList">Ruizhe Jia</li><li class="nameList Last">Steven Yin</li></ul><div class="DLabstract"><div style="display:inline">
<p>We study the competition between blockchains in a multi-chain environment, where a dominant EVM-compatible blockchain (e.g., Ethereum) co-exists with an alternative EVM-compatible (e.g., Avalanche) and an EVM-incompatible (e.g., Algorand) blockchain. While EVM compatibility allows existing Ethereum users and developers to migrate more easily over to the alternative layer-1, EVM incompatibility might allow the firms to build more loyal and "sticky'' user base, and in turn a more robust ecosystem. As such, the choice to be EVM-compatible is not merely a technological decision, but also an important strategic decision. In this paper, we develop a game theoretic model to study this competitive dynamic, and find that at equilibrium, new entrants/developers tend to adopt the dominant blockchain. To avoid adoption failure, the alternative blockchains have to either (1) directly subsidize the new entrant firms or (2) offer better features, which in practice can take form in lower transaction costs, faster finality, or larger network effects. We find that it is easier for EVM-compatible blockchains to attract users through direct subsidy, while it is more efficient for EVM-incompatible blockchains to attract users through offering better features/products.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560832.3563436">A Framework for Single-Item NFT Auction Mechanism Design</a></h3><ul class="DLauthors"><li class="nameList">Jason Milionis</li><li class="nameList">Dean Hirsch</li><li class="nameList">Andy Arditi</li><li class="nameList Last">Pranav Garimidi</li></ul><div class="DLabstract"><div style="display:inline">
<p>Lately, Non-Fungible Tokens (NFTs), i.e., uniquely discernible assets on a blockchain, have skyrocketed in popularity by addressing a broad audience. However, the typical NFT auctioning procedures are conducted in various, ad hoc ways, while mostly ignoring the context that the blockchain provides, i.e., new possibilities, but at the same time new challenges in auction design. One of the main targets of this work is to shed light on the vastly unexplored design space of NFT Auction Mechanisms, especially in those characteristics that fundamentally differ from traditional and more contemporaneous forms of auctions. We focus on the case that bidders have a valuation for the auctioned NFT, i.e., what we term the single-item NFT auction case. In this setting, we formally define an NFT Auction Mechanism, give the properties that we would ideally like a perfect mechanism to satisfy (broadly known as incentive compatibility and collusion resistance) and prove that it is impossible to have such a perfect mechanism. Even though we cannot have an all-powerful protocol like that, we move on to consider relaxed notions of those properties that we may desire the protocol to satisfy, as a trade-off between implementability and economic guarantees. Specifically, we define the notion of an equilibrium-truthful auction, where neither the seller nor the bidders can improve their utility by acting non-truthfully, so long as the counter-party acts truthfully. We also define asymptotically second-price auctions, in which the seller does not lose asymptotically any revenue in comparison to the theoretically-optimal (static) second-price sealed-bid auction, in the case that the bidders' valuations are drawn independently from some distribution. We showcase why these two are very desirable properties for an auction mechanism to enjoy, and construct the first known NFT Auction Mechanism which provably possesses such formal guarantees.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560832.3563439">FairTraDEX: A Decentralised Exchange Preventing Value Extraction</a></h3><ul class="DLauthors"><li class="nameList">Conor McMenamin</li><li class="nameList">Vanesa Daza</li><li class="nameList">Matthias Fitzi</li><li class="nameList Last">Padraic O'Donoghue</li></ul><div class="DLabstract"><div style="display:inline">
<p>We present FairTraDEX, a decentralized exchange (DEX) protocol based on frequent batch auctions (FBAs), which provides formal game-theoretic guarantees against extractable value. FBAs, when run by a trusted third-party, ensure that the unique game-theoretic optimal strategy for all players is to trade at the true market-implied price of the underlying token swap, excluding explicit, pre-determined fees. FairTraDEX replicates the key features of an FBA that provide these game-theoretic guarantees using a combination of set-membership in zero-knowledge protocols and an escrow-enforced commit-reveal mechanism. We extend the results of FBAs to handle monopolistic and/or malicious liquidity providers. We provide real-world examples that demonstrate that the costs of executing orders in existing academic and industry-standard protocols become prohibitive as order size increases due to basic value extraction techniques, popularized as maximal extractable value. We further demonstrate that FairTraDEX protects against these execution costs, guaranteeing a fixed fee model independent of order size, the first guarantee of it's kind for a DEX protocol. We also provide detailed Solidity and pseudo-code implementations of FairTraDEX, making FairTraDEX a novel and practical contribution.</p>
</div></div>

<h2>SESSION: Session 3: AMM</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560832.3563435">Exploring Price Accuracy on Uniswap V3 in Times of Distress</a></h3><ul class="DLauthors"><li class="nameList">Lioba Heimbach</li><li class="nameList">Eric Schertenleib</li><li class="nameList Last">Roger Wattenhofer</li></ul><div class="DLabstract"><div style="display:inline">
<p>Financial markets have evolved over centuries, and exchanges have converged to rely on the order book mechanism for market making. Latency on the blockchain, however, has prevented decentralized exchanges (DEXes) from utilizing the order book mechanism and instead gave rise to the development of market designs that are better suited to a blockchain. Although the first widely popularized DEX, Uniswap V2, stood out through its astonishing simplicity, a recent design overhaul introduced with Uniswap V3 has introduced increasing levels of complexity aiming to increase capital efficiency. In this work, we empirically study the ability of Unsiwap V3 to handle unexpected price shocks. Our analysis finds that the prices on Uniswap V3 were inaccurate during the recent abrupt price drops of two stablecoins: UST and USDT. We identify the lack of agility required of Unsiwap V3 liquidity providers as the root cause of these worrying price inaccuracies. Additionally, we outline that there are too few incentives for liquidity providers to enter liquidity pools, given the elevated volatility in such market conditions.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560832.3564260">A Note On Borrowing Constant Function Market Maker Shares</a></h3><ul class="DLauthors"><li class="nameList">Tarun Chitra</li><li class="nameList">Guillermo Angeris</li><li class="nameList">Alex Evans</li><li class="nameList Last">Hsien-Tang Kao</li></ul><div class="DLabstract"><div style="display:inline">
<p>Constant function market makers (CFMMs) such as Uniswap, Balancer, and Curve, among many others, make up some of the largest decentralized exchanges on smart contract platforms like Ethereum. As the amount of capital deposited in these protocols has grown, improving capital efficiency for liquidity providers (LPs) has become an increasingly important challenge. One way to improve efficiency is to allow LPs to borrow Ether or USD against their shares in a CFMM protocol. In this note, we investigate the security and capital efficiency of allowing such lending. We provide sufficient conditions for LP borrowing to be at least as secure and capital efficient as direct borrowing in Aave/Compound. Furthermore, we show that the exposure taken by CFMM lenders can be replicated via barrier options, allowing for risks to be hedged. Finally, we show that the payoff of borrowed CFMM LP shares replicates bounded convex payoffs. Combined, these results suggest that CFMM lending is a safe mechanism for improving capital efficiency.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560832.3563438">Concentrated Liquidity Analysis in Uniswap V3</a></h3><ul class="DLauthors"><li class="nameList">Saleh Hashemseresht</li><li class="nameList Last">Mohsen Pourpouneh</li></ul><div class="DLabstract"><div style="display:inline">
<p>Uniswap V3 is one of the most successful decentralized exchanges for digital cryptocurrencies. The latest version of the Uniswap (V3) introduces a number of new features, notably the concentrated liquidity that allows the liquidity providers to add liquidity within a specific price range. In this paper, we analyze the effect of concentrated liquidity on the return of the liquidity providers and present an approximation for the expected fees and the impermanent loss of a liquidity provider. First, we provide analytical results and then verify them using simulations.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560832.3563441">Quantifying Loss in Automated Market Makers</a></h3><ul class="DLauthors"><li class="nameList">Jason Milionis</li><li class="nameList">Ciamac C. Moallemi</li><li class="nameList">Tim Roughgarden</li><li class="nameList Last">Anthony Lee Zhang</li></ul><div class="DLabstract"><div style="display:inline">
<p>We consider the market microstructure of automated market making and, specifically, constant function market makers (CFMMs), from the economic perspective of passive liquidity providers (LPs). In a frictionless, continuous-time Black-Scholes setting and in the absence of trading fees, we decompose the return of an LP into a instantaneous market risk component and a non-negative, non-decreasing, and predictable component which we call "loss-versus-rebalancing'' (ŁVR, pronounced "lever''). Market risk can be fully hedged, but once eliminated, ŁVR remains as a running cost that must be offset by trading fee income in order for liquidity provision to be profitable. ŁVR is distinct from the more commonly known metric of "impermanent loss'' or "divergence loss''; this latter metric is more fundamentally described as "loss-versus-holding'' and is not a true running cost. We express ŁVR simply and in closed-form: instantaneously, it is the scaled product of the variance of prices and the marginal liquidity available in the pool. As such, ŁVR is easily calibrated to market data and specific CFMM structure. ŁVR provides tradeable insight in both the ex ante and ex post assessment of CFMM LP investment decisions, and can also inform the design of CFMM protocols. For a more complete version of this paper, please refer to <a href="https://arxiv.org/pdf/2208.06046.pdf">https://arxiv.org/pdf/2208.06046.pdf</a>.</p>
</div></div>

</div></div></body></html>
