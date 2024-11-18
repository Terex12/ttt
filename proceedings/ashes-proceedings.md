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

</style><title>ASHES'22: Proceedings of the 2022 Workshop on Attacks and Solutions in Hardware Security</title></head><body><div id="DLtoc"><div id="DLheader"><h1>ASHES'22: Proceedings of the 2022 Workshop on Attacks and Solutions in Hardware Security</h1><a class="DLcitLink" title="Go to the ACM Digital Library for additional information about this proceeding" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/proceedings/10.1145/3560834"><img class="DLlogo" alt="Digital Library logo" height="30" src="https://dl.acm.org/specs/products/acm/releasedAssets/images/footer-logo1.png">
Full Citation in the ACM Digital Library
</a></div><div id="DLcontent"><h2>SESSION: Keynote Talks</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560834.3563762">Towards Remote Verifiable Computation without Digital Secrets</a></h3><ul class="DLauthors"><li class="nameList Last">Marten van Dijk</li></ul><div class="DLabstract"><div style="display:inline">
<p>The development of secure processor architecture technology has seen many challenges. It turns out difficult to implement efficient resource sharing and at the same time eliminate or protect against side channels as a result of shared caches and other buffers. For this reason, implemented hardware isolation cannot provide confidential computing (as of yet). Nevertheless, the hardware isolation for access control as implemented by micro code and added circuitry cannot be circumvented and this allows for verifiable computation. However, even though computations can be isolated in enclaves, how can we provide remote attestation of computed output? Remote attestation requires digital secrets which may leak due to side channels. We show two puzzle pieces which together can be used to implement remote attestation without secure digital computation or digital secrets: We use a strong PUF for masking "session signing keys' and we use these in a new one-time signature primitive. In essence, computing a signature for an output boils down to directly reading out a signature from unmasked digital storage.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560834.3564147">Automating Cryptographic Code Generation</a></h3><ul class="DLauthors"><li class="nameList Last">Yuval Yarom</li></ul><div class="DLabstract"><div style="display:inline">
<p>Cryptography provides the data protection mechanisms that underly security and privacy in the modern connected world. Given this pivotal role, implementations of cryptographic code must not only be correct, but also meet stringent performance and security requirements. Achieving these aims is often difficult and requires significant investment in software development and manual tuning. This talk presents two approaches for automating the task of generating correct, secure, and efficient cryptographic code. The first, Rosita, uses a power consumption emulator to detect unintended leaky interactions between values in the microarchitecture. It then rewrites the code to eliminate these interactions and produce code that is resistant to power analysis. The second, CryptOpt, uses evolutionary computation to search for the most efficient constant-time implementation of a cryptographic function. It then formally verifies that the produced implementation is semantically equivalent to the original code. Rosita is a joint work with Lejla Batina, Lukasz Chmielewski, Francesco Regazzoni, Niels Samwel, Madura A. Shelton, and Markus Wagner. CryptOpt is a joint work with Adam Chlipala, Chitchanok Chuengsatiansup, Andres Erbsen, Daniel Genkin, Jason Gross, Joel Kuepper, Chuyue Sun, Markus Wagner, and David Wu.</p>
</div></div>

<h2>SESSION: Workshop Full Papers</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560834.3563826">Leveraging Layout-based Effects for Locking Analog ICs</a></h3><ul class="DLauthors"><li class="nameList">Muayad J. Aljafar</li><li class="nameList">Florence Azaïs</li><li class="nameList">Marie-Lise Flottes</li><li class="nameList Last">Samuel Pagliarini</li></ul><div class="DLabstract"><div style="display:inline">
<p>While various obfuscation methods exist in the digital domain, techniques for protecting Intellectual Property (IP) in the analog domain are mostly overlooked. Understandably, analog components have a small footprint as most of the surface of an Integrated Circuit (IC) is digital. Yet, since they are challenging to design and tune, they constitute a valuable IP that ought to be protected. This paper is the first to show a method to secure analog IP by exploiting layout-based effects that are typically seen as undesirable detractors in IC design. Specifically, we make use of the effects of Length of Oxide Diffusion and Well Proximity Effect on transistors for tuning the devices' critical parameters (e.g., gm and Vth). Such parameters are hidden behind key inputs, akin to the logic locking approach for digital ICs. The proposed technique is applied for locking an Operational Transconductance Amplifier. In order to showcase the robustness of the achieved obfuscation, the case studied circuit is simulated for a large number of key sets, i.e., &gt;50K and &gt;300K, and the results show a wide range of degradation in open-loop gain (up to 130dB), phase margin (up to 50 deg), 3dB bandwidth (≈2.5MHz), and power (≈1mW) of the locked circuit when incorrect keys are applied. Our results show the benefit of the technique and the incurred overheads. We also justify the non-effectiveness of reverse engineering efforts for attacking the proposed approach. More importantly, our technique employs only regular transistors and requires neither changes to the IC fabrication process nor any foundry-level coordination or trust.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560834.3563830">SpecDefender: Transient Execution Attack Defender using Performance Counters</a></h3><ul class="DLauthors"><li class="nameList">Amit Choudhari</li><li class="nameList">Sylvain Guilley</li><li class="nameList Last">Khaled Karray</li></ul><div class="DLabstract"><div style="display:inline">
<p>Side-channel attacks based on speculative execution have gained enough traction for researchers. This has resulted in the development of more creative variants of Spectre and its defences. However, many of these defence strategies end up making speculative execution or branch prediction ineffective. While these techniques protect the system, they cut down performance by more than 50%. Hence, these solutions cannot be deployed. In this paper, we present a framework that not only protects against different variants of Spectre but also maintains the performance. We prototyped this framework using a novel tool SpecDefender. It leverages Hardware Performance Counter (HPC) registers to dynamically detect active Spectre attacks and performs dynamic instrumentation to defend against them. This makes the tool widely applicable without any need for static analysis. Overall, the tool brings back the balance between performance and security. The tool was evaluated based on its accuracy and precision to detect an attack in different scenarios. It exhibit &gt;90% precision when five out of ten processes were simultaneously attacked. The response time for the tool to detect is ~2 sec. Furthermore, the throughput of the process under attack was comparable to normal execution in presence of SpecDefender.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560834.3563824">Differential Fault Attack on PHOTON-Beetle</a></h3><ul class="DLauthors"><li class="nameList">Amit Jana</li><li class="nameList Last">Goutam Paul</li></ul><div class="DLabstract"><div style="display:inline">
<p>In this paper, we report the first differential fault attack (DFA) on nonce-based AE scheme PHOTON-BEETLE, which is one of the finalists in the ongoing NIST LwC competition. In general, it is a challenging task to perform DFA for any nonce-based sponge AE because of a unique nonce in the encryption query. However, the decryption procedure (with a fixed nonce) is still susceptible to DFA. We propose two fault attack models, and for both, we give theoretical estimates of the number of faulty queries to get multiple forgeries. Our simulated values corroborate closely the theoretical estimates. Finally, we devise an algorithm to recover the state based on the collected forgeries. Under the random fault attack model, to retrieve the secret key, we need approximately 2^37.15 number of faulty queries. Also, the offline time and memory complexities of this attack are respectively 216 and 210 nibbles. In the known fault attack model, we need around 211.05 number of faulty queries to retrieve the secret key. Also, the time and memory complexities of this state recovery attack are respectively 211 and 29 nibbles. Further, we have reduced the number of faulty queries to 640 under the precise bit-flip fault model.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560834.3563829">Secure FMCW LiDAR Systems with Frequency Encryption</a></h3><ul class="DLauthors"><li class="nameList">Marziyeh Rezaei</li><li class="nameList">Liban Hussein</li><li class="nameList Last">Sajjad Moazeni</li></ul><div class="DLabstract"><div style="display:inline">
<p>Robust and secure ranging is among the most vital capabilities demanded by future autonomous vehicles and robotics for precise navigation and avoiding collisions. Light detection and ranging (LiDAR) is a promising 3D imaging technology for this aim. However, the security vulnerabilities of LiDAR systems can impose critical threats to human safety and security, similar to other types of sensors. While LiDARs are becoming standard technologies for self-driving cars, their security aspects have not yet been studied well so far.</p> <p>In this paper, we will first summarize various security attack scenarios against different LiDAR types. We focus on beam-steering and frequency modulated continuous wave (FMCW) LiDAR systems as they have been considered the most secure LiDAR systems proposed so far. We will show that an attacker can reverse engineer the victim's LiDAR system and build a spoofing system using commercially available electro-optical components. To do so, we will develop an electro-optical co-simulation framework in MATLAB Simulink and use that to study the feasibility of the spoofing attack in today's FMCW LiDAR systems. Finally, we propose the frequency encryption technique as a countermeasure to mitigate the possibility of spoofing FMCW beam-steering LiDAR systems. The proposed approach can ensure the security of future FMCW LiDAR systems without compromising functionality or accuracy.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560834.3563823">Breaking KASLR on Mobile Devices without Any Use of Cache Memory</a></h3><ul class="DLauthors"><li class="nameList">Milad Seddigh</li><li class="nameList">Mahdi Esfahani</li><li class="nameList">Sarani Bhattacharya</li><li class="nameList">Mohammad Reza Aref</li><li class="nameList Last">Hadi Soleimany</li></ul><div class="DLabstract"><div style="display:inline">
<p>Microarchitectural attacks utilize the performance optimization constructs that have been studied over decades in computer architecture research and show the vulnerability of such optimizations in a realistic framework. One such highly performance driven vulnerable construct is speculative execution. In this paper, we focus on the problem of breaking the kernel address-space layout randomization (KASLR) on modern mobile devices without using cache memory as a medium of observation. However, there are some challenges to breaking KASLR on ARM CPUs. The first challenge is that eviction strategies on ARM CPUs are slow, and the microarchitectural attacks exploiting the cache as a covert channel cannot be implemented on modern ARM CPUs. The second challenge is that non-canonical addresses are stored in the store buffer, although they are invalid. As a result, previous microarchitectural attacks distinguish such addresses as valid kernel addresses erroneously.</p> <p>In this paper, we focus on these challenges to close current gaps in the implementation of recent attacks against modern CPUs. We show how a Translation Look-aside Buffer (TLB) can be used to circumvent the cache memory as a covert channel in order to attack ASLR on both ARM and Intel CPUs. To the best of our knowledge, we are the first to break KASLR on ARM-based Android and iOS mobile devices. Furthermore, our attacks can be performed in JavaScript to break KASLR of the browser without the need for an Evict+Reload operation, which consumes a lot of time. The results of our attacks show that the attacker can distinguish whether or not the virtual address is valid in less than 0.0417 seconds and 0.0488 seconds on Android and iOS mobile devices, respectively.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560834.3563827">On-Chip Side-Channel Analysis of the Loop PUF</a></h3><ul class="DLauthors"><li class="nameList">Lars Tebelmann</li><li class="nameList">Moritz Wettermann</li><li class="nameList Last">Michael Pehl</li></ul><div class="DLabstract"><div style="display:inline">
<p>In recent years, Side-Channel Analysis (SCA) that leverages power measurements from peripherals or on-chip power sensors has gained increasing attention. Instead of direct physical access to the victim device, these so-called remote SCA attacks can be mounted if an attacker shares resources on the same Power Distribution Network (PDN), e.g., in a multi-tenant Field Programmable Gate Array (FPGA) cloud scenario. Previous work on remote SCA focused on cryptographic algorithms such as AES and RSA. In this work, we analyze the possibility of on-chip SCA of Physical Unclonable Function (PUF) primitives and compare their efficiency to classical SCA attacks. We target the Loop PUF, that derives entropy from a configurable oscillator, where an attacker can retrieve the secret by observing oscillation frequencies. We employ a Time-to-Digital Converter (TDC) sensor, and compare two Artix-7 FPGAs with different resources to compare differences in the Signal-to-Noise Ratio (SNR). Further, we vary the relative placement of the targeted PUF and the TDC sensor. Even though the number of traces required is increased compared to classical SCA, the experiments illustrate the feasibility of extracting the secret key from a PUF-based storage from on-chip SCA.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560834.3563828">Putting IMT to the Test: Revisiting and Expanding Interval Matching Techniques and their Calibration for SCA</a></h3><ul class="DLauthors"><li class="nameList">Jens Trautmann</li><li class="nameList">Nikolaos Patsiatzis</li><li class="nameList">Andreas Becher</li><li class="nameList">Stefan Wildermann</li><li class="nameList Last">Jürgen Teich</li></ul><div class="DLabstract"><div style="display:inline">
<p>Side-Channel Analysis (SCA) requires the detection of the specific time frame Cryptographic Operations (COs) take place in the side-channel signal. Under laboratory conditions with full control over the Device under Test (DuT), dedicated trigger signals can be implemented to indicate the start and end of COs. For real-world scenarios, waveform-matching techniques have been established which compare the side-channel signal with a template of the CO's pattern in real time to detect the CO in the side channel. State-of-the-Art approaches describe implementations based on Field-Programmable Gate Arrays (FPGAs). However, the maximal length of the template is restricted by the resources available on an FPGAs. Particularly, for high sampling rates the recording of an entire CO may need more samples than the maximum template length supported by a waveform-matching system. Consequently, the template has to be reduced such that it fits the resources while still containing all features relevant for detecting the COs via waveform matching.</p> <p>In this paper, we introduce a generic interval-matching technique which provides several degrees of freedom for fine-tuning it to the statistical deviations of waveform measurements of COs. Moreover, we introduce a novel calibration method that finds the best parameters automatically based on statistical analysis of training data. Furthermore, we investigate a technique to reduce the number of features used for the interval matching by utilizing machine-learning-based feature extraction to find the most important samples in a template.</p> <p>Finally, we evaluate the state-of-the-art interval matching and our expansions during calibration and during the application on a test set. The results show, that a reliable reduction to 10% of the original template size is possible with a reduction method from literature for our example. However, the combination of our proposed methods can reliably work with only 1.5% of the original size and is less volatile than the state-of-the-art approach for reducing the number of features.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560834.3563825">Injecting Permanent Faults into the Flash Memory of a Microcontroller with Laser Illumination During Read Operations</a></h3><ul class="DLauthors"><li class="nameList">Raphael Viera</li><li class="nameList">Jean-Max Dutertre</li><li class="nameList Last">Rodrigo Silva Lima</li></ul><div class="DLabstract"><div style="display:inline">
<p>Microcontrollers embed an integrated Flash memory which has been proven to be vulnerable to certain hardware attacks. The Flash memory stores the microcontroller unit (MCU) firmware and, eventually, security related data such as passwords and cryptographic keys. Recent research works report the use of Laser Fault Injection (LFI) to corrupt the firmware at run time by targeting the Flash memory during its read operations. These faults, induced on a single bit and following a bit-set fault model, are non-permanent: the data stored in the Flash remain unchanged while only their read copies are corrupted. In this work, we report an extension of this model on the Flash memory of a 32-bit MCU. By compromising the stored data during read operations, we are able to induce permanent faults in the Flash memory. Furthermore, by means of a double-spot LFI, we were able to concurrently induce permanent bit-set faults at two distinct locations. We also present an example of a practical application of this fault model by iteratively changing all the 32 bits of a password to logic "1" while defeating a basic counter for login attempts. Physical related limitations of using multi-laser spots are also covered in this work.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560834.3563831">To Be, or Not to Be Stateful: Post-Quantum Secure Boot using Hash-Based Signatures</a></h3><ul class="DLauthors"><li class="nameList">Alexander Wagner</li><li class="nameList">Felix Oberhansl</li><li class="nameList Last">Marc Schink</li></ul><div class="DLabstract"><div style="display:inline">
<p>While research in post-quantum cryptography (PQC) has gained significant momentum, it is only slowly adopted for real-world products. This is largely due to concerns about practicability and maturity. The secure boot process of embedded devices is one scenario where such restraints can result in fundamental security problems. In this work, we present a flexible hardware/software co-design for hash-based signature (HBS) schemes which enables the move to a post-quantum secure boot today. These signature schemes stand out due to their straightforward security proofs and are on the fast track to standardisation. In contrast to previous works, we exploit the performance intensive similarities of the stateful LMS and XMSS schemes as well as the stateless SPHINCS+ scheme. Thus, we enable designers to use a stateful or stateless scheme depending on the constraints of each individual application. To show the feasibility of our approach, we compare our results with hardware accelerated implementations of classical asymmetric algorithms. Further, we lay out the usage of different HBS schemes during the boot process. We compare different schemes, show the importance of parameter choices, and demonstrate the performance gain with different levels of hardware acceleration.</p>
</div></div>

<h2>SESSION: Workshop Short Papers</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560834.3563833">Exposing Side-Channel Leakage of SEAL Homomorphic Encryption Library</a></h3><ul class="DLauthors"><li class="nameList">Furkan Aydin</li><li class="nameList Last">Aydin Aysu</li></ul><div class="DLabstract"><div style="display:inline">
<p>This paper reveals a new side-channel leakage of Microsoft SEAL homomorphic encryption library. The proposed attack exploits the leakage of ternary value assignments made during the Number Theoretic Transform (NTT) sub-routine. Notably, the attack can steal the secret key coefficients from a single power/electromagnetic measurement trace. To achieve high accuracy with a single-trace, we build a novel machine-learning based side-channel profiler. Moreover, we implement a defense based on random delay insertion based defense mechanism to mitigate the shown leakage. The results on an ARM Cortex-M4F processor show that our attack extracts secret key coefficients with 98.3% accuracy and random delay insertion defense does not reduce the success rate of our attack.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560834.3563832">PR Crisis: Analyzing and Fixing Partial Reconfiguration in Multi-Tenant Cloud FPGAs</a></h3><ul class="DLauthors"><li class="nameList">Emre Karabulut</li><li class="nameList">Chandu Yuvarajappa</li><li class="nameList">Mohammed Iliyas Shaik</li><li class="nameList">Seetal Potluri</li><li class="nameList">Amro Awad</li><li class="nameList Last">Aydin Aysu</li></ul><div class="DLabstract"><div style="display:inline">
<p>FPGAs are increasingly being used in cloud systems, mainly due to their performance and energy advantages. Recent FPGAs have a relatively large amount of resources, which enables multi-tenancy and hence improves the utilization and economic value for both the cloud providers and customers. However, the ability to co-locate designs from different tenants requires efficient safeguards and support. Fortunately, the majority of the recent FPGAs, e.g., those from Xilinx (currently AMD), include partial reconfiguration (PR) capabilities which enable partitioning and independently programming the FPGA resources. FPGA's PR capability is considered vital for the temporal and spatial sharing of FPGAs in cloud environments. In this work, we systematically study how the various power profiles for FPGA partitions can impact the process of programming partitions and the overall functionality of the FPGA. Surprisingly, we observe that high power activity in partitions can significantly impact the programming time of other partitions. Even worse, we observe that carefully crafted power viruses can delay (or even) fail the whole PR process, and in some cases cause the shutting down of the whole FPGA. Accordingly, we describe such attacks in detail and discuss how they can impact the availability and timeliness (in the case of real-time workloads) of multi-tenant FPGAs. Finally, we propose a lightweight solution that can effectively detect such abnormal power activities and hence blocks any channels for such attacks before the PR process starts.</p>
</div></div>

</div></div></body></html>
