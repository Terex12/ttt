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

</style><title>CCSW'22: Proceedings of the 2022 on Cloud Computing Security Workshop</title></head><body><div id="DLtoc"><div id="DLheader"><h1>CCSW'22: Proceedings of the 2022 on Cloud Computing Security Workshop</h1><a class="DLcitLink" title="Go to the ACM Digital Library for additional information about this proceeding" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/proceedings/10.1145/3560810"><img class="DLlogo" alt="Digital Library logo" height="30" src="https://dl.acm.org/specs/products/acm/releasedAssets/images/footer-logo1.png">
Full Citation in the ACM Digital Library
</a></div><div id="DLcontent"><h2>SESSION: Keynote Talks</h2>
<h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560810.3565289">Cryptographic Protection of Random Access Memory: How Inconspicuous can Hardening Against the most Powerful Adversaries be?</a></h3><ul class="DLauthors"><li class="nameList Last">Roberto Avanzi</li></ul><div class="DLabstract"><div style="display:inline">
<p>For both cloud and client applications, the protection of the confidentiality and integrity of remotely processed information is an increasingly common feature request. It is also a very challenging goal to achieve with reasonable costs in terms of memory overhead and performance penalty. In turn, this usually leads to security posture compromises in products. In this keynote we review the main technologies that have been proposed so far to solve this problem, as well as some new techniques and combinations thereof. We systematise the treatment of protecting data in use by starting with models of the adversaries, thus allowing us to define different, yet consistent protection levels. We perform a systematic evaluation of the storage and performance impacts, including the impact on systems where the measured benchmarks are the only running tasks and where they are just one task in a cloud server under full load. Using advanced techniques to compress counters can make it viable to store them on-chip -- for instance by adding on chip RAM that can be as small as to 1/256-th of the off-chip RAM. This allows for implementations of memory protection up to anti-replay with hitherto unattained penalties, especially in combination with the repurposing of ECC bits to store integrity tags. The performance penalty on a memory bandwidth saturated server can thus be contained to under 1%. This keynote is based on joint work with Ionut Mihalcea, David Schall, and Andreas Sandberg, and includes previous work with Matthias Boettcher, Mike Campbell, Hector Montaner, and Prakash Ramrakhyani.</p>
</div></div>


<h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560810.3565290">Intel HERACLES: Homomorphic Encryption Revolutionary Accelerator with Correctness for Learning-oriented End-to-End Solutions</a></h3><ul class="DLauthors"><li class="nameList Last">Rosario Cammarota</li></ul><div class="DLabstract"><div style="display:inline">
<p>In spite strong advances in confidential computing technologies to protect data, the status is that data is encrypted while temporarily not in use and unencrypted during computation. The inability to keep data encrypted during computation can inhibit the ability to fully share and extract the maximum value out of data, e.g., via statistical and machine learning methods with the additional risk of third-party data leakage. Fully Homomorphic Encryption (FHE) enables users to delegate computation to the cloud by enabling the cloud to process users' encrypted inputs without decryption and return encrypted output to the intended recipients. The adoption of FHE by the industry has been slow. First, processing encrypted data incurs a huge performance tax even for simple operations - ciphertexts operations can be several orders of magnitude slower with respect to cleartext operations on existing hardware. Second, there is lack of automation tools for translating data and applications to enable FHE. Third, there is lack of standards and best practices for FHE secure deployment in combination with other confidential computing techniques. The DARPA DPRIVE program [1] is the first publicly visible program aiming to build a platform to accelerate FHE and a path to their commercialization, for their use in healthcare, communication (5G to XG), and cloud computing. The program represents a steppingstone toward FHE adoption. Under the DARPA DPRIVE program, Intel® is designing a new type of computer architecture to reduce the performance tax currently associated with FHE. Intel® collaborates with Microsoft® Azure Global in realization of the project [2]. The design includes flexible arithmetic circuits for algebraic lattices with unprecedented vector parallelism and data transfer capacity between vector slots, to increase ciphertext processing speed, coupled with near-memory computation, to reduce data movement. The software stack leverages the Microsoft® SEAL library [3] augmented the BGV mechanism including bootstrapping [4], and automatic translation tools to explore trade-offs in algorithmic optimization and data encoding to fit the performance requirements [5]. When fully realized, the HERACLES platform will deliver a massive improvement in executing FHE workloads over existing CPU-driven systems, potentially reducing ciphertext processing time by five orders of magnitude. Beyond the new hardware and software stack, Intel® work with international standard bodies to develop standards for and best practices for FHE secure deployment [6] and invests in academic research to advance both theory and application [7].</p>
</div></div>


<h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560810.3565288">Byzantine Fault Tolerance in the Age of Blockchains and Cloud Computing</a></h3><ul class="DLauthors"><li class="nameList Last">Haibin Zhang</li></ul><div class="DLabstract"><div style="display:inline">
<p>BFT is a generic technique used for ordering transactions on a distributed system even if a fraction of the processes are controlled by a malicious adversary. BFT is widely known as the model for permissioned blockchains, and is increasingly used in various permissionless blockchains. BFT has also been used in various cloud computing scenarios, such as blockchain-as-a-service, the multi-cloud scenario, and their fault-tolerant components.</p> <p>It is widely believed that there is no one-size-fits-all BFT protocol. We review and discuss some recent results on BFT protocols, covering both partially synchronous BFT protocols and completely asynchronous BFT protocols, and covering their building blocks (e.g., reliable broadcast, Byzantine agreement).</p>
</div></div>


<h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560810.3560852">Multi-Tenant Cloud FPGAs: Side-Channel Security and Safety</a></h3><ul class="DLauthors"><li class="nameList Last">Aydin Aysu</li></ul><div class="DLabstract"><div style="display:inline">
<p>FPGAs are increasingly being used in cloud systems, mainly due to their performance and energy advantages. Recent FPGAs have a relatively large amount of resources, which enables multi-tenancy and hence improves the utilization and economic value for both the cloud providers and customers. However, the ability to co-locate designs from different tenants requires efficient safeguards and support. In this talk, I will explore security and safety issues related to multi-tenant cloud FPGA. Specifically, I will describe recent work on remote physical side-channel attacks and power safety issues, and how to mitigate them for next-generation cloud infrastructure.</p>
</div></div>

<h2>SESSION: Workshop Presentations</h2>
<h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560810.3564266">Contextualizing System Calls in Containers for Anomaly-Based Intrusion Detection</a></h3><ul class="DLauthors"><li class="nameList">Asbat El Khairi</li><li class="nameList">Marco Caselli</li><li class="nameList">Christian Knierim</li><li class="nameList">Andreas Peter</li><li class="nameList Last">Andrea Continella</li></ul><div class="DLabstract"><div style="display:inline">
<p>Container technology has gained ground in the industry for its scalability and lightweight virtualization, especially in cloud environments. Nevertheless, research has shown that containerized applications are an appealing target for cyberattacks, which may lead to interruption of business-critical services and financial damage. State-of-the-art anomaly-based host intrusion detection systems (HIDS) may enhance container runtime security. However, they were not designed to deal with the characteristics of containerized environments. Specifically, they cannot effectively cope with the scalability of containers and the diversity of anomalies. To address these challenges, we introduce a novel anomaly-based HIDS that relies on monitoring heterogeneous properties of system calls. Our key idea is that anomalies can be accurately detected when those properties are examined jointly within their context. To this end, we model system calls leveraging a graph-based structure that emphasizes their dependencies within their relative context, allowing us to precisely discern between normal and malicious activities. We evaluate our approach on two datasets of 20 different attack scenarios containing 11,700 normal and 1,980 attack system call traces. The achieved results show that our solution effectively detects various anomalies with reasonable runtime overhead, outperforming state-of-the-art tools.</p>
</div></div>


<h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560810.3564265">Mitigating Threats Emerging from the Interaction between SDN Apps and SDN (Configuration) Datastore</a></h3><ul class="DLauthors"><li class="nameList">Sana Habib</li><li class="nameList">Tiffany Bao</li><li class="nameList">Yan Shoshitaishvili</li><li class="nameList Last">Adam Doupé</li></ul><div class="DLabstract"><div style="display:inline">
<p>Software-defined networking (SDN) has established itself in networking and standardization efforts are under way to strengthen the next generation of this essential technology. The Network Management Datastore Architecture (NMDA), RFC 8342, is the notable achievement in this regard, which standardizes the two vital SDN datastores: configuration and operational. Even though the configuration datastore itself has been standardized, the guidelines for addressing its security as well as safeguarding interactions between SDN apps and SDN configuration datastore are hazy, which leaves room for security vulnerabilities. Both industry and academia have realized the threats that arise due to the interactions between SDN apps and the SDN configuration datastore. But, to date only partial solutions exist for the problem. In this paper, we focus on mitigating such threats by proposing four security design principles that we believe should be uniformly used across all SDN platforms: (i) authentication (of SDN apps), (ii) authorization (of SDN apps), (iii) accountability (of SDN apps), (iv) real-time conflict detection and resolution of configuration rules (belonging to the same/different SDN app/s). Based on these four security design principles, we develop and present a prototype implementation of the \foo\space framework, an open-source vendor independent system for ensuring secure interactions between SDN apps-SDN configuration datastore. We then evaluate the security of the \foo\space framework using two datasets: (i) real-world complicated cases of rule conflicts, (ii) 50,000+ real-world configuration (attack) rules. Our experiments reveal that the \foo\space system mitigates the threats that emerge from SDN apps-SDN configuration datastore interactions with a one-time latency of \approx7ms for the insertion of 50,000^\textth rule in the configuration datastore.</p>
</div></div>


<h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560810.3564263">A Verifiable Multiparty Computation Solver for the Linear Assignment Problem: And Applications to Air Traffic Management</a></h3><ul class="DLauthors"><li class="nameList">Thomas Loruenser</li><li class="nameList">Florian Wohner</li><li class="nameList Last">Stephan Krenn</li></ul><div class="DLabstract"><div style="display:inline">
<p>The assignment problem is an essential problem in many application fields and frequently used to optimize resource usage. The problem is well understood and various efficient algorithms exist to solve the problem. However, it was unclear what practical performance could be achieved for privacy-preserving implementations based on multiparty computation (MPC) by leveraging more efficient solution strategies than MPC-based generic simplex solvers for linear programs. We solve this question by implementing and comparing different optimized MPC algorithms to solve the assignment problem for reasonable problem sizes. Our empirical approach revealed various insights to MPC-based optimization and we measured a significant (50x) speed-up compared to the known simplex-based approach. Furthermore, we also study the overhead introduced by making the results publicly verifiable by means of non-interactive zero-knowledge proofs. By leveraging modern proof systems we also achieve significant speed-up for proof and verification times compared to the previously proposed approaches as well as compact proof sizes. Our research was motivated by a real-world use case, based on detailed discussions with representative stakeholders from the aviation industry.</p>
</div></div>


<h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560810.3564267">On Matrix Multiplication with Homomorphic Encryption</a></h3><ul class="DLauthors"><li class="nameList">Panagiotis Rizomiliotis</li><li class="nameList Last">Aikaterini Triakosia</li></ul><div class="DLabstract"><div style="display:inline">
<p>Homomorphic Encryption (HE) is one of the main cryptographic tools used to enable secure computation outsourcing. Data is outsourced encrypted to an untrusted service provider and remain encrypted during processing. In the last decade, the performance of HE schemes has impressively improved up to several orders of magnitude thanks to advances in the theory and to more efficient implementations. However, it is still significantly slower than plaintext computations, while realizing HE-based computations is complex for the non-expert. Matrix multiplication is a fundamental computation for a variety of applications that are offered as a service, like machine learning model inference. The matrices are HE encrypted and they are outsourced to an untrusted computation environment. In order to improve the performance of HE schemes, several matrices are encoded in a single ciphertext, known also as message packing. However, a single ciphertext usually has several thousands of slots, and, it is common many of these slots to remain empty due to lack of data. In this work, we introduce a secure matrix multiplication outsourcing method that takes advantage of the message packing, when the available matrix entries are very few, i.e. when several ciphertext slots remain empty. We evaluate the complexity of our proposal in terms of basic homomorphic encryption operations and we compute the multiplicative depth of the corresponding arithmetic circuit. Finally, we implement our multiplication algorithm using the CKKS HE scheme, as it is supported in the MS SEAL library.</p>
</div></div>


<h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560810.3564264">Detecting Anomalous Misconfigurations in AWS Identity and Access Management Policies</a></h3><ul class="DLauthors"><li class="nameList">Thijs van Ede</li><li class="nameList">Niek Khasuntsev</li><li class="nameList">Bas Steen</li><li class="nameList Last">Andrea Continella</li></ul><div class="DLabstract"><div style="display:inline">
<p>In recent years, misconfigurations of cloud services have led to major security incidents and large-scale data breaches. Due to the dynamic and complex nature of cloud environments, misconfigured (e.g., overly permissive) access policies can be easily introduced and often go undetected for a long period of time. Therefore, it is critical to identify any potential misconfigurations before they can be abused. In this paper, we present a novel misconfiguration detection approach for identity and access management policies in AWS. We base our approach on the observation that policies can be modeled as permissions between entities and objects in the form of a graph. Our key idea is that misconfigurations can be effectively detected as anomalies in such a graph representation. We evaluate our approach on real-world identity and access management policy data from three enterprise cloud environments. We investigate the effectiveness of our approach to detect misconfigurations, showing that it has a slightly lower precision compared to rule-based systems, but it is able to correctly detect between 3.7 and 6.4 times as many misconfigurations.</p>
</div></div>

</div></div></body></html>
