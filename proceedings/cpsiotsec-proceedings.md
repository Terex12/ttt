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

</style><title>CPSIoTSec'22: Proceedings of the 4th Workshop on CPS &amp; IoT Security and Privacy</title></head><body><div id="DLtoc"><div id="DLheader"><h1>CPSIoTSec'22: Proceedings of the 4th Workshop on CPS &amp; IoT Security and Privacy</h1><a class="DLcitLink" title="Go to the ACM Digital Library for additional information about this proceeding" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/proceedings/10.1145/3560826"><img class="DLlogo" alt="Digital Library logo" height="30" src="https://dl.acm.org/specs/products/acm/releasedAssets/images/footer-logo1.png">
Full Citation in the ACM Digital Library
</a></div><div id="DLcontent"><h2>SESSION: Session 1: Industrial Control and Crypto (graphy, not currency)</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560826.3563380">Security Analysis of Vendor Implementations of the OPC UA Protocol for Industrial Control Systems</a></h3><ul class="DLauthors"><li class="nameList">Alessandro Erba</li><li class="nameList">Anne Müller</li><li class="nameList Last">Nils Ole Tippenhauer</li></ul><div class="DLabstract"><div style="display:inline">
<p>The OPC UA protocol is an upcoming de-facto standard for building Industry 4.0 processes in Europe, and one of the few industrial protocols that promises security features to prevent attackers from manipulating and damaging critical infrastructures. Despite the importance of the protocol, challenges in the adoption of OPC UA's security features by product vendors, libraries implementing the standard, and end-users were not investigated so far. In this work, we systematically investigate 48 publicly available artifacts consisting of products and libraries for OPC UA and show that 38 out of the 48 artifacts have one (or more) security issues. We show that 7 OPC UA artifacts do not support the security features of the protocol at all. In addition, 31 artifacts that partially feature OPC UA security rely on incomplete libraries and come with misleading instructions. Consequently, relying on those products and libraries will result in vulnerable implementations of OPC UA security features. To verify our analysis, we design, implement, and demonstrate attacks in which the attacker can steal credentials exchanged between victims, eavesdrop on process information, manipulate the physical process through sensor values and actuator commands, and prevent the detection of anomalies.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560826.3563385">Single-Server Delegation of Small-Exponent Exponentiation from Quasilinear-Time Clients and Applications</a></h3><ul class="DLauthors"><li class="nameList">Giovanni Di Crescenzo</li><li class="nameList">Matluba Khodjaeva</li><li class="nameList">Rajesh Krishnan</li><li class="nameList Last">David Shur</li></ul><div class="DLabstract"><div style="display:inline">
<p>Motivated by reducing the cost of public-key encryption on resource-constrained devices, we investigate the problem of delegating operations in cryptography schemes from client devices that only perform quasilinear-time or lower-order computations (e.g., modular additions and subtractions, multiplications with a small modulus, etc.) to a single, possibly malicious, server. Almost all of previous work considered clients capable of computing higher-order operations, such as fully homomorphic encryption, group exponentiations or several group multiplications with a large modulus. We show the (first in this model) single-server protocols to efficiently delegate the computation of small-exponent ring exponentiation, while satisfying desirable result correctness, input privacy and result security requirements. Small-exponent exponentiation is part of, for instance, the exponential El Gamal encryption algorithm. The asymptotic improvements in our delegation protocols are also backed up by concrete implementation results, showing that the improvements hold also for parameter values of practical interest. As an application example, we show that our protocols can be used to delegate encryption in the exponential El Gamal public-key cryptosystem, which can in turn be used for confidential transfer of, for instance, the average of multiple data values measured by a group of IoT client devices, with remarkable communication efficiency (i.e., a single public-key encryption ciphertext for each group).</p>
</div></div>

<h2>SESSION: Session 2: Reboots in the air</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560826.3563384">Secure Reboots for Real-Time Cyber-Physical Systems</a></h3><ul class="DLauthors"><li class="nameList">Vijay Banerjee</li><li class="nameList">Sena Hounsinou</li><li class="nameList">Habeeb Olufowobi</li><li class="nameList">Monowar Hasan</li><li class="nameList Last">Gedare Bloom</li></ul><div class="DLabstract"><div style="display:inline">
<p>Cyber-Physical Systems (CPS) such as industrial control systems, automobiles, and medical devices often consist of applications with real-time properties. Due to the safety-critical nature of the application domain, multiple security and fault tolerance approaches have been studied and used in safety-critical CPS. One of the popular approaches for CPS safety is the Simplex architecture, which has also been used recently to strengthen the security of the CPS. The simplex architecture supports the integration of safe controllers for dependable systems, and when combined with periodic restarts, the architecture can reset the CPS into a safe state after each restart. However, these restart-based systems do not protect the system against attacks that persist beyond a restart. Such attacks can be mitigated using secure boot, which is a widely used approach for securing general computing systems but is not used in real-time systems due to the overhead of the boot process. This paper presents an analytical framework and derives feasibility conditions to enable secure reboots in real-time applications. The schedulability conditions presented can be used to design and integrate secure reboot into Simplex-based CPS. Our analysis shows that secure boot adds a deterministic and low-performance overhead, which can be as low as 0.08%.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560826.3563381">RoSym: Robust Symmetric Key Based IoT Software Upgrade Over-the-Air</a></h3><ul class="DLauthors"><li class="nameList">Pegah Nikbakht Bideh</li><li class="nameList Last">Christian Gehrmann</li></ul><div class="DLabstract"><div style="display:inline">
<p>Internet of Things (IoT) firmware upgrade has turned out to be a challenging task with respect to security. While Over-The-Air (OTA) software upgrade possibility is an essential feature to achieve security, it is also most sensitive to attacks and lots of different firmware upgrade attacks have been presented in the literature. Several security solutions exist to tackle these problems. We observe though that most prior art solutions are public key-based, they are not flexible with respect to firmware image distribution principles and it is challenging to make a design with good Denial-Of-Service (DoS) attacks resistance. Apart from often being rather resource demanding, a limitation with current public key-based solutions is that they are not quantum computer resistant. Hence, in this paper, we take a new look into the firmware upgrade problem and propose RoSym, a secure, firmware distribution principle agnostic, and DoS protected upgrade mechanism purely based on symmetric cryptography. We present an experimental evaluation on a real testbed environment for the scheme. The results show that the scheme is efficient in comparison to other state of the art solutions. We also make a formal security verification of RoSym showing that it is robust against different attacks.</p>
</div></div>

<h2>SESSION: Session 3B: Satellites and ML?!</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560826.3563382">Stargaze: A LEO Constellation Emulator for Security Experimentation</a></h3><ul class="DLauthors"><li class="nameList">Patrick Tser Jern Kon</li><li class="nameList">Diogo Barradas</li><li class="nameList Last">Ang Chen</li></ul><div class="DLabstract"><div style="display:inline">
<p>Low-earth orbit (LEO) satellite constellations are a special type of cyber-physical systems. Their meteoric rise has led to the proposition of many novel use cases and applications. Recent research has also highlighted the broad and unique threat landscape afflicting LEO constellations. However, the CPS security community lacks an experimentation platform to thoroughly identify and explore attacks and their corresponding defenses. We report our experience in building such a platform and perform initial case studies.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560826.3563383">CloudPAD: Managed Anomaly Detection for ICS</a></h3><ul class="DLauthors"><li class="nameList">Sanjeev Rao</li><li class="nameList">Majid Ghaderi</li><li class="nameList Last">Hongwen Zhang</li></ul><div class="DLabstract"><div style="display:inline">
<p>Modern attacks on Industrial Control Systems (ICSs) are the result of several colliding circumstances: historically insecure communication protocols, increased ICS connectivity, and the rise of state-sponsored attackers. Extensive research has been conducted on using anomaly detection (AD) to counter this; here, deviations from an ICS's normal operation are monitored to indicate potentially dangerous situations. However, most works either assume an on-site deployment, or focus only on the neural architecture and disregard the deployment environment altogether. For the former, failure to update local AD can result in otherwise preventable attacks going undetected; as for the latter, directly porting these architectures to a cloud deployment can result in stale predictions due to communication delays, timeout-induced gaps in predictions, and surcharges due to bandwidth costs. In this work, we presentCloudPAD, an ICS anomaly detection pipeline that accounts for the issues introduced by an off-premises deployment, which uses theClozeLSTM ---a neural network based on the Long Short-Term Memory (LSTM) architecture---to detect anomalies. We train and test theClozeLSTM on the Secure Water Treatment (SWaT) dataset, and show that it outperforms an advanced attention baseline, with a precision-recall AUC of 0.797 vs. 0.717. We also discuss measures to minimizeCloudPAD 's bandwidth consumption, and show that performance remains competitive with a maximum decrease in PR AUC by 0.01 when running in this mode.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560826.3563386">Real-Time Scheduling of TrustZone-enabled DNN Workloads</a></h3><ul class="DLauthors"><li class="nameList">Mohammad Fakhruddin Babar</li><li class="nameList Last">Monowar Hasan</li></ul><div class="DLabstract"><div style="display:inline">
<p>Limited resources in embedded devices often hinder the execution of computation-heavy machine learning processes. Running deep neural network (DNN) workloads while preserving the integrity of the model parameters and without compromising temporal constraints of real-time applications, is a challenging problem. Although secure enclaves such as ARM TrustZone can ensure the integrity of applications, off-the-shelf implementations are often infeasible for DNN workloads - especially those with real-time requirements - due to additional resource and temporal constraints. This paper presents a real-time scheduling framework that enables the execution of resource-intensive DNN workloads inside TrustZone-enabled secure enclaves. Our approach reduces the resource overhead by fusing multiple layers of multiple tasks and running them all together inside the enclaves while retaining real-time grantees. We derive mathematical conditions that will allow the designer to test the feasibility of deploying DNN workload in a TrustZone-enabled system. Our comparisons with a standard fixed-priority real-time scheduler show that we can schedule up to 21.33% more tasksets in higher utilization (e.g., &gt; 80%) scenarios.</p>
</div></div>

</div></div></body></html>
