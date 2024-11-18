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

</style><title>ConsensusDay '22: Proceedings of the 2022 ACM Workshop on Developments in Consensus on ACM Workshop on Developments in Consensus</title></head><body><div id="DLtoc"><div id="DLheader"><h1>ConsensusDay '22: Proceedings of the 2022 ACM Workshop on Developments in Consensus on ACM Workshop on Developments in Consensus</h1><a class="DLcitLink" title="Go to the ACM Digital Library for additional information about this proceeding" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/proceedings/10.1145/3560829"><img class="DLlogo" alt="Digital Library logo" height="30" src="https://dl.acm.org/specs/products/acm/releasedAssets/images/footer-logo1.png">
        Full Citation in the ACM Digital Library
    </a></div><div id="DLcontent"><h2>SESSION: Workshop Papers</h2>
                <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560829.3563557">Blockchain Security when Messages are Lost</a></h3><ul class="DLauthors"><li class="nameList">Taha Ameen</li><li class="nameList">Suryanarayana Sankagiri</li><li class="nameList Last">Bruce Hajek</li></ul><div class="DLabstract"><div style="display:inline">
<p>Security analyses for consensus protocols in blockchain research have primarily focused on the synchronous model, where point-to-point communication delays are upper bounded by a known finite constant. These models are unrealistic in noisy settings, where messages may be lost (i.e. incur infinite delay). In this work, we study the impact of message losses on the security of the proof-of-work longest-chain protocol. We introduce a new communication model to capture the impact of message loss called the 0-∞ model, and derive a region of tolerable adversarial power under which the consensus protocol is secure. The guarantees are derived as a simple bound for the probability that a transaction violates desired security properties. Specifically, we show that this violation probability decays almost exponentially in the security parameter. Our approach involves constructing combinatorial objects from blocktrees, and identifying random variables associated with them that are amenable to analysis. This approach improves existing bounds and extends the known regime for tolerable adversarial threshold in settings where messages may be lost.</p>
</div></div>


                <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560829.3563558">Leveraging Democracy to Optimize Distributed Random Beacons</a></h3><ul class="DLauthors"><li class="nameList">Alejandro Ranchal-Pedrosa</li><li class="nameList Last">Vincent Gramoli</li></ul><div class="DLabstract"><div style="display:inline">
<p>Random beacons, protocols that produce a reliable source of randomness, are crucial in a variety of applications. However, solving the random beacon problem has recently been shown to be at least as hard as solving consensus. In this work, we propose Kleroterion, a random beacon protocol that builds on top of recent works in order to ensure a trustless setup that is not costly, and that tolerates up to less than a third of Byzantine processes under partial synchrony. Kleroterion executes n instances of Pinakion, our novel Publicly-Verifiable Secret Sharing (PVSS) protocol, in order to share one input per process. Then, Kleroterion runs a consensus protocol that selects and aggregates a third of these shared inputs. Compared to previous works that are also quadratic in the communication complexity, Kleroterion allows for inputs to be shared without having to be routed through a specific node, a so-called leader. We refer thus to Kleroterion as a democratic protocol. We show that democratizing protocols improves both communication and computation performance, in that shared bits and computation are scattered across all channels and processes, thus removing the bottleneck at the leader. This is shown in that Kleroterion has linear computation complexity and a number of bits sent per channel of the network independent of the number of processes, except for the reconstruction phase and for one message per leader during agreement. Contrary to leader-less protocols, Kleroterion has a leader of the embedded consensus protocol that proposes a bitmask referencing one bit per shared input. This bitmask can thus reference more information shared by processes, enabling batching with other information. An example of this is a blockchain application in which the output of the random beacon can be used for a secure committee sortition protocol, and the bitmask references both a set of proposed blocks of transactions and of shared inputs.</p>
</div></div>


                <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560829.3563559">Proof-of-Stake Longest Chain Protocols: Security vs Predictability</a></h3><ul class="DLauthors"><li class="nameList">Vivek Bagaria</li><li class="nameList">Amir Dembo</li><li class="nameList">Sreeram Kannan</li><li class="nameList">Sewoong Oh</li><li class="nameList">David Tse</li><li class="nameList">Pramod Viswanath</li><li class="nameList">Xuechao Wang</li><li class="nameList Last">Ofer Zeitouni</li></ul><div class="DLabstract"><div style="display:inline">
<p>The Nakamoto longest chain protocol is remarkably simple and has been proven to provide security against any adversary with less than 50% of the total hashing power. Proof-of-stake (PoS) protocols are an energy efficient alternative; however existing protocols adopting Nakamoto's longest chain design achieve provable security only by allowing long-term predictability, subjecting the system to serious bribery attacks. In this paper, we prove that a natural longest chain PoS protocol with similar predictability as Nakamoto's PoW protocol can achieve security against any adversary with less than 1/(1+e) fraction of the total stake. Moreover we propose a new family of longest chain PoS protocols with a formal proof of their security against a 50% adversary, while only requiring short-term predictability.</p>
</div></div>


                <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560829.3563560">Two More Attacks on Proof-of-Stake GHOST/Ethereum</a></h3><ul class="DLauthors"><li class="nameList">Joachim Neu</li><li class="nameList">Ertem Nusret Tas</li><li class="nameList Last">David Tse</li></ul><div class="DLabstract"><div style="display:inline">
<p>Ethereum, the world's second largest cryptocurrency with a market capitalization exceeding 120 billion USD as of this writing, aims to switch from Proof-of-Work (PoW) to Proof-of-Stake (PoS) based consensus later in the year 2022 (`the Merge'). Yet, so far, the proposed PoS consensus protocol lacks in rigorous security analysis. We present two new attack strategies targeting the PoS Ethereum consensus protocol. The first attack suggests a fundamental conceptual incompatibility between PoS and the Greedy Heaviest-Observed Sub-Tree (GHOST) fork choice paradigm employed by PoS Ethereum. In a nutshell, PoS allows an adversary with a vanishing amount of stake to produce an unlimited number of equivocating blocks. While most equivocating blocks will be orphaned, such orphaned 'uncle blocks' still influence fork choice under the GHOST paradigm, bestowing upon the adversary devastating control over the canonical chain. While the Latest Message Driven (LMD) aspect of current PoS Ethereum prevents a straightforward application of this attack, our second attack shows how LMD specifically can be exploited to obtain a new variant of the balancing attack that overcomes 'proposer boosting', a recent protocol addition that was intended to mitigate balancing-type attacks. Thus, in its current form, PoS Ethereum without and with LMD is vulnerable to our first and second attack, respectively.</p>
</div></div>


                <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560829.3563563">Pikachu: Securing PoS Blockchains from Long-Range Attacks by Checkpointing into Bitcoin PoW using Taproot</a></h3><ul class="DLauthors"><li class="nameList">Sarah Azouvi</li><li class="nameList Last">Marko Vukolić</li></ul><div class="DLabstract"><div style="display:inline">
<p>Blockchain systems based on a reusable resource, such as proof-of-stake (PoS), provide weaker security guarantees than those based on proof-of-work. Specifically, they are vulnerable to long-range attacks, where an adversary can corrupt prior participants in order to rewrite the full history of the chain. To prevent this attack on a PoS chain, we propose a protocol that checkpoints the state of the PoS chain to a proof-of-work blockchain such as Bitcoin. Our checkpointing protocol hence does not rely on any central authority. Our work uses Schnorr signatures and leverages Bitcoin recent Taproot upgrade, allowing us to create a checkpointing transaction of constant size. We argue for the security of our protocol and present an open-source implementation that was tested on the Bitcoin testnet.</p>
</div></div>


                <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560829.3563562">Linear View Change in Optimistically Fast BFT</a></h3><ul class="DLauthors"><li class="nameList">Matthieu Rambaud</li><li class="nameList">Andrei Tonkikh</li><li class="nameList Last">Mark Abspoel</li></ul><div class="DLabstract"><div style="display:inline">
<p>To be competitive with centralized applications, consensus protocols in blockchains must provide minimal latency while being able to scale to thousands of participants in order to preserve a high level of decentralization. A common way to minimize latency is to augment a consensus protocol with a <em>fast track,</em> which ensures that a decision is reached in just a couple of message delays in favorable conditions. However, it is a challenging task to preserve safety and good performance when these favorable conditions do not hold. To the best of our knowledge, all existing Byzantine fault-tolerant consensus protocols with fast tracks require view change protocols with quadratic authenticator complexity. In this paper, we provide the first solution to Byzantine consensus with fast track with a linear view change. The protocol incurs no asymptotic overhead over the baseline while reducing the latency in favorable conditions by a factor of 2. Our construction is based on a novel type of cryptographic proofs, which we call <em>Proofs of Exclusivity</em> (or <em>PoE</em> for short), which may be of independent interest. While our protocol for constructing a PoE comes at no extra costs in latency or asymptotic complexities, it does require some extra computation. To make sure that it does not impair the overall performance, we also show how to apply <em>accountability</em> and <em>proofs of misbehavior</em> in order to reduce to zero the overhead incurred by the computation of a PoE. More precisely, our mechanism guarantees that whenever this overhead is not zero, then automatically honest participants obtain a publicly verifiable proof that a well-identified malicious participant openly misbehaved. In this case, the overhead of computing a few extra threshold signatures for the Proof of Exclusivity can be seen as a relatively small price to get rid of a malicious participant.</p>
</div></div>

            </div></div></body></html>
