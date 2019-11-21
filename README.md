Haruo Suzuki (haruo[at]g-language[dot]org)  
Last Update: 2019-10

----------

# Codon usage

## Table of Contents
- [featuring](#featuring)
- [updates](#updates)
[2019](#2019)
[2018](#2018)
[2017](#2017)
[2016](#2016)
[2001](#2001)
- [review](#review)
- [book](#book)
- [video](#video)
- [heterologous gene expression](#heterologous-gene-expression)
- [tRNA](#trna)
- [tRNA gene cluster](#trna-gene-cluster)
- [lifestyle](#lifestyle) ライフスタイル
- [mge](#mge)
  - [plasmids](#plasmids)
  - [virus](#virus)
- [metagenome](#metagenome)
- [temperature](#temperature) 温度
- [replication](#replication) 複製
- [people](#people)
[Ikemura](#ikemura)
[Kanaya](#kanaya)
[Musto](#musto)
[Olsen](#olsen)
[Rocha](#rocha)
[Sharp](#sharp)
[Supek](#supek)
[Suzuki](#suzuki)
- [unclassified](#unclassified)
- [japanese](#japanese) 日本語
- [synthetic_biology](#synthetic_biology)
- [database](#database)
- [tools](#tools)
  - [R](#r)
- [methods](#methods)
  - [RSCU](#rscu)
- [chi square test](#chi-square-test) カイ二乗検定
- [growth rate](#growth-rate) 増殖速度
- [translational selection](#translational-selection) 翻訳選択
- [gene expression](#gene-expression) 遺伝子の発現量
- [optimal codon](#optimal-codon) 適合コドン / 最適コドン

----------

- https://ja.wikipedia.org/wiki/コドン
- http://bioinfo.ie.niigata-u.ac.jp/?遺伝子発現量予測
- http://bioinfo.ie.niigata-u.ac.jp/?コドン組成に基づくBLSOM解析
- http://www.g-language.org/wiki/restgenomeanalysisjapanese#コドン使用の解析
- https://github.com/haruosuz/DS4GD/blob/master/2019/CaseStudy.md#codon-usage
- https://github.com/haruosuz/DS4GD/blob/master/2018giga/CaseStudy.md#codon-usage
- https://github.com/haruosuz/DS4GD/blob/master/2018/CaseStudy.md#codon-usage

----------
## chi square test
https://ja.wikipedia.org/wiki/カイ二乗検定

Switches in Genomic GC Content Drive Shifts of Optimal Codons under Sustained Selection on Synonymous Sites.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5629928/
Codons used significantly more or less frequently in the highly expressed gene data set compared with the whole genome data set (chi-squared test, cutoff P = 0.01) were defined as optimal (+) and nonoptimal (−) codons according to the Ribosomal Protein (RP) method.

Predicting gene expression level from codon usage bias
https://academic.oup.com/mbe/article/24/1/10/1070854#supplementary-data
Codons occurring at significantly higher frequencies (P<5%) in the High dataset are in bold; significance was assessed by chi squared tests within synonym sets, using a sequential Bonferroni approach (Rice 1989) to overcome the problem of multiple tests. These 18 codons (for 15 amino acids) are inferred to be the translationally optimal codons.

Synonymous codon usage in Pseudomonas aeruginosa PA01.
https://www.sciencedirect.com/science/article/pii/S0378111902005036?via%3Dihub
Codon usage in the two data sets (Table 2) was compared using chi square tests, with the sequential Bonferroni correction (Rice, 1989) to assess significance. Sixteen codons, for 12 amino acids, were identified as significantly (P , 0:05) more frequent in the High data set.

Synonymous Codon Usage Analysis of Thirty Two Mycobacteriophage Genomes
https://www.hindawi.com/journals/abi/2009/316936/
To estimate the codon usage variation between these two sets of genes we have performed Chi square tests taking as significant criterion.

----------
## growth rate
増殖速度
## translational selection
翻訳選択
## gene expression
遺伝子の発現量

https://ja.wikipedia.org/wiki/コドン
コドン出現頻度の違いは遺伝子の発現量やそのコドンに対応する tRNA の量と関係があることが知られている。発現量の多い遺伝子のコドン出現頻度の偏りは大きくなり、頻出するコドンに対応する tRNA は細胞内の存在量も多い。

http://bioinfo.ie.niigata-u.ac.jp/?遺伝子発現量予測
1. Z1軸の性質は長浜バイオ大学　池村淑道教授が整理した最適コドン決定規則 (tRNA量に基づいた翻訳効率と関わる最適コドンの決定法, 表1) により説明することができます[1-2,10-12]。したがって、最適コドン決定規則を用いることにより、情報科学的解析のみで種固有の最適コドンを推定することができる。
2. リボソーム蛋白質遺伝子および翻訳伸長因子といういわゆる細胞内で常に発現量が高いと仮定される遺伝子のコドン使用が生物全体の遺伝子のコドン使用とは異なっていることがZ1軸における遺伝子の分布により観察することができた。

https://www.nig.ac.jp/museum/evolution/04_c.html
遺伝暗号(コドン）使用の種による多様性
2.単細胞微生物のコドン選択の生物種による方言;
　 大腸菌とサルモネラ菌ならびに酵母遺伝子に見られるコドン選択の偏りを例に
c)　同一生物種の遺伝子間を比較した場合、多量にタンパク質を生産する遺伝子ほど方言がきつく、生産量が下がるにつれて、同質の方言を用いながらも、その方言の程度が緩くなります。図4では、生物ごとに、タンパク質生産量の高い遺伝子を左側に配置してあります。大腸菌のtufAB(ポリペプチド鎖延長因子)、ompC(外膜タンパク質)は多量にタンパク質を生産する遺伝子の例であり、trpやthrはアミノ酸合成系の遺伝子で、通常条件下では中程度ないしは少量のタンパク質しか生産していません。酵母のG3PDHやenolaseは解糖系の酵素で、最も多量に生産されるタンパク質であり、TRPやCYCは中程度ないしは比較的少量しか生産されない例に属します。生産量の高い遺伝子ほどコドン選択の偏りが顕著で(方言がきつい)、生産量の低い遺伝子では偏りの程度が緩くなります。この傾向は広範囲の遺伝子で成立することが判明しています。

http://www.g-language.org/wiki/restgenomeanalysisjapanese#コドン使用の解析
- 遺伝子発現量の予測
- 翻訳選択 (Translational selection) の検出
- コドン使用データの多変量解析

https://www.ncbi.nlm.nih.gov/pubmed/18940873
DNA Res. 2008 Dec;15(6):357-65. doi: 10.1093/dnares/dsn028. Epub 2008 Oct 21.
Comparison of correspondence analysis methods for synonymous codon usage in bacteria.
Suzuki H1, Brown CJ, Forney LJ, Top EM.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2608848/
- Thirdly, genes expressed at high levels in fast-growing bacteria tend to preferentially use translationally optimal codons that are recognized by the most abundant tRNAs. This presumably reflects natural selection for synonymous codons that are translated more efficiently and accurately.7,8 
- Secondly, to analyze the correlation between scores of each of the three axes [Equation (4)] and levels of gene expression (Expression), we tested for the distribution of the axis scores for 40 genes expected to be expressed constitutively at high levels.10 This set included the genes encoding translation elongation factors Tu (tuf), Ts (tsf) and G (fus), and 37 of the larger ribosomal proteins (encoded by genes rplA-rplF, rplI-rplT, and rpsB-rpsT). In each axis, the score for each gene was standardized by subtracting the mean and dividing by the standard deviation of scores for all protein genes. For each axis, Expression was detected as the main source of variation among genes on the axis when the mean absolute standard score for the 40 highly expressed genes was >1.644854 (an interval in which theoretically only 5% of all protein genes are included).
- The third feature, Expression, was detected as a major source of synonymous codon usage variation among genes in C. trachomatis D/UW-3/CX, C. perfringens 13, E. coli K12 MG1655 and H. influenzae Rd KW20, which is consistent with previous findings (Table 2).

----------
## optimal codon
適合コドン / 最適コドン

http://bioinfo.ie.niigata-u.ac.jp/?遺伝子発現量予測
表1　翻訳過程による最適コドン決定規則
規則1:コドン使用は細胞内のtRNA量による制約を受ける。最適コドンは、細胞内に多量に含まれるtRNAのアンチコドンと対応する。

https://www.nig.ac.jp/museum/evolution/04_d.html
遺伝暗号(コドン）使用の種による多様性
3.コドン使用とtRNA量との関係、遺伝子工学との係り

規則 1)　1種類のアミノ酸にアンチコドンの異なる複数種類のisoaccepting tRNAが存在する場合、最大量tRNAの解読するコドンが好まれる。

我々のグループは、規則1ー3を総合して導かれる翻訳能率を最適化すると推定されるコドンを、適合コドン(optimal codon)と呼んでいます。

https://en.wikipedia.org/wiki/Codon_usage_bias
Optimal codons in fast-growing microorganisms, like Escherichia coli or Saccharomyces cerevisiae (baker's yeast), reflect the composition of their respective genomic transfer RNA (tRNA) pool.[2] It is thought that optimal codons help to achieve faster translation rates and high accuracy.

Sun et al. (2017) における「optimal codons」と「abundant codons」の定義
Switches in Genomic GC Content Drive Shifts of Optimal Codons under Sustained Selection on Synonymous Sites.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5629928/
- We define optimal codons as codons that evolve under selection for translational efficiency in the highly expressed genes, and abundant codons as codons used at high frequency in the majority of genes. 
- We defined optimal codons as codons that were significantly more abundant in the RP than in the WG data set, irrespectively of their actual frequencies. Thus, it should be noted that both highly abundant (major) and lowly abundant (minor) codons might be considered optimal.

最適コドンと準最適コドン（the primary and secondary optimal codons）
https://www.ncbi.nlm.nih.gov/pubmed/23315666
DNA Res. 2013 Apr;20(2):135-50. doi: 10.1093/dnares/dss039. Epub 2013 Jan 11.
Evaluation of codon biology in citrus and Poncirus trifoliata based on genomic features and frame corrected expressed sequence tags.
Ahmad T1, Sablok G, Tatarinova TV, Xu Q, Deng XX, Guo WW.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3628444/
We further observed that for most amino acids with 2- to 6-fold degeneracy level, there has been a general preference for the usage of two or more codons as optimal codons. For example, in Glycine, two highly distributed optimal codons GGA and GGT were identified and they could be classified as the primary and secondary optimal codons preferentially based on the RSCU (GGA, ∼1.16 and GGT, ∼1.09). 


https://www.ncbi.nlm.nih.gov/pubmed/17038449
Mol Biol Evol. 2007 Jan;24(1):10-2. Epub 2006 Oct 12.
Predicting gene expression level from codon usage bias.
Henry I, Sharp PM.
https://academic.oup.com/mbe/article/24/1/10/1070854
Translationally optimal codons can be identified as those best recognized by the most abundant tRNAs, and the frequency of these codons in a gene is highly correlated with gene expression level (Post and Nomura 1980; Ikemura 1981; Gouy and Gautier 1982). 

https://www.ncbi.nlm.nih.gov/pubmed/6175758
J Mol Biol. 1981 Sep 25;151(3):389-409.
Correlation between the abundance of Escherichia coli transfer RNAs and the occurrence of the respective codons in its protein genes: a proposal for a synonymous codon choice that is optimal for the E. coli translational system.
Ikemura T.
https://www.sciencedirect.com/science/article/pii/0022283681900036
The synonymous codon predicted in this way to be the most preferred codon was thought to be optimized for the E. coli translational system and designated as the “Optimal codon”. E. coli genes encoding abundant protein species use the optimal codons selectively, and other E. coli genes, such as amino acid synthesizing genes, use optimal and “non-optimal” codons to a roughly equal degree. 

https://www.ncbi.nlm.nih.gov/pubmed/6167728
J Mol Biol. 1981 Feb 15;146(1):1-21.
Correlation between the abundance of Escherichia coli transfer RNAs and the occurrence of the respective codons in its protein genes.
Ikemura T.

----------
## book
本

### 2018-11-21
![](https://ars.els-cdn.com/content/image/3-s2.0-C20180021659-cov200h.gif)

Multivariate Analyses of Codon Usage Biases - 1st Edition
https://www.sciencedirect.com/book/9781785482960/multivariate-analyses-of-codon-usage-biases
https://www.elsevier.com/books/multivariate-analyses-of-codon-usage-biases/lobry/978-1-78548-296-0
http://www.iste.co.uk/book.php?id=1403

### 2012-02-23

![](https://global.oup.com/academic/covers/uk/pdp/9780199601165)

http://www.oxfordscholarship.com/view/10.1093/acprof:osobl/9780199601165.001.0001/acprof-9780199601165
Codon Evolution: Mechanisms and Models - Oxford Scholarship
http://wp.biota.utoronto.ca/chang/files/2016/02/Chang-et-al-Codon-Evolution-Chapter11.pdf

----------
## video

https://www.youtube.com/watch?v=P-fjZPf3Dnw
Codon optimization: Why & how to design DNA sequences for optimal soluble protein expression - YouTube
Published on Nov 3, 2014


----------

## updates

### 2019

https://twitter.com/LiatShenhav/status/1187818150970085376
Liat Shenhav on Twitter: "We uncover a strong purifying selective pressure across marine microbial life that is driven by resource conservation, and also demonstrate that it is a central driving force in selection processes guiding codon usage. https://t.co/S4P6DXNi03" / Twitter
4:48 AM · Oct 26, 2019
https://www.biorxiv.org/content/10.1101/790345v2
Resource conservation manifests in the genetic code | bioRxiv
 KEGG and eggNOG orthologies

https://twitter.com/astrogenomics/status/1186949418294996992
Juan C. Villada on Twitter: "Our new pre-print is up! We explored how codon usage may be associated with hydrogen bonding in dsDNA. We found signals of a ramp that smoothly increases the number of hydrogen bonds per codon position. https://t.co/K3Ouu2unkj" / Twitter
7:16 PM · Oct 23, 2019

Posted August 09, 2019.
https://www.biorxiv.org/content/10.1101/730473v1
Using Machine Learning and Gene Nonhomology Features to Predict Gene Ontology | 
Methods
Composition of the Prediction Variable Dataset
For protein-coding genes, a codon usage bias score which describes the degree of bias towards the most
frequently used codons for multiple encoding amino acids in a given species was calculated following the
method described in (Sharp and Li, 1987) as implemented in the SeqIO module in biopython (v1.72) package
(Cock et al., 2009).

https://twitter.com/Tyu_Shi/status/1116749787569672193
Tyu_Shi on Twitter: "DeeplyEssential: A Deep Neural Network for Predicting Essential Genes in Microbes https://t.co/GbQ0522csF 配列の特徴のみ（遺伝子のコドン使用頻度や長さ、GC含量、アミノ酸使用頻度等）を特徴量として使っているようだ。でも本当に知りたいのは典型的では無いのに必須な遺伝子なんだよね…。"
2:07 AM · Apr 13, 2019


Published: 10 July 2019
https://academic.oup.com/gbe/advance-article/doi/10.1093/gbe/evz146/5530595
Critical Role of Codon Composition on the Translation Efficiency Robustness of the Hepatitis A Virus Capsid | Genome Biology and Evolution | Oxford Academic

Posted June 25, 2019.
https://www.biorxiv.org/content/10.1101/478016v2
Hidden patterns of codon usage bias across kingdoms

6 Jun 2019
https://twitter.com/ytksai/status/1136571651133329408
放線菌のコドン最適化に関する研究がScientific Reportsに採択されました。産総研の人工知能研究センターと生物プロセス研究部門の共同研究です。https://www.nature.com/articles/s41598-019-44500-z … プレスリリースを出しました。https://www.aist.go.jp/aist_j/press_release/pr2019/pr20190606/pr20190606.html 
生体分子の設計問題のうち、タンパク質発現量を向上させる目的でmRNAの塩基配列を同義置換の範囲内で設計する問題をコドン最適化と呼びます。本研究では、産総研の所有するタンパク質発現データの解析から、放線菌におけるコドン最適化に重要な設計指標を見出し、その有効性の実験検証も行いました。

### 2019-05

https://twitter.com/pacyc1841/status/1134711913265295360
この論文関係あるかわからないけど、この前ほんとにコドンユーセージでOligonucleotide frequencyが説明できるか話題になった
2:42 AM - 1 Jun 2019
https://www.ncbi.nlm.nih.gov/pubmed/31138741
MBio. 2019 May 28;10(3). pii: e00505-19. doi: 10.1128/mBio.00505-19.
Codon Usage Heterogeneity in the Multipartite Prokaryote Genome: Selection-Based Coding Bias Associated with Gene Location, Expression Level, and Ancestry.
López JL1, Lozano MJ1, Lagares A Jr2,3, Fabre ML1, Draghi WO1, Del Papa MF1, Pistorio M1, Becker A3, Wibberg D4, Schlüter A4, Pühler A4, Blom J5, Goesmann A5, Lagares A6.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6538778/
- Sinorhizobium meliloti, which harbors a chromosome, a chromid (pSymB), a megaplasmid (pSymA), and, in many strains, one or more accessory plasmids.
- modal codon usages

https://twitter.com/search?q=大腸菌%20コドン

https://twitter.com/enuroi/status/1128893267402059776
Ken Kuroki on Twitter: "大腸菌の全ゲノムを合成DNAで置換することに成功。59種のセンスコドンと2種の終止コドンしか使わないよう18,000コドンを変更。増殖時間は1.6倍に長くなったのみ。 https://t.co/u8DUxSJ8AI"
1:21 AM - 16 May 2019

https://twitter.com/hornistyf/status/1128821862337695744
Y. Furuta on Twitter: "大腸菌ゲノム上のセリンのコドン2つとストップコドン1つを同義コドンに置換した話。著者らが前に開発したREXER法でゲノム全体のコドンに適用。置換が難しかったのは、隣接遺伝子のORFやUTRと被っていたケース。／Total synthesis of Escherichia coli with a recoded genome https://t.co/fSqvontp6M"
8:37 PM - 15 May 2019


https://twitter.com/torusengoku/status/1128827977498677248
torusengoku on Twitter: "Nature, DNAコドンのうちTCG, TCA（ともにSerをコード）とTAG（アンバーストップコドン）を持たない大腸菌を作成。将来、これらのコドンに新しいアミノ酸をコードさせる遺伝暗号拡張が容易に。 https://t.co/KvQSOXbjCc どこまで減らせるのかな。"
9:02 PM - 15 May 2019

2019年5月16日
https://www.natureasia.com/ja-jp/nature/pr-highlights/12951
【合成生物学】大腸菌の遺伝コードを圧縮する | Nature | Nature Research

https://www.nature.com/articles/s41586-019-1192-5
Total synthesis of Escherichia coli with a recoded genome | Nature

### 2019-04

26 April 2019
https://www.sciencedirect.com/science/article/pii/S0022283619302281
Codon and Codon-Pair Usage Tables (CoCoPUTs): Facilitating Genetic Variation Analyses and Recombinant Gene Design - ScienceDirect


https://www.ncbi.nlm.nih.gov/pubmed/30828719
Nucleic Acids Res. 2019 Mar 4. pii: gkz151. doi: 10.1093/nar/gkz151. [Epub ahead of print]
Prediction and large-scale analysis of primary operons in plastids reveals unique genetic features in the evolution of chloroplasts.
Shahar N1, Weiner I1,2, Stotsky L1, Tuller T2,3, Yacoby I1.
https://academic.oup.com/nar/advance-article/doi/10.1093/nar/gkz151/5369010
For each gene pair we computed roughly 1100 features (Figure 1B-3 and Supplementary Figure S2) based on sequence analysis alone—thus, they could be computed for any sequenced plastome without requiring additional data (e.g. RNA-Seq). These features were designed to capture essential gene characteristics (e.g. coded protein hydrophobicity, RNA structure, codon usage bias, nucleotide composition) and to quantify their level of similarity within each couple of adjacent genes (Supplementary Figure S2).

https://www.ncbi.nlm.nih.gov/pubmed/30728279
mSphere. 2019 Feb 6;4(1). pii: e00011-19. doi: 10.1128/mSphereDirect.00011-19.
Gene Expansion and Positive Selection as Bacterial Adaptations to Oligotrophic Conditions.
Props R1,2,3, Monsieurs P2,4, Vandamme P5, Leys N2, Denef VJ6, Boon N7.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6365617/
For example, nitrogen and carbon limitations have been correlated with genome size, GC content, and carbon/nitrogen protein content (13), thermal adaptation with genome size (8), and growth rate with GC content and codon usage bias (14, 15).
Patterns of (genome-wide) positive selection have revealed lineage-specific adaptations, and together with codon usage bias, are thought to mediate fine-tuning of gene expression (18,–20). 
The Ramlibacter sp. MAG was part of the monophyletic Ramlibacter clade, and its GC content (70.6%), codon usage bias (SCUO = 0.57 ± 0.10), and genome size (3.95 Mbp) closely matched these of other Ramlibacter genomes (Fig. 2B). 

### 2018

https://www.ncbi.nlm.nih.gov/pubmed/29726922
Bioinformatics. 2018 Oct 1;34(19):3396-3398. doi: 10.1093/bioinformatics/bty382.
MACARON: a python framework to identify and re-annotate multi-base affected codons in whole genome/exome sequence data.
Khan W1,2, Varma Saripella G1,2, Ludwig T3, Cuppens T3, Thibord F1,2, Génin E3, Deleuze JF4, Trégouët DA1,2.


https://www.ncbi.nlm.nih.gov/pubmed/30247489
Nat Biotechnol. 2018 Sep 24. doi: 10.1038/nbt.4238. [Epub ahead of print]
Evaluation of 244,000 synthetic sequences reveals design principles to optimize translation in Escherichia coli.
Cambray G1,2, Guimaraes JC1,3, Arkin AP3,4.
- We precisely designed 244,000 DNA sequences implementing 56 replicates of a full factorial design to evaluate nucleotide, secondary structure, codon and amino acid properties in combination. 
- Codon composition has a sizable impact on translatability, but only in comparatively rare elongation-limited transcripts.


https://twitter.com/Paul_Carini/status/1023315547985870848
Paul Carini on Twitter: "https://t.co/1dN1Ku6uX4 "however, contrary to our expectations, a majority of bacteria that showed a positive response to plant growth were predicted to have longer generation times based on codon-usage bias, meaning their genomes bear signatures of slower growth rates"… https://t.co/DH7gNpnQJG"
5:13 PM - 28 Jul 2018
https://www.ncbi.nlm.nih.gov/pubmed/29556109
Nat Microbiol. 2018 Apr;3(4):470-480. doi: 10.1038/s41564-018-0129-3. Epub 2018 Mar 19.
Dynamic root exudate chemistry and microbial substrate preferences drive patterns in rhizosphere microbial community assembly.
Zhalnina K1,2, Louie KB1, Hao Z2, Mansoori N1,3, da Rocha UN2,4, Shi S5, Cho H2,6, Karaoz U2, Loqué D1,3,6,7, Bowen BP1, Firestone MK2,8, Northen TR9, Brodie EL10,11.

https://twitter.com/kfuku0502/status/1003768475871875072
Kenji Fukushima on Twitter: "高発現遺伝子だけでなく低発現遺伝子でもコドン使用頻度は選択を受けているらしい。大腸菌でそういうサイトの同義置換を入れて適応度が下がるケースを発見している。 https://t.co/nFGnUi3m2A"
6:40 PM - 4 Jun 2018
https://www.ncbi.nlm.nih.gov/pubmed/29688501
Genome Biol Evol. 2018 Apr 1;10(5):1237-1246. doi: 10.1093/gbe/evy084.
The Codon Usage of Lowly Expressed Genes Is Subject to Natural Selection.
Yannai A1, Katz S1, Hershberg R1.


https://www.ncbi.nlm.nih.gov/pubmed/29596640
Mol Biol Evol. 2018 Jun 1;35(6):1463-1472. doi: 10.1093/molbev/msy047.
Multiple Factors Confounding Phylogenetic Detection of Selection on Codon Usage.
Laurin-Lemay S1, Philippe H1,2, Rodrigue N3.


高度発現遺伝子群のコドンバイアスが、他の遺伝子群の翻訳に影響する。
https://www.ncbi.nlm.nih.gov/pubmed/29735666
Proc Natl Acad Sci U S A. 2018 May 22;115(21):E4940-E4949. doi: 10.1073/pnas.1719375115. Epub 2018 May 7.
Codon usage of highly expressed genes affects proteome-wide translation efficiency.
Frumkin I1, Lajoie MJ2, Gregg CJ2, Hornung G3, Church GM4, Pilpel Y5.

Interestingly, we could alleviate the observed phenotypes by increasing the supply of the tRNA for the highly demanded codon, thus demonstrating that the codon usage of highly expressed genes was selected in evolution to maintain the efficiency of global protein translation.

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6003480/

### 2017

https://www.ncbi.nlm.nih.gov/pubmed/28992099
DNA Res. 2017 Dec 1;24(6):623-633. doi: 10.1093/dnares/dsx030.
Co-adaption of tRNA gene copy number and amino acid usage influences translation rates in three life domains.
Du MZ1, Wei W1, Qin L1, Liu S1, Zhang AY1,2, Zhang Y1,2, Zhou H1,2, Guo FB1,2,3.

https://www.ncbi.nlm.nih.gov/pubmed/27540085
Genome Biol Evol. 2017 Oct 1;9(10):2560-2579. doi: 10.1093/gbe/evw201.
Switches in Genomic GC Content Drive Shifts of Optimal Codons under Sustained Selection on Synonymous Sites.
Sun Y1, Tamarit D1, Andersson SGE1.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5629928/
- Materials and Methods
- The strength of selected codon usage bias was estimated from the S index, which is used as a proxy for translational selection on individual genomes (Sharp et
al. 2005, 2010). 
- Results
Switches in GC Content in Lactobacillus and Bifidobacterium Species
- fig. 2.—
Phylogenetic relationships and genome features of Lactobacillus species.
A schematic figure illustrates the variation in GC contents, selective constraints (S-value), genome sizes and number of tRNAs in the species selected for an in-depth analysis.
- In order to quantify the relative strength of selection, we calculated the S indexes for the genomes in this study (supplementary table S2, Supplementary Material online). The S index is inferred from the relative use of C-ending codons for Asn, Ile, Phe, Tyr (Sharp et
al. 2005), 

### 2016

https://www.ncbi.nlm.nih.gov/pubmed/27671647
Proc Natl Acad Sci U S A. 2016 Oct 11;113(41):E6117-E6125. Epub 2016 Sep 26.
Codon usage is an important determinant of gene expression levels largely through its effects on transcription.
Zhou Z1, Dang Y1, Zhou M2, Li L3, Yu CH1, Fu J1, Chen S3, Liu Y4.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5068308/
Codon Optimization, Plasmid Constructs, and Neurospora Transformation.


### 2015

https://www.ncbi.nlm.nih.gov/pubmed/26504241
Proc Natl Acad Sci U S A. 2015 Nov 10;112(45):14030-5. doi: 10.1073/pnas.1515387112. Epub 2015 Oct 26.
Importance of codon usage for the temporal regulation of viral gene expression.
Shin YC1, Bischof GF2, Lauer WA1, Desrosiers RC3.


https://www.ncbi.nlm.nih.gov/pubmed/26282127
BMC Evol Biol. 2015 Aug 19;15:163. doi: 10.1186/s12862-015-0441-y.
The evolutionary dynamics of tRNA-gene copy number and codon-use in E. coli.
McDonald MJ1, Chou CH2,3, Swamy KB4, Huang HD5,6, Leu JY7.

### 2014

https://twitter.com/copypasteusa/status/583464468820000769
遺伝子発現の最適化に利用されてきた特徴：コドンバイアス、連続コドンバイアス、RNA二次構造、リボソーム結合部位、制限部位、隠れ終止コドン、他のモチーフ回避 
8:02 PM - 1 Apr 2015
REVIEW
https://www.ncbi.nlm.nih.gov/pubmed/25340050
Front Bioeng Biotechnol. 2014 Oct 6;2:41. doi: 10.3389/fbioe.2014.00041. eCollection 2014.
Computational tools and algorithms for designing customized synthetic genes.
Gould N1, Hendy O2, Papamichail D1.

### 2011

微生物群集内の翻訳効率と遺伝子水平伝播との関連
https://www.ncbi.nlm.nih.gov/pubmed/21343180
Nucleic Acids Res. 2011 Jun;39(11):4743-55. doi: 10.1093/nar/gkr054. Epub 2011 Feb 22.
Association between translation efficiency and horizontal gene transfer within microbial communities.
Tuller T1, Girshovich Y, Sella Y, Kreimer A, Freilich S, Kupiec M, Gophna U, Ruppin E.

### 2010

なぜ細菌の第二染色体上で遺伝子が速く進化するのか
https://www.ncbi.nlm.nih.gov/pubmed/20369015
PLoS Comput Biol. 2010 Apr 1;6(4):e1000732. doi: 10.1371/journal.pcbi.1000732.
Why genes evolve faster on secondary chromosomes in bacteria.
Cooper VS1, Vohr SH, Wrocklage SC, Hatcher PJ.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2848543/

### 2004

https://www.ncbi.nlm.nih.gov/pubmed/15448185
Nucleic Acids Res. 2004 Sep 24;32(17):5036-44. Print 2004.
Solving the riddle of codon usage preferences: a test for translational selection.
dos Reis M1, Savva R, Wernisch L.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC521650/
As expected (Figure ​(Figure3),3), S.cerevisiae and E.coli show the highest S-values, C.elegans shows a moderate S-value, while H.pylori and H.sapiens show no sign of translational selection acting on their genomes.


----------
## featuring

https://www.ncbi.nlm.nih.gov/pubmed/12952536
Genome Biol. 2003;4(9):R57. Epub 2003 Aug 21.
The source of laterally transferred genes in bacterial genomes.
Daubin V1, Lerat E, Perrière G.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC193657/
The codon usage of LTGs: comparison with native genes
We computed four independent factorial correspondence analyses (FCA) on the genes of each type (native and transferred genes, IS, and phages) for the four species E. coli O157:H7, Helicobacter pylori, Salmonella enterica, and Streptococcus pneumoniae.
Figure 4
Intraspecies FCA.


https://www.biophys.jp/dl/journal/53-1.pdf
生物物理 53（1），015-019（2013）
交通流と翻訳過程
御手洗菜美子　コペンハーゲン大学ニールス・ボーア研究所

https://twilog.org/copypasteusa/search?word=コドン




----------
## review

https://www.ncbi.nlm.nih.gov/pubmed/29018283
Nat Rev Mol Cell Biol. 2017 Oct 11.
Codon optimality, bias and usage in translation and mRNA decay.
Hanson G1, Coller J1.

review
https://www.ncbi.nlm.nih.gov/pubmed/26029354
Comput Struct Biotechnol J. 2015 May 4;13:352-7. doi: 10.1016/j.csbj.2015.04.005. eCollection 2015.
Homology-independent metrics for comparative genomics.
Coutinho TJ1, Franco GR1, Lobo FP2.
In this review we compile several sequence metrics that do not rely on homology inference and can be used to compare nucleotide sequences and extract biologically meaningful information from them. These metrics comprise several compositional parameters calculated from sequence data alone, such as GC content, dinucleotide odds ratio, and several codon bias metrics. 

https://www.ncbi.nlm.nih.gov/pubmed/26186290
Mol Cell. 2015 Jul 16;59(2):149-61. doi: 10.1016/j.molcel.2015.05.035.
Codon Bias as a Means to Fine-Tune Gene Expression.
Quax TE1, Claassens NJ2, Söll D3, van der Oost J4.

https://www.ncbi.nlm.nih.gov/pubmed/22889422
Biol Rev Camb Philos Soc. 2013 Feb;88(1):49-61. doi: 10.1111/j.1469-185X.2012.00242.x. Epub 2012 Aug 14.
Codon usage bias: causative factors, quantification methods and genome-wide patterns: with emphasis on insect genomes.
Behura SK1, Severson DW.

https://www.ncbi.nlm.nih.gov/pubmed/22921354
Trends Genet. 2012 Nov;28(11):574-81. doi: 10.1016/j.tig.2012.07.006. Epub 2012 Aug 23.
Speeding with control: codon usage, tRNAs, and ribosomes.
Novoa EM1, Ribas de Pouplana L.

http://www.ncbi.nlm.nih.gov/pubmed/21102527
Nat Rev Genet. 2011 Jan;12(1):32-42. doi: 10.1038/nrg2899. Epub 2010 Nov 23.
Synonymous but not the same: the causes and consequences of codon bias.
Plotkin JB1, Kudla G.
https://www.bio.upenn.edu/sites/default/files/research/Plotkin/Plotkin_Kudla_NatRevGenetics_2011.pdf

https://www.ncbi.nlm.nih.gov/pubmed/18983258
Annu Rev Genet. 2008;42:287-99. doi: 10.1146/annurev.genet.42.110807.091442.
Selection on codon bias.
Hershberg R1, Petrov DA.

https://www.ncbi.nlm.nih.gov/pubmed/11719972
Curr Issues Mol Biol. 2001 Oct;3(4):91-7.
Synonymous codon usage in bacteria.
Ermolaeva MD1.



----------
## heterologous gene expression
異種遺伝子発現

https://www.ncbi.nlm.nih.gov/pubmed/29410400
Nat Commun. 2018 Feb 6;9(1):522. doi: 10.1038/s41467-018-02944-3.
Biochemical mechanisms determine the functional compatibility of heterologous genes.
Porse A1, Schou TS1, Munck C1, Ellabaan MMH1, Sommer MOA2.
In contrast to previous work, we find that GC content, codon usage, and mRNA-folding energy are of minor importance for the compatibility of mechanistically diverse gene products at moderate expression. 

https://galaxyproject.org/use/codon-harmonizer/
Codon Harmonizer
:	Easily generate codon harmonized variants of gene sequences for heterologous expression

https://www.ncbi.nlm.nih.gov/pubmed/28902855
PLoS One. 2017 Sep 13;12(9):e0184355. doi: 10.1371/journal.pone.0184355. eCollection 2017.
Improving heterologous membrane protein production in Escherichia coli by combining transcriptional tuning and codon usage algorithms.
Claassens NJ1, Siliakus MF1, Spaans SK1, Creutzburg SCA1, Nijsse B2, Schaap PJ2, Quax TEF3, van der Oost J1.

https://www.ncbi.nlm.nih.gov/pubmed/28855614
Sci Rep. 2017 Aug 30;7(1):9926. doi: 10.1038/s41598-017-10546-0.
Predicting synonymous codon usage and optimizing the heterologous gene for expression in E. coli.
Tian J1, Yan Y1,2, Yue Q1,3, Liu X1, Chu X1, Wu N4, Fan Y1.

2016年1月21日
https://www.natureasia.com/ja-jp/nature/highlights/71552
生物工学：タンパク質翻訳を改善する
J Huntたちは今回、複数のタンパク質発現実験の結果の詳細な解析を行い、コドンの影響の新たな指標を導き出した。この指標を用いて遺伝子を再設計すると、転写には影響が出ないが、翻訳効率が大幅に高まることが分かった。彼らは、in vivoでのmRNA分解と翻訳の過程は競合しており、この指標を用いることでタンパク質産生を高めることができると結論付けている。

https://www.ncbi.nlm.nih.gov/pubmed/22847936
Bioinformatics. 2012 Oct 15;28(20):2683-4. doi: 10.1093/bioinformatics/bts465. Epub 2012 Jul 30.
EuGene: maximizing synthetic gene design for heterologous expression.
Gaspar P1, Oliveira JL, Frommlet J, Santos MA, Moura G.

https://www.ncbi.nlm.nih.gov/pubmed/19696103
Microbiology. 2009 Nov;155(Pt 11):3581-8. doi: 10.1099/mic.0.030064-0. Epub 2009 Aug 20.
Overcoming codon-usage bias in heterologous protein expression in Streptococcus gordonii.
Lee SF1, Li YJ, Halperin SA.
tRNA genes encoding 10 of the 12 rare codons were cloned into a plasmid. The plasmid was transformed into strains of S. gordonii expressing the fusion protein SpaP/S1, the anti-complement receptor 1 (CR1) single-chain variable fragment (scFv) antibody, or the Toxoplasma gondii cyclophilin C18 protein. 

2001
http://wolfson.huji.ac.il/expression/rosetta.pdf
Overcoming the codon bias of E. coli for enhanced protein expression
tRNA levels can be
elevated by increasing the copy number of
the respective tRNA gene. This is typically
accomplished by inserting the wild type
tRNA gene on a multiple copy plasmid.
The tRNA gene is either inserted into the
expression vector itself or placed on a compatible
plasmid. 

----------
## tRNA

http://trna.ie.niigata-u.ac.jp/cgi-bin/trnadb/index.cgi
Home | tRNADB-CE : tRNA gene database curated manually by experts

Details of annotation strategy written in Japanese (click here).
https://www.jstage.jst.go.jp/article/cicsj/26/1/26_1_11/_pdf
Silicibacter pomeroyi DSS-3 のゲノムからは51個の tRNA遺伝子が見出されていたが、フェニルアラニンのアンチコドンをもった遺伝子が不足していた。ゲノムのデータを調べてみると、この菌はプラスミドを保有しており、不足分のフェニルアラニン tRNA 遺伝子はそのプラスミド上に乗っていることが解かった。宿主ゲノムからプラスミドにその tRNA 遺伝子が移行した可能性は充分考えられる。この菌ではそのプラスミドを失う事は出来ず、tRNA 遺伝子がプラスミドの安定な保持に働いていると考えられる。

生物種リストから
http://trna.ie.niigata-u.ac.jp/cgi-bin/trnadb/whole_spe_list_inc.cgi?STYPE=B&DTYPE=CMP
```
Shewanella oneidensis MR-1	tRNA seq.|Anticodon
```

https://integbio.jp/dbcatalog/record/nbdc00720
tRNADB-CE - Integbio データベースカタログ

https://dbarchive.biosciencedbc.jp/jp/trnadb-ce/data-1.html
tRNA配列、アノテーション及びキュレーションのデータ - tRNADB-CE | LSDB Archive

https://www.ncbi.nlm.nih.gov/pubmed/29846694
Mol Biol Evol. 2018 Aug 1;35(8):2046-2059. doi: 10.1093/molbev/msy110.
Wobbling Forth and Drifting Back: The Evolutionary History and Impact of Bacterial tRNA Modifications.
Diwan GD1,2, Agashe D1.

https://www.ncbi.nlm.nih.gov/pubmed/24782525
Nucleic Acids Res. 2014 Jun;42(10):6552-66. doi: 10.1093/nar/gku245. Epub 2014 Apr 29.
Auxiliary tRNAs: large-scale analysis of tRNA genes reveals patterns of tRNA repertoire dynamics.
Wald N1, Margalit H2.

https://www.ncbi.nlm.nih.gov/pubmed/18058157
J Mol Evol. 2008 Jan;66(1):21-35. Epub 2007 Dec 4.
The origin and evolution of tRNA inferred from phylogenetic analysis of structure.
Sun FJ1, Caetano-Anollés G.

https://www.researchgate.net/post/Why_is_tRNA_not_used_for_phylogenetic_analysis
Why is tRNA not used for phylogenetic analysis?

----------
## tRNA gene cluster
tRNA遺伝子クラスター

古細菌
https://www.ncbi.nlm.nih.gov/pubmed/30624459
Mem Inst Oswaldo Cruz. 2019 Jan 7;114:e180348. doi: 10.1590/0074-02760180348.
Exploring tRNA gene cluster in archaea.
Morgado SM1, Vicente ACP1.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6333295/
In prokaryotes, tRNA gene clusters were characterised in some bacteria, being prevalent in Firmicutes phylum and Mycobacterium genus, 6 , 7 

マイコバクテリウム属
https://www.ncbi.nlm.nih.gov/pubmed/29867913
Front Microbiol. 2018 May 17;9:1042. doi: 10.3389/fmicb.2018.01042. eCollection 2018.
Beyond the Limits: tRNA Array Units in Mycobacterium Genomes.
Morgado SM1, Vicente ACP1.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5966550/
- In high GC content phyla, as Actinobacteria, they were found only in few genomes but none from Mycobacterium genus (Tran et al., 2016).
- Each tRNA predicted by ARAGORN provides information about its genomic coordinate and contig number, which were accessed by our in-house script. tRNA array units were defined as genomic regions with 20 or more tRNAs and a minimum density of two tRNA/kb (Tran et al., 2016). 
- The Acidithiobacillus ferrooxidans ATCC 23270 genome was used as positive control to the identification of tRNA array unit (Tran et al., 2016).
- In order to identify the presence of any tRNA array unit in these genomes we used our in-house script that was based on the tRNA array unit definition: a genomic region containing at least 20 tRNA genes with a minimal density of two tRNA genes per kilobase (Tran et al., 2016). 
- Types of tRNA array
Tran et al. (2016), based on the tRNA amino acid isotypes and organization of each array, assigned the arrays in seven groups. 

https://www.ncbi.nlm.nih.gov/pubmed/26710853
Genome Biol Evol. 2015 Dec 28;8(1):282-95. doi: 10.1093/gbe/evv254.
A Comprehensive tRNA Genomic Survey Unravels the Evolutionary History of tRNA Arrays in Prokaryotes.
Tran TT1, Belahbib H1, Bonnefoy V1, Talla E2.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4758250/

Materials and Methods
- tRNA Gene Prediction and Identification of tRNA Array Units
tRNAscan-SE 1.3.1 program (Lowe and Eddy 1997) 
 Aragon tool (Laslett and Canback 2004) was also used 
, we first identified regions of 5, 10, 15, 20, 25 and 30 kb along the genome (incremental path of 1 kb) that contain at least 5, 10, 15, 20, 25, or 30 tRNA genes, named array seeds (supplementary table S1, Supplementary Material online). 
 Consequently, tRNA array seeds were thus defined as a genomic region of 10 kb containing at least 20 tRNA genes. 

- Structural Organization of tRNA Array Units

Results
- Occurrence and Distribution of tRNA Array Units
A tRNA array unit was defined as a genomic region containing at least 20 tRNA genes with a minimal tRNA gene density of two tRNA genes per kilobase. Thi

Discussion
In E. coli, tRNA arrays significantly influence global tRNA expression at high growth rates (Ardell and Kirsebom 2005). 
No relationship was found between the presence of the array units and the organism’s lifestyle (aerobic or anaerobic, optimal growth temperature, pathogenicity or environmental conditions) (data not shown). 


----------
## lifestyle
ライフスタイル

https://www.ncbi.nlm.nih.gov/pubmed/23024607
Curr Genomics. 2012 Apr;13(2):153-62.
Microbial lifestyle and genome signatures.
Dutta C1, Paul S.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3308326/
c) Codon Usage
Distinct niche-specific trends in synonymous codon usage have also been observed in microbes thriving at high salinity [24]. An analysis of synonymous codon usage patterns in bacterial and fungal genomes by Willenbrok et al. [49] demonstrated that differences in codon preferences of translational codon adaptation and dominant codon adaptation provide an environmental signature that can segregate bacteria according to their lifestyle, for instance soil bacteria and soil symbionts, spore formers, enteric bacteria, aquatic bacteria, and small intercellular and extracellular pathogens.

https://www.ncbi.nlm.nih.gov/pubmed/22032172
Genome Biol. 2011 Oct 27;12(10):R109. doi: 10.1186/gb-2011-12-10-r109.
Variation in global codon usage bias among prokaryotic organisms is associated with their lifestyles.
Botzman M1, Margalit H.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3333779/

コドン使用バイアスは、ライフスタイルの異なるグループ（土壌細菌、共生細菌、腸内細菌、水生細菌、胞子形成菌、病原体）に細菌を分けることで、環境の情報を提供する。
https://www.ncbi.nlm.nih.gov/pubmed/17156429
Genome Biol. 2006;7(12):R114.
An environmental signature for 323 microbial genomes based on codon adaptation indices.
Willenbrock H1, Friis C, Juncker AS, Ussery DW.
group bacteria according to their lifestyle, 
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1794427/
- Background
Here, we calculate and compare a translational CAI (tCAI) based on that proposed by Sharp and Li [1] with a purely mathematical dominant CAI (dCAI) [8] for 318 bacterial and 5 fungal genomes for which full sequences are deposited in Genbank and available from the Genome Atlas Database (version 19.1) [11].
- Figure 2
Two-dimensional cluster analysis of differential codon preferences for tCAI and dCAI.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1794427/figure/F2/
- Conclusion
It was previously postulated that fast-growing bacteria share codon usage preferences because they have more abundant and similar tRNAs [12]. Here, we offer a biological explanation by showing a clear relationship between environment and similarities in codon usage biases. Specifically, differences in codon preferences of translational codon adaptation and dominant codon adaptation provide an environmental signature by which it is possible to divide bacteria into groups representing different lifestyles, such as soil bacteria and symbionts, enterics, aquatic bacteria, spore formers, and small intercellular and extracellular pathogens.

https://www.ncbi.nlm.nih.gov/pubmed/15537809
Mol Biol Evol. 2005 Mar;22(3):547-61. Epub 2004 Nov 10.
Codon bias signatures, organization of microorganisms in codon space, and lifestyle.
Carbone A1, Képès F, Zinovyev A.
https://academic.oup.com/mbe/article/22/3/547/1075922

https://www.ncbi.nlm.nih.gov/pubmed/14594704
Bioinformatics. 2003 Nov 1;19(16):2005-15.
Codon adaptation index as a measure of dominating codon bias.
Carbone A1, Zinovyev A, Képès F.

----------

## database
データベース

https://integbio.jp/dbcatalog/record/nbdc00033
Codon Usage Database - Integbio データベースカタログ
http://www.kazusa.or.jp/codon/
Codon Usage Database

https://www.ncbi.nlm.nih.gov/pubmed/28865429
BMC Bioinformatics. 2017 Sep 2;18(1):391. doi: 10.1186/s12859-017-1793-7.
A new and updated resource for codon usage tables.
Athey J1, Alexaki A1, Osipova E2, Rostovtsev A2, Santana-Quintero LV2, Katneni U1, Simonyan V2, Kimchi-Sarfaty C3.
High-performance Integrated Virtual Environment-Codon Usage Tables (HIVE-CUTs)
http://hive.biochemistry.gwu.edu/review/codon
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5581930/
However, as plasmids are located in the same area as the genome, draw from the same tRNA pools, and use the same genetic code as the genome, plasmid coding sequences are not separated from the organism’s genomic codon usage table. 

https://www.ncbi.nlm.nih.gov/pubmed/22536831
BMC Bioinformatics. 2012 Apr 26;13:62. doi: 10.1186/1471-2105-13-62.
CBDB: the codon bias database.
Hilterbrand A1, Saelens J, Putonti C.

----------
## tools
ツール

https://github.com/enovoa/codonAutocorrelation
Compute codon autocorrelation (aka codon covariation, codon reuse, codon pair usage) from fasta sequences.
This code was used in the analyses of the manuscript 'Elucidation of codon usage signatures across the domains of life' (Novoa et al., Mol Biol Evol 2019), available here: https://doi.org/10.1093/molbev/msz124

https://www.ncbi.nlm.nih.gov/pubmed/30738198
Genomics. 2019 Feb 6. pii: S0888-7543(18)30608-6. doi: 10.1016/j.ygeno.2019.02.002. [Epub ahead of print]
CodSeqGen: A tool for generating synonymous coding sequences with desired GC-contents.
Al-Ssulami AM1, Azmi AM2, Hussain M3.
Availability
CodSeqGen executable is available for free download at: https://github.com/Abdulrakeeb/CodSeqGen

https://www.ncbi.nlm.nih.gov/pubmed/17439967
Nucleic Acids Res. 2007 Jul;35(Web Server issue):W126-31. Epub 2007 Apr 16.
OPTIMIZER: a web server for optimizing the codon usage of DNA sequences.
Puigbò P1, Guzmán E, Romeu A, Garcia-Vallvé S.

https://www.ncbi.nlm.nih.gov/pubmed/15980527
Nucleic Acids Res. 2005 Jul 1;33(Web Server issue):W526-31.
JCat: a novel tool to adapt codon usage of a target gene to its potential expression host.
Grote A1, Hiller K, Scheer M, Münch R, Nörtemann B, Hempel DC, Jahn D.

http://codonw.sourceforge.net
Correspondence Analysis of Codon Usage
CodonW
15/Apr/2005

http://pbil.univ-lyon1.fr/datasets/charif04/
Online Synonymous Codon Usage Analyses with the ade4 and seqinR packages
2004

http://bioinfo.ie.niigata-u.ac.jp/?Codon%20Usage%20Generator
Codon Usage Generator (CUG) †
本プログラムは，コドン組成を計算するためのソフトウェアです．

----------
### R

http://rpubs.com/dbg
Daniel Bryan Goodman
- http://rpubs.com/dbg/3350
Step 07 - Looking at Codon and tRNA Adaptation Indices
- http://rpubs.com/dbg/3351
Step 10 - Looking at amino acid and codon usage

### ComputeNEC

https://rdrr.io/github/fredysiegrist/statanacoseq/
fredysiegrist/statanacoseq: Statistical Analyses of Codon Usage in Custom Genome Sequences version 0.0.0.9002 from GitHub

Install the latest version of this package by entering the following in R:
```
install.packages("remotes")
remotes::install_github("fredysiegrist/statanacoseq")

```


https://rdrr.io/github/fredysiegrist/statanacoseq/man/ComputeNEC.html
ComputeNEC: Effective number of codons in fredysiegrist/statanacoseq: Statistical Analyses of Codon Usage in Custom Genome Sequences

Author(s)
Roth, A.; Siegrist, F. and Cannarozzi, G. M. gina@cannarozzi.com



### vhica

https://cran.r-project.org/web/packages/vhica/index.html
CRAN - Package vhica
vhica: Vertical and Horizontal Inheritance Consistence Analysis
Version:	0.2.4

https://cran.r-project.org/web/packages/vhica/vhica.pdf
April 5, 2016

CUB Computes the Codon Usage Bias of DNA sequences
Description
The function reads aligned sequences in a fasta file and estimates the codon usage bias for each sequence. Several methods exist to estimate CUB; so far, only the "Effective Number of Codons" (ENC) calculation is available.

https://rdrr.io/cran/vhica/man/CUB.html
https://www.rdocumentation.org/packages/vhica/versions/0.2.4/topics/CUB

### coRdon

https://github.com/haruosuz/r4bioinfo/tree/master/R_coRdon
A, Kuzman M, Vlahovicek K (2019). coRdon: Codon Usage Analysis and Prediction of Gene Expressivity. 

### sscu

22 Aug 2018
https://arxiv.org/abs/1808.07259
[1808.07259] SSCU: an R/Bioconductor package for analyzing selective profile in synonymous codon usage


https://bioconductor.org/packages/release/bioc/html/sscu.html

```
library(sscu)
s_index
```

https://bioconductor.org/packages/devel/bioc/manuals/sscu/man/sscu.pdf
October 30, 2019

----------
## methods

### RSCU
relative synonymous codon usage

https://www.megasoftware.net/web_help_7/rh_rscu.htm
Many amino acids are coded by more than one codon; thus multiple codons for a given amino acid are synonymous. However, many genes display a non-random usage of synonymous codons for specific amino acids. A measure of the extent of this non-randomness is given by the Relative Synonymous Codon Usage (RSCU) (Sharp et al. 1986).

http://www.lirmm.fr/~rivals/rscu/
RSCURS: Measuring the bias in codon usage from ribosomal activity 
Paulet et al. DNA Research 2017

Elucidation of Codon Usage Signatures across the Domains of Life
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6759073/
fig. 1.
(A) Hierarchical clustering of the average relative synonymous codon usage (RSCU) for each species (n = 1,625). 

https://www.bio.upenn.edu/sites/default/files/research/Plotkin/Plotkin_Kudla_NatRevGenetics_2011.pdf
Figure 1 | Codon bias within and between genomes.

https://www.ncbi.nlm.nih.gov/pubmed/21699680
BMC Genomics. 2011 Jun 23;12:325. doi: 10.1186/1471-2164-12-325.
Unresolved orthology and peculiar coding sequence properties of lamprey genes: the KCNA gene family as test case.
Qiu H1, Hildebrand F, Kuraku S, Meyer A.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3141671/
Synonymous codon usage was investigated by within-group correspondence analysis (WCA) of codon counts [22,23] and by correspondence analysis of relative synonymous codon usage (CA-RSCU). The latter is the most widely used method for codon usage analysis, whereas the former has been recently demonstrated to produce more unbiased results because it takes into account both amino acid composition and codon degeneracy information [48]. 

最尤推定
https://www.ncbi.nlm.nih.gov/pubmed/18495752
Nucleic Acids Res. 2008 Jun;36(11):3819-27. doi: 10.1093/nar/gkn288. Epub 2008 May 21.
SCUMBLE: a method for systematic and accurate detection of codon usage bias by maximum likelihood estimation.
Kloster M1, Tang C.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2441815/
The algorithm's; ability to detect weak biases is well illustrated by the genome of Helicobacter pylori, which has been claimed to contain no codon bias for highly expressed genes (31). 

We found that SCUMBLE performs better than WCA or CA/RSCU in detecting GC or GT biases in prokaryote genomes. SCUMBLE is also able to detect far more biases in prokaryote genomes than a variety of other approaches using PCA (37) (Supplementary Tables S1 and S2). Unlike PCA, SCUMBLE shows a clear signature for the strength of the different biases: GC bias is most often the dominant bias, followed by expression bias and GT bias.

----------
## mge
Mobile genetic elements (MGEs)
https://ja.wikipedia.org/wiki/可動遺伝因子

### plasmids

https://www.ncbi.nlm.nih.gov/pubmed/28206693
Mol Ecol. 2017 Apr;26(7):1832-1847. doi: 10.1111/mec.14056. Epub 2017 Mar 13.
Plasmid and clonal interference during post horizontal gene transfer evolution.
Bedhomme S1,2, Perez Pantoja D3, Bravo IG2.
KEYWORDS:
antibiotic resistance; clonal interference; codon usage preferences; multilevel selection; plasmid
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5392415/
Plasmid carriage costs are not the only costs to plasmid-mediated HGT. Another potentially important one is the mismatch in codon usage preferences between the transferred gene and the receiving genome (Baltrus 2013). Each species is indeed characterized by specific frequencies of use of the different codons within a synonymous codon family. An important evolutionary force shaping codon usage preferences is coevolution with the translation machinery: codon usage frequencies are strongly related with the copy number of corresponding tRNA genes, especially for highly expressed genes and for rapidly growing organisms (Rocha 2004). Genes transferred horizontally from a different organism can present a mismatch in codon usage preferences with the receiving genome, and such mismatch is known to affect translation accuracy and speed (Komar et al. 1999, Burgess-Brown et al. 2008). 

and comparative approaches demonstrate that HGT is more likely to be successful between genomes with similar codon usage preferences (Tuller et al. 2011, Medrano-Soto 2004).

The cost of plasmid carriage was quantified and we showed that mismatches in codon usage preferences generate differences in chloramphenicol resistance. 

https://www.ncbi.nlm.nih.gov/pubmed/20369015
PLoS Comput Biol. 2010 Apr 1;6(4):e1000732. doi: 10.1371/journal.pcbi.1000732.
Why genes evolve faster on secondary chromosomes in bacteria.
Cooper VS1, Vohr SH, Wrocklage SC, Hatcher PJ.

Further, in every bacterial genome with multiple chromosomes that we studied, genes on secondary chromosomes exhibited significantly weaker codon usage bias than those on primary chromosomes. Faster evolution and reduced codon bias

https://www.ncbi.nlm.nih.gov/pubmed/20080407
Trends Microbiol. 2010 Apr;18(4):141-8. doi: 10.1016/j.tim.2009.12.010. Epub 2010 Jan 18.
Introducing the bacterial 'chromid': not a chromosome, not a plasmid.
Harrison PW1, Lower RP, Kim NK, Young JP.

Chromids carry some core genes, and their nucleotide composition and codon usage are very similar to those of the chromosomes they are associated with.

https://linkinghub.elsevier.com/retrieve/pii/S0966-842X(09)00269-8

Chromid genes have a similar codon usage to chromosomal genes
A large number of studies (reviewed by Lynn et al.[11]) have investigated synonymous codon usage and demonstrated that it is highly patterned. It is known that individual genomes have characteristic synonymous codon usage signatures [12]. Our analysis demonstrates that individual replicons also have distinct codon usage characteristics, and chromids are much more similar to chromosomes than to the plasmids that are found in the same organisms. For example, in the genome of Agrobacterium tumefaciens C58 the chromosome and chromid are very similar in average codon usage but rather distinct from the two plasmids (Figure 1). 

https://www.ncbi.nlm.nih.gov/pubmed/19221094
DNA Res. 2009 Apr;16(2):91-104. doi: 10.1093/dnares/dsp001. Epub 2009 Feb 15.
Codon usages of genes on chromosome, and surprisingly, genes in plasmid are primarily affected by strand-specific mutational biases in Lawsonia intracellularis.
Guo FB1, Yuan JB.

https://www.ncbi.nlm.nih.gov/pubmed/18391244
In Silico Biol. 2007;7(4-5):547-58.
Analysis of codon usage patterns and predicted highly expressed genes for six phytopathogenic Xanthomonas genomes shows a high degree of conservation.
Sen G1, Sur S, Bose D, Mondal U, Furnholm T, Bothra A, Tisa L, Sen A.

https://www.ncbi.nlm.nih.gov/pubmed/14597394
Gene. 2003 Nov 27;320:109-16.
The strength of translational selection for codon usage varies in the three replicons of Sinorhizobium meliloti.
Peixoto L1, Zavala A, Romero H, Musto H.

https://www.ncbi.nlm.nih.gov/pubmed/9820537
J Immunol. 1998 Nov 15;161(10):5594-9.
Optimization of codon usage of plasmid DNA vaccine is required for the effective MHC class I-restricted T cell responses against an intracellular bacterium.
Uchijima M1, Yoshida A, Nagata T, Koide Y.

### virus

https://www.ncbi.nlm.nih.gov/pubmed/27278133
Sci Rep. 2016 Jun 9;6:27546. doi: 10.1038/srep27546.
Codon optimization of the adenoviral fiber negatively impacts structural protein expression and viral fitness.
Villanueva E1, Martí-Solano M2, Fillat C1,3.

https://www.ncbi.nlm.nih.gov/pubmed/22016848
Mob Genet Elements. 2011 May;1(1):75-77.
Codon bias, tRNA pools and horizontal gene transfer.
Tuller T1.

https://www.ncbi.nlm.nih.gov/pubmed/19888206
Mol Syst Biol. 2009;5:311. doi: 10.1038/msb.2009.71. Epub 2009 Oct 13.
Viral adaptation to host: a proteome-based analysis of codon usage and amino acid preferences.
Bahir I1, Fromer M, Prat Y, Linial M.

https://www.ncbi.nlm.nih.gov/pubmed/18463708
PLoS Comput Biol. 2008 Feb 29;4(2):e1000001. doi: 10.1371/journal.pcbi.1000001.
Genome landscapes and bacteriophage codon usage.
Lucks JB1, Nelson DR, Kudla GR, Plotkin JB.

----------
## metagenome

Posted September 30, 2019.
https://www.biorxiv.org/content/10.1101/786939v1
Benchmarking metagenomic marine microbial growth prediction from codon usage bias and peak-to-trough ratios | bioRxiv

https://twitter.com/EvaMariaNovoa/status/1130910439817252864
Eva Maria Novoa on Twitter: "Our paper is out! :-) Codon usage signatures across species are not just consequence of GC content - and these biases can be used for metagenomic binning! #codonusage #metagenome @manoliskellis https://t.co/fKZNIcWIll"
2:57 PM - 21 May 2019
https://www.ncbi.nlm.nih.gov/pubmed/31220870
Mol Biol Evol. 2019 Oct 1;36(10):2328-2339. doi: 10.1093/molbev/msz124.
Elucidation of Codon Usage Signatures across the Domains of Life.
Novoa EM1,2,3,4, Jungreis I1,2, Jaillon O1,2,5, Kellis M1,2.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6759073/

2019-05-02
Anamaria Elek
https://www.bioconductor.org/packages/devel/bioc/vignettes/coRdon/inst/doc/coRdon.html
Codon usage (CU) analysis in R
- This approach can be efficiently used to predict highly expressed genes in a single genome, but is especially useful at the higher level of an entire metagenome.

https://www.ncbi.nlm.nih.gov/pubmed/29947757
Bioinformatics. 2018 Jun 27. doi: 10.1093/bioinformatics/bty519. [Epub ahead of print]
BMC3C: Binning Metagenomic Contigs using Codon usage, sequence Composition and read Coverage.
Yu G1, Jiang Y1, Wang J1, Zhang H2, Luo H2.

https://www.ncbi.nlm.nih.gov/pubmed/29742107
PLoS One. 2018 May 9;13(5):e0195869. doi: 10.1371/journal.pone.0195869. eCollection 2018.
Codon usage bias reveals genomic adaptations to environmental conditions in an acidophilic consortium.
Hart A1, Cortés MP2,3, Latorre M2,3,4,5, Martinez S6.


review
https://www.ncbi.nlm.nih.gov/pubmed/26951112
Microbiome. 2016 Mar 8;4:8. doi: 10.1186/s40168-016-0154-5.
Recovering complete and draft population genomes from metagenome datasets.
Sangwan N1,2, Xia F3, Gilbert JA4,5,6,7.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4782286/
However, another framework for analysis relies on variation in codon bias to determine the genome-wide influence of in situ functional constraints on individual taxa. Since percentage codon bias variation analysis is a phylogenetically independent method that directly reflects the strength of selection and the translation efficiency of expressed genes [77, 78], it circumvents the need for reference genomes and can reveal the influence of in situ functional constraints over natural selection patterns. It is important to note that for complete genome sequences, codon use patterns are influenced by nucleotide composition (mutational biases) and horizontal gene transfer. However, because each gene in a reassembled genome represents the population with an even nucleotide composition, one can assume that these clonal isolate-based limitations will not skew codon usage.

https://www.ncbi.nlm.nih.gov/pubmed/25680374
Acta Biochim Pol. 2015;62(1):161-6. Epub 2015 Feb 13.
The most widespread problems in the function-based microbial metagenomics.
Felczykowska A1, Krajewska A1, Zielińska S1, Łoś JM1, Bloch SK1, Nejman-Faleńczyk B1.
 Codon usage bias, internal cell accumulation, correct protein folding or presence of proper initiation factors are discussed and possible ways to overcome these problems are proposed. 
http://www.actabp.pl/pdf/1_2015/2014_917.pdf


https://www.ncbi.nlm.nih.gov/pubmed/27115650
Methods Mol Biol. 2016;1415:509-31. doi: 10.1007/978-1-4939-3572-7_26.
Big Data, Evolution, and Metagenomes: Predicting Disease from Gut Microbiota Codon Usage Profiles.
Fabijanić M1, Vlahoviček K2.

https://phylogenomics.blogspot.jp/2013/08/great-use-of-metagenomic-data-community.html
August 09, 2013
Great use of metagenomic data: community wide adaptation signatures

https://www.ncbi.nlm.nih.gov/pubmed/23921637
Nucleic Acids Res. 2013 Oct;41(19):8842-52.
Environmental shaping of codon usage and functional adaptation across microbial communities.
Roller M1, Lucić V, Nagy I, Perica T, Vlahovicek K.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3799439/
Single bacterial species’ genomes and annotation
Codon usage within metagenomes follows similar patterns as in single microbial genomes



----------
## temperature

https://www.ncbi.nlm.nih.gov/pubmed/16989961
Gene. 2006 Dec 30;385:128-36. 
Synonymous codon usage and its potential link with optimal growth temperature in prokaryotes.
Lobry JR1, Necşulea A.

https://www.ncbi.nlm.nih.gov/pubmed/12364606
Nucleic Acids Res. 2002 Oct 1;30(19):4272-7.
Synonymous codon usage is subject to selection in thermophilic bacteria.
Lynn DJ1, Singer GA, Hickey DA.

----------
## replication
**複製**

https://github.com/haruosuz/DS4GD/blob/master/2019/CaseStudy.md
GC skew

http://www.iu.a.u-tokyo.ac.jp/~kadota/JSLAB_9_kadota.pdf
　環状ゲノムの場合、どこを配列の起点として表記する
かは明確にルールが決まっているわけではないが、慣例
として dnaA 遺伝子が配列の先頭となるように “ 回転 ”
させておくことが多い。

LH_draft2.fa を入力として再度予備的に行った
DFAST アノテーション結果においては、chromosome 上
の相補鎖側の［1436009, 1437325 bp］にdnaA がコードさ
れていた［W2-2］。

　具体的な手順としては、まず dnaA 遺伝子を含む領
域［1, 1437425 bp］とそれ以外の領域［1437426, 2277983
bp］を入れ替えた（回転させた）後に、相補鎖変換を行
えばよい［W4-4］。

入力は、Genbank 形
式の DFAST アノテーション結果ファイル（annotation.
gbk）である。①時計の 0 時に相当する部分が複製開始点
である。一番外側から、②順鎖上および相補鎖上の CDS、

実際の複製では、①の
複製開始点から時計回りに進む順鎖側、そして反時計回り
に進む相補鎖側がリーディング鎖となる。

- https://kotobank.jp/word/リーディング鎖-773894
DNAの複製に際し，岡崎フラグメントで複製される方でなく，その反対の連続的に複製される側の鎖．ラギング鎖（lagging strand）の対語
- https://kotobank.jp/word/ラギング鎖-773723
リーディング鎖の対語で，二本鎖のDNAのうちの1本で，DNAの複製に際して，鎖が短い断片（岡崎フラグメント）として合成される側の鎖．
- 「ゲノム DNA は二重鎖であり、片方の鎖はセンス鎖(sense strand )、もう一方はアンチセンス鎖(antisense strand )と呼ばれる。センス鎖はワトソン鎖(Watson strand )またはプラス鎖とも呼ばれ、アンチセンス鎖はクリック鎖(Crick strand )またはマイナス鎖とも呼ばれる。」
- https://ja.wikipedia.org/wiki/センス鎖
- https://ja.wikipedia.org/wiki/アンチセンス鎖
- https://www.weblio.jp/content/マイナス鎖
２本鎖DNAの片側の鎖をプラスとした時の反対側の鎖。一本鎖ウイルスの粒子中に取り込まれる側や転写される側の鎖をプラスとすることが多い。

https://www.ncbi.nlm.nih.gov/pubmed/12036591
Gene. 2002 May 1;289(1-2):131-9.
Synonymous codon usage in Pseudomonas aeruginosa PA01.
Grocock RJ1, Sharp PM.
https://www.sciencedirect.com/science/article/pii/S0378111902005036?via%3Dihub
This discordance appears to have arisen because Gupta and Ghosh did not correctly identify which genes are located on the leading and lagging strands. They reported finding only 39% of genes on the leading strand. This would be surprising, since most bacteria have an excess of genes on the leading strand: among nine species previously examined only one (Synechocystis) had as few as 50% of genes on the leading strand (McLean et al., 1998). In fact, we found a majority of genes (56%) on the leading strand in P. aeruginosa. It appears that Gupta and Ghosh counted all genes (whether on the leading or lagging strand) between 0 and 250 kb as ‘leading strand’, and all genes in the remainder of the chromosome as being on the ‘lagging strand’.
*中略*
They based their conclusion about the link between axis 1 and gene expression on this correlation, but that line of reasoning is circular, and led to quite erroneous conclusions.

https://www.ncbi.nlm.nih.gov/pubmed/10075995
Nucleic Acids Res. 1999 Apr 1;27(7):1642-9.
Proteome composition and codon usage in spirochaetes: species-specific and DNA strand-specific mutational biases.
Lafay B1, Lloyd AT, McLean MJ, Devine KM, Sharp PM, Wolfe KH.

https://www.ncbi.nlm.nih.gov/pubmed/9724767
Proc Natl Acad Sci U S A. 1998 Sep 1;95(18):10698-703.
Replicational and transcriptional selection on codon usage in Borrelia burgdorferi.
McInerney JO1.


### Karlin
https://www.ncbi.nlm.nih.gov/pubmed/9928479
Annu Rev Genet. 1998;32:185-225.
Comparative DNA analysis across diverse genomes.
Karlin S1, Campbell AM, Mrázek J.
- CODON BIASES IN BACTERIAL GENOMES
- Anomalies of Ribosomal Proteins

https://www.ncbi.nlm.nih.gov/pubmed/15883368
Proc Natl Acad Sci U S A. 2005 May 17;102(20):7303-8. Epub 2005 May 9.
Predicted highly expressed genes in archaeal genomes.
Karlin S1, Mrázek J, Ma J, Brocchieri L.

[Karlin S (2001) Trends Microbiol. "Detecting anomalous gene clusters and pathogenicity islands in diverse bacterial genomes."](https://www.ncbi.nlm.nih.gov/pubmed/11435108) | [pdf](https://eclass.uoa.gr/modules/document/file.php/D473/Βιβλιογραφία/DNA%20Composition/Karlin_2001.pdf)

http://www.cmbl.uga.edu/software/ASeqH.htm
PHX/PA user guide
Analysis of sequence heterogeneity by sliding window plots

http://www.cmbl.uga.edu/software/PHX-PA-guide.htm
CMBL- PHX/PA user guide

----------

### Amino acid usage

https://www.ncbi.nlm.nih.gov/pubmed/11904428
Proc Natl Acad Sci U S A. 2002 Mar 19;99(6):3695-700.
Metabolic efficiency and amino acid composition in the proteomes of Escherichia coli and Bacillus subtilis.
Akashi H1, Gojobori T.

https://www.ncbi.nlm.nih.gov/pubmed/11965430
J Mol Evol. 2002 May;54(5):563-8.
Trends in codon and amino acid usage in Thermotoga maritima.
Zavala A1, Naya H, Romero H, Musto H.

https://www.ncbi.nlm.nih.gov/pubmed/9461405
Gene. 1997 Dec 31;205(1-2):309-16.
Influence of genomic G+C content on average amino-acid composition of proteins from 59 bacterial species.
Lobry JR1.

https://www.ncbi.nlm.nih.gov/pubmed/8065933
Nucleic Acids Res. 1994 Aug 11;22(15):3174-80.
Hydrophobicity, expressivity and aromaticity are the major trends of amino-acid usage in 999 Escherichia coli chromosome-encoded genes.
Lobry JR1, Gautier C.

#### "amino acid usage" mutational bias

https://www.ncbi.nlm.nih.gov/pubmed/16936139
Mol Biol Evol. 2006 Dec;23(12):2303-15. Epub 2006 Aug 25.
The evolution of biased codon and amino acid usage in nematode genomes.
Cutter AD1, Wasmuth JD, Blaxter ML.

https://www.ncbi.nlm.nih.gov/pubmed/14672975
Genome Res. 2004 Jan;14(1):44-53. Epub 2003 Dec 12.
Mutational and selective pressures on codon and amino acid usage in Buchnera, endosymbiotic bacteria of aphids.
Rispe C1, Delmotte F, van Ham RC, Moya A.

https://www.ncbi.nlm.nih.gov/pubmed/12949182
Microbiology. 2003 Sep;149(Pt 9):2585-96.
Gene expression level influences amino acid usage, but not codon usage, in the tsetse fly endosymbiont Wigglesworthia.

https://www.ncbi.nlm.nih.gov/pubmed/12200484
Mol Biol Evol. 2002 Sep;19(9):1575-84.
A strong effect of AT mutational bias on amino acid usage in Buchnera is mitigated at high-expression genes.
Palacios C1, Wernegreen JJ.

https://www.ncbi.nlm.nih.gov/pubmed/11305938
Genome Biol. 2001;2(4):RESEARCH0010.
A simple model based on mutation and selection explains trends in codon and amino-acid usage and GC composition within and across genomes.
Knight RD1, Freeland SJ, Landweber LF.

https://www.ncbi.nlm.nih.gov/pubmed/11070046
Mol Biol Evol. 2000 Nov;17(11):1581-8.
Nucleotide bias causes a genomewide bias in the amino acid composition of proteins.
Singer GA1, Hickey DA.


----------
## people

### Abe
### Ikemura
### Kanaya

Takashi Abe

https://www.ncbi.nlm.nih.gov/pubmed/11675589
J Mol Evol. 2001 Oct-Nov;53(4-5):290-8.
Codon usage and tRNA genes in eukaryotes: correlation of codon usage diversity with translation efficiency and with CG-dinucleotide usage as assessed by multivariate analysis.
Kanaya S1, Yamada Y, Kinouchi M, Kudo Y, Ikemura T.

https://www.ncbi.nlm.nih.gov/pubmed/11591475
Gene. 2001 Oct 3;276(1-2):89-99.
Analysis of codon usage diversity of bacterial genes with a self-organizing map (SOM): characterization of horizontally transferred genes with emphasis on the E. coli O157 genome.
Kanaya S1, Kinouchi M, Abe T, Kudo Y, Yamada Y, Nishi T, Mori H, Ikemura T.

https://www.ncbi.nlm.nih.gov/pubmed/10570992
Gene. 1999 Sep 30;238(1):143-55.
Studies of codon usage and tRNA genes of 18 unicellular organisms and quantification of Bacillus subtilis tRNAs: gene expression level and species-specific diversity of codon usage based on multivariate analysis.
Kanaya S1, Yamada Y, Kudo Y, Ikemura T.

1989 – 1991
https://kaken.nii.ac.jp/ja/grant/KAKENHI-PROJECT-02238105/
コドン選択

https://www.ncbi.nlm.nih.gov/pubmed/3916708
Mol Biol Evol. 1985 Jan;2(1):13-34.
Codon usage and tRNA content in unicellular and multicellular organisms.
Ikemura T1.

### Musto

https://www.ncbi.nlm.nih.gov/pubmed/23288542
Microbiology. 2013 Mar;159(Pt 3):555-64.
Evolution of optimal codon choices in the family Enterobacteriaceae.
Iriarte A1, Baraibar JD, Romero H, Castro-Sowinski S, Musto H.
https://www.microbiologyresearch.org/content/journal/micro/10.1099/mic.0.061952-0#tab2
- These results were confirmed by means of the estimation of the strength of selection on CU as developed by Sharp et al. (2005).
- Within-group correspondence analysis (WCA) (Charif et al., 2005; Suzuki et al., 2008) was calculated as implemented in the ADE4 package of R (Thioulouse et al., 1997).

https://www.ncbi.nlm.nih.gov/pubmed/10773076
Nucleic Acids Res. 2000 May 15;28(10):2084-90.
Codon usage in Chlamydia trachomatis is the result of strand-specific mutational biases and a complex pattern of selective forces.
Romero H1, Zavala A, Musto H.

### Olsen

http://www.life.illinois.edu/gary/programs/codon_usage.html
Codon Usage Programs

https://www.youtube.com/watch?v=gzYCZ80OygU
The Alien-Looking Codon Usages of Recently Acquired Genes Are Not Alien - Gary Olsen - YouTube
Published on Oct 7, 2015

https://www.ncbi.nlm.nih.gov/pubmed/22128332
Proc Natl Acad Sci U S A. 2011 Dec 13;108(50):20154-9. doi: 10.1073/pnas.1109451108. Epub 2011 Nov 29.
Similarity of genes horizontally acquired by Escherichia coli and Salmonella enterica is evidence of a supraspecies pangenome.
Karberg KA1, Olsen GJ, Davis JJ.

https://www.ncbi.nlm.nih.gov/pubmed/20679093
Mol Biol Evol. 2011 Jan;28(1):211-21. doi: 10.1093/molbev/msq185. Epub 2010 Aug 2.
Characterizing the native codon usages of a genome: an axis projection approach.
Davis JJ1, Olsen GJ.

https://www.ncbi.nlm.nih.gov/pubmed/20018979
Mol Biol Evol. 2010 Apr;27(4):800-10. doi: 10.1093/molbev/msp281. Epub 2009 Dec 17.
Modal codon usage: assessing the typical codon usage of a genome.
Davis JJ1, Olsen GJ.

### Rocha

rRNA/tRNA遺伝子コピー数が多いほど、
rRNA遺伝子の複製起点からの距離が小さいほど、
高発現遺伝子の同義コドン使用バイアスが強い（方言がきつい）ほど、
原核生物の最小倍加時間が小さい（増殖速度が速い）

https://www.ncbi.nlm.nih.gov/pubmed/20090831
PLoS Genet. 2010 Jan 15;6(1):e1000808. doi: 10.1371/journal.pgen.1000808.
The systemic imprint of growth and its uses in ecological (meta)genomics.
Vieira-Silva S1, Rocha EP.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2797632/
- Figure 1
Genomic signatures correlated to minimum generation time (d) for 214 prokaryotes.
Correlation between d and (A) the number of rRNA operons in the genome, (B) the relative distance from the origin of replication to rRNA genes (excluding species with no retrievable origin), 0.5 corresponds to half the replicon, (C,D) codon usage bias indices ΔENC′ [35] and S [46]. Spearman correlations are given (ρ) with all p-values<0.0001. Dashed lines represent the trend of the correlation.
- As expected, we found an increase in copy number of rRNA (Figure 1) and tRNA genes (Figure S1) with decreasing minimal generation times (ρ = −0.59 and ρ = −0.51, all p-value<0.0001). 
- As described above, gene dosage of highly expressed genes can be increased transiently when these genes are located near the origin of replication in fast growing cells. Indeed, a positive correlation was found between minimum generation time and the relative distance to the origin of replication of rRNA genes (ρ = 0.36, Figure 1), RNA polymerase genes (ρ = 0.42), ribosomal proteins coding genes (ρ = 0.42), tRNA (ρ = 0.35) and ubi-tRNA (ρ = 0.41) genes (Figure S2) (all p-values<0.0001).
- Finally, two previously proposed indices of codon usage bias in highly expressed genes ΔENC′ [35] and S [46] correlate negatively with d (respectively, ρ = −0.64 and ρ = −0.54, p-value<0.0001, Figure 1). 
- Following a previous work [35], we extracted from primary literature 214 minimal generation times (d) of species of bacteria and archaea (Table S1). 
- We extracted from primary literature the minimal generation times (d) for the 214 species of bacteria and archaea (Table S1).
- Table S1
List of the 214 genomes composing our dataset and their characteristics. Generation times were retrieved from the literature. We defined the minimum generation time (Column “d”) as the smallest value reported (Column “d reference”) for one species. For very few bacteria the generation times for closely related species were used. The optimum growth temperature of the species (Column “OGT”) was retrieved from DSMZ database.
```
Species name	Ori	OGT	d (h)	d reference
Clostridium acetobutylicum ATCC824	1808	37	0.58	[47]

Clostridium perfringens 13	1784	37	0.2	[48]

Clostridium tetani E88	50965	37	0.5	[49]

Escherichia coli MG1655	3923657	37	0.35	[64]

Geobacter sulfurreducens PCA	1368	30	6	[66]
Mycobacterium leprae	1567	37	240	[101]
Salmonella typhimurium LT2 	4083788	37	0.4	[64]
Shewanella oneidensis MR-1	6419	30	0.66	[138]
```

- The resulting ΔENC′ and S values were then subject to principal components analysis, of which the first component (Fa) was compared with the one obtained from the whole genome.
- Codon usage bias is the best determinant of minimum generation time
- Figure 7
Average predicted minimum generation time for 3 environmental metagenomes.
- Figure 8
Average predicted minimum generation time for the gut metagenomes of humans of different age groups.

https://www.ncbi.nlm.nih.gov/pubmed/15479947
Genome Res. 2004 Nov;14(11):2279-86. Epub 2004 Oct 12.
Codon usage bias from tRNA's point of view: redundancy, specialization, and efficient decoding for translation optimization.
Rocha EP1.
- We show that as minimal generation times get shorter, the genomes contain more tRNA genes, but fewer anticodon species. 
- It also provides new evidence that a selective force for the optimization of the translation machinery is the maximization of growth.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC525687/
- Genome and tRNA data
One hundred and two genomes, corresponding to 102 bacterial species, were retrieved from GenBank (see Supplemental Table 1 for a comprehensive listing). Minimal generation times were taken from the literature or obtained by personal communication with researchers in the field. 
https://genome.cshlp.org/content/14/11/2279.long
https://genome.cshlp.org/content/14/11/2279/suppl/DC1
Supplemental Research Data
https://genome.cshlp.org/content/suppl/2004/10/18/gr.2896904.DC1/tableA1.pdf
Table A1- Data table with major results. 
the growth rate class (μ). the optimal doubling time (1/μ).
```
Clostridium perfringens 13	F	0.2
Escherichia coli K12	F	0.35
Geobacter sulfurreducens PCA	S	6
Mycobacterium leprae	S	12
Salmonella typhimurium LT2	F	0.4
Shewanella oneidensis MR-1	F	2
```

### Sharp

2011
https://www.era.lib.ed.ac.uk/handle/1842/4893
Codon usage bias in Archaea
Emery, Laura R.

https://www.ncbi.nlm.nih.gov/pubmed/20308095
Philos Trans R Soc Lond B Biol Sci. 2010 Apr 27;365(1544):1203-12. doi: 10.1098/rstb.2009.0305.
Forces that influence the evolution of codon bias.
Sharp PM1, Emery LR, Zeng K.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2871821/
- Here we show that the strength of selected codon usage bias is highly correlated with bacterial growth rate, suggesting that selection has favoured translational efficiency. 
- For example, C. perfringens has 10 rRNA operons and 96 tRNA genes and can replicate in only 7 min under ideal conditions (Labbe & Huang 1995).
- To test this association with growth rate, we have used minimum generation time data for 76 of these 80 species, drawn from the compilations made by E.P.C. Rocha (Rocha 2004; Coutourier & Rocha 2006).

https://www.ncbi.nlm.nih.gov/pubmed/17038449
Mol Biol Evol. 2007 Jan;24(1):10-2. Epub 2006 Oct 12.
Predicting gene expression level from codon usage bias.
Henry I, Sharp PM.
https://academic.oup.com/mbe/article/24/1/10/1070854
- We outline a simple approach, first to check whether a genome shows evidence of selected codon usage bias and then to assess the strength of bias in genes as a guide to their likely expression level; we illustrate this with an analysis of Shewanella oneidensis.
- As an example, we have analyzed Shewanella oneidensis, a member of the gamma proteobacteria (Heidelberg et al. 2002). Eighteen codons, for 15 amino acids, occur at significantly higher frequencies in highly expressed genes than in the genome as a whole (see Supplementary Material online). Importantly, these codons do not reflect any simple compositional bias, such as G + U richness due to location of the highly expressed genes on the leading strand of replication. Rather, they include many codons which would be expected to be optimal, either because they are decoded by the most abundant tRNA species (e.g., 6 of the 9 Arg tRNA genes match CGU) or because they are perfectly complementary to the only tRNA species for the amino acid (e.g., UUC, UAC, CAC, AAC, GAC, and GAA). 

細菌の増殖速度、rRNAオペロン数、tRNA遺伝子コピー数、（翻訳の効率と正確度に関連する）高発現遺伝子の同義コドン使用バイアスの相関
https://www.ncbi.nlm.nih.gov/pubmed/15728743
Nucleic Acids Res. 2005 Feb 23;33(4):1141-53. Print 2005.
Variation in the strength of selected codon usage bias among bacteria.
Sharp PM1, Bailes E, Grocock RJ, Peden JF, Sockett RE.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC549432/
- These results are consistent with the hypothesis that species exposed to selection for rapid growth have more rRNA operons, more tRNA genes and more strongly selected codon usage bias. For example, Clostridium perfringens, the species with the highest value of S, can have a generation time as short as 7 min.
- a set of 40 genes expected to be expressed constitutively at very high levels. This set included the genes encoding translation elongation factors Tu (tufA), Ts (tsf) and G (fusA), and 37 of the larger ribosomal proteins (encoded by genes rplA-rplF, rplI-rplT and rpsB-rpsT).
- Inter-specific variation in bacterial growth rate appears to be positively correlated with the number of rRNA operons (42).
- Information regarding the growth rate of bacteria in the wild is sparse, and so we have used the number of rRNA operons as a (very approximate) guide to the growth rate of species. Remarkably, C.perfringens, the species with the highest S-value (2.65) and 10 rRNA operons, can grow with a generation time under 7 min in specific laboratory conditions (55).

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC549432/table/tbl1/
Table 1
The 80 bacterial genome sequences analysed
```
Species codea	Gene numbersb	GC contentc	Sd	Randome	Nf	Accession nosg	Species
rRNA	tRNA	ORF	i	ii	iii					
Gamma proteobacteria

    Sheone	9	100	4630	46	45	37	1.377	(0.313/−0.275)	983	AE014299	Shewenella oneidensis
```

http://www.g-language.org/data/g-language/lib/G/Seq/Codon.pm
```
```

https://www.ncbi.nlm.nih.gov/pubmed/10784043
Microbiology. 2000 Apr;146 ( Pt 4):851-60.
Absence of translationally selected synonymous codon usage bias in Helicobacter pylori.
Lafay B1, Atherton JC, Sharp PM.

https://www.ncbi.nlm.nih.gov/pubmed/8662004
J Mol Evol. 1996 May;42(5):525-36.
Codon usage and base composition in Rickettsia prowazekii.
Andersson SG1, Sharp PM.

https://www.ncbi.nlm.nih.gov/pubmed/3118331
Nucleic Acids Res. 1987 Oct 12;15(19):8023-40.
Synonymous codon usage in Bacillus subtilis reflects both translational selection and mutational biases.
Shields DC1, Sharp PM.

https://www.ncbi.nlm.nih.gov/pubmed/3526280
Nucleic Acids Res. 1986 Jul 11;14(13):5125-43.
Codon usage in yeast: cluster analysis clearly differentiates highly and lowly expressed genes.
Sharp PM, Tuohy TM, Mosurski KR.
Cluster analysis on relative synonymous codon usage revealed two distinct groups of genes. 

----------
### Supek

https://www.ncbi.nlm.nih.gov/pubmed/27915291
Nucleic Acids Res. 2016 Dec 1;44(21):10074-10090. Epub 2016 Oct 24.
The landscape of microbial phenotypic traits and associated genes.
Brbić M1, Piškorec M1, Vidulin V1, Kriško A2, Šmuc T1, Supek F3,4,5.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5137458/
- INTRODUCTION
Statistical associations of genes to phenotypes can implicate certain proteins or pathways, providing insight into the mechanistic basis of phenotypic traits (3,4), as demonstrated for adaptation to stress (5,6), host-association (7,8), pathogenesis (9,10), drug resistance (11,12) and relevance to biotechnological applications (13,14).
- RESULTS
Systematic inference of phenotypes from codon adaptation
Such genomic signatures of translation efficiency within certain gene families have been used to infer the adaptive value of individual genes to various environmental niches (6) and we thus hypothesized that the overall pattern of codon adaptation across many genes of an organism can predict its phenotype (Materials and Methods).
- DISCUSSION
Further generalizing this well-known gene content-based methodology, our work demonstrates how other comparative genomics approaches normally used to predict gene function—here, synteny patterns (58,59) and codon adaptation (6,70)—can be efficiently repurposed into phenotype predictors. 

https://www.ncbi.nlm.nih.gov/pubmed/26538122
J Mol Evol. 2016 Jan;82(1):65-73. doi: 10.1007/s00239-015-9714-8. Epub 2015 Nov 4.
The Code of Silence: Widespread Associations Between Synonymous Codon Biases and Gene Function.
Supek F1,2,3.

コドン適応の変化は（過酸化水素、熱、高塩分）ストレス耐性を増強する。好気性菌で複数遺伝子のコドン適応（翻訳効率）変化が、鉄とNAD(P)Hの量を調節し、酸化ストレス耐性を付与する証拠
https://www.ncbi.nlm.nih.gov/pubmed/24580753
Genome Biol. 2014 Mar 3;15(3):R44. doi: 10.1186/gb-2014-15-3-r44.
Inferring gene function from evolutionary change in signatures of translation efficiency.
Krisko A, Copic T, Gabaldón T, Lehner B, Supek F.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4054840/

https://www.ncbi.nlm.nih.gov/pubmed/26451481
Cell. 2015 Oct 8;163(2):292-300. doi: 10.1016/j.cell.2015.09.041.
Pausing on Polyribosomes: Make Way for Elongation in Translational Control.
Richter JD1, Coller J2.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4600128/

https://www.ncbi.nlm.nih.gov/pubmed/25768907
Cell. 2015 Mar 12;160(6):1111-24. doi: 10.1016/j.cell.2015.02.029.
Codon optimality is a major determinant of mRNA stability.
Presnyak V1, Alhusaini N1, Chen YH1, Martin S1, Morris N2, Kline N1, Olson S3, Weinberg D4, Baker KE1, Graveley BR3, Coller J5.

### Suzuki

人工環境で同定された細菌のゲノムの特徴（ゲノムサイズ、GC含量、DNA複製鎖間の非対称度、コドン使用バイアス）
https://www.ncbi.nlm.nih.gov/pubmed/30691394
BMC Genomics. 2019 Jan 28;20(1):92. doi: 10.1186/s12864-018-5389-z.
Comparative genomics of Bacteria commonly identified in the built environment.
Merino N1,2, Zhang S3,4, Tomita M5,6, Suzuki H7,8.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6350394/

葉緑体のコドン適応
http://www.ncbi.nlm.nih.gov/pubmed/27196606
PLoS One. 2016 May 19;11(5):e0154306.
Codon Adaptation of Plastid Genes.
Suzuki H, Morton BR.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4873144/

ミドリゾウリムシのトランスクリプトーム（RNA-seq）データを用いて、クロレラ共生下で発現低下した遺伝子群では発現量とアミノ酸・同義コドン使用との間の相関が高いこと（ミドリゾウリムシとクロレラの共生に関わる自然選択？）を明らかにした。
http://www.ncbi.nlm.nih.gov/pubmed/26341535
FEBS Lett. 2015 Oct 7;589(20 Pt B):3113-8.
Analysis of amino acid and codon usage in Paramecium bursaria.
Dohra H, Fujishima M, Suzuki H.

同義コドン使用の多様性
http://www.ncbi.nlm.nih.gov/pubmed/19480720
BMC Bioinformatics. 2009 Jun 1;10:167.
Measure of synonymous codon usage diversity among genes in bacteria.
Suzuki H1, Saito R, Tomita M.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2697163/

対応分析
https://www.ncbi.nlm.nih.gov/pubmed/18940873
DNA Res. 2008 Dec;15(6):357-65. doi: 10.1093/dnares/dsn028. Epub 2008 Oct 21.
Comparison of correspondence analysis methods for synonymous codon usage in bacteria.
Suzuki H1, Brown CJ, Forney LJ, Top EM.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2608848/
- Thirdly, genes expressed at high levels in fast-growing bacteria tend to preferentially use translationally optimal codons that are recognized by the most abundant tRNAs. This presumably reflects natural selection for synonymous codons that are translated more efficiently and accurately.7,8 
- Secondly, to analyze the correlation between scores of each of the three axes [Equation (4)] and levels of gene expression (Expression), we tested for the distribution of the axis scores for 40 genes expected to be expressed constitutively at high levels.10 This set included the genes encoding translation elongation factors Tu (tuf), Ts (tsf) and G (fus), and 37 of the larger ribosomal proteins (encoded by genes rplA-rplF, rplI-rplT, and rpsB-rpsT). In each axis, the score for each gene was standardized by subtracting the mean and dividing by the standard deviation of scores for all protein genes. For each axis, Expression was detected as the main source of variation among genes on the axis when the mean absolute standard score for the 40 highly expressed genes was >1.644854 (an interval in which theoretically only 5% of all protein genes are included).
- The third feature, Expression, was detected as a major source of synonymous codon usage variation among genes in C. trachomatis D/UW-3/CX, C. perfringens 13, E. coli K12 MG1655 and H. influenzae Rd KW20, which is consistent with previous findings (Table 2).

http://www.ncbi.nlm.nih.gov/pubmed/18350114
EURASIP J Bioinform Syst Biol. 2007:61374.
Variation in the correlation of G + C composition with synonymous codon usage bias among bacteria.
Suzuki H1, Saito R, Tomita M.

主成分分析
http://www.ncbi.nlm.nih.gov/pubmed/16289058
FEBS Lett. 2005 Nov 21;579(28):6499-504.
A problem in multivariate analysis of codon usage data and a possible solution.
Suzuki H1, Saito R, Tomita M.

同義コドン使用の均等度
http://www.ncbi.nlm.nih.gov/pubmed/15194186
Gene. 2004 Jun 23;335:19-23.
The 'weighted sum of relative entropy': a new index for synonymous codon usage bias.
Suzuki H1, Saito R, Tomita M.

[コドン - Haruo Suzuki / Bioinformatics](http://d.hatena.ne.jp/haruosuz/20130122)

[論文 - Haruo Suzuki / Bioinformatics](http://d.hatena.ne.jp/haruosuz/20090605)

http://www.kri.sfc.keio.ac.jp/report/mori/2005/b-13.html
研究課題名        バイオインフォマティックスによる遺伝暗号解析


----------
## synthetic_biology

https://ja.wikipedia.org/wiki/合成生物学
安価で大規模にコドンを変化させて遺伝子発現を改善したり、新たなアミノ酸を導入する手法などによる研究がなされている[3]。

https://wired.jp/2018/01/06/semi-synthetic-organism/
6つのコードをもつ「半合成生物」で、自然界に存在しないタンパク質を生み出すことに成功：研究結果｜WIRED.jp

https://www.sciencedirect.com/science/article/pii/S2588933818300104
Synthetic biology: Recent progress, biosafety and biosecurity concerns, and possible solutions - ScienceDirect
```
2.1. 
A “codon harmonization” algorithm has been devised to improve functional protein expression.23 
2.2. 
For example, the replication and infectivity of poliovirus can be reduced through genome scale changes in codon sets in the genome; this approach makes the poliovirus vaccines safer.26 
4.2. 
In addition, a strategy focusing on stop codon suppression has been proposed because three stop codons are responsible for terminating protein biosynthesis in organisms. When the function of a stop codon is suppressed or altered by introducing a new engineered aminoacyl-tRNA synthetase::tRNAs pairs into the cells, it will force the cell to use several noncanonical amino acid codes as stop codons, such as l-4,4′-biophenylalanine. A redesigned essential enzyme named “bipA aminoacyl-tRNA synthetase (bipARS)/tRNAbipA system” has been constructed in E. coli strain C321.ΔA, and the UAG stop codon was assigned to a nonstandard amino acid.69 
```

 2018-12-21
https://www.labinnew.net/column3_artificial_gene/
連載　西村尚子の生命科学探訪③人工塩基でコドンを拡張し、細胞に新規タンパク質を作らせる – Lab'in New

https://seikagaku.jbsoc.or.jp/10.14952/SEIKAGAKU.2015.870101/data/index.html
DNAの文字を増やす合成生物学—Xenobiologyに向けて

http://tenure5.vbl.okayama-u.ac.jp/HM_blog/?s=コドン
コドン | 酵母とシステムバイオロジー
- 2015-03-20 コドンの最適度はmRNAの安定性を決める主要な要因である。
- 2011-08-31 合成遺伝子で「コドンの最適化」をどう行なうのか？

2017/1/18
http://yfuruta.sakura.ne.jp/blog/?p=824
コドン最適化

2013年 第11号
https://www.sbj.or.jp/wp-content/uploads/file/sbj/9111/9111_biomedia_2(1).pdf
コドンが決め手!?組換えタンパク質の高発現法 今中 洋行

http://www.genscript.jp/codon-opt.html
Codon Optimization - Increase Protein Expression
http://www.genscript.jp/high-throughput-gene-synthesis.html
コドン最適化無料：独自のOptimumGene™コドン最適化ツールを無料で提供します。

----------
## japanese

https://www.nig.ac.jp/museum/evolution/04.html
遺伝暗号(コドン）使用の種による多様性

2.単細胞微生物のコドン選択の生物種による方言;
　 大腸菌とサルモネラ菌ならびに酵母遺伝子に見られるコドン選択の偏りを例に

３．コドン使用とtRNA量との関係、遺伝子工学との係り
タンパク質生産量の高い遺伝子ほどコドン選択の方言がきつく、生産量が下がるにつれて、同質の方言を用いながらも、方言の程度が緩くなることを指摘しました。

４．コドン使用とゲノム解析との係り
単細胞微生物の場合、各遺伝子のコドン使用パターンが、そのタンパク質の細胞内存在量、すなわち生産量と関係しています。各遺伝子がどの程度にtRNA量に適合した同義コドンを使用しているのかを定量化することで、タンパク質生産量を推定することが可能になっています(11-16,20,21)。タンパク質の細胞内における存在量は、その機能を推定する上で重要な知見であり、ゲノム解析においてこの面でも重要な貢献が期待できます。

https://bio.edu-wiki.org/コドン表

浜島 聖文，金井 昭夫 著 - ‎2014
http://www.jbsoc.or.jp/seika/wp-content/uploads/2015/03/86-04-10.pdf
普遍遺伝暗号表に従わない tRNA

https://twitter.com/yuifu/status/210003682958389252
Haruka Ozaki on Twitter: "バイオインフォだけでCell（実験はtRNAマイクロアレイだけ）．真核生物，真正細菌，古細菌の500種のゲノムでtRNA遺伝子の数とコドン使用頻度の相関を確認．tRNA修飾酵素によるペア拡大を考慮したのが新規？ http://t.co/fialW5zx #Everydayペーパー"
9:42 AM - 5 Jun 2012

2010-08-25
http://d.hatena.ne.jp/morimori-08/20100825/1282745255
コドンバイアスはタンパク質のフォールディングのエラーを少なくする

蛋白質核酸酵素 42(11), 1815-1827, 1997-08
https://ci.nii.ac.jp/naid/40002328271/
多義語コドンの発見--複数のアミノ酸と結合するファジ-なtRNA


----------
## unclassified

----------



