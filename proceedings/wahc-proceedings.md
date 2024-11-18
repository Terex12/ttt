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

</style><title>WAHC'22: Proceedings of the 10th Workshop on Encrypted Computing &amp; Applied Homomorphic Cryptography</title></head><body><div id="DLtoc"><div id="DLheader"><h1>WAHC'22: Proceedings of the 10th Workshop on Encrypted Computing &amp; Applied Homomorphic Cryptography</h1><a class="DLcitLink" title="Go to the ACM Digital Library for additional information about this proceeding" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/proceedings/10.1145/3560827"><img class="DLlogo" alt="Digital Library logo" height="30" src="https://dl.acm.org/specs/products/acm/releasedAssets/images/footer-logo1.png">
Full Citation in the ACM Digital Library
</a></div><div id="DLcontent"><h2>SESSION: Full length papers I</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560827.3563376">Liberating TFHE: Programmable Bootstrapping with General Quotient Polynomials</a></h3><ul class="DLauthors"><li class="nameList">Marc Joye</li><li class="nameList Last">Michael Walter</li></ul><div class="DLabstract"><div style="display:inline">
<p>All known instantiations for fully homomorphic encryption (FHE) produce noisy ciphertexts and rely on a technique called bootstrapping to reduce the noise so as to enable an arbitrary number of homomorphic operations. Bootstrapping is the main performance bottleneck and arguably the biggest obstacle to widespread adoption of FHE. Among the FHE schemes, TFHE and its variations present the appealing property of having a bootstrapping procedure---as well as its extension to programmable bootstrapping---that is relatively light-weight. The essential operations consist of a series of multiplications in (Z/qZ)[X]/(X^N+1). While the NTT is seemingly the natural candidate for evaluating these multiplications in a fast and exact way, it restricts the possible choices for and . To the authors' knowledge, all current implementations of TFHE with a power of two actually employ the FFT over the complex numbers instead. This introduces real numbers to the otherwise purely discrete algorithms, including all the drawbacks of the need to approximate them using finite precision. This work studies the avenues available to apply the NTT in the context of TFHE-like schemes. In particular, it considers various combinations of coefficient rings and quotient polynomials that are compatible with the requirements of the underlying scheme. Importantly, this work provides methods for adapting the (programmable) bootstrapping to quotient polynomials beyond power-of-two cyclotomics. As a side effect, it also demonstrates how this may enhance the programmability of the bootstrapping.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560827.3563378">Efficient Homomorphic Evaluation of Arbitrary Bivariate Integer Functions</a></h3><ul class="DLauthors"><li class="nameList">Daisuke Maeda</li><li class="nameList">Koki Morimura</li><li class="nameList Last">Takashi Nishide</li></ul><div class="DLabstract"><div style="display:inline">
<p>We propose how to homomorphically evaluate arbitrary bivariate integer functions such as division. A prior work proposed by Okada et al.\ (WISTP'18) uses polynomial evaluations such that the scheme is still compatible with the SIMD operations in BFV and BGV, and is implemented with the input domain size \mathbbZ _257 . However, the scheme of Okada et al.\ requires the quadratic number of plaintext-ciphertext multiplications and ciphertext-ciphertext additions in the input domain size, and although these operations are more lightweight than the ciphertext-ciphertext multiplication, the quadratic complexity makes handling larger inputs quite inefficient. In this work, first we improve the prior work and also propose a new approach that exploits the packing method to handle the larger input domain size instead of enabling the SIMD operation, thus making it possible to work with the larger input domain size, e.g., \mathbbZ _2^15 in a reasonably efficient way. In addition, we show how to extend the input domain size to \mathbbZ _2^16 with a relatively moderate overhead. We implement the prior work of Okada et al., our improved scheme of Okada et al., and our new scheme in PALISADE with the input domain size \mathbbZ _2^15 , and confirm that the estimated run-times of the prior work and our improved scheme of the prior work are still about 117 days and 59 days respectively while our new scheme can be computed in 307 seconds.</p>
</div></div>

<h2>SESSION: Full length papers II</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560827.3563377">PROBONITE: PRivate One-Branch-Only Non-Interactive decision Tree Evaluation</a></h3><ul class="DLauthors"><li class="nameList">Sofiane Azogagh</li><li class="nameList">Victor Delfour</li><li class="nameList">Sébastien Gambs</li><li class="nameList Last">Marc-Olivier Killijian</li></ul><div class="DLabstract"><div style="display:inline">
<p>Decision trees are among the most widespread machine learning models used for data classification, in particular due to their interpretability that makes it easy to explain their prediction. In this paper, we propose a novel protocol for the private classification of a client request in a non-interactive manner. In contrast to existing solutions to this problem, which are either interactive or require evaluating all the branches of the decision tree, our approach only evaluates a single branch of the tree. Our protocol is based on two primitives that we also introduce in this paper and that may be of independent interest : Blind Node Selection and Blind Array Access. Those contributions are based on recent advances in homomorphic cryptography, such as the functional bootstrapping mechanism recently proposed for the Fully Homomorphic Encryption over the Torus scheme TFHE. Our private decision tree evaluation algorithm is highly efficient as it requires only one round of communication and d comparisons, with d being the depth of the tree, while other state-of-the-art non-interactive protocols need 2^d comparisons.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560827.3563375">Efficient and Accurate Homomorphic Comparisons</a></h3><ul class="DLauthors"><li class="nameList">Olive Chakraborty</li><li class="nameList Last">Martin Zuber</li></ul><div class="DLabstract"><div style="display:inline">
<p>We design and implement a new efficient and accurate fully homomorphic argmin/min or argmax/max comparison operator, which finds its application in numerous real-world use cases as a classifier. In particular we propose two versions of our algorithms using different tools from TFHE's functional bootstrapping toolkit. Our algorithm scales to any number of input data points with linear time complexity and logarithmic noise-propagation. Our algorithm is the fastest on the market for non-parallel comparisons with a high degree of accuracy and precision. For MNIST and SVHN datasets, which work under the PATE framework, using our algorithm, we achieve an accuracy of around 99.95% for both.</p>
</div></div>

<h2>SESSION: Short papers</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560827.3563374">Acceleration of Homomorphic Unrolled Trace-Type Function using AVX512 instructions</a></h3><ul class="DLauthors"><li class="nameList">Kotaro Inoue</li><li class="nameList">Takuya Suzuki</li><li class="nameList Last">Hayato Yamana</li></ul><div class="DLabstract"><div style="display:inline">
<p>More and more data analysis is being outsourced due to the spread of cloud computing. Therefore, protection of the data from privacy violations and information leaks is required. In particular, homomorphic encryption, which allows computation to be performed with encrypted data, is being actively studied as one of the protection method. Ring learning with errors based homomorphic encryption schemes support packing which allows to pack several elements into slots of a plaintext and ciphertext. A trace-type function, which combines shifting slots (rotation) and homomorphic addition to obtain summation of slots, is often used in homomorphic encryption applications and acceleration of the trace-type function is important. In this paper, we further accelerate the trace-type function using Intel AVX512 compared to existing optimized trace-type function with loop unrolling. The results show that our AVX512 version was 1.05-2.30 times speedup compared to the non-AVX512 version.</p>
</div></div>

<h2>SESSION: Demo &amp; Working Session</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560827.3563379">OpenFHE: Open-Source Fully Homomorphic Encryption Library</a></h3><ul class="DLauthors"><li class="nameList">Ahmad Al Badawi</li><li class="nameList">Jack Bates</li><li class="nameList">Flavio Bergamaschi</li><li class="nameList">David Bruce Cousins</li><li class="nameList">Saroja Erabelli</li><li class="nameList">Nicholas Genise</li><li class="nameList">Shai Halevi</li><li class="nameList">Hamish Hunt</li><li class="nameList">Andrey Kim</li><li class="nameList">Yongwoo Lee</li><li class="nameList">Zeyu Liu</li><li class="nameList">Daniele Micciancio</li><li class="nameList">Ian Quah</li><li class="nameList">Yuriy Polyakov</li><li class="nameList">Saraswathy R.V.</li><li class="nameList">Kurt Rohloff</li><li class="nameList">Jonathan Saylor</li><li class="nameList">Dmitriy Suponitsky</li><li class="nameList">Matthew Triplett</li><li class="nameList">Vinod Vaikuntanathan</li><li class="nameList Last">Vincent Zucca</li></ul><div class="DLabstract"><div style="display:inline">
<p>Fully Homomorphic Encryption (FHE) is a powerful cryptographic primitive that enables performing computations over encrypted data without having access to the secret key. We introduce OpenFHE, a new open-source FHE software library that incorporates selected design ideas from prior FHE projects, such as PALISADE, HElib, and HEAAN, and includes several new design concepts and ideas. The main new design features can be summarized as follows: (1) we assume from the very beginning that all implemented FHE schemes will support bootstrapping and scheme switching; (2) OpenFHE supports multiple hardware acceleration backends using a standard Hardware Abstraction Layer (HAL); (3) OpenFHE includes both user-friendly modes, where all maintenance operations, such as modulus switching, key switching, and bootstrapping, are automatically invoked by the library, and compiler-friendly modes, where an external compiler makes these decisions. This paper focuses on high-level description of OpenFHE design, and the reader is pointed to external OpenFHE references for a more detailed/technical description of the software library.</p>
</div></div>

</div></div></body></html>
