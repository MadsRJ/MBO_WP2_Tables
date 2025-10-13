# MBO_WP2_Tables
Three tables generated as part of MBO WP2's work on identifying primers, reference databases and pipelines used for metabarcoding studies. The first table serves as an excellent starting point for ctrl+F searches for given primer sequences, e.g. when comparing across studies. We specifically include both 5'-3' and 3'-5' primer sequences to enable this ctrl+F search, as the same primers are sometimes reported in diferrent directions across studies. The second table identifies key reference databases often encountered in the literature, with specific details associated with each of them. The third table is a comprehensive (but likely incomplete) list of pipelines for processing metabarcoding data, providing external links to where to find more information about each of them.

### Table 1: An incomplete overview of empirically tested and/or frequently used metabarcoding primers and their target groups

|Primer&nbsp;combination&nbsp;name|Individual&nbsp;primer&nbsp;names&nbsp;(F&nbsp;and&nbsp;R)|F-primer (5′-3′) <br> F-primer (3′-5′)|R-primer (5′-3′) <br> R-primer (3′-5′)|Marker&nbsp;gene|Target&nbsp;group|Fragment&nbsp;size&nbsp;(bp)|Reference(s)|Additional&nbsp;usage&nbsp;notes&nbsp;and&nbsp;relevant&nbsp;information|
|-----------|------------|--------------------------------------|--------------------------------------|------|------------|------------------|------------|-----|
|`18S_allshorts`|**F:** 18S_allshorts forward <br> **R:** 18S_allshorts reverse|TTTGTCTGSTTAATTSCG <br> GCSTTAATTSGTCTGTTT|TCACAGACCTGTTATTGC <br> CGTTATTGTCCAGACACT|18S (V7)|Eukaryotes|~110|Guardiola et al. (2015)|Highly specific for eukaryotes. Amplifies same region as Hardy et al. (2010), with almost same resolution for 40 bp less.|
|`18S_allshorts (mod. "Euka02")`|**F:** 18S_allshorts forward <br> **R:** 18S_allshorts reverse (mod.)|TTTGTCTGSTTAATTSCG <br> GCSTTAATTSGTCTGTTT|CACAGACCTGTTATTGC <br> CGTTATTGTCCAGACAC|18S (V7)|Eukaryotes|~110|Guardiola et al. (2015), Taberlet et al. (2018)|First "T" omitted compared to original reverse primer to better equilibrate the melting temperatures of the two primers.|
|`Aves01` **CHECK**|**F:** dsa - **CHECK** <br> **R:** dsa - **CHECK**|GATTAGATACCCCACTATGC <br> CGTATCACCCCATAGATTAG|GTTTTAAGCGTTTGTGCTCG <br> GCTCGTGTTTGCGAATTTTG|12S|Aves (birds)|~52|Epp et al. (2012)|Limited taxonomic resolution, but highly specific to birds.|
|`Arch01`|**F:** Arch01-F <br> **R:** Arch01-R|CCTGCTCCTTGCACACAC <br> CACACACGTTCCTCGTCC|CCTACGGCTACCTTGTTAC <br> CATTGTTCCATCGGCATCC|16S (V9)|Archaea|~85|Taberlet et al. (2018)|Highly specific of Archaea.|
|`Baci01`|**F:** Baci01-F <br> **R:** Baci01-R|ATTCCAGCTCCAATAGCGTA <br> ATGCGATAACCTCGACCTTA|CTTTRAACRCLCTRATTTYTTCAC <br> CACTTYTTTARTCLCRCAARTTTC|18S (V4)|Bacillariophyta (diatoms)|~150|Taberlet et al. (2018)|Will also amplify other eukaryotes.|
|`Bact02`|**F:** Bact02-F <br> **R:** Bact02-R|GCCAGCMGCCGCGGTAA <br> AATGGCGCCGMCGACCG|GGACTACCMGGGTATCTAA <br> AATCTATGGGMCCATCAGG|16S (V4)|Bacteria+Archaea|~254|Taberlet et al. (2018)||
|`Bact03` **CHECK**|**F:** 515F – **was this modified compared to original?** <br> **R:** 806RB|GTGYCAGCMGCCGCGGTAA <br> AATGGCGCCGMCGACYGTG|GGACTACNVGGGTWTCTAAT <br> TAATCTWTGGGVNCATCAGG|16S (V4)|Bacteria+Archaea|~253|Baker et al. (2003), Quince et al. (2011), Apprill et al. (2015)|Recommended by Earth Microbiome Project. Not necessary to degenerate both primers if only targeting bacteria (Taberlet et al. 2018).|
|`Bact04` **CHECK**|**F:** dsa – **CHECK** <br> **R:** dsa - **CHECK**|GTGYCAGCMGCCGCGGTAA <br> AATGGCGCCGMCGACYGTG|CCGYCAATTYMTTTRAGTTT <br> TTTGARTTTMYTTAACYGCC|16S (V4-V5)|Bacteria+Archaea|~373-378|Baker et al. (2003), Quince et al. (2011)|Recommended by Earth Microbiome Project. Also amplifies a relatively large number of eukaryotes (Taberlet et al. 2018).|
|`BACTB`|**F:** BACTB-F <br> **R:** BACTB-R|GGATTAGATACCCTGGTAGT <br> TGATGGTCCCATAGATTAGG|CACGACACGAGCTGACG <br> GCAGTCGAGCACAGCAC|16S (V5-V6)|Bacteria|~258|Fliegerova et al. (2014)||
|`Balzano`|**F:** TAReuk454FWD1 (V4F) <br> **R:** V4RB|CCAGCASCYGCGGTAATTCC <br> CCTTAATGGCGYCSACGACC|ACTTTCGTTCTTGATYRR <br> RRYTAGTTCTTGCTTTCA|18S (V4)|Eukaryotes|~380|Stoeck et al. (2010), Balzano et al. (2015)||
|`Banos`|**F:** nu-SSU-1333-5′ (FF390) <br> **R:** nu-SSU-1647-3′ (FR-1)|CGATAACGAACGAGACCT <br> TCCAGAGCAAGCAATAGC|AICCATTCAATCGGTAIT <br> TIATGGCTAACTTACCIA|18S (V7-V8)|Fungi|~348|Banos et al. (2018)|Note that “I” (inosine) often gets replaced with “N” for bioinformatic software to recognize the wobble-base.|
|`Batr01`|**F:** dsa - **CHECK** <br> **R:** dsa - **CHECK**|ACACCGCCCGTCACCCT <br> TCCCACTGCCCGCCACA|GTAYACTTACCATGTTACGACTT <br> TTCAGCATTGTACCATTCAYATG|12S|Batrachia (frogs and salamanders)|~51|Valentini et al. (2016)||
|`BF1/BR1`|**F:** BF1 <br> **R:** BR1|ACWGGWTGRACWGTNTAYCC <br> CCYATNTGWCARGTWGGWCA|ARYATDGTRATDGCHCCDGC <br> CGDCCHCGDTARTGDTAYRA|COI|Macroinvertebrates|217|Elbrecht & Leese (2017)|Designed for mock communities, so co-amplifies a lot of undesired taxa when applied to eDNA samples.|
|`Bryo01`|**F:** dsa - **CHECK** <br> **R:**  Bryo01-R|GATTCAGGGAAACTTAGGTTG <br> GTTGGATTCAAAGGGACTTAG|CCATYGAGTCTCTGCACC <br> CCACGTCTCTGAGYTACC|trnL|Bryophyta|~53|Epp et al. (2012), Taberlet et al. (2018)|One degenerated bp in reverse primer compared to Epp et al. (2012).|
|`Caporaso`|**F:** F515 <br> **R:** R806|GTGCCAGCMGCCGCGGTAA <br> AATGGCGCCGMCGACCGTG|GGACTACHVGGGTWTCTAAT <br> TAATCTWTGGGVHCATCAGG|16S|Bacteria|**CHECK** XX|Caporaso et al. (2011)||
|`Cole01`|**F:** Cole01-F <br> **R:** Cole01-R|TGCWAAGGTAGCATAATMATTAG <br> GATTAMTAATACGATGGAAWCGT|TCTATAGGGTCTTCTCGTC <br> CTGCTCTTCTGGGATATCT|16S|Coleoptera (beetles)|~107|Taberlet et al. (2018)|Modified primers from Epp et al. (2012). Also amplifies other metazoans.|
|`Coll01` **CHECK**|**F:** dsa - **CHECK** <br> **R:** dsa - **CHECK**|ACGCTGTTATCCCTWAGG <br> GGAWTCCCTATTGTCGCA|GACGATAAGACCCTWTAGA <br> AGATWTCCCAGAATAGCAG|16S|Collembola (springtails)|~132|Janssen et al. (2017)||
|`Culi01` **CHECK**|**F:** dsa - **CHECK** <br> **R:** dsa - **CHECK**|ACGCTGTTATCCCTAAGGTAACTTA <br> ATTCAATGGAATCCCTATTGTCGCA|GACGAGAAGACCCTATAGATCTTTAT <br> TATTTCTAGATATCCCAGAAGAGCAG|16S|Culicidae (mosquitos)|~145|Schneider et al. (2016)||
|`Cyan01`|**F:** Cyan01-F <br> **R:** Cyan01-R|CTYAAGCCGACATTCTCAC <br> CACTCTTACAGCCGAAYTC|GACAACYAGGAGGTTTGC <br> CGTTTGGAGGAYCAACAG|23S|Cyanobacteria|~180|Taberlet et al. (2018)||
|`Elas02`|**F:** Elas02-F <br> **R:** Elas02-R|GTTGGTHAATCTCGTGCCAGC <br> CGACCGTGCTCTAAHTGGTTG|CATAGTAGGGTATCTAATCCTAGTTTG <br> GTTTGATCCTAATCTATGGGATGATAC|12S|Elasmobranchii|~182|Taberlet et al. (2018)||
|`Ench01` **CHECK**|**F:** dsa - **CHECK** <br> **R:** dsa - **CHECK**|GCTGCACTTTGACTTGAC <br> CAGTTCAGTTTCACGTCG|AGCCTGTGTACTGCTGTC <br> CTGTCGTCATGTGTCCGA|12S|Enchytraeidae|~48|Epp et al. (2012)||
|`Euka01` **CHECK**|**F:** dsa - **CHECK** <br> **R:** dsa - **CHECK**|TGGTGCATGGCCGTTCTTAGT <br> TGATTCTTGCCGGTACGTGGT|CATCTAAGGGCATCACAGACC <br> CCAGACACTACGGGAATCTAC|18S (V7)|Eukaryotes|~161|Hardy et al. (2010)|Highly specific of eukaryotes. Much longer fragment for certain insects, amphipods and isopods (Taberlet et al. 2018).|
|`Euka03`|**F:** Euka03-F <br> **R:** Euka03-R|CCCTTTGTACACACCGCC <br> CCGCCACACATGTTTCCC|CTTCYGCAGGTTCACCTAC <br> CATCCACTTGGACGYCTTC|18S (V9)|Eukaryotes|~133|Taberlet et al. (2018)|18S V9 has less reference sequences than V7, but this marker should provide higher taxonomic resolution and has a more standardized fragment size (Taberlet et al. 2018).|
|`Euk1391f-EukBr`|**F:** Euk1391f <br> **R:** EukBr|GTACACACCGCCCGTC <br> CTGCCCGCCACACATG|TGATCCTTCTGCAGGTTCACCTAC <br> CATCCACTTGGACGTCTTCCTAGT|18S (V9)|Eukaryotes|~128|Amaral-Zettler et al. (2009), Stoeck et al. (2010), https://earthmicrobiome.org/protocols-and-standards/18s/|Highly specific of eukaryotes. Used by Earth Microbiome Project. The reverse primer is not optimal. Described as “Euka04” in Taberlet et al. (2018).|
|`Fung01` **CHECK**|**F:** dsa - **CHECK** <br> **R:** dsa - **CHECK**|GGAAGTAAAAGTCGTAACAAGG <br> GGAACAATGCTGAAAATGAAGG|CCAAGAGATCCGTTGYTGAAAGT <br> TGAAAGTYGTTGCCTAGAGAACC|ITS1|Fungi|~226|Epp et al. (2012)|Does not properly amplify Glomeromycota. Highly variable fragment length for some fungi (Taberlet et al. 2018).|
|`Fung02` **CHECK**|**F:** dsa - **CHECK** <br> **R:** Fung02-R|GGAAGTAAAAGTCGTAACAAGG <br> GGAACAATGCTGAAAATGAAGG|CAAGAGATCCGTTGYTGAAAGTK <br> KTGAAAGTYGTTGCCTAGAGAAC|ITS1|Fungi|~225|Epp et al. (2012), Taberlet et al. (2018)|Modified version of Epp et al (2012)’s reverse primer to properly amplify Glomeromycota. Highly variable fragment length for some fungi (Taberlet et al. 2018).|
|`Inse01`|**F:** Inse01-F <br> **R:** Inse01-R|RGACGAGAAGACCCTATARA <br> ARATATCCCAGAAGAGCAGR|ACGCTGTTATCCCTAARGTA <br> ATGRAATCCCTATTGTCGCA|16S|Insecta|~155|Taberlet et al. (2018)|Close to the Clarke et al. (2014) primers.|
|`Isop01`|**F:** Isop01-F <br> **R:** Isop01-R|ATTTCAGGTCAAGGTGCAGCTT <br> TTCGACGTGGAACTGGACTTTA|ATTACAACCAAATCCAATTTCA <br> ACTTTAACCTAAACCAACATTA|12S|Isoptera (termites)|~66|Taberlet et al. (2018)||
|`Leray`|**F:** mlCOIintF <br> **R:** jgHCO2198|GGWACWGGWTGAACWGTWTAYCCYCC <br> CCYCCYATWTGWCAAGTWGGWCAWGG|TAIACYTCIGGRTGICCRAARAAYCA <br> ACYAARAARCCIGTRGGICTYCAIAT|COI|Metazoans|313|Leray et al. (2013), Geller et al. (2013)|Note that “I” (inosine) often gets replaced with “N” for bioinformatic software to recognize the wobble-base.|
|`Leray-XT`|**F:** mlCOIintF-XT <br> **R:** jgHCO2198|GGWACWRGWTGRACWITITAYCCYCC <br> CCYCCYATITIWCARGTWGRWCAWGG|TAIACYTCIGGRTGICCRAARAAYCA <br> ACYAARAARCCIGTRGGICTYCAIAT|COI|Metazoans|313|Geller et al. (2013), Wangensteen et al. (2018)||
|`Lumb01`|**F:** Lumb01-F <br> **R:** Lumb01-R|CAAGAAGACCCTATAGAGCTT <br> TTCGAGATATCCCAGAAGAAC|GGTCGCCCCAACCGAAT <br> TAAGCCAACCCCGCTGG|16S|Lumbricina (earthworms)|~31|Bienert et al. (2012)||
|`Lumb02`|**F:** Lumb02-F <br> **R:** Lumb02-R|ATTCGGTTGGGGCGACC <br> CCAGCGGGGTTGGCTTA|CTGTTATCCCTAAGGTAGCTT <br> TTCGATGGAATCCCTATTGTC|16S|Lumbricina (earthworms)|~74|Bienert et al. (2012)||
|`Mamm01`|**F:** Mamm01-F <br> **R:** Mamm01-R|CCGCCCGTCACCCTCCT <br> TCCTCCCACTGCCCGCC|GTAYRCTTACCWTGTTACGAC <br> CAGCATTGTWCCATTCRYATG|12S|Mammals|~58|Taberlet et al. (2018)||
|`Mamm02`|**F:** Mamm02-F <br> **R:** dsa - **CHECK**|CGAGAAGACCCTRTGGAGCT <br> TCGAGGTRTCCCAGAAGAGC|CCGAGGTCRCCCCAACC <br> CCAACCCCRCTGGAGCC|16S|Mammals|~74|Taberlet et al. (2018), Giguet-Covex et al. (2014)|Forward primer slightly modified from Giguet-Covex et al. (2014). Also amplifies some other vertebrates.|
|`MarVer1`|**F:** MmoMV1F <br> **R:** MarVer1R-ndC|CGTGCCAGCCACCGCG <br> GCGCCACCGACCGTGC|GGGTATCTAATCCYAGTTTG <br> GTTTGAYCCTAATCTATGGG|12S|Vertebrates|**CHECK** 202?|Valsecchi et al. (2020)||
|`MarVer2`|**F:** MarVer2F-ndC <br> **R:** MmoMV2R|CCGCCCGTCACCCTC <br> CTCCCACTGCCCGCC|CTTATCTCCTCTTATATTTTTATACGTA <br> ATGCATATTTTTATATTCTCCTCTATTC|12S|Vertebrates|**CHECK** XXX|Valsecchi et al. (2020)||
|`MarVer3`|**F:** MmoMV3F <br> **R:** MarVer3R|GCTTTAATTAATTAATCCAATAGAATAAAATTAACC <br> CCAATTAAAATAAGATAACCTAATTAATTAATTTCG|GGATTGCGCTGTTATCCC <br> CCCTATTGTCGCGTTAGG|16S|Vertebrates|**CHECK** 245?|Valsecchi et al. (2020)||
|`Meta01`|**F:** Meta01-F <br> **R:** Meta01-R|YYCRMCTGTTTAYCAAAAACA <br> ACAAAAACYATTTGTCMRCYY|CCGGTYTGAACTCARATC <br> CTARACTCAAGTYTGGCC|16S|Metazoa|∼548|Taberlet et al. (2018)|Close to primers designed by Palumbi et al. (2002). Quite long fragment amplified, not likely to work for degraded samples.|
|`MiFish-E`|**F:** MiFish-E-F <br> **R:** MiFish-E-R|GTTGGTAAATCTCGTGCCAGC <br> CGACCGTGCTCTAAATGGTTG|CATAGTGGGGTATCTAATCCTAGTTTG <br> GTTTGATCCTAATCTATGGGGTGATAC|12S|Fishes/vertebrates|170–185|Miya et al. (2015)|Elasmobranch-optimized.|
|`MiFish-U`|**F:** MiFish-U-F <br> **R:** MiFish-U-R|GTCGGTAAAACTCGTGCCAGC <br> CGACCGTGCTCAAAATGGCTG|CATAGTGGGGTATCTAATCCCAGTTTG <br> GTTTGACCCTAATCTATGGGGTGATAC|12S|Fishes/vertebrates|163–185|Miya et al. (2015)|Universal version.|
|`MiFish-U (UiT mod.)`|**F:** MiFish-U-F (UiT mod.) <br> **R:** MiFish-U-R|GCCGGTAAAACTCGTGCCAGC <br> CGACCGTGCTCAAAATGGCCG|CATAGTGGGGTATCTAATCCCAGTTTG <br> GTTTGACCCTAATCTATGGGGTGATAC|12S|Fishes/vertebrates|163–185|Miya et al. (2015), Sales et al. (2019)|Note that the second base in the F primer has been replaced compared to the original.|
|`Poly01`|**F:** Poly01-F <br> **R:** Poly01-R|CCGGTYTGAACTCAGMTCA <br> ACTMGACTCAAGTYTGGCC|TGGCACCTCGATGTTGGCT <br> TCGGTTGTAGCTCCACGGT|16S|Polychaetes|~63|Taberlet et al. (2018)||
|`Riaz1`|**F:** F1 <br> **R:** R1|ACTGGGATTAGATACCCC <br> CCCCATAGATTAGGGTCA|TAGAACAGGCTCCTCTAG <br> GATCTCCTCGGACAAGAT|12S|Vertebrates|~106|Riaz et al. (2011)||
|`Riaz2 (12S-V5)`|**F:** dsa - **CHECK** <br> **R:** dsa - **CHECK**|dsa - **CHECK** <br> dsa - **CHECK**|dsa - **CHECK** <br> dsa - **CHECK**|12S|Vertebrates|~97|Riaz et al. (2011)||
|`Sper01` **CHECK**|**F:** Sper01-F - **CHECK** <br> **R:** Sper01-R - **CHECK**|GGGCAATCCTGAGCCAA <br> AACCGAGTCCTAACGGG|CCATTGAGTCTCTGCACCTATC <br> CTATCCACGTCTCTGAGTTACC|trnL, P6 loop|Spermatophyta (seed plants)|~48|Taberlet et al. (2007)|Widely used for degraded material due to the short length.|
|`Stoeck`|**F:** TAReuk454FWD1 (V4F) <br> **R:** TAReukREV3 (V4R)|CCAGCASCYGCGGTAATTCC <br> CCTTAATGGCGYCSACGACC|ACTTTCGTTCTTGATYRA <br> ARYTAGTTCTTGCTTTCA|18S (V4)|Eukaryotes|~380|Stoeck et al. (2010)||
|`Tele01`|**F:** dsa - **CHECK** <br> **R:** dsa - **CHECK**|ACACCGCCCGTCACTCT <br> TCTCACTGCCCGCCACA|CTTCCGGTACACTTACCATG <br> GTACCATTCACATGGCCTTC|12S|Teleostei|~64|Valentini et al. (2016)|Poor resolution for Cyprinidae and Gadidae.|
|`Tele02`|**F:** Tele02-F <br> **R:** Tele02-R|AAACTCGTGCCAGCCACC <br> CCACCGACCGTGCTCAAA|GTTTGACCCTAATCTATGGG <br> GGGTATCTAATCCCAGTTTG|12S|Fishes/vertebrates|129-209|Taberlet et al. (2018), Thomsen et al. (2016)|F-primer first described as "V05F_898" from Thomsen et al. (2016).|

### Table 2: An overview of frequently used reference databases
|Database|Target&nbsp;group|Website/download&nbsp;link|Marker(s)|Known&nbsp;deficiencies|Last&nbsp;updated|Licence&nbsp;type|Coverage&nbsp;(Regions)|Notes|
|--------|-----------------|--------------------------|---------|------------|-----------------|-----------------|----------------------------|-----|
|`BOLD`|Animals, plants, fungi|https://boldsystems.org/|COI, rbcL, matK, ITS, 18S, 12S|Lack of prokaryotes. Taxonomic backbone different to other databases. Needs curation.|Frequent updates|Open/Restricted|Worldwide|Widely used database for species-level identification in DNA barcoding|
|`CRABS_NordicRefDBs`|||||||||
|`DDBJ`|||||||||
|`EMBL`|||||||||
|`ENSEMBL`|||||||||
|`FlyBase`|||||||||
|`GOLD`|||||||||
|`GreenGenes`|||||||||
|`GTDB`|||||||||
|`HMP`|||||||||
|`IMG`|||||||||
|`KEGG`|||||||||
|`MetaPhlAn`|||||||||
|`MIDORI2`|||||||||
|`NCBI nr`|||||||||
|`NCBI nt`|||||||||
|`NCBI RefSeq`|||||||||
|`PDB`|||||||||
|`Pfam`|||||||||
|`Phytozome`|||||||||
|`PR2`|||||||||
|`RDP`|||||||||
|`Silva`|||||||||
|`TARA Oceans`|||||||||
|`UNITE`|Fungi|https://unite.ut.ee/|ITS|Limited to fungal taxa|Specialized for fungal ITS sequences|YYYY-MM-DD - **CHECK**|Open|Fungal taxa|
|`WormBase`|||||||||
|`ZFIN`|||||||||

### Table 3: An alphabetically ordered, incomplete overview of existing metabarcoding pipelines
|Pipeline|Primary software used|Language|Clustering|Link|Notes|
|-----------|------------|--------------------------------------|------|------------|------------------|
|`AMPtk`||||||
|`Anacapa`||||https://github.com/limey-bean/Anacapa/||
|`APSCALE`||||||
|`Banzai`||||https://github.com/jimmyodonnell/banzai/||
|`Barque`||||https://github.com/enormandeau/barque/||
|`BIOCOM-PIPE`||||||
|`Cascabel`||||||
|`CoMA`||||||
|`DADA2`||||https://benjjneb.github.io/dada2/tutorial.html||
|`Dadaist2`||||||
|`dadasnake`||||||
|`DAnIEL`||||||
|`eDNAflow`||||https://github.com/mahsa-mousavi/eDNAFlow/||
|`FROGS`||||||
|`gDAT`||||||
|`JAMP`||||||
|`LotuS2`||||||
|`MetaBarFlow`||||https://github.com/evaegelyng/MetaBarFlow/||
|`MetaWorks`||||https://github.com/terrimporter/MetaWorks/||
|`MetaWorksSite`||||https://terrimporter.github.io/MetaWorksSite/||
|`MiFish`||||https://mitofish.aori.u-tokyo.ac.jp/mifish/||
|`MICCA`||||||
|`MJOLNIR`||||https://github.com/uit-metabarcoding/MJOLNIR/||
|`mothur`||||||
|`NextITS`||||||
|`nfcore/ampliseq`||||https://nf-co.re/ampliseq/2.9.0/||
|`OBITools3`||||||
|`PacMan`||||https://github.com/iobis/PacMAN-pipeline/||
|`PEMA`||||https://github.com/hariszaf/pema/||
|`PipeCraft2`||||||
|`PIPITS`||||||
|`QIIME 2`||||||
|`SCATA`||||||
|`Seed2`||||https://www.biomed.cas.cz/mbu/lbwrf/seed/||
|`Slim`||||https://trtcrd.github.io/SLIM/||
|`Tourmaline`||||||
|`USEARCH`||||||
|`VSEARCH`||||||
|`VTAM`||||||

## Acknowledgements
This repository was created under the framework of the EU-project [MARCO-BOLO](https://marcobolo-project.eu/). The MARCO-BOLO project is funded by the European Union under the Horizon Europe Programme, Grant Agreement No. 101082021 (MARCO-BOLO). Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the European Union or the European Research Executive Agency (REA). Neither the European Union nor the granting authority can be held responsible for them. UK participants in MARCO-BOLO are supported by the UKRI’s Horizon Europe Guarantee under the Grant No. 10068180 (MS); No. 10063994 (MBA); No. 10048178 (NOC).

![Fig1](figures_readme/MARCO-BOLO_logo_col.png)

## References 
Amaral-Zettler, L. A., McCliment, E. A., Ducklow, H. W., Huse, S. M. (2009). A method for studying protistan diversity using massively parallel sequencing of V9 hypervariable regions of small-subunit ribosomal RNA genes. PLOS One 4(7): e6372. https://doi.org/10.1371/journal.pone.0006372.

Baker, G. C., Smith, J. J., Cowan, D. A. (2003). Review and re-analysis of domain-specific 16S primers. Journal of Microbiological Methods 55(3), 541-555. https://doi.org/10.1016/j.mimet.2003.08.009.

Balzano, S., Abs, E., Leterme, S. C. (2015). Protist diversity along a salinity gradient in a coastal lagoon. Aquatic Microbial Ecology 74, 263-277 https://doi.org/10.3354/ame01740.

Banos, S., Lentendu, G., Kopf, A., Wubet, T., Glöckner, F. O., Reich, M. (2018). A comprehensive fungi-specific 18S rRNA gene sequence primer toolkit suited for diverse research issues and sequencing platforms. BMC Microbiol 18, 190. https://doi.org/10.1186/s12866-018-1331-4.

Bienert, F. De Danieli, S., Miquel, C., Coissac, E., Poillot, C., Brun, J.-J., Taberlet, P. (2012). Tracking earthworm communities from soil DNA. Molecular Ecology 21(8), 2017-2030. https://doi.org/10.1111/j.1365-294X.2011.05407.x.

Caporaso, J. G., Lauber, C. L., Walters, W. A., Berg-Lyons, D., Lozupone, C. A., Turnbaugh, P. J., Fierer, N., Knight, R. (2011). Global patterns of 16S rRNA diversity at a depth of millions of sequences per sample. Proc. Natl. Acad. Sci. U.S.A. 108 (supplement_1), 4516-4522. https://doi.org/10.1073/pnas.1000080107.

Elbrecht, V. & Leese, F. (2017). Validation and development of COI metabarcoding primers for freshwater macroinvertebrate bioassessment. Frontiers in Environmental Science 5, 11. https://doi.org/10.3389/fenvs.2017.00011.

Epp et al. (2012)

Hardy et al. (2010)

Fliegerova et al. (2014)

Geller, J., Meyer, C., Parker, M., & Hawk, H. (2013). Redesign of PCR primers for mitochondrial cytochrome c oxidase subunit I for marine invertebrates and application in all-taxa biotic surveys. Molecular Ecology Resources 13(5), 851-861. https://doi.org/10.1111/1755-0998.12138.

Giguet-Covex et al. (2014)

Guardiola et al. (2015)

Janssen et al. (2017)

Leray, M., Yang, J. Y., Meyer, C. P., Mills, S. C., Agudelo, N., Ranwez, V., Boehm, J. T., & Machida, R. J. (2013). A new versatile primer set targeting a short fragment of the mitochondrial COI region for metabarcoding metazoan diversity: application for characterizing coral reef fish gut contents. Frontiers in Zoology 10, 34. https://doi.org/10.1186/1742-9994-10-34.

Miya et al. (2015)

Quince et al. (2011)

Riaz et al. (2011)

Sales et al. (2019)

Schneider et al. (2016)

Stoeck et al. (2010)

Taberlet et al. (2007)

Taberlet et al. (2018)

Thomsen et al. (2016)

Valentini et al. (2016)

Valsecchi et al. (2020)

Wangensteen, O. S., Palacín, C., Guardiola, M., & Turon, X. (2018). DNA metabarcoding of littoral hard-bottom communities: high diversity and database gaps revealed by two molecular markers. PeerJ 6, e4705. https://doi.org/10.7717/peerj.4705.

++++

## Questions
If you have questions or issues, email Mads Reinholdt Jensen (mads.jensen@uit.no) or leave a comment on this repository.
