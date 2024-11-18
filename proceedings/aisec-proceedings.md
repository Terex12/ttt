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

</style><title>AISec'22: Proceedings of the 15th ACM Workshop on Artificial Intelligence and Security</title></head><body><div id="DLtoc"><div id="DLheader"><h1>AISec'22: Proceedings of the 15th ACM Workshop on Artificial Intelligence and Security</h1><a class="DLcitLink" title="Go to the ACM Digital Library for additional information about this proceeding" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/proceedings/10.1145/3560830"><img class="DLlogo" alt="Digital Library logo" height="30" src="https://dl.acm.org/specs/products/acm/releasedAssets/images/footer-logo1.png">
    Full Citation in the ACM Digital Library
</a></div><div id="DLcontent"><h2>SESSION: Session 1: Privacy-Preserving Machine Learning</h2>
            <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560830.3563734">Label-Only Membership Inference Attack against Node-Level Graph Neural Networks</a></h3><ul class="DLauthors"><li class="nameList">Mauro Conti</li><li class="nameList">Jiaxin Li</li><li class="nameList">Stjepan Picek</li><li class="nameList Last">Jing Xu</li></ul><div class="DLabstract"><div style="display:inline">
<p>Graph Neural Networks (GNNs), inspired by Convolutional Neural Networks (CNNs), aggregate the message of nodes' neighbors and structure information to acquire expressive representations of nodes for node classification, graph classification, and link prediction. Previous studies have indicated that node-level GNNs are vulnerable to Membership Inference Attacks (MIAs), which infer whether a node is in the training data of GNNs and leak the node's private information, like the patient's disease history. The implementation of previous MIAs takes advantage of the models' probability output, which is infeasible if GNNs only provide the prediction label (label-only) for the input.</p> <p>In this paper, we propose a label-only MIA against GNNs for node classification with the help of GNNs' flexible prediction mechanism, e.g., obtaining the prediction label of one node even when neighbors' information is unavailable. Our attacking method achieves around 60% accuracy, precision, and Area Under the Curve (AUC) for most datasets and GNN models, some of which are competitive or even better than state-of-the-art probability-based MIAs implemented under our environment and settings. Additionally, we analyze the influence of the sampling method, model selection approach, and overfitting level on the attack performance of our label-only MIA. All of those three factors have an impact on the attack performance. Then, we consider scenarios where assumptions about the adversary's additional dataset (shadow dataset) and extra information about the target model are relaxed. Even in those scenarios, our label-only MIA achieves a better attack performance in most cases. Finally, we explore the effectiveness of possible defenses, including Dropout, Regularization, Normalization, and Jumping knowledge. None of those four defenses prevent our attack completely.</p>
</div></div>


            <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560830.3563721">Repeated Knowledge Distillation with Confidence Masking to Mitigate Membership Inference Attacks</a></h3><ul class="DLauthors"><li class="nameList">Federico Mazzone</li><li class="nameList">Leander van den Heuvel</li><li class="nameList">Maximilian Huber</li><li class="nameList">Cristian Verdecchia</li><li class="nameList">Maarten Everts</li><li class="nameList">Florian Hahn</li><li class="nameList Last">Andreas Peter</li></ul><div class="DLabstract"><div style="display:inline">
<p>Machine learning models are often trained on sensitive data, such as medical records or bank transactions, posing high privacy risks. In fact, membership inference attacks can use the model parameters or predictions to determine whether a given data point was part of the training set. One of the most promising mitigations in literature is Knowledge Distillation (KD). This mitigation consists of first training a teacher model on the sensitive private dataset, and then transferring the teacher knowledge to a student model, by the mean of a surrogate dataset. The student model is then deployed in place of the teacher model. Unfortunately, KD on its own does not provide users much flexibility, meant as the possibility to arbitrarily decide how much utility to sacrifice to get membership-privacy. To address this problem, we propose a novel approach that combines KD with confidence score masking. Concretely, we repeat the distillation procedure multiple times in series and, during each distillation, perturb the teacher predictions using confidence masking techniques. We show that our solution provides more flexibility than standard KD, as it allows users to tune the number of distillation rounds and the strength of the masking function. We implement our approach in a tool, RepKD, and assess our mitigation against white- and black-box attacks on multiple models and datasets. Even when the surrogate dataset is different from the private one (which we believe to be a more realistic setting than is commonly found in literature), our mitigation is able to make the black-box attack completely ineffective and significantly reduce the accuracy of the white-box attack at the cost of only 0.6% test accuracy loss.</p>
</div></div>


            <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560830.3563731">Forgeability and Membership Inference Attacks</a></h3><ul class="DLauthors"><li class="nameList">Zhifeng Kong</li><li class="nameList">Amrita Roy Chowdhury</li><li class="nameList Last">Kamalika Chaudhuri</li></ul><div class="DLabstract"><div style="display:inline">
<p>A membership inference (MI) attack predicts whether a data point was used for training a machine learning (ML) model. MI attacks are currently the most widely deployed attack for auditing privacy of a ML model. A recent work by Thudi et. al. [18] show that approximate machine unlearning is ill-defined. For this, they introduce the notion of forgeability where using forged datasets, one could unlearn without modifying the model at all. In this paper, we show a connection between machine unlearning and membership inferencing. Specifically, we study how to leverage forgeability to repudiate claims on membership inferencing. We show that the ability to forge enables the dataset owner to construct a Proof-of-Repudiation (PoR) which empowers the dataset owner to plausibly repudiate the predictions of an MI attack. This casts a doubt on the reliability of MI attacks in practice. Our empirical evaluations show that it is possible to construct PoRs efficiently.</p>
</div></div>


            <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560830.3563729">PROV-FL: Privacy-preserving Round Optimal Verifiable Federated Learning</a></h3><ul class="DLauthors"><li class="nameList">Vishnu Asutosh Dasu</li><li class="nameList">Sumanta Sarkar</li><li class="nameList Last">Kalikinkar Mandal</li></ul><div class="DLabstract"><div style="display:inline">
<p>Federated learning is a distributed framework where a server computes a global model by aggregating the local models trained on users' private data. However, for a stronger data privacy guarantee, the server should not access the local models except the aggregated one. One way to achieve this is to use a secure aggregation protocol that comes with the cost of several rounds of interactions between the server and users in the absence of a fully trusted third party (TTP). In this paper, we present PROV-FL, an efficient privacy-preserving federated learning training system that securely aggregates users' local models. PROV-FL requires only one round of communication between the server and users for aggregating local models without a TTP. Based on the homomorphic encryption and differential privacy techniques, we develop two PROV-FL training protocols for two different, namely single and multi-aggregator, scenarios. PROV-FL enjoys the verifiability feature in which the server can verify the authenticity of the aggregated model and efficiently handles users' dynamic joining and leaving. We evaluate and compare the performance of PROV-FL by running experiments on training CNN/DNN models with a diverse set of real-world datasets.</p>
</div></div>


            <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560830.3563725">Inferring Class-Label Distribution in Federated Learning</a></h3><ul class="DLauthors"><li class="nameList">Raksha Ramakrishna</li><li class="nameList Last">György Dán</li></ul><div class="DLabstract"><div style="display:inline">
<p>Federated Learning (FL) has become a popular distributed learning method for training classifiers by using data that are private to individual clients. The clients´ data are typically assumed to be confidential, but their heterogeneity and potential class-imbalance adversely impact the accuracy of the trained model. The class-imbalance may not be common knowledge or may even be confidential information itself. Thus, the inference of the class-label distribution of the training data is important both from a performance and from a privacy perspective. In this paper, we study the problem of class-label distribution inference from an adversarial perspective, based on model parameter updates sent to the parameter server. Firstly, we present conditions under which exact inference is possible. We then introduce four new methods to estimate class-label distribution in the general FL setting. We evaluate the proposed inference methods on four different datasets and our results show that they significantly outperform state of the art methods.</p>
</div></div>

        <h2>SESSION: Session 2A: Adversarial Machine Learning</h2>
            <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560830.3563722">Video is All You Need: Attacking PPG-based Biometric Authentication</a></h3><ul class="DLauthors"><li class="nameList">Lin Li</li><li class="nameList">Chao Chen</li><li class="nameList">Lei Pan</li><li class="nameList">Jun Zhang</li><li class="nameList Last">Yang Xiang</li></ul><div class="DLabstract"><div style="display:inline">
<p>Unobservable physiological signals enhance biometric authentication systems. Photoplethysmography (PPG) signals are convenient owing to its ease of measurement and are usually well protected against remote adversaries in authentication. Any leaked PPG signals help adversaries compromise the biometric authentication systems, and the advent of remote PPG (rPPG) enables adversaries to acquire PPG signals through restoration. While potentially dangerous, rPPG-based attacks are overlooked because existing methods require the victim's PPG signals. This paper proposes a novel spoofing attack approach that uses the waveforms of rPPG signals extracted from video clips to fool the PPG-based biometric authentication. We develop a new PPG restoration model to accomplish adversarial attacks without leaked PPG signals. Empirical study results on state-of-art PPG-based biometric authentication show that the signals recovered through rPPG pose a severe threat to PPG-based biometric authentication.</p>
</div></div>


            <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560830.3563723">Magnitude Adversarial Spectrum Search-based Black-box Attack against Image Classification</a></h3><ul class="DLauthors"><li class="nameList">Kim A. B. Midtlid</li><li class="nameList">Johannes Åsheim</li><li class="nameList Last">Jingyue Li</li></ul><div class="DLabstract"><div style="display:inline">
<p>Recent development has revealed that deep neural networks used in image classification systems are vulnerable to adversarial attacks. Thus, it is critical to understand the possible adversarial attacks to develop effective defense mechanisms. In this study, we designed an untargeted query-efficient decision-based black-box attack against image classification models that produce imperceptible adversarial examples. The proposed attack method, MASSA, includes two novel components to generate the initial noise and reduce the noise in the frequency domain. The evaluation results show that MASSA requires significantly fewer queries than the state-of-the-art decision-based black-box attack, i.e., HSJA. In addition, MASSA can create adversarial examples with 74,16% lower L2 distance than HSJA after only 250 queries. We also demonstrate that two existing defense mechanisms, namely, JPEG compression and adversarial training, are ineffective in defending against MASSA. Results of the study give new insights into the potential risks of using deep neural networks in critical systems and encourage the community to study improved defense approaches to mitigate the risks.</p>
</div></div>

        <h2>SESSION: Session 2B: Adversarial Machine Learning</h2>
            <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560830.3563733">Assessing the Impact of Transformations on Physical Adversarial Attacks</a></h3><ul class="DLauthors"><li class="nameList">Paul Andrei Sava</li><li class="nameList">Jan-Philipp Schulze</li><li class="nameList">Philip Sperl</li><li class="nameList Last">Konstantin Böttinger</li></ul><div class="DLabstract"><div style="display:inline">
<p>The decision of neural networks is easily shifted at an attacker's will by so-called adversarial attacks. Initially only successful when directly applied to the input, recent advances allow attacks to breach the digital realm, leading to over-the-air physical adversarial attacks. During training, some physical phenomena are simulated through equivalent transformations to increase the attack's success. In our work, we evaluate the impact of the selected transformations on the performance of physical adversarial attacks. We quantify their performance across diverse attack scenarios, e.g., multiple distances and angles. Our evaluation motivates that some transformations are indeed essential for successful attacks, no matter the target class. These also appear to be responsible for creating shapes within the attacks, which are semantically related to the target class. However, they do not ensure physical robustness alone. The choice of the remaining transformations appears to be context-dependent, e.g., some being more advantageous for long-range attacks, but not for close-range ones. With our findings, we not only provide useful information on generating physical adversarial attacks, but also help research on defenses to understand their weaknesses.</p>
</div></div>


            <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560830.3563730">Just Rotate it: Deploying Backdoor Attacks via Rotation Transformation</a></h3><ul class="DLauthors"><li class="nameList">Tong Wu</li><li class="nameList">Tianhao Wang</li><li class="nameList">Vikash Sehwag</li><li class="nameList">Saeed Mahloujifar</li><li class="nameList Last">Prateek Mittal</li></ul><div class="DLabstract"><div style="display:inline">
<p>Recent works have demonstrated that deep learning models are vulnerable to backdoor poisoning attacks, where these attacks instill spurious correlations to external trigger patterns or objects (e.g., stickers, sunglasses, etc.). We find that such external trigger signals are not necessary, as highly effective backdoors can be easily inserted using rotation-based image transformation. Our method constructs the poisoned dataset by rotating a limited amount of objects and labeling them incorrectly; once trained with it, the victim's model will make undesirable predictions during run-time inference. It exhibits a significantly high attack success rate while maintaining clean performance through comprehensive empirical studies on image classification and object detection tasks. Furthermore, we evaluate standard data augmentation techniques and five different backdoor defenses against our attack and find that none of them can serve as a consistent mitigation approach. Our attack can be easily deployed in the real world since it only requires rotating the object, as shown in both image classification and object detection applications. Overall, our work highlights a new, simple, physically realizable, and highly effective vector for backdoor attacks. Our video demo is available at <a href="https://youtu.be/6JIF8wnX34M">https://youtu.be/6JIF8wnX34M</a></p>
</div></div>


            <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560830.3563727">Proactive Detection of Query-based Adversarial Scenarios in NLP Systems</a></h3><ul class="DLauthors"><li class="nameList">Mohammad Maghsoudimehrabani</li><li class="nameList">Amin Azmoodeh</li><li class="nameList">Ali Dehghantanha</li><li class="nameList">Behrouz Zolfaghari</li><li class="nameList Last">Gautam Srivastava</li></ul><div class="DLabstract"><div style="display:inline">
<p>Adversarial attacks can mislead a Deep Learning (DL) algorithm into generating erroneous predictions via feeding maliciously-disturbed inputs called adversarial examples. DL-based Natural Language Processing (NLP) algorithms are severely threatened by adversarial attacks. In real-world, black-box adversarial attacks, the adversary needs to submit many highly-similar queries before drafting an adversarial example. Due to this long process, in-progress attack detection can play a significant role in adversarial defense in DL-based NLP algorithms. Although there are several approaches for detecting adversarial attacks in NLP, these approaches are reactive in the sense that they can detect adversarial examples only when they are fabricated and fed into the algorithm. In this study, we take one step towards proactive detection of adversarial attacks in NLP systems by proposing a robust, history-based model named Stateful Query Analysis (SQA) to identify suspiciously-similar sequences of queries capable of generating textual adversarial examples to which we refer by adversarial scenarios. The model exhibits a detection rate of over 99.9% in our extensive experimental tests against several state-of-the-art black-box adversarial attack methods.</p>
</div></div>

        <h2>SESSION: Session 3: Machine Learning for Cybersecurity</h2>
            <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560830.3563728">Context-Based Clustering to Mitigate Phishing Attacks</a></h3><ul class="DLauthors"><li class="nameList">Tarini Saka</li><li class="nameList">Kami Vaniea</li><li class="nameList Last">Nadin Kökciyan</li></ul><div class="DLabstract"><div style="display:inline">
<p>Phishing is by far the most common and disruptive type of cyber-attack faced by most organizations. Phishing messages may share common attributes such as the same or similar subject lines, the same sending infrastructure, similar URLs with certain parts slightly varied, and so on. Attackers use such strategies to evade sophisticated email filters, increasing the difficulty for computing support teams to identify and block all incoming emails during a phishing attack. Limited work has been done on grouping human-reported phishing emails, based on the underlying scam, to help the computing support teams better defend organizations from phishing attacks. In this paper, we explore the feasibility of using unsupervised clustering techniques to group emails into scams that could ideally be addressed together. We use a combination of contextual and semantic features extracted from emails and perform a comparative study on three clustering algorithms with varying feature sets. We use a range of internal and external validation methods to evaluate the clustering results on real-world email datasets. Our results show that unsupervised clustering is a promising approach for scam identification and grouping, and analyzing reported phishing emails is an effective way of mitigating phishing attacks and utilizing the human perspective.</p>
</div></div>


            <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560830.3563726">Quo Vadis: Hybrid Machine Learning Meta-Model Based on Contextual and Behavioral Malware Representations</a></h3><ul class="DLauthors"><li class="nameList Last">Dmitrijs Trizna</li></ul><div class="DLabstract"><div style="display:inline">
<p>We propose a hybrid machine learning architecture that simultaneously employs multiple deep learning models analyzing contextual and behavioral characteristics of Windows portable executable, producing a final prediction based on a decision from the meta-model. The detection heuristic in contemporary machine learning Windows malware classifiers is typically based on the static properties of the sample since dynamic analysis through virtualization is challenging for vast quantities of samples. To surpass this limitation, we employ a Windows kernel emulation that allows the acquisition of behavioral patterns across large corpora with minimal temporal and computational costs. We partner with a security vendor for a collection of more than 100k int-the-wild samples that resemble the contemporary threat landscape, containing raw PE files and filepaths of applications at the moment of execution. The acquired dataset is at least ten folds larger than reported in related works on behavioral malware analysis. Files in the training dataset are labeled by a professional threat intelligence team, utilizing manual and automated reverse engineering tools. We estimate the hybrid classifier's operational utility by collecting an out-of-sample test set three months later from the acquisition of the training set. We report an improved detection rate, above the capabilities of the current state-of-the-art model, especially under low false-positive requirements. Additionally, we uncover a meta-model's ability to identify malicious activity in both validation and test sets even if none of the individual models express enough confidence to mark the sample as malevolent. We conclude that the meta-model can learn patterns typical to malicious samples out of representation combinations produced by different analysis techniques. Furthermore, we publicly release pre-trained models and anonymized dataset of emulation reports.</p>
</div></div>


            <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560830.3563724">Optimising Vulnerability Triage in DAST with Deep Learning</a></h3><ul class="DLauthors"><li class="nameList">Stuart Millar</li><li class="nameList">Denis Podgurskii</li><li class="nameList">Dan Kuykendall</li><li class="nameList">Jesús Martínez del Rincón</li><li class="nameList Last">Paul Miller</li></ul><div class="DLabstract"><div style="display:inline">
<p>False positives generated by vulnerability scanners are an industry-wide challenge in web application security. Accordingly, this paper presents a novel multi-view deep learning architecture to optimise Dynamic Application Security Testing (DAST) vulnerability triage, with task-specific design decisions exploiting the structure of traffic exchanges between our rules-based DAST scanner and a given web app. Leveraging convolutional neural networks, natural language processing and word embeddings, our model learns separate yet complementary internal feature representations of these exchanges before fusing them together to make a prediction of a verified vulnerability or a false positive. Given the amount of time and cognitive effort required to constantly manually review high volumes of DAST results correctly, the addition of this deep learning capability to a rules-based scanner creates a hybrid system that enables expert analysts to rank scan results, deprioritise false positives and concentrate on likely real vulnerabilities. This improves productivity and reduces remediation time, resulting in stronger security postures. Evaluations are conducted on a real-world dataset containing 91,324 findings of 74 different vulnerability types curated from DAST scans on nineteen organisations. Results show our multi-view architecture significantly reduces both the false positive rate by 20% and the false negative rate by 40% on average across all organisations compared to the single-view approach.</p>
</div></div>


            <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560830.3563732">Bridging Automated to Autonomous Cyber Defense: Foundational Analysis of Tabular Q-Learning</a></h3><ul class="DLauthors"><li class="nameList">Andy Applebaum</li><li class="nameList">Camron Dennler</li><li class="nameList">Patrick Dwyer</li><li class="nameList">Marina Moskowitz</li><li class="nameList">Harold Nguyen</li><li class="nameList">Nicole Nichols</li><li class="nameList">Nicole Park</li><li class="nameList">Paul Rachwalski</li><li class="nameList">Frank Rau</li><li class="nameList">Adrian Webster</li><li class="nameList Last">Melody Wolk</li></ul><div class="DLabstract"><div style="display:inline">
<p>Leveraging security automation and orchestration technologies enables security analysts to respond more quickly and accurately to threats. However, current tooling is limited to automating very finely scoped and hand-coded situations, such as quarantining known malware and blocking traffic from known malicious domains. Recent research has sought to bridge the gap between this kind of automated security and autonomous cyber defense, leveraging reinforcement learning (RL) on top of basic automation to enable intelligent response. This paper provides foundational analysis of autonomous agents trained with Tabular Q-Learning through a series of experiments examining a range of network scenarios. Our results demonstrate that off-the-shelf Tabular Q-Learning does not offer a single, superior solution across all scenarios. However, we also find that modifying the underlying state encoding and update function can influence the robustness of the defensive agent to generalize to unseen evaluation environments without a significant loss in accuracy. These results highlight potential optimizations for more advanced RL techniques as well as provide a baseline for others leveraging RL for defensive cyber automation.</p>
</div></div>

</div></div></body></html>
