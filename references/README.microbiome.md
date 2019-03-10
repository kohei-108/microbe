Haruo Suzuki (haruo[at]g-language[dot]org)  
Last Update: 2019-03-10

----------

# microbiome
**微生物群集**

## Table of Contents

- [featuring](#featuring)
- [updates](#updates)
- [forensic](#forensic) 法科学
- [host](#host) 宿主
- [16S](#16s)
- [amplicon-shotgun](#amplicon-shotgun)
- [mothur-qiime](#mothur-qiime)
- [American Gut](#american-gut)
- [Artificial sweeteners](#artificial-sweeteners)
- [Earth Microbiome Project](#emp)
- [meta-analysis](#meta-analysis)
- [UniFrac](#unifrac)
- [unclassified](#unclassified)

----------

https://github.com/haruosuz/metasub
MetaSUB: Metagenomics & Metadesign of Subways & Urban Biomes
都市の微生物群集

----------
## featuring

----------
## updates

### 2019

国際会議のデータ解析イベント
https://twitter.com/CAMDA_conf
CAMDA 2019 (@CAMDA_conf) | Twitter
International Conference on Critical Assessment of Massive Data Analysis

http://camda.info/
The Metagenomic Forensics Challenge presents thousands of city microbiome profiles in a global context. Construct multi-source microbiome fingerprints and predict the geographical origin of mystery samples.

ISMB/ECCB 2019 (21–25 Jul 2019) / CAMDA2019 (24-25 Jul 2019) @ Basel, Switzerland


### 2018

https://www.ncbi.nlm.nih.gov/pubmed/29950328
J Clin Microbiol. 2018 Aug 27;56(9). pii: e00813-18. doi: 10.1128/JCM.00813-18. Print 2018 Sep.
Lowering the Barriers to Routine Whole-Genome Sequencing of Bacteria in the Clinical Microbiology Laboratory.
Rhoads DD1,2.


https://www.ncbi.nlm.nih.gov/pubmed/29460198
J Plant Res. 2018 Jul;131(4):709-717. doi: 10.1007/s10265-018-1017-x. Epub 2018 Feb 19.
Collaborative environmental DNA sampling from petal surfaces of flowering cherry Cerasus × yedoensis 'Somei-yoshino' across the Japanese archipelago.
Ohta T1, Kawashima T2, Shinozaki NO3, Dobashi A4, Hiraoka S5, Hoshino T6, Kanno K7, Kataoka T8, Kawashima S9, Matsui M10, Nemoto W11, Nishijima S12,13,14, Suganuma N15, Suzuki H16, Taguchi YH17, Takenaka Y18, Tanigawa Y19, Tsuneyoshi M20, Yoshitake K21, Sato Y22, Yamashita R22, Arakawa K23, Iwasaki W10.

Fig.2: "Deblur" -> "Deblur or DADA2" に修正し
https://twitter.com/merenbey/status/999416078446071809
A. Murat Eren (Meren) on Twitter: "This is unfair to DADA2
6:25 PM - 23 May 2018

----------
## forensic
https://ja.wikipedia.org/wiki/法科学

https://twitter.com/search?q=forensic%20microbiome

https://microbiomedigest.com/microbiome-papers-collection/non-human-microbiome-paper-collection/forensic-microbiology/
Forensic Microbiology | Microbiome Digest - Bik's Picks

https://www.nij.gov/topics/forensics/evidence/Pages/microbiome.aspx
Forensic Applications of Microbiomes

https://www.npa.go.jp/nrips/jp/first/section5.html
生物第五研究室 - 科学警察研究所

2018.3.20 07:30
https://www.sankei.com/west/news/180320/wst1803200001-n1.html
皮膚のウイルスに日本人特有のＤＮＡ、犯罪捜査への応用も…高知大チームが発見（1/3ページ） - 産経ニュース

https://www.jcvi.org/forensics-microbiome-database
Forensics Microbiome Database | J. Craig Venter Institute
https://www.ncbi.nlm.nih.gov/pubmed/28728057
Forensic Sci Int Genet. 2017 Sep;30:141-147. doi: 10.1016/j.fsigen.2017.06.008. Epub 2017 Jun 27.
Integrating the microbiome as a resource in the forensics toolkit.
Clarke TH1, Gomez A1, Singh H1, Nelson KE1, Brinkac LM2.

https://www.ncbi.nlm.nih.gov/pubmed/28887423
Appl Environ Microbiol. 2017 Sep 8. pii: AEM.01672-17. doi: 10.1128/AEM.01672-17. [Epub ahead of print]
Forensic human identification using skin microbiomes.
Schmedes SE1,2, Woerner AE2, Budowle B3,4.

2017-07-20
https://katosei.jsbba.or.jp/view_html.php?aid=840
https://www.jstage.jst.go.jp/article/kagakutoseibutsu/55/8/55_559/_pdf
犯罪捜査におけるDNA鑑定によるヒトの異同識別
微生物群集構造プロファイリングによる新たな法科学的手法の可能性

https://www.ncbi.nlm.nih.gov/pubmed/28244273
Microb Biotechnol. 2017 Mar;10(2):228-230. doi: 10.1111/1751-7915.12699.
The human microbiome: an emerging tool in forensics.
Hampton-Marcell JT1,2,3, Lopez JV4, Gilbert JA1,3,5.

https://nge.jp/2015/05/16/post-104618
犯罪捜査の手掛かりとなるか？体内細菌群から個人を特定する研究結果が発表 | FUTURUS（フトゥールス）
https://www.ncbi.nlm.nih.gov/pubmed/25964341
Proc Natl Acad Sci U S A. 2015 Jun 2;112(22):E2930-8. doi: 10.1073/pnas.1423854112. Epub 2015 May 11.
Identifying personal microbiomes using metagenomic codes.
Franzosa EA1, Huang K2, Meadow JF3, Gevers D2, Lemon KP4, Bohannan BJ3, Huttenhower C5.
forensic genetics; human microbiome; metagenomics; microbial ecology; strain variation

https://wired.jp/2015/10/11/bacteria-clouds/
人間は「微生物のクラウド」に包まれている：マイクロバイオーム最新研究より｜WIRED.jp

https://gigazine.net/news/20151012-microbial-cloud/
各個人が固有で持ち、指紋やDNAのように個人を特定できる「微生物雲」とは？ - GIGAZINE
その結果、人間は1時間あたり100万個のバクテリアを空気中に放出しており、実験開始から4時間程度でそれぞれの被験者を明確に区別できるほどの特徴を持つパターンが確認されたとのこと。確認されたバクテリアは連鎖球菌やプロピオン酸菌属、コリネバクテリウム属に含まれるものだったそうです。
![https://gigazine.net/news/20151012-microbial-cloud/](https://i.gzn.jp/img/2015/10/12/microbial-cloud/01_m.png)
https://www.ncbi.nlm.nih.gov/pubmed/26417541
PeerJ. 2015 Sep 22;3:e1258. doi: 10.7717/peerj.1258. eCollection 2015.
Humans differ in their personal microbial cloud.
Meadow JF1, Altrichter AE1, Bateman AC1, Stenson J2, Brown GZ2, Green JL3, Bohannan BJ1.

https://www.natureasia.com/static/ja-jp/ndigest/pdf/v5/n10/ndigest.2008.081034.pdf
microbial forensics: 微生物法医学、微生物鑑識学

----------
## host
宿主

https://www.ncbi.nlm.nih.gov/pubmed/29629413
mSystems. 2018 Mar 20;3(2). pii: e00174-17. doi: 10.1128/mSystems.00174-17. eCollection 2018 Mar-Apr.
Role of the Gut Microbiome in Vertebrate Evolution.
Sharpton TJ1,2.

https://twitter.com/animalculum/status/946402176921980928
Lukas VF Novak on Twitter: ""We compare microbiomes from human populations, placing them in the context of microbes from humanity’s near and distant animal relatives. We discuss potential mechanisms to generate host-specific microbiome configurations and the consequences of disrupting those configurations"… https://t.co/XAtRg1eMDk"
10:27 AM - 28 Dec 2017
https://www.ncbi.nlm.nih.gov/pubmed/29282061
BMC Biol. 2017 Dec 27;15(1):127. doi: 10.1186/s12915-017-0454-7.
The human microbiome in evolution.
Davenport ER1, Sanders JG2, Song SJ2, Amato KR3, Clark AG1, Knight R4,5,6.

https://www.ncbi.nlm.nih.gov/pubmed/28770836
Nature. 2017 Aug 2;548(7665):43-51. doi: 10.1038/nature23292.
The evolution of the host microbiome as an ecosystem on a leash.
Foster KR1, Schluter J2, Coyte KZ1,2,3, Rakoff-Nahoum S3.

2017年8月
http://www.nikkei-science.com/page/sci_book/bessatu/51221_prologue.html
人と微生物の深くて長い関係 | 日経サイエンス

「会話するバクテリア」で描かれているように，細菌もまた，代謝産物を使って他の細菌や宿主と頻繁に情報交換している。宿主との会話は往々にして「一方的」ではあるが，感染症の治療の標的として注目されている。
　続く第2章「共生と進化」では，宿主と微生物の間の相互作用や，それによる進化の様子を紹介している。「細菌が操る性転換」は，昆虫に広く分布しその生殖に大きな影響を与えているボルバキア菌についての詳しい解説だ。
「ウイルスは生きているのか」では，最近発見された巨大ウイルスの話題や，ウイルスが宿主の進化に貢献してきた可能性を紹介している。
　「脳を操る寄生生物トキソプラズマ」は，単細胞の真核生物である原虫の一種，トキソプラズマの話である。トキソプラズマが発見されたのは100年以上昔のことであるが，宿主である動物に異常な行動を引き起こすことが報告されたのは比較的最近だ。

2007 年
https://www.jstage.jst.go.jp/article/seitai/57/3/57_KJ00004816813/_article/-char/ja/
消化管共生微生物を介した動物の環境適応
https://www.jstage.jst.go.jp/article/seitai/57/3/57_KJ00004816813/_pdf
腸内微生物群集はどのように形作られるのだろうか？
生まれる前の動物の消化管は通常無菌である（

----------
## amplicon-shotgun

targeted amplicon sequencing (16S, 18S, ITS) vs. shotgun sequencing (metagenomics)

https://www.ncbi.nlm.nih.gov/pubmed/28337071
J Biomol Tech. 2017 Apr;28(1):8-18. doi: 10.7171/jbt.17-2801-006. Epub 2017 Mar 17.
International Standards for Genomes, Transcriptomes, and Metagenomes.
Mason CE1, Afshinnekoo E2, Tighe S3, Wu S4, Levy S5.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5359768/table/T3/
TABLE 3
Comparison of metagenomic assay capabilities and limitations

https://www.ncbi.nlm.nih.gov/pubmed/28761145
Sci Rep. 2017 Jul 31;7(1):6589. doi: 10.1038/s41598-017-06665-3.
Large-scale differences in microbial biodiversity discovery between 16S amplicon and shotgun sequencing.
Tessler M1,2, Neumann JS3, Afshinnekoo E4,5,6, Pineda M4,5, Hersch R7, Velho LFM8,9, Segovia BT8, Lansac-Toha FA8, Lemke M10, DeSalle R7, Mason CE11,12,13, Brugler MR14,15.

https://www.ncbi.nlm.nih.gov/pubmed/21121044
Pac Symp Biocomput. 2011:165-76.
Comparing bacterial communities inferred from 16S rRNA gene sequencing and shotgun metagenomics.
Shah N1, Tang H, Doak TG, Ye Y.

----------
## Knight R

https://knightlab.ucsd.edu/wordpress/?page_id=25

https://www.ncbi.nlm.nih.gov/pubmed/29795328
Nat Rev Microbiol. 2018 Jul;16(7):410-422. doi: 10.1038/s41579-018-0029-9.
Best practices for analysing microbiomes.
Knight R1,2,3, Vrbanac A4, Taylor BC4, Aksenov A5, Callewaert C6,7, Debelius J6, Gonzalez A6, Kosciolek T6, McCall LI5, McDonald D6, Melnik AV5, Morton JT6,8, Navas J8, Quinn RA5, Sanders JG6, Swafford AD9, Thompson LR10,11, Tripathi A12, Xu ZZ6, Zaneveld JR13, Zhu Q6, Caporaso JG14, Dorrestein PC9,5,6.

https://www.ncbi.nlm.nih.gov/pubmed/29795540
Nat Microbiol. 2018 Jun;3(6):652-661. doi: 10.1038/s41564-018-0156-0. Epub 2018 May 24.
Methods for phylogenetic analysis of microbiome data.
Washburne AD1, Morton JT2,3, Sanders J3, McDonald D3, Zhu Q3, Oliverio AM4,5, Knight R2,3.

----------
## Mason CE

https://www.ncbi.nlm.nih.gov/pubmed/29930288
Nat Rev Microbiol. 2018 Jun 21. doi: 10.1038/s41579-018-0047-7. [Epub ahead of print]
Surveying what's flushed away.
Iraola G1,2,3, Kumar N3.
https://www.nature.com/articles/s41579-018-0047-7

https://www.ncbi.nlm.nih.gov/pubmed/29890228
Drug Discov Today. 2018 Jun 8. pii: S1359-6446(17)30357-4. doi: 10.1016/j.drudis.2018.06.005. [Epub ahead of print]
Interrogating the microbiome: experimental and computational considerations in support of study reproducibility.
Poussin C1, Sierro N1, Boué S1, Battey J1, Scotti E1, Belcastro V1, Peitsch MC1, Ivanov NV1, Hoeng J2.
Review
Informatics

https://link.springer.com/protocol/10.1007/978-1-4939-7463-4_8
Comparative Metagenomics | SpringerLink
Andrew Maltez ThomasFelipe Prata LimaLivia Maria Silva MouraAline Maria da SilvaEmmanuel Dias-NetoJoão C. SetubalEmail author
Protocol
First Online: 26 December 2017

https://www.ncbi.nlm.nih.gov/pubmed/28978331
Microbiome. 2017 Oct 4;5(1):132. doi: 10.1186/s40168-017-0349-4.
Communicating the promise, risks, and ethics of large-scale, open space microbiome and metagenome research.
Shamarina D1, Stoyantcheva I1, Mason CE2,3,4, Bibby K5, Elhaik E6.

https://www.ncbi.nlm.nih.gov/pubmed/28934964
Genome Biol. 2017 Sep 21;18(1):182. doi: 10.1186/s13059-017-1299-7.
Comprehensive benchmarking and ensemble approaches for metagenomic classifiers.
McIntyre ABR1,2,3, Ounit R4, Afshinnekoo E2,3,5, Prill RJ6, Hénaff E2,3, Alexander N2,3, Minot SS7, Danko D1,2,3, Foox J2,3, Ahsanuddin S2,3, Tighe S8, Hasan NA9,10, Subramanian P9, Moffat K9, Levy S11, Lonardi S4, Greenfield N7, Colwell RR9,12, Rosen GL13, Mason CE14,15,16.

https://www.ncbi.nlm.nih.gov/pubmed/28349976
Nat Microbiol. 2017 Mar 28;2:16275. doi: 10.1038/nmicrobiol.2016.275.
Geomicrobiology of the built environment.
Gadd GM1.
http://www.nature.com/articles/nmicrobiol2016275

https://www.ncbi.nlm.nih.gov/pubmed/27941038
Br Med Bull. 2016 Dec;120(1):27-33. Epub 2016 Nov 23.
Globalizing and crowdsourcing biomedical research.
Afshinnekoo E1,2,3, Ahsanuddin S1,2,4, Mason CE5,2,6.

----------
## mothur-qiime
https://mothur.org

https://www.pediatricsurgery.site/entry/2017/11/19/200241
mothur開発者によるmothurとQIIMEの比較 - Note of Pediatric Surgery

https://biosciencedbc.jp/gadget/human/170831_mori_170830.pdf
メタ16S解析利点
・マシンパワーは少なくて済み、解析ツールも普及(QIIME・mothur等)

https://www.jstage.jst.go.jp/article/jim/29/3/29_135/_article/-char/ja/
総　　説 ＜特集：腸内細菌叢Microbiotaの分子生物学的解析法の成果と未来＞
進化する次世代シーケンサーによる腸内細菌叢の解析
東 佳那子, 中山 二郎
2015 年 29 巻 3 号 p. 135-144
https://www.jstage.jst.go.jp/article/jim/29/3/29_135/_pdf
データセットは,16S rRNA 配列から菌叢データを 得るためのオープンソースソフトウェアを開発してい る Mothur プロジェクト(4)が,Silva の 16S rRNA の全長配列データベースから 14,956 本を網羅的に抽出 し作成したデータセット silva.bacteria.fasta を用いた(http://www.mothur.org/wiki/Silva_reference_files).

ここで は,Mothur 同様,菌叢解析のオープンソースソフトウェ アである QIIME(Quantitative Insights into Microbial Ecology, http://qiime.org/)(5) の assign_taxonomy.py のプログラムの uclust のアルゴリズムを用いた.

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3775626/
PeerJ. 2013; 1: e157.
Abundance-weighted phylogenetic diversity measures distinguish microbial community states and are robust to sampling depth

In microbial ecology studies, the most commonly used ways of investigating alpha (within-sample) diversity are either to apply non-phylogenetic measures such as Simpson’s index to Operational Taxonomic Unit (OTU) groupings, or to use classical phylogenetic diversity (PD), which is not abundance-weighted. 

As of the publication of this paper, no abundance-weighted phylogenetic alpha diversity measures are implemented in either mothur (Schloss et al., 2009) or QIIME (Caporaso et al., 2010), two of the most popular tools for analysis of microbial ecology data. 


----------
## Greengenes

http://greengenes.secondgenome.com
The Greengenes Database

http://greengenes.secondgenome.com/downloads
Download Area

----------
## RDP

https://www.ncbi.nlm.nih.gov/pubmed/24288368
Nucleic Acids Res. 2014 Jan;42(Database issue):D633-42. doi: 10.1093/nar/gkt1244. Epub 2013 Nov 27.
Ribosomal Database Project: data and tools for high throughput rRNA analysis.
Cole JR1, Wang Q, Fish JA, Chai B, McGarrell DM, Sun Y, Brown CT, Porras-Alfaro A, Kuske CR, Tiedje JM.

http://rdp.cme.msu.edu
RDP Release 11 -- Sequence Analysis Tools

http://rdp.cme.msu.edu/misc/resources.jsp
RDP Resource Download Area

----------
## 16S

https://www.biorxiv.org/content/early/2018/10/13/441576
Nomenclature Errors in Public 16S rRNA Gene Reference Databases

https://www.ncbi.nlm.nih.gov/pubmed/29506021
Bioinformatics. 2018 Jul 15;34(14):2371-2375. doi: 10.1093/bioinformatics/bty113.
Updating the 97% identity threshold for 16S ribosomal RNA OTUs.
Edgar RC1.

https://www.ncbi.nlm.nih.gov/pubmed/29688343
FEMS Microbiol Lett. 2018 May 1;365(10). doi: 10.1093/femsle/fny104.
A town on fire! Integrating 16S rRNA gene amplicon analyses into an undergraduate microbiology lecture class.
Tobin TC1, Shade A2.
In this module, microbiology students used Quantitative Insights into Microbial Ecology (QIIME) to perform taxonomic, phylogenetic and statistical analyses on bacterial communities from three hot mine fire-impacted surface soils using 16S rRNA gene amplicon sequences. 

https://twitter.com/BioMickWatson

https://www.ncbi.nlm.nih.gov/pubmed/29427429
Appl Environ Microbiol. 2018 Mar 19;84(7). pii: e02627-17. doi: 10.1128/AEM.02627-17. Print 2018 Apr 1.
The Madness of Microbiome: Attempting To Find Consensus "Best Practice" for 16S Microbiome Studies.
Pollock J#1,2, Glendinning L#2, Wisedchanwet T2, Watson M2.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5861821/
Of the three most commonly used alignments which are guided by secondary structure (i.e., Greengenes [73], RDP [74], and SILVA [75]), the Greengenes alignment was observed to be of poor quality, leading to significantly greater richness and diversity estimates.

https://www.microbe.net/2018/03/03/the-attempt-to-find-best-practice-for-16s-studies/
The attempt to find “best practice” for 16S studies – microBEnet: the microbiology of the Built Environment network

https://www.ncbi.nlm.nih.gov/pubmed/29305502
Appl Environ Microbiol. 2018 Mar 1;84(6). pii: e00014-18. doi: 10.1128/AEM.00014-18. Print 2018 Mar 15.
How Much Do rRNA Gene Surveys Underestimate Extant Bacterial Diversity?
Rodriguez-R LM1,2,3, Castro JC1,2, Kyrpides NC4, Cole JR5,6, Tiedje JM5,7,6, Konstantinidis KT8,2,3.

https://twitter.com/BioMickWatson/status/968147242401058817
Mick Watson on Twitter: "If you're working in 16S microbiome research, please read our paper which tries to suggest best practices! https://t.co/XWVRxUKFRW"
The madness of microbiome: Attempting to find consensus “best practice” for 16S microbiome studies
10:34 AM - 26 Feb 2018

https://twitter.com/search?q=ゲノム%2016S

https://twitter.com/Tyu_Shi/status/969218896371707904
16S rRNA遺伝子配列で85%以下のIdentityの場合には、近縁系統のゲノム内16S rRNA遺伝子コピー数を補正に使うと補正精度が悪くなるという結果を出し、それを根拠にCopyRighter等の既存の補正ツールを批判しているが、そんな遠い系統を基準に補正をしては精度が下がるのは当然だ。
9:32 AM - 1 Mar 2018

https://twitter.com/yokadzaki/status/968841333400944640
Yusuke Okazaki on Twitter: "16Sアンプリコンseqで各系統のrrnオペロンのコピー数の違いの補正に近縁系統の情報を使う方法はアテにならないので、補正しないで済むデータの使い方をしたほうがマシである、という論文"
8:32 AM - 28 Feb 2018

https://twitter.com/yokadzaki/status/968837626013794304
Yusuke Okazaki on Twitter: "この論文はBioRxivのコメント欄でやりあっていて面白いので併せて読んだほうがよい https://t.co/dq9i5so7XG"
8:17 AM - 28 Feb 2018

https://twitter.com/yokadzaki/status/949628412804481025
DB上の細菌ゲノムを使って、全ゲノム>95％で定義されるOTUと16S rRNA>97%で定義されるOTUがどれくらい乖離しているのかを調べた研究。その乖離度が系統によって大きく異なるという結果も（予想通りだけど）面白い。ゲノムサイズが関係ありそうな結果だけど、本文には言及が無かった
8:07 AM - 6 Jan 2018

https://twitter.com/yokadzaki/status/940465660852703232
ゲノムサイズが小さいもの同士でも「近縁系統とのゲノムの違いがどれくらい連続的か」というのに系統間で明らかな差があるというのは面白い。そしてこの結果は「16Sで見えていたものはバイアスだらけ」ということも意味している
1:17 AM - 12 Dec 2017

https://twitter.com/yokadzaki/status/936042447452323840
それを「種」と呼んでいいのかは分からないけど、全ゲノムの相同性で明確に他の系統と区別できる（中間的なものが存在しない）形でクラスターができるという報告が増えてきて、16Sで>97%とかいう謎の基準に依存した研究はもうじき過去のものになりそう
8:21 PM - 29 Nov 2017

https://www.pediatricsurgery.site/entry/2017/11/19/200241
mothur開発者によるmothurとQIIMEの比較 - Note of Pediatric Surgery

mothurではRDP、SILVA、greengenesを使用することができる

https://www.ncbi.nlm.nih.gov/pubmed/28705636
J Biotechnol. 2017 Nov 10;261:2-9. doi: 10.1016/j.jbiotec.2017.07.010. Epub 2017 Jul 10.
A review of bioinformatics platforms for comparative genomics. Recent developments of the EDGAR 2.0 platform and its utility for taxonomic and phylogenetic studies.
Yu J1, Blom J2, Glaeser SP3, Jaenicke S4, Juhre T4, Rupp O4, Schwengers O4, Spänig S4, Goesmann A4.
https://www.sciencedirect.com/science/article/pii/S0168165617315225
But, because it is well known that the phylogenetic resolution of the primary phylogenetic marker, the 16S rRNA gene, is limited at the lower taxonomic levels, the integration of a genome sequence based phylogeny into the polyphasic approach of the prokaryotic taxonomy and systematics is the clear consequence in the genome area (Chun and Rainey, 2014, Ramasamy et al., 2014, Oren and Garrity, 2014, Vandamme and Peeters, 2014, Sangal et al., 2016).

https://www.ncbi.nlm.nih.gov/pubmed/28662636
BMC Genomics. 2017 Jun 29;18(1):499. doi: 10.1186/s12864-017-3888-y.
Relating genomic characteristics to environmental preferences and ubiquity in different microbial taxa.
Cobo-Simón M1, Tamames J2.

https://www.researchgate.net/post/Is_Greengenes_or_SILVA_better_for_bacterial_microbiome_studies
Is Greengenes or SILVA better for bacterial microbiome studies?

https://www.ncbi.nlm.nih.gov/pubmed/28361695
BMC Genomics. 2017 Mar 14;18(Suppl 2):114. doi: 10.1186/s12864-017-3501-4.
SILVA, RDP, Greengenes, NCBI and OTT - how do these taxonomies compare?
Balvočiūtė M1, Huson DH2.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5374703/
For the comparisons we used a taxonomy associated with the Greengenes database as released on May 2013. Although Greengenes is still included in some metagenomic analyses packages, for example QIIME [22], it has not been updated for the last three years.

Mar 2017
https://forum.qiime2.org/t/classification-using-greengenes-v-silva/409
Classification using GreenGenes v. SILVA - User support - QIIME 2 Forum

https://www.ncbi.nlm.nih.gov/pubmed/27166378
Nucleic Acids Res. 2016 Jun 20;44(11):5022-33. doi: 10.1093/nar/gkw396. Epub 2016 May 10.
Phylogeny-aware identification and correction of taxonomically mislabeled sequences.
Kozlov AM1, Zhang J2, Yilmaz P3, Glöckner FO4, Stamatakis A5.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4914121/
First, we evaluate taxonomic annotations of type strains only, using the same sequence set and alignment (LTP v123) for all four databases (data sets GG13_T, LTP123_T, RDP11_T and SLV123_T in Table ​Table1).1). 

http://blog.mothur.org/2015/08/04/No-greengenes-hasnt-improved/
No, greengenes' reference alignment hasn't improved

- SILVA (good for alignment and classification)
- greengenes (good for alignment and classification)
- RDP (good for classification)

https://www.ncbi.nlm.nih.gov/pubmed/27603265
Genome. 2016 Oct;59(10):783-791. Epub 2016 May 11.
bcgTree: automatized phylogenetic tree building from bacterial core genomes.
Ankenbrand MJ1,1, Keller A1,1.
The need for multi-gene analyses in scientific fields such as phylogenetics and DNA barcoding has increased in recent years. In particular, these approaches are increasingly important for differentiating bacterial species, where reliance on the standard 16S rDNA marker can result in poor resolution. 

https://www.ncbi.nlm.nih.gov/pubmed/23460914
PLoS One. 2013;8(2):e57923. doi: 10.1371/journal.pone.0057923. Epub 2013 Feb 27.
The variability of the 16S rRNA gene in bacterial genomes and its consequences for bacterial community analyses.
Větrovský T1, Baldrian P.


2017/08/30
https://www.aist.go.jp/aist_j/press_release/pr2017/pr20170830/pr20170830.html
産総研：進化系統分類の指標となる16S rRNA遺伝子の進化的な中立性を実験的に証明

https://www.nite.go.jp/nbrc/safety/risk_assessment.html
微生物利用におけるリスク評価に関する技術情報の提供 | バイオテクノロジー | 製品評価技術基盤機構
DDHにおける菌種判定の閾値である類似度70%は、ANIにおいて95-96%に相当すると報告されています。このことから、近年では、DDHの代替としてANIに基づく新種の提案が行われてきています(Baek et al. 2015, IJSEM 65: 504; Shahraki et al. 2015, IJSEM 65: 504)。
OTUとは、ある一定以上の類似性（一般的には96-97%）を持つ配列同士を一つの菌種のように扱うための操作上の分類単位です。

バイオレメディエーションにおける生態系影響評価手法	Illumina社MiSeqシーケンサーを用いた、環境中の微生物生態系解析の実験手法およびパイプラインツール「QIIME」を用いたデータ解析手法の手順書です。 2016年3月25日 https://www.nite.go.jp/data/000081956.pdf

https://seikagaku.jbsoc.or.jp/10.14952/SEIKAGAKU.2015.870475/data/index.html
Journal of Japanese Biochemical Society 87(4): 475-477 (2015)
16SリボソームRNAの水平伝播実験からみえてくるリボソームの可塑性
佃 美雪1,2，宮崎 健太郎1,3

https://www.jstage.jst.go.jp/article/kagakutoseibutsu/52/2/52_70/_pdf
化学と生物 Vol. 52, No. 2, 2014
16S rRNA遺伝子の「水平伝播」
異種16S rRNAによる遺伝的相補

2014
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3903645/
MetaMetaDB: A Database and Analytic System for Investigating Microbial Habitability

Therefore, MetaMetaDB chooses the hits exhibiting above 97%, 95%, 90%, 85%, and 80% identity from the search result list, which correspond approximately to the taxonomic levels of species, genus, family, order, and class [1], respectively, 

02/02/13
http://www.jarmam.gr.jp/situmon/16sr_rna.html
16s rRNA の相同性と同定精度の関係は???
一般的には, 97%以上の相同性があれば類縁関係があり、99%以上であれば同種である可能性が高いとしています。
極端な例では, 100%の相同性が認められても, 属レベルで異なる例さえ示されているのです。

2012 年
https://www.jstage.jst.go.jp/article/jslab/23/1/23_24/_pdf
総説
16S rRNA 遺伝子の大量シークェンシングによる 菌叢解析の現状と問題点
是則 有希, Jiahui Jiang, 中山 二郎
属レベルまでの菌叢プロファイルであ れば、Ribosomal Database Project I(I 以下、RDP II)のウェ ブサイトにある RDP classifier を用いることで容易に菌叢 プロファイルに変換することができる。
一方、種レベルでの菌叢データを得ることは非常に困難 である。実際に、理論上 16S rRNA 遺伝子の部分配列か ら種を特定することは不可能であり、

http://www.aist.go.jp/aist_j/press_release/pr2012/pr20121030/pr20121030.html
産総研：生物種を越えた16S rRNA遺伝子の機能相補性を確認

2011
https://www.sbj.or.jp/wp-content/uploads/file/sbj/8912/8912_yomoyama_2.pdf
生物工学基礎講座 バイオよもやま話 何から始めよう 微生物の同定 細菌・アーキア編
浜田 盛之,鈴木 健一朗
特に 16S rRNA 遺伝子配列の相同値が 97% に満たない場合 などは新属になる可能性もあるため,系統樹を作成して 既知の属のクラスターに含まれるのかどうかを慎重に確 認したほうがよい.

https://www.mitsui-norin.co.jp/mmid/knowledge/yokota/index3.html
MMID｜微生物を知ろう｜微生物分類同定講座
16S ｒRNA遺伝子塩基配列の相同性が98％以上の場合、必ずしも同種であるとは限らず、属によっては99％以上であっても別種の場合があります。

https://ja.wikipedia.org/wiki/16S_rRNA系統解析

http://www.jarmam.gr.jp/situmon3/16sr-rna.html
16S rRNAでの微生物同定


----------
## American Gut 

May 15, 2018
https://www.sciencedaily.com/releases/2018/05/180515092931.htm
Big data from world's largest citizen science microbiome project serves food for thought
How factors such as diet, antibiotics and mental health status can influence the microbial and molecular makeup of your gut

http://msystems.asm.org/content/3/3/e00031-18
American Gut: an Open Platform for Citizen Science Microbiome Research

2013.01.07
http://natgeo.nikkeibp.co.jp/nng/article/news/14/7342/
人の消化管に棲む微生物を大規模調査 | ナショナルジオグラフィック日本版サイト

----------
## Artificial sweeteners

https://jp.illumina.com/content/dam/illumina-marketing/apac/japan/documents/pdf/publicaton_metagenome_for-human-health-j.pdf
[PDF]ヒトの健康における 細菌およびメタゲノム - イルミナ株式会社
例えば、特定の人工甘味料はマウスの腸管を乱れさせ、耐 糖能を減少させます 28。

2017年6月9日
https://www.alic.go.jp/joho-s/joho07_001494.html
人工甘味料と糖代謝｜農畜産業振興機構

2016-09-06
https://unlog.me/topics/05theses-artificial-sweeteners
人工甘味料は腸内細菌を変化させ、血糖値が下がりにくくなる

2014年9月19日
http://aasj.jp/news/watch/2190
人工甘味料による糖尿（Nature オンライン版掲載論文）

https://www.natureasia.com/ja-jp/nature/514/7521/
微生物学：人工甘味料は腸内微生物相を変化させることで耐糖能異常を引き起こす
https://www.ncbi.nlm.nih.gov/pubmed/25231862
Nature. 2014 Oct 9;514(7521):181-6. doi: 10.1038/nature13793. Epub 2014 Sep 17.
Artificial sweeteners induce glucose intolerance by altering the gut microbiota.


----------
## EMP

2017.12.14
https://wired.jp/2017/12/14/catalogue-every-microbe/
地球上の無数の細菌をすべてカタログ化──壮大なプロジェクトが目指すもの
地球上の微生物の一覧をつくるプロジェクト「アース・マイクロバイオーム・プロジェクト（EMP）」。

2017年11月2日
https://www.natureasia.com/ja-jp/nature/pr-highlights/12252
【微生物学】地球における微生物多様性に関するデータのクラウドソーシング
このメタ分析は、地球マイクロバイオームプロジェクト（EMP）の第一段階の一環として実施された。EMPは、地球上の微生物の特徴を明らかにすることを目標としている。

5 Nov 2017
https://twitter.com/NatureDigest/status/927029560788500481
Nature ダイジェスト、編集部 on Twitter: "地球上の微生物の多様性評価のために2007年に発足したEMP（Earth Microbiome Project）から最初の報告。論文はオープンです。 doi:10.1038/nature24621 https://t.co/2BpJiFIr7F"

https://www.ncbi.nlm.nih.gov/pubmed/29088705
Nature. 2017 Nov 23;551(7681):457-463. doi: 10.1038/nature24621. Epub 2017 Nov 1.
A communal catalogue reveals Earth's multiscale microbial diversity.
Earth Microbiome Project Consortium.

Thursday, 26 October 2017 10:16
https://www.asm.org/index.php/podcasts/meet-the-microbiologist/item/6882-mtm-68
Microbiomes everywhere with Jack Gilbert - MTM 68

----------
## UniFrac

https://en.wikipedia.org/wiki/UniFrac

https://twitter.com/yoshikivb/status/1001558730490634243
Yoshiki Vázquez B. on Twitter: "Ever wondered what a UniFrac ordination looked like with >110K samples? Wonder no more, you can now look at it live (will work best on your desktop): https://t.co/itSsrIzXhL thanks to a recent PR, @mcdonadt and @qiime2… https://t.co/6WPLTbyP6Q"


平成 28 年 3 月版（Ver.0.9）
https://www.nite.go.jp/data/000081956.pdf
次世代シーケンサーを用いた菌叢解析
（16S rRNA 遺伝子 PCR サンプルの解析）
独立行政法人 製品評価技術基盤機構
バイオテクノロジーセンター
2.5 UniFrac 解析
比較するサンプルの OTU 代表配列を用いて系統樹解析を行い、試料間で共有されるOTU の枝長と各試料で固有な枝長の割合から、菌叢構造の違いを距離 UniFrac distance として計算する解析方法をいう。算出された UniFrac distance を用いて、主座標分析(PCoA:Principal Coordinate Analysis)や UPGMA 法によるクラスタリング解析を行うことで、試料間の相違度を視覚化することができる。また、リード数を考慮し細菌叢の構成を表す Weighted UniFrac 解析と、リード数を考慮せず細菌叢の構成メンバーを表す UnweightedUniFrac 解析がある。

2014 年
https://www.jstage.jst.go.jp/article/jsci/37/5/37_412/_article/-char/ja/
ヒト腸内マイクロバイオーム解析のための最新技術
服部 正平
https://www.jstage.jst.go.jp/article/jsci/37/5/37_412/_pdf/-char/ja
二つ目は検出された OTU 間の配列類似度から各細菌叢の系統樹を作成し，その系統樹の類似性（比較する細菌叢との系統樹間で共有する枝の長さとそれぞれの細菌叢に固有な枝の割合）から，細菌叢間の全体構造の相違の程度を求める．この解析を UniFrac 解析と言い，細菌叢間の類似性を 0（100% 類似する）～ 1（100% 類似しない）の距離（UniFrac 距離）で表す6）．UniFrac 解析にはOTU に含まれるリード数（組成比）を考慮しないunweighted と考慮した weighted UniFrac 解析がある．前者は菌種の有無だけが，後者は同一菌種の組成比の相違が両細菌叢間の類似性の距離に反映される．

https://twitter.com/Tyu_Shi/status/411124035401949184
Tyu_Shi on Twitter: "昨日からの発表を聴いていると、みんなUniFrac Distanceを万能の距離尺度と考えて使っているように感じられるが、あれはUniFrac Distanceを計算する系統樹が問題無いことを前提にしているのだから、その前提の確認無しに信頼しすぎるのはマズいよ。"
8:23 AM - 12 Dec 2013

https://twitter.com/windowmoon/status/411154169328709633
窓月㌠・CC-BY on Twitter: "@Tyu_Shi 万単位になってくるとブートストラップなしでも系統樹推定苦しいのでは。系統樹使わずに分子同定した上で、分類体系に合うように樹形制約を入れれば可能かもしれません。ブートストラップもなしで単発の推定結果を樹形の不確実性考慮せずに使うのはかなり拙いでしょうね。"
10:22 AM - 12 Dec 2013

https://twitter.com/yuifu/status/187741115720548352
Haruka Ozaki on Twitter: "UniFracの元論文。細菌叢の配列集合間の距離を計算する手法。系統樹上で共有する枝長を使い、かつ、距離を定義したことが新しかったらしい。オルタナティブを作ろうとすると、優位性を示す方法がないことが課題。 http://t.co/nZudriEa #Everydayペーパー"
11:19 PM - 4 Apr 2012

https://www.ncbi.nlm.nih.gov/pubmed/20827291
ISME J. 2011 Feb;5(2):169-72. doi: 10.1038/ismej.2010.133. Epub 2010 Sep 9.
UniFrac: an effective distance metric for microbial community comparison.
Lozupone C1, Lladser ME, Knights D, Stombaugh J, Knight R.

----------
## unclassified

https://jp.illumina.com/content/dam/illumina-marketing/apac/japan/documents/pdf/publicaton_metagenome_for-human-health-j.pdf
ヒトの健康における細菌およびメタゲノムイルミナテクノロジーを使用した最新論文の概要
https://jp.illumina.com/science/publication-reviews.html
論文集 | 最近発表された研究の要点

https://www.jstage.jst.go.jp/article/johokanri/55/3/55_167/_html/-char/ja
メタゲノム解析の現状と将来　知識データベースの開発
森 宙史, 山田 拓司, 黒川 顕
55 巻 (2012) 3 号 p. 167-175
さらに大規模なプロジェクトとして進行中なのが，2010年に日本を除く米欧中を中心とした12か国70人の研究者が立ち上げたEMP（Earth Microbiome Project）10)である。

山田拓司 著

https://www.jstage.jst.go.jp/article/jim/29/1/29_19/_article/-char/ja/
https://www.jstage.jst.go.jp/article/jim/29/1/29_19/_pdf
腸内細菌群集構造のメタゲノム解析 - J-Stage
腸内細菌学雑誌 29 : 19-22,2015

https://jp.illumina.com/content/dam/illumina-marketing/apac/japan/documents/pdf/2014_webinar_mktg30_microbiology.pdf
[PDF]ヒト腸内細菌叢メタゲノム解析

https://www.jstage.jst.go.jp/article/kagakutoseibutsu/51/12/51_802/_pdf
ヒト腸内メタゲノム解析が 広げる医療展開 - J-Stage
化学と生物 Vol. 51, No. 12, 2013

----------


2010年12月23日
http://www.nikkei-science.com/?p=14373
Science誌の選ぶこの10年の10大成果：マイクロバイオーム | 日経サイエンス


----------
## meta-analysis
https://ja.wikipedia.org/wiki/メタアナリシス

https://github.com/haruosuz/statistics#meta-analysis

https://twitter.com/search?f=tweets&q=microbiome%20meta-analysis

### Qiita

https://twitter.com/strnr/status/1047841444214558720
Stephen Turner on Twitter: "Qiita (pronounced chee-tah): rapid, web-enabled microbiome meta-analysis Paper: https://t.co/aXTv0cTCND Web: https://t.co/XfwpO4bP0I Docs: https://t.co/CKEEffUSCW Source: https://t.co/HWOT2qYHeZ… https://t.co/RVMns0X6Eo"
9:30 AM - 4 Oct 2018

Qiita (pronounced chee-tah): rapid, web-enabled microbiome meta-analysis 

Paper: https://www.nature.com/articles/s41592-018-0141-9 …
Web: https://qiita.ucsd.edu/ 
Docs: https://qiita.ucsd.edu/static/doc/html/index.html …
Source: https://github.com/biocore/qiita 

https://twitter.com/gibbological/status/1046878477981343744
Sean Gibbons on Twitter: "Qiita: rapid, web-enabled microbiome meta-analysis https://t.co/4Osl11rR8X from @KnightLabNews @gregcaporaso and @Pdorrestein1 labs. Useful tool for all us 'data parasites' :)"
5:44 PM - 1 Oct 2018

batch effect
バッチ効果

https://twitter.com/jongsanders/status/1046836821286686721
Jon Sanders on Twitter: "The Qiita paper is out! So happy to have been able to contribute to this amazing resource. Congrats, @KnightLabNews! https://t.co/QkQ2x363Xi"
2:58 PM - 1 Oct 2018
![](https://pbs.twimg.com/card_img/1046836828454703105/ZFWvyfj5?format=jpg&name=144x144_2)

01 October 2018  & Rob Knight 
https://www.nature.com/articles/s41592-018-0141-9
Qiita: rapid, web-enabled microbiome meta-analysis

### almlab
http://almlab.mit.edu/

https://twitter.com/gibbological/status/988476547614105601
Sean Gibbons on Twitter: "Befuddled by batch effects? Check out our simple, non-parametric solution for 16S case-control studies in @PLOSCompBiol https://t.co/grMDm7SIQl -- method available as a @qiime2 plugin thanks to @cduvallet"

https://www.ncbi.nlm.nih.gov/pubmed/29684016
PLoS Comput Biol. 2018 Apr 23;14(4):e1006102. doi: 10.1371/journal.pcbi.1006102. eCollection 2018 Apr.
Correcting for batch effects in case-control microbiome studies.
Gibbons SM1,2,3, Duvallet C1,2, Alm EJ1,2,3.
微生物群集の症例対照研究におけるバッチ効果の補正

April 17, 2018
https://cduvallet.github.io/posts/2018/04/microbiome-data
An empirical analysis of microbiome data availability - Claire Duvallet

https://www.ncbi.nlm.nih.gov/pubmed/29209090
Nat Commun. 2017 Dec 5;8(1):1784. doi: 10.1038/s41467-017-01973-8.
Meta-analysis of gut microbiome studies identifies disease-specific and shared responses.
Duvallet C1,2, Gibbons SM1,2,3, Gurry T1,2,3, Irizarry RA4,5, Alm EJ6,7,8.
We perform a cross-disease meta-analysis of these studies using standardized methods. 
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5716994/
Code availability
The code to reproduce all of the analyses in this paper is available at https://github.com/cduvallet/microbiomeHD. 

https://twitter.com/Kazu_Kasahara/status/938469390739234816
Kazu_Kasahara on Twitter: "流行しているマイクロバイオーム研究に警鐘を鳴らす論文。28報の研究、10疾患のメタ解析から、病気で認める"dysbiosis"の多くは疾患特異的ではなく、バイオマーカーになり難い。 https://t.co/AVJHhcCCcI"
1:05 PM - 6 Dec 2017

### 2018-06
https://twitter.com/ayaKT/status/1005378142146457600
ayaKT on Twitter: "~19000人規模のmicrobiome-GWAS に着手しました論文。どんな解析結果が出てくるのか楽しみ。 いろんな16Sシーケンス手法を比較可能にする考えかたも、勉強になる。fmfm https://t.co/hNMXyZHzWj"
5:16 AM - 9 Jun 2018

https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-018-0479-3
Meta-analysis of human genome-microbiome association studies: the MiBioGen consortium initiative | Microbiome
We are now in the process of benchmarking the association tests and performing meta-analyses of genome-wide associations. All pipeline and summary statistics results will be shared using public data repositories.

### 2017-12-22
https://www.ncbi.nlm.nih.gov/pubmed/29273717
Nat Commun. 2017 Dec 22;8(1):2260. doi: 10.1038/s41467-017-02209-5.
Strain profiling and epidemiology of bacterial species from metagenomic sequencing.
Albanese D1, Donati C2.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5741664/
- Here we present StrainEst, a novel, reference-based method that uses the single-nucleotide variants (SNV) profiles of the available genomes of selected species to determine the number and identity of coexisting strains and their relative abundances in mixed metagenomic samples.
- meta-analyses

### 2017-11-20
https://twitter.com/NatureMicrobiol/status/932704694912389120
Nature Microbiology on Twitter: ".@drkellysierra & co: Integration and meta-analysis of global #soil datasets uncover patterns of #microbial structure,… https://t.co/QB51kFBtK5"
3:18 PM - 20 Nov 2017

https://www.nature.com/articles/s41564-017-0062-x
Detecting macroecological patterns in bacterial communities across independent studies of global soils | Nature Microbiology
- Whereas previous meta-analysis efforts have focused on bacterial diversity measures or abundances of major taxa, we show that disparate amplicon sequence data can be combined at the taxonomy-based level to assess bacterial community structure.

### 2016
https://www.ncbi.nlm.nih.gov/pubmed/27400279
PLoS Comput Biol. 2016 Jul 11;12(7):e1004977. doi: 10.1371/journal.pcbi.1004977. eCollection 2016 Jul.
Machine Learning Meta-analysis of Large Metagenomic Datasets: Tools and Biological Insights.
Pasolli E1, Truong DT1, Malik F2, Waldron L2, Segata N1.
http://segatalab.cibio.unitn.it/tools/metaml
MetAML - Metagenomic prediction Analysis based on Machine Learning
機械学習

### 2015
https://www.ncbi.nlm.nih.gov/pubmed/26459172
Microbiome. 2015 Oct 13;3:49. doi: 10.1186/s40168-015-0108-3.
Microbiota of the indoor environment: a meta-analysis.
Adams RI1, Bateman AC2, Bik HM3,4, Meadow JF5.
室内環境の微生物群集：メタアナリシス

----------

