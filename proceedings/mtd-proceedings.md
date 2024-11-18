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

</style><title>MTD'22: Proceedings of the 9th ACM Workshop on Moving Target Defense</title></head><body><div id="DLtoc"><div id="DLheader"><h1>MTD'22: Proceedings of the 9th ACM Workshop on Moving Target Defense</h1><a class="DLcitLink" title="Go to the ACM Digital Library for additional information about this proceeding" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/proceedings/10.1145/3560828"><img class="DLlogo" alt="Digital Library logo" height="30" src="https://dl.acm.org/specs/products/acm/releasedAssets/images/footer-logo1.png">
Full Citation in the ACM Digital Library
</a></div><div id="DLcontent"><h2>SESSION: Keynote 1</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560828.3564002">Dynamic Security with SDN: Opportunities, Challenges, and Lessons Learned</a></h3><ul class="DLauthors"><li class="nameList Last">Cristina Nita-Rotaru</li></ul><div class="DLabstract"><div style="display:inline">
<p>SDN paradigm to create and enforce dynamic security mechanisms. In the first part of the talk, I will present NetViews [1], a framework to enforce least-privilege network access control policies where each host has a different, limited view of the other hosts and services within a network. Our evaluation shows that NetViews has network latency and throughput comparable to baseline reactive forwarding. Furthermore, an optimization for multi-connection flows significantly reduces both redundant access control checks and forwarding state storage in switches, making NetViews a practical primitive for removing the reliance on security perimeters within enterprise networks.</p> <p>In the second part of the talk, I will describe how SDN can be used to provide a different security service - confidentiality - in an environment where one can not rely on traditional cryptographic building blocks due to the presence of practical quantum computers that will break the computational assumptions made by scheme that rely on discrete logarithm or factorization problems. We designed and implemented a framework based on Multi-path Switching with Secret Sharing (MSSS), a scheme that combines secret sharing with path hoping to achieve provable security under the assumption that the adversary has unbounded computational power but limited observability of the network and limited storage. We showed that schemes like MSSS are feasible, however in the process we uncovered how theoretical assumptions made in order to prove the security of such schemes are not met in practice, due to network side-channel attacks [4] that put at risk the security of the scheme.</p>
</div></div>

<h2>SESSION: Session 1: New Techniques</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560828.3564008">Rave: A Modular and Extensible Framework for Program State Re-Randomization</a></h3><ul class="DLauthors"><li class="nameList">Christopher Blackburn</li><li class="nameList">Xiaoguang Wang</li><li class="nameList Last">Binoy Ravindran</li></ul><div class="DLabstract"><div style="display:inline">
<p>Dynamic software diversification is an effective way to boost software security. Existing diversification-based approaches often target a single node environment and leverage in-process agents to diversify code and data, resulting in an unnecessary attack surface on a fixed software/hardware stack. This paper presents Rave, a practical system designed to enable out-of-bound program state shuffling on a moving target environment, avoiding any sensitive agent code invoked within the running target. Rave relies on a user-space page fault handling mechanism introduced in the latest Linux kernel and seamlessly integrates with CRIU, the battle-tested process migration tool for Linux.</p> <p>Rave consists of two components: librave, a library for static binary analysis and instrumentation, and CRIU-Rave, a runtime that dynamically updates program execution states (e.g., internal stack data layout and the machine node the program runs on). We built a prototype of Rave and evaluated it with four real-world server applications and 13 applications from the SPEC CPU 2017 and the SNU C version of NAS Parallel Benchmarks (NPB) benchmark suites. We demonstrated that Rave can continuously re-randomize the program state (e.g., internal stack layout, instruction sequences, and machine node to run on). The evaluation shows that Rave increases the internal program state entropy with an additional ≈200 ms time overhead for each re-randomization epoch on average.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560828.3564007">Multi-variant Execution at the Edge</a></h3><ul class="DLauthors"><li class="nameList">Javier Cabrera Arteaga</li><li class="nameList">Pierre Laperdrix</li><li class="nameList">Martin Monperrus</li><li class="nameList Last">Benoit Baudry</li></ul><div class="DLabstract"><div style="display:inline">
<p>Edge-Cloud computing offloads parts of the computations that traditionally occurs in the cloud to edge nodes. The binary format WebAssembly is increasingly used to distribute and deploy services on such platforms. Edge-Cloud computing providers let their clients deploy stateless services in the form of WebAssembly binaries, which are then translated to machine code, sandboxed and executed at the edge. In this context, we propose a technique that (i) automatically diversifies WebAssembly binaries that are deployed to the edge and (ii) randomizes execution paths at runtime. Thus, an attacker cannot exploit all edge nodes with the same payload. Given a service, we automatically synthesize functionally equivalent variants for the functions providing the service. All the variants are then wrapped into a single multivariant WebAssembly binary. When the service endpoint is executed, every time a function is invoked, one of its variants is randomly selected. We implement this technique in the MEWE tool and we validate it with 7 services for which MEWE generates multivariant binaries that embed hundreds of function variants. We execute the multivariant binaries on the world-wide edge platform provided by Fastly, as part as a research collaboration. We show that multivariant binaries exhibit a real diversity of execution traces across the whole edge platform distributed around the globe.</p>
</div></div>

<h2>SESSION: Keynote 2</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560828.3564001">The Role of Randomization in Trustworthy Machine Learning</a></h3><ul class="DLauthors"><li class="nameList Last">Nicolas Papernot</li></ul><div class="DLabstract"><div style="display:inline">
<p>Machine learning has been perhaps this decade's most significant technological development, with the prospect of becoming a general-purpose technology. Applications range from autonomous driving to assisting with court decisions. In many of these settings, the worst-case performance of machine learning is critical. Yet, the predictions of machine learning often appear fragile, with no hint as to the reasoning behind them-and may be dangerously wrong. This situation is in large part due to the absence of security considerations in the design of machine learning algorithms. This is unacceptable: society must be able to trust and hold machine learning accountable. </p> <p>One direction that has been proposed to develop more trustworthy ML algorithms is the introduction of randomization. In this keynote, we contrast the success of randomized algorithms for privacy-preserving learning with failed applications of randomization to develop more robust machine learning models. From this comparison, we identify best practices for the research community, moving forward, as it continues to research the role of randomization in trustworthy machine learning.</p>
</div></div>

<h2>SESSION: Session 2: Insights and Lessons Learned</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560828.3564010">Hardware Moving Target Defenses against Physical Attacks: Design Challenges and Opportunities</a></h3><ul class="DLauthors"><li class="nameList">David S. Koblah</li><li class="nameList">Fatemeh Ganji</li><li class="nameList">Domenic Forte</li><li class="nameList Last">Shahin Tajik</li></ul><div class="DLabstract"><div style="display:inline">
<p>The concept of moving target defense (MTD) has entrenched itself as a viable strategy to reverse the typical asymmetries in cyber warfare. MTDs are technologies that seek to make target systems dynamically change in order to limit the time and information available to complete an attack, increase the likelihood of detection, and/or deter attackers from proceeding. The benefits of MTD have been shown for network-, operating system-, and application-level security. Hardware roots-of-trust, however, are static "sitting ducks", especially against physical attacks, and can therefore benefit from the dynamics brought about by MTDs. Although many MTD concepts seem transferable to hardware applications, there has hardly been any work to establish a functioning research pipeline for countermeasures to physical attacks. The aim of this paper is to introduce viable MTD concepts, describe the issues that they can address, and chart a path towards their realization for the community.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560828.3564016">On Randomization in MTD Systems</a></h3><ul class="DLauthors"><li class="nameList">Majid Ghaderi</li><li class="nameList">Samuel Jero</li><li class="nameList">Cristina Nita-Rotaru</li><li class="nameList Last">Reihaneh Safavi-Naini</li></ul><div class="DLabstract"><div style="display:inline">
<p>Randomization is one of the main strategies in providing security in moving-target-defense (MTD) systems. However, randomization has an associated cost and estimating this cost and its impact on the overall system is crucial to ensure adoption of the MTD strategy. In this paper we discuss our experience in attempting to estimate the cost of path randomization in a message transmission system that used randomization of paths in the network. Our conclusions are (i) the cost crucially depends on the underlying network control technology, (ii) one can reduce this cost by better implementation, and (iii) reducing one type of cost may result in increased costs of a different type, for example a higher device cost. These suggest that estimating the cost of randomization is a multivariable optimization problem that requires a full understanding of the system components.</p>
</div></div>

<h2>SESSION: Session 3: Analysis and Evaluation</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560828.3564006">Evaluating Deception and Moving Target Defense with Network Attack Simulation</a></h3><ul class="DLauthors"><li class="nameList">Daniel Reti</li><li class="nameList">Daniel Fraunholz</li><li class="nameList">Karina Elzer</li><li class="nameList">Daniel Schneider</li><li class="nameList Last">Hans Dieter Schotten</li></ul><div class="DLabstract"><div style="display:inline">
<p>In the field of network security, with the ongoing arms race between attackers, seeking new vulnerabilities to bypass defense mechanisms and defenders reinforcing their prevention, detection and response strategies, the novel concept of cyber deception has emerged. Starting from the well-known example of honeypots, many other deception strategies have been developed such as honeytokens and moving target defense, all sharing the objective of creating uncertainty for attackers and increasing the chance for the attacker of making mistakes. In this paper a methodology to evaluate the effectiveness of honeypots and moving target defense in a network is presented. This methodology allows to quantitatively measure the effectiveness in a simulation environment, allowing to make recommendations on how many honeypots to deploy and on how quickly network addresses have to be mutated to effectively disrupt an attack in multiple network and attacker configurations. With this optimum, attacks can be detected and slowed down with a minimal resource and configuration overhead. With the provided methodology, the optimal number of honeypots to be deployed and the optimal network address mutation interval can be determined. Furthermore, this work provides guidance on how to optimally deploy and configure them with respect to the attacker model and several network parameters.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560828.3564009">Reasoning about Moving Target Defense in Attack Modeling Formalisms</a></h3><ul class="DLauthors"><li class="nameList">Gabriel Ballot</li><li class="nameList">Vadim Malvone</li><li class="nameList">Jean Leneutre</li><li class="nameList Last">Etienne Borde</li></ul><div class="DLabstract"><div style="display:inline">
<p>Since 2009, Moving Target Defense (MTD) has become a new paradigm of defensive mechanism that frequently changes the state of the target system to confuse the attacker. This frequent change is costly and leads to a trade-off between misleading the attacker and disrupting the quality of service. Optimizing the MTD activation frequency is necessary to develop this defense mechanism when facing realistic, multi-step attack scenarios. Attack modeling formalisms based on DAG are prominently used to specify these scenarios. Our contribution is a new DAG-based formalism for MTDs and its translation into a Price Timed Markov Decision Process to find the best activation frequencies against the attacker's time/cost optimal strategies. For the first time, MTD activation frequencies are analyzed in a state-of-the-art DAG-based representation. Moreover, this is the first paper that considers the specificity of MTDs in the automatic analysis of attack modeling formalisms. Finally, we present some experimental results using Uppaal Stratego to demonstrate its applicability and relevance.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560828.3563995">Game Theory Approaches for Evaluating the Deception-based Moving Target Defense</a></h3><ul class="DLauthors"><li class="nameList">Duohe Ma</li><li class="nameList">Zhimin Tang</li><li class="nameList">Xiaoyan Sun</li><li class="nameList">Lu Guo</li><li class="nameList">Liming Wang</li><li class="nameList Last">Kai Chen</li></ul><div class="DLabstract"><div style="display:inline">
<p>Moving target defense (MTD) is a proactive defensive mechanism proposed to disrupt and disable potential attacks, thus reversing the defender's disadvantages. Cyber deception is a complementary technique that is often used to enhance MTD by utilizing misinformation to deceive and mislead attackers. Deception elements, such as honeypot, honey bait, honey token, breadcrumb, and well-constructed deception scenes, can significantly increase the uncertainties for attackers. Deception-based MTD techniques can change the asymmetry situation between defenders and attackers through affecting the attacker's perception of the system. However, there is still a lack of understanding about the role of cyber deception in MTD, and few research works have evaluated the effectiveness of cyber deception.</p> <p>In this paper, we propose a concept of deception attack surface to illustrate deception-based moving target defense. Moreover, we propose a quantitative method to measure deception, which includes two core concepts: exposed falseness degree and hidden truth degree. We further formulate a deception game model between an attacker and a defender, in which the defender attempts to protect the entry points on the attack surface by creating or changing a deception attack surface. Furthermore, we provide a detailed example scenario and analyze the deception game's equilibrium. Finally We verify the effectiveness of our proposed method through a real attack and defense experiment.</p>
</div></div>

</div></div></body></html>
