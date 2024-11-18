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

</style><title>Checkmate '22: Proceedings of the 2022 ACM Workshop on Research on offensive and defensive techniques in the context of Man At The End (MATE) attacks</title></head><body><div id="DLtoc"><div id="DLheader"><h1>Checkmate '22: Proceedings of the 2022 ACM Workshop on Research on offensive and defensive techniques in the context of Man At The End (MATE) attacks</h1><a class="DLcitLink" title="Go to the ACM Digital Library for additional information about this proceeding" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/proceedings/10.1145/3560831"><img class="DLlogo" alt="Digital Library logo" height="30" src="https://dl.acm.org/specs/products/acm/releasedAssets/images/footer-logo1.png">
Full Citation in the ACM Digital Library
</a></div><div id="DLcontent"><h2>SESSION: Session 1: Software Protection &amp; Analysis</h2>
    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560831.3564257">ApkDiff: Matching Android App Versions Based on Class Structure</a></h3><ul class="DLauthors"><li class="nameList">Robbe De Ghein</li><li class="nameList">Bert Abrath</li><li class="nameList">Bjorn De Sutter</li><li class="nameList Last">Bart Coppens</li></ul><div class="DLabstract"><div style="display:inline">
<p>Reverse engineering an application requires attackers to invest time and effort doing manual and automatic analyses. When a new version of the application is released, this investment could be lost completely, if all the analyses had to be re-done. The gained insights into how an application functions might be transferred from one version to the next, however, if the versions do not differ too much. Diffing tools are thus valuable to reverse engineers attempting to transfer their knowledge across versions, as well as to defenders trying to assess this attack vector, and whether or how much a new version has to be diversified. While such diffing tools exist and are in widespread use for binary applications, they are in short supply for Android apps.</p> <p>This paper presents ApkDiff, a tool for diffing Android apps based on the semantic features of the class structure. To evaluate our tool we selected 20 popular financial apps available in the Google Play Store, and tracked their version updates over eight months. We found that on average 79% of all classes had a unique match across version updates. When we consider only classes for which we detect explicit obfuscations being applied (by applying heuristics on their identifiers), we still find that we can find a match for 56% of the classes (ranging from 23% to 85%), suggesting that these obfuscated apps are not resilient to our matching strategies. Our results suggest that ApkDiff provides a valuable approach to diffing Android apps.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560831.3564258">Program Synthesis-based Simplification of MBA Obfuscated Malware with Restart Strategies</a></h3><ul class="DLauthors"><li class="nameList">Seoyeon Kang</li><li class="nameList">Jeongwoo Kim</li><li class="nameList">Eun-Sun Cho</li><li class="nameList Last">Seokwoo Choi</li></ul><div class="DLabstract"><div style="display:inline">
<p>Program obfuscation is one of the frequently used methods to make malware hard to analyze. Among the various obfuscation techniques, Mixed Boolean-Arithmetic (MBA) obfuscation, which mixes arithmetic and Boolean operations in an expression, is often considered hard to solve. Recently, synthesis-based methods have emerged to simplify MBA-obfuscated expressions. However, despite promising results, they still have limitations. Fortunately, recent work in super optimization shows that stochastic synthesis is generally sped up by a proper restart strategy. We adopt this principle to enhance the performance of existing works. Experimental results show that we would achieve improvement in the rate of correct answers and better length reduction.</p>
</div></div>


    <h3><a class="DLtitleLink" title="Full Citation in the ACM Digital Library" referrerpolicy="no-referrer-when-downgrade" href="https://dl.acm.org/doi/10.1145/3560831.3564256">Efficient Deobfuscation of Linear Mixed Boolean-Arithmetic Expressions</a></h3><ul class="DLauthors"><li class="nameList">Benjamin Reichenwallner</li><li class="nameList Last">Peter Meerwald-Stadler</li></ul><div class="DLabstract"><div style="display:inline">
<p>Mixed Boolean-Arithmetic (MBA) expressions are frequently used for obfuscation. As they combine arithmetic as well as Boolean operations, neither arithmetic laws nor transformation rules for logical formulas can be applied to suitably complex expressions, making MBAs hard to simplify and solve.</p> <p>In 2019, Liu et al. demystified linear MBAs, leveraging a transformation between the set <em>B</em>={0, 1} of bit values and the set <em>B<sup>n</sup></em> of words of length <em>n</em>∊N for linear MBAs, originally introduced by Zhou et al. in 2007. With their <em>MBA-Blast</em> and <em>MBA-Solver</em> algorithms, they outperform existing tools noticably in terms of performance as well as ability to simplify of such MBAs.</p> <p>We propose a surprisingly simple algorithm called <em>SiMBA</em> that improves upon MBA-Blast and MBA-Solver in that it can deobfuscate all linear MBAs, does not miss particularly simple solutions and takes only a fraction of their runtime.</p>
</div></div>

</div></div></body></html>
