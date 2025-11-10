# MBO_WP2_Tables
Three tables generated as part of MBO WP2's work on identifying primers, reference databases and pipelines used for metabarcoding studies. The first table serves as an excellent starting point for ctrl+F searches for given primer sequences, e.g. when comparing across studies. We specifically include both 5'-3' and 3'-5' primer sequences to enable this ctrl+F search, as the same primers are sometimes reported in diferrent directions across studies. The second table identifies key reference databases often encountered in the literature, with specific details associated with each of them. The third table is a comprehensive (but likely incomplete) list of pipelines for processing metabarcoding data, providing external links to where to find more information about each of them.

### Table 1: An incomplete overview of empirically tested and/or frequently used metabarcoding primers and their target groups

|Primer&nbsp;combination&nbsp;name|Individual&nbsp;primer&nbsp;names&nbsp;(F&nbsp;and&nbsp;R)|F-primer (5′-3′) <br> F-primer (3′-5′)|R-primer (5′-3′) <br> R-primer (3′-5′)|Marker&nbsp;gene|Target&nbsp;group|Fragment&nbsp;size&nbsp;(bp)|Reference(s)|Additional&nbsp;usage&nbsp;notes&nbsp;and&nbsp;other&nbsp;relevant&nbsp;information|
|-----------|------------|--------------------------------------|--------------------------------------|------|------------|------------------|------------|-----|
|`18S_allshorts`|**F:** 18S_allshorts forward <br> **R:** 18S_allshorts reverse|TTTGTCTGSTTAATTSCG <br> GCSTTAATTSGTCTGTTT|TCACAGACCTGTTATTGC <br> CGTTATTGTCCAGACACT|18S (V7)|Eukaryotes|~110|Guardiola et al. (2015)|Highly specific for eukaryotes. Amplifies same region as Hardy et al. (2010), with almost same resolution for 40 bp less.|
|`18S_allshorts (mod. "Euka02")`|**F:** 18S_allshorts forward <br> **R:** 18S_allshorts reverse (mod.)|TTTGTCTGSTTAATTSCG <br> GCSTTAATTSGTCTGTTT|CACAGACCTGTTATTGC <br> CGTTATTGTCCAGACAC|18S (V7)|Eukaryotes|~110|Guardiola et al. (2015), Taberlet et al. (2018)|First "T" omitted compared to original reverse primer to better equilibrate the melting temperatures of the two primers.|
|`Aves01`|**F:** Aves_12Sa <br> **R:** Aves_12Sc|GATTAGATACCCCACTATGC <br> CGTATCACCCCATAGATTAG|GTTTTAAGCGTTTGTGCTCG <br> GCTCGTGTTTGCGAATTTTG|12S|Aves (birds)|~52|Epp et al. (2012)|Limited taxonomic resolution, but highly specific to birds.|
|`Arch01`|**F:** Arch01-F <br> **R:** Arch01-R|CCTGCTCCTTGCACACAC <br> CACACACGTTCCTCGTCC|CCTACGGCTACCTTGTTAC <br> CATTGTTCCATCGGCATCC|16S (V9)|Archaea|~85|Taberlet et al. (2018)|Highly specific of Archaea.|
|`Baci01`|**F:** Baci01-F <br> **R:** Baci01-R|ATTCCAGCTCCAATAGCGTA <br> ATGCGATAACCTCGACCTTA|CTTTRAACRCLCTRATTTYTTCAC <br> CACTTYTTTARTCLCRCAARTTTC|18S (V4)|Bacillariophyta (diatoms)|~150|Taberlet et al. (2018)|Will also amplify other eukaryotes.|
|`Bact02`|**F:** Bact02-F <br> **R:** Bact02-R|GCCAGCMGCCGCGGTAA <br> AATGGCGCCGMCGACCG|GGACTACCMGGGTATCTAA <br> AATCTATGGGMCCATCAGG|16S (V4)|Bacteria+Archaea|~254|Taberlet et al. (2018)||
|`Bact03`|**F:** Bact03-F <br> **R:** 806RB|GTGYCAGCMGCCGCGGTAA <br> AATGGCGCCGMCGACYGTG|GGACTACNVGGGTWTCTAAT <br> TAATCTWTGGGVNCATCAGG|16S (V4)|Bacteria+Archaea|~253|Baker et al. (2003), Quince et al. (2011), Apprill et al. (2015)|Recommended by Earth Microbiome Project. Not necessary to degenerate both primers if only targeting bacteria (Taberlet et al. 2018). There appears to be a couple of different versions of the F-primer, with "GTGCCAGCMGCCGCGGTAA" reported by Baker et al. (2003), "GTGNCAGCMGCCGCGGTAA" reported by Quince et al. (2011), and "GTGYCAGCMGCCGCGGTAA" first reported by Watanabe et al. (2001) and later Asami et al. (2005)|
|`Bact04`|**F:** Bact03-F <br> **R:** R926|GTGYCAGCMGCCGCGGTAA <br> AATGGCGCCGMCGACYGTG|CCGYCAATTYMTTTRAGTTT <br> TTTGARTTTMYTTAACYGCC|16S (V4-V5)|Bacteria+Archaea|~373-378|Baker et al. (2003), Quince et al. (2011)|Recommended by Earth Microbiome Project. Also amplifies a relatively large number of eukaryotes (Taberlet et al. 2018).|
|`BACTB`|**F:** BACTB-F <br> **R:** BACTB-R|GGATTAGATACCCTGGTAGT <br> TGATGGTCCCATAGATTAGG|CACGACACGAGCTGACG <br> GCAGTCGAGCACAGCAC|16S (V5-V6)|Bacteria|~258|Fliegerova et al. (2014)||
|`Balzano`|**F:** TAReuk454FWD1 (V4F) <br> **R:** V4RB|CCAGCASCYGCGGTAATTCC <br> CCTTAATGGCGYCSACGACC|ACTTTCGTTCTTGATYRR <br> RRYTAGTTCTTGCTTTCA|18S (V4)|Eukaryotes|~380|Stoeck et al. (2010), Balzano et al. (2015)||
|`Banos`|**F:** nu-SSU-1333-5′ (FF390) <br> **R:** nu-SSU-1647-3′ (FR-1)|CGATAACGAACGAGACCT <br> TCCAGAGCAAGCAATAGC|AICCATTCAATCGGTAIT <br> TIATGGCTAACTTACCIA|18S (V7-V8)|Fungi|~348|Banos et al. (2018)|Note that “I” (inosine) often gets replaced with “N” for bioinformatic software to recognize the wobble-base.|
|`Batr01`|**F:** batra_F <br> **R:** batra_R|ACACCGCCCGTCACCCT <br> TCCCACTGCCCGCCACA|GTAYACTTACCATGTTACGACTT <br> TTCAGCATTGTACCATTCAYATG|12S|Batrachia (frogs and salamanders)|~51|Valentini et al. (2016)||
|**CHECK**`Berry 16S-Fish`|**F:** Fish16sF/D <br> **R:** 16s2R (degenerate)|GACCCTATGGAGCTTTAGAC <br> CAGATTTCGAGGTATCCCAG|CGCTGTTATCCCTADRGTAACT <br> TCAATGRDATCCCTATTGTCGC|16S|Fishes|~200|Berry et al. (2017), Deagle et al. (2007)||
|`BF1/BR1`|**F:** BF1 <br> **R:** BR1|ACWGGWTGRACWGTNTAYCC <br> CCYATNTGWCARGTWGGWCA|ARYATDGTRATDGCHCCDGC <br> CGDCCHCGDTARTGDTAYRA|COI|Macroinvertebrates|217|Elbrecht & Leese (2017)|Designed for mock communities, so co-amplifies a lot of undesired taxa when applied to eDNA samples.|
|`Bryo01`|**F:** bryo_P6F <br> **R:**  Bryo01-R|GATTCAGGGAAACTTAGGTTG <br> GTTGGATTCAAAGGGACTTAG|CCATYGAGTCTCTGCACC <br> CCACGTCTCTGAGYTACC|trnL|Bryophyta|~53|Epp et al. (2012), Taberlet et al. (2018)|One degenerated bp in reverse primer compared to Epp et al. (2012).|
|`Caporaso`|**F:** F515 <br> **R:** R806|GTGCCAGCMGCCGCGGTAA <br> AATGGCGCCGMCGACCGTG|GGACTACHVGGGTWTCTAAT <br> TAATCTWTGGGVHCATCAGG|16S|Bacteria|~253|Baker et al. (2003), Caporaso et al. (2011)||
|`Cole01`|**F:** Cole01-F <br> **R:** Cole01-R|TGCWAAGGTAGCATAATMATTAG <br> GATTAMTAATACGATGGAAWCGT|TCTATAGGGTCTTCTCGTC <br> CTGCTCTTCTGGGATATCT|16S|Coleoptera (beetles)|~107|Taberlet et al. (2018)|Modified primers from Epp et al. (2012). Also amplifies other metazoans.|
|`Coll01`|**F:** COLA <br> **R:** COLB|ACGCTGTTATCCCTWAGG <br> GGAWTCCCTATTGTCGCA|GACGATAAGACCCTWTAGA <br> AGATWTCCCAGAATAGCAG|16S|Collembola (springtails)|~132|Janssen et al. (2017)||
|`Culi01`|**F:** Culicidae-f <br> **R:** Culicidae-r|ACGCTGTTATCCCTAAGGTAACTTA <br> ATTCAATGGAATCCCTATTGTCGCA|GACGAGAAGACCCTATAGATCTTTAT <br> TATTTCTAGATATCCCAGAAGAGCAG|16S|Culicidae (mosquitos)|~145|Schneider et al. (2016)||
|`Cyan01`|**F:** Cyan01-F <br> **R:** Cyan01-R|CTYAAGCCGACATTCTCAC <br> CACTCTTACAGCCGAAYTC|GACAACYAGGAGGTTTGC <br> CGTTTGGAGGAYCAACAG|23S|Cyanobacteria|~180|Taberlet et al. (2018)||
|`Elas02`|**F:** Elas02-F <br> **R:** Elas02-R|GTTGGTHAATCTCGTGCCAGC <br> CGACCGTGCTCTAAHTGGTTG|CATAGTAGGGTATCTAATCCTAGTTTG <br> GTTTGATCCTAATCTATGGGATGATAC|12S|Elasmobranchii|~182|Taberlet et al. (2018)||
|`Ench01`|**F:** Ench_12Sa <br> **R:** Ench_12Sc|GCTGCACTTTGACTTGAC <br> CAGTTCAGTTTCACGTCG|AGCCTGTGTACTGCTGTC <br> CTGTCGTCATGTGTCCGA|12S|Enchytraeidae|~48|Epp et al. (2012)||
|`Euka01`|**F:** All18SF <br> **R:** All18SR|TGGTGCATGGCCGTTCTTAGT <br> TGATTCTTGCCGGTACGTGGT|CATCTAAGGGCATCACAGACC <br> CCAGACACTACGGGAATCTAC|18S (V7)|Eukaryotes|~161|Hardy et al. (2010)|Highly specific of eukaryotes. Much longer fragment for certain insects, amphipods and isopods (Taberlet et al. 2018).|
|`Euka03`|**F:** Euka03-F <br> **R:** Euka03-R|CCCTTTGTACACACCGCC <br> CCGCCACACATGTTTCCC|CTTCYGCAGGTTCACCTAC <br> CATCCACTTGGACGYCTTC|18S (V9)|Eukaryotes|~133|Taberlet et al. (2018)|18S V9 has less reference sequences than V7, but this marker should provide higher taxonomic resolution and has a more standardized fragment size (Taberlet et al. 2018).|
|`Euk1391f-EukBr`|**F:** Euk1391f <br> **R:** EukBr|GTACACACCGCCCGTC <br> CTGCCCGCCACACATG|TGATCCTTCTGCAGGTTCACCTAC <br> CATCCACTTGGACGTCTTCCTAGT|18S (V9)|Eukaryotes|~128|Amaral-Zettler et al. (2009), Stoeck et al. (2010), https://earthmicrobiome.org/protocols-and-standards/18s/|Highly specific of eukaryotes. Used by Earth Microbiome Project. The reverse primer is not optimal. Described as “Euka04” in Taberlet et al. (2018).|
|`Fung01`|**F:** ITS5 <br> **R:** Fung01-R|GGAAGTAAAAGTCGTAACAAGG <br> GGAACAATGCTGAAAATGAAGG|CCAAGAGATCCGTTGYTGAAAGT <br> TGAAAGTYGTTGCCTAGAGAACC|ITS1|Fungi|~226|Epp et al. (2012)|Does not properly amplify Glomeromycota. Highly variable fragment length for some fungi (Taberlet et al. 2018). Reverse primer appears inspired from Epp et al. (2012), but is not identical to "5.8S_fungi" (CAAGAGATCCGTTGTTGAAAGTT)|
|`Fung02`|**F:** ITS5 <br> **R:** Fung02-R|GGAAGTAAAAGTCGTAACAAGG <br> GGAACAATGCTGAAAATGAAGG|CAAGAGATCCGTTGYTGAAAGTK <br> KTGAAAGTYGTTGCCTAGAGAAC|ITS1|Fungi|~225|Epp et al. (2012), Taberlet et al. (2018)|Modified version of Epp et al (2012)’s reverse primer to properly amplify Glomeromycota. Highly variable fragment length for some fungi (Taberlet et al. 2018).|
|`Hadziavdic 18S`|**F:** F-566 <br> **R:** R-1200|CAGCAGCCGCGGTAATTCC <br> CCTTAATGGCGCCGACGAC|CCCGTGTTGAGTCAAATTAAGC <br> CGAATTAAACTGAGTTGTGCCC|18S (V4-V5)|Eukaryotes|~654|Hadziavdic et al., 2014||
|`Inse01`|**F:** Inse01-F <br> **R:** Inse01-R|RGACGAGAAGACCCTATARA <br> ARATATCCCAGAAGAGCAGR|ACGCTGTTATCCCTAARGTA <br> ATGRAATCCCTATTGTCGCA|16S|Insecta|~155|Taberlet et al. (2018)|Close to the Clarke et al. (2014) primers.|
|`Isop01`|**F:** Isop01-F <br> **R:** Isop01-R|ATTTCAGGTCAAGGTGCAGCTT <br> TTCGACGTGGAACTGGACTTTA|ATTACAACCAAATCCAATTTCA <br> ACTTTAACCTAAACCAACATTA|12S|Isoptera (termites)|~66|Taberlet et al. (2018)||
|`Leray`|**F:** mlCOIintF <br> **R:** jgHCO2198|GGWACWGGWTGAACWGTWTAYCCYCC <br> CCYCCYATWTGWCAAGTWGGWCAWGG|TAIACYTCIGGRTGICCRAARAAYCA <br> ACYAARAARCCIGTRGGICTYCAIAT|COI|Metazoans|313|Leray et al. (2013), Geller et al. (2013)|Note that “I” (inosine) often gets replaced with “N” for bioinformatic software to recognize the wobble-base.|
|`Leray-XT`|**F:** mlCOIintF-XT <br> **R:** jgHCO2198|GGWACWRGWTGRACWITITAYCCYCC <br> CCYCCYATITIWCARGTWGRWCAWGG|TAIACYTCIGGRTGICCRAARAAYCA <br> ACYAARAARCCIGTRGGICTYCAIAT|COI|Metazoans|313|Geller et al. (2013), Wangensteen et al. (2018)||
|`Lumb01`|**F:** Lumb01-F <br> **R:** Lumb01-R|CAAGAAGACCCTATAGAGCTT <br> TTCGAGATATCCCAGAAGAAC|GGTCGCCCCAACCGAAT <br> TAAGCCAACCCCGCTGG|16S|Lumbricina (earthworms)|~31|Bienert et al. (2012)||
|`Lumb02`|**F:** Lumb02-F <br> **R:** Lumb02-R|ATTCGGTTGGGGCGACC <br> CCAGCGGGGTTGGCTTA|CTGTTATCCCTAAGGTAGCTT <br> TTCGATGGAATCCCTATTGTC|16S|Lumbricina (earthworms)|~74|Bienert et al. (2012)||
|`Mamm01`|**F:** Mamm01-F <br> **R:** Mamm01-R|CCGCCCGTCACCCTCCT <br> TCCTCCCACTGCCCGCC|GTAYRCTTACCWTGTTACGAC <br> CAGCATTGTWCCATTCRYATG|12S|Mammals|~58|Taberlet et al. (2018)||
|`Mamm02`|**F:** Mamm02-F <br> **R:** MamP007R|CGAGAAGACCCTRTGGAGCT <br> TCGAGGTRTCCCAGAAGAGC|CCGAGGTCRCCCCAACC <br> CCAACCCCRCTGGAGCC|16S|Mammals|~74|Taberlet et al. (2018), Giguet-Covex et al. (2014)|Forward primer slightly modified from Giguet-Covex et al. (2014). Also amplifies some other vertebrates.|
|`MarVer1`|**F:** MmoMV1F <br> **R:** MarVer1R-ndC|CGTGCCAGCCACCGCG <br> GCGCCACCGACCGTGC|GGGTATCTAATCCYAGTTTG <br> GTTTGAYCCTAATCTATGGG|12S|Vertebrates|**CHECK** 202?|Valsecchi et al. (2020)||
|`MarVer2`|**F:** MarVer2F-ndC <br> **R:** MmoMV2R|CCGCCCGTCACCCTC <br> CTCCCACTGCCCGCC|CTTATCTCCTCTTATATTTTTATACGTA <br> ATGCATATTTTTATATTCTCCTCTATTC|12S|Vertebrates|**CHECK** XXX|Valsecchi et al. (2020)||
|`MarVer3`|**F:** MmoMV3F <br> **R:** MarVer3R|GCTTTAATTAATTAATCCAATAGAATAAAATTAACC <br> CCAATTAAAATAAGATAACCTAATTAATTAATTTCG|GGATTGCGCTGTTATCCC <br> CCCTATTGTCGCGTTAGG|16S|Vertebrates|**CHECK** 245?|Valsecchi et al. (2020)||
|`Meta01`|**F:** Meta01-F <br> **R:** Meta01-R|YYCRMCTGTTTAYCAAAAACA <br> ACAAAAACYATTTGTCMRCYY|CCGGTYTGAACTCARATC <br> CTARACTCAAGTYTGGCC|16S|Metazoa|∼548|Taberlet et al. (2018)|Close to primers designed by Palumbi et al. (2002). Quite long fragment amplified, not likely to work for degraded samples.|
|`MiFish-E`|**F:** MiFish-E-F <br> **R:** MiFish-E-R|GTTGGTAAATCTCGTGCCAGC <br> CGACCGTGCTCTAAATGGTTG|CATAGTGGGGTATCTAATCCTAGTTTG <br> GTTTGATCCTAATCTATGGGGTGATAC|12S|Fishes/vertebrates|170–185|Miya et al. (2015)|Elasmobranch-optimized.|
|`MiFish-U`|**F:** MiFish-U-F <br> **R:** MiFish-U-R|GTCGGTAAAACTCGTGCCAGC <br> CGACCGTGCTCAAAATGGCTG|CATAGTGGGGTATCTAATCCCAGTTTG <br> GTTTGACCCTAATCTATGGGGTGATAC|12S|Fishes/vertebrates|163–185|Miya et al. (2015)|Universal version.|
|`MiFish-U (UiT mod.)`|**F:** MiFish-U-F (UiT mod.) <br> **R:** MiFish-U-R|GCCGGTAAAACTCGTGCCAGC <br> CGACCGTGCTCAAAATGGCCG|CATAGTGGGGTATCTAATCCCAGTTTG <br> GTTTGACCCTAATCTATGGGGTGATAC|12S|Fishes/vertebrates|163–185|Miya et al. (2015), Sales et al. (2019)|Note that the second base in the F primer has been replaced compared to the original.|
|`Parada`|**F:** 1389 F <br> **R:** 1510 R|TTGTACACACCGCCC <br> CCCGCCACACATGTT|CCTTCYGCAGGTTCACCTAC <br> CATCCACTTGGACGCTTCC|16S(V4-V5)/18S(V4)|Universal|~180|Parada et al. (2016)||
|`Poly01`|**F:** Poly01-F <br> **R:** Poly01-R|CCGGTYTGAACTCAGMTCA <br> ACTMGACTCAAGTYTGGCC|TGGCACCTCGATGTTGGCT <br> TCGGTTGTAGCTCCACGGT|16S|Polychaetes|~63|Taberlet et al. (2018)||
|`Riaz1`|**F:** F1 <br> **R:** R1|ACTGGGATTAGATACCCC <br> CCCCATAGATTAGGGTCA|TAGAACAGGCTCCTCTAG <br> GATCTCCTCGGACAAGAT|12S|Vertebrates|~106|Riaz et al. (2011)||
|`Riaz2 (12S-V5)`|**F:** 12S-V5-F <br> **R:** 12S-V5-R|TAGAACAGGCTCCTCTAG <br> GATCTCCTCCGACAAAGT|TTAGATACCCCACTATGC <br> GCATAGTGGGGTATCTAA|12S|Vertebrates|~97|Riaz et al. (2011)||
|`Sper01`|**F:** g-A49425 (Sper01-F) <br> **R:** h-B49466 (Sper01-R)|GGGCAATCCTGAGCCAA <br> AACCGAGTCCTAACGGG|CCATTGAGTCTCTGCACCTATC <br> CTATCCACGTCTCTGAGTTACC|trnL, P6 loop|Spermatophyta (seed plants)|~48|Taberlet et al. (2007)|Widely used for degraded material due to the short length.|
|`Stoeck`|**F:** TAReuk454FWD1 (V4F) <br> **R:** TAReukREV3 (V4R)|CCAGCASCYGCGGTAATTCC <br> CCTTAATGGCGYCSACGACC|ACTTTCGTTCTTGATYRA <br> ARYTAGTTCTTGCTTTCA|18S (V4)|Eukaryotes|~380|Stoeck et al. (2010)||
|`Tele01`|**F:** teleo_F <br> **R:** teleo_R|ACACCGCCCGTCACTCT <br> TCTCACTGCCCGCCACA|CTTCCGGTACACTTACCATG <br> GTACCATTCACATGGCCTTC|12S|Teleostei|~64|Valentini et al. (2016)|Poor resolution for Cyprinidae and Gadidae.|
|`Tele02`|**F:** Tele02-F <br> **R:** Tele02-R|AAACTCGTGCCAGCCACC <br> CCACCGACCGTGCTCAAA|GTTTGACCCTAATCTATGGG <br> GGGTATCTAATCCCAGTTTG|12S|Fishes/vertebrates|129-209|Taberlet et al. (2018), Thomsen et al. (2016)|F-primer first described as "V05F_898" from Thomsen et al. (2016).|

### Table 2: An overview of frequently used reference databases
|Database|Target&nbsp;group|Website/download&nbsp;link|Marker(s)|Known&nbsp;deficiencies|Last&nbsp;updated|Licence&nbsp;type|Coverage&nbsp;(Regions)|Additional&nbsp;usage&nbsp;notes&nbsp;and&nbsp;other&nbsp;relevant&nbsp;information|
|--------|-----------------|--------------------------|---------|------------|-----------------|-----------------|----------------------------|-----|
|`BOLD`|Animals, plants, fungi|https://boldsystems.org/|COI, rbcL, matK, ITS, 18S, 12S|Lack of prokaryotes. Taxonomic backbone different to other databases. Needs curation.|Frequent updates|Open/Restricted|Worldwide|Widely used database for species-level identification in DNA barcoding|
|`CRABS_NordicRefDBs`|Nordic&nbsp;Marine&nbsp;eDNA|https://github.com/MadsRJ/CRABS_NordicRefDBs|COI, 12S|Regional scope; under development|2025 (beta)|CC&nbsp;BY&nbsp;4.0|Nordic Seas|Regionally curated database initiative focusing on species from Nordic countries.|
|`DDBJ`|General|https://www.ddbj.nig.ac.jp/services/index-e.html?tag=database|All|Mirrors NCBI and ENA; metadata in Japanese|Continuous|Data is shared freely among DDBJ, NCBI, and ENA|Worldwide|DNA DataBank of Japan — part of the International Nucleotide Sequence Database Collaboration (INSDC).|
|`eKOI`|Eukaryotes, protists|https://github.com/rubenmiguens/eKOI_taxonomy_database/|COI|New and relatively untested|Uncertain|Not specified|Worldwide|Curated GenBank and mitogenome sequences, focusing on protists|
|`ENA (formerly EMBL)`|General|https://www.ebi.ac.uk/ena/browser/home|All|Low curation and heterogeneous metadata across submissions; sequences include both validated and unverified entries.|Continuous|Data is shared freely among DDBJ, NCBI, and ENA|Worldwide|European Nucleotide Archive; part of INSDC.|
|`ENSEMBL`|Eukaryotic&nbsp;genomes|https://ensembl.org/|Genomic|Focus on model and medically relevant organisms|Continuous|CC&nbsp;BY&nbsp;4.0|Worldwide|Genome browser integrating multiple assemblies and annotations.|
|`FlyBase`|Insects, *Drosophila* spp.|https://flybase.org/|Genomic and transcriptomic|Focused on model *Drosophila* species; not representative of insect diversity|Continuous|CC&nbsp;BY&nbsp;4.0|Worldwide (model species)|Comprehensive curated source for *Drosophila* genomics; mainly relevant for model-organism studies rather than environmental surveys|
|`GOLD`|Microbes (genomes, metagenomes)|https://gold.jgi.doe.gov/|Genomic, metagenomic|Metadata quality depends on submitter; limited marker-level annotation|Continuous|Open|Worldwide|Genomes OnLine Database—metadata registry for microbial genomes and metagenomes; often used to track projects integrated into IMG|
|`GreenGenes2`|Bacteria, Archaea|https://ftp.microbio.me/greengenes_release/current/|16S&nbsp;rRNA|Superseded by SILVA/GTDB; limited recent updates; partial taxonomy inconsistencies|2024-09-xx|BSD 2-Clause License, but with a 3rd clause that prohibits others from using the name of the copyright holder or its contributors to promote derived products without written consent.|Worldwide|Outdated but still used in some microbial studies|
|`GTDB`|Bacteria, Archaea|https://gtdb.ecogenomic.org/|16S, genomes|Only prokaryotes; taxonomy differs from NCBI|2025-04-16|CC&nbsp;BY&nbsp;4.0|Worldwide|Widely used for standardized bacterial and archaeal taxonomy.|
|`HMP`|Human microbiome|https://microbiomedb.org/mbio/app|16S, WGS|Limited to human-associated microbiomes; not applicable to environmental or non-human samples; and not updated on a regular basis|2024-05-07|CC&nbsp;BY&nbsp;4.0|Worldwide|Human Microbiome Project reference set.|
|`IMG`|Microbes (genomes, metagenomes, metatranscriptomes)|https://img.jgi.doe.gov/|Whole&nbsp;genomes,&nbsp;16S,&nbsp;functional&nbsp;genes|Annotation and taxonomy depend on submitter metadata; not optimized for marker-gene metabarcoding workflows|Continuous|DOE&nbsp;Data&nbsp;Policy&nbsp;(open&nbsp;for&nbsp;publicly&nbsp;released&nbsp;datasets)|Worldwide|Integrated Microbial Genomes (IMG) system maintained by JGI; provides analysis tools for genome, metagenome, and metatranscriptome datasets; linked to GOLD for project metadata|
|`KEGG`|General (functional genes, pathways)|https://www.genome.jp/kegg/|Functional&nbsp;genes|Primarily pathway-focused; limited taxonomic coverage and sequence-level annotation|Continuous|CC&nbsp;BY-NC&nbsp;4.0|Worldwide|Kyoto Encyclopedia of Genes and Genomes; integrates genomic and metabolic information for pathway and functional analyses|
|`MetaPhlAn`|Microbiomes (taxonomic profiling)|https://huttenhower.sph.harvard.edu/metaphlan/|Marker&nbsp;genes|Primarily human-associated; not suitable for general environmental communities|2023-11-10|CC&nbsp;BY&nbsp;4.0|Worldwide|Database of unique clade-specific marker genes used by MetaPhlAn for taxonomic profiling of microbial communities|
|`MIDORI2`|Eukaryotes|https://www.reference-midori.info/|Many markers|No prokaryotes included|Updates occur with every GenBank update|CC&nbsp;BY&nbsp;4.0|Worldwide|MIDORI2 comes in two curated versions, either with or without binomial species descriptions, such as "cf.," "aff.," and "sp."|
|`NCBI nr`|General|https://ftp.ncbi.nlm.nih.gov/blast/db/FASTA/|Any|Low curation and heterogeneous metadata across submissions; sequences include both validated and unverified entries.|Continuous|Data is shared freely among DDBJ, NCBI, and ENA|Worldwide|Comprehensive non-redundant version of NCBI nt|
|`NCBI nt`|General|https://ftp.ncbi.nlm.nih.gov/blast/db/FASTA/|Any|Low curation and heterogeneous metadata across submissions; sequences include both validated and unverified entries.|Continuous|Data is shared freely among DDBJ, NCBI, and ENA|Worldwide|Comprehensive but includes uncurated and redundant sequences|
|`NCBI RefSeq`|Curated representative taxa|https://ftp.ncbi.nlm.nih.gov/refseq/|Full genomes and individual gene sequences (including common barcoding markers).|Continuous|Open|Worldwide|Data is shared freely among DDBJ, NCBI, and ENA|Curated, non-redundant subset of INSDC sequences; standardized annotations for reference genomes|
|`PDB`|Proteins, macromolecular structures|https://www.rcsb.org/|Protein structures|Limited nucleotide data; experimental bias toward crystallizable proteins|Continuous|CC0|Worldwide|Protein Data Bank—key archive for experimentally determined 3D structures; relevant for structural bioinformatics|
|`Pfam`|Protein&nbsp;families|[http://pfam.xfam.org/](http://pfam.xfam.org/)|Protein sequences (domains)|Functional, not taxonomic focus; limited marker-level application|2025-06-19|CC0|Worldwide|Curated collection of protein domains and families; used for functional and phylogenetic annotation|
|`Phytozome`|Plants|https://phytozome-next.jgi.doe.gov/ & https://academic.oup.com/nar/article/40/D1/D1178/2903577?login=true|Genomes||Continuously|Creative Commons Attribution 4.0 International License|Worldwide|Relevant if exploring nuclear plant markers, otherwise not|
|`PR2`|Protists|https://pr2-database.org/|18S||2025-04-02|MIT License|Worldwide|Specialized and curated for protist ribosomal sequences|
|`RDP`|Bacteria, Archaea, Fungi||16S, 28S||||Worldwide|Focused on ribosomal RNA sequences, ideal for microbial metabarcoding.|
|`Silva`|Microbes, eukaryotes|https://www.arb-silva.de/|16S, 18S, 23S, 28S|Taxonomic inconsistencies, biases toward well-studied organisms, sequence quality issues|2024-07-11|CC&nbsp;BY&nbsp;4.0|Worldwide|A comprehensive online resource for quality checked and aligned ribosomal RNA sequence data|
|`TARA Oceans`|Marine microbes, plankton|https://www.ocean-microbiome.org/|16S,&nbsp;18S,&nbsp;metagenomic&nbsp;markers&nbsp;genetic&nbsp;and&nbsp;functional profiles|Ocean-focused; uneven coverage across depth zones and taxa|2019-11-12|Open|Global&nbsp;ocean|TARA Oceans reference dataset integrates global planktonic metagenomes and marker genes; foundational for marine microbiome and virome studies|
|`UNITE`|Fungi|https://unite.ut.ee/|ITS|Limited to fungal taxa|2025-06-17|CC0|Worldwide|Specialized for fungal ITS sequences|
|`WormBase`|*C. elegans* and related nematodes|https://www.alliancegenome.org/members/wormbase|Genomic and transcriptomic|Focused on model C. elegans; limited to nematodes|News and discussions on website, updates regularly|CC BY 4.0|Worldwide (model species)|Comprehensive curated source for nematode genomics; mainly relevant for model-organism studies rather than environmental surveys|
|`ZFIN`|*Danio rerio* (zebrafish)|https://zfin.org/|Genomic|||Creative Commons Attribution 4.0 International License|Zebrafish are native to South Asia, but sold worldwide in aquarium trade|Only relevant for studies of the model organism zebrafish|

### Table 3: An alphabetically ordered, incomplete overview of existing metabarcoding pipelines


|Pipeline|Link|Incl_Data_Challenge|Language|Relevant_marker|Error_rate_tool|ASV_OTU|Otu_raw_description|Tax_assign_cat|Otu_seq_comp_appr|Tax_class_collapse|
|--------|----|-------------------|--------|---------------|---------------|-------|-------------------|--------------|-----------------|------------------|
|`AMPtk`|https://github.com/nextgenusfs/amptk/|No|Python/R/Other|Any|UPARSE/DADA2/UNOISE2/UNOISE3|User defined|Spike-in filtering|Sequence similarity/Sequence composition|Hybrid/modular|LCA|
|`Anacapa`|https://github.com/limey-bean/Anacapa/|Yes|Python/Shell/R|All|DADA2|ASV||Other|bowtie2-blca|NA|
|`APSCALE`|https://github.com/DominikBuchner/apscale/|Yes|Python|CHECK|vsearch/DnoisE|ASV/OTU|LULU|Sequence similarity/Sequence composition|BOLDIGGER3/vsearch SINTAX|NA|
|`Banzai`|https://github.com/jimmyodonnell/banzai/|No|Shell/R/Python/HTML/Ruby|Any|vsearch/Swarm|OTU||Sequence similarity|CHECK|NA|
|`Barque`|https://github.com/enormandeau/barque/|No|Python/Shell/R|Any|vsearch/unoise3|Check||Sequence similarity/Sequence composition|vsearch/blast|NA|
|`BIOCOM-PIPE`|https://doi.org/10.1186/s12859-020-03829-3 & https://forge.inrae.fr/biocom/biocom-pipe|No|Perl/Python/HTML/Java/CSS|16S, 18S, 23S|CHECK|OTU||Sequence composition|rdp/other|LCA/other|
|`Cascabel`|https://github.com/AlejandroAb/CASCABEL/|Yes|Python/Java/R/Shell/Perl|Any|Other/DADA2|ASV/OTU||Sequence similarity/Sequence composition|vsearch/DADA2|LCA/NA|
|`CoMA3`|https://github.com/SebH87/CoMA3/|No|Python/Shell|16S/18S/23S/28S/ITS|DADA2/Unoise3/vsearch|OTU||Sequence similarity/Sequence composition|rdp/other|LCA|
|`DADA2`|https://benjjneb.github.io/dada2/tutorial.html|Yes|R|All|DADA2|ASV||Sequence similarity/Sequence composition|DADA2(CHECK)|CHECK|
|`Dadaist2`|https://github.com/quadram-institute-bioscience/dadaist2/|No|HTML/UnrealScript/Perl/R/Python/Nextflow/Other/|Any|DADA2|ASV||Sequence similarity/Sequence composition|DECIPHER/DADA2|LCA/other|
|`dadasnake`|https://github.com/a-h-b/dadasnake/|No|Python/R/Shell|16S/ITS/Any|DADA2|ASV/OTU||Sequence similarity/Sequence composition|MOTHUR/DECIPHER|LCA|
|`DAnIEL`|https://github.com/bioinformatics-leibniz-hki/DAnIEL|No|R/Python/TeX/Shell/Dockerfile/CSS/Other|ITS|DADA2|ASV/OTU||Sequence composition|SINTAX/rdp|LCA|
|`eDNAflow`|https://github.com/mahsa-mousavi/eDNAFlow/|No|||||||||
|`FROGS`|https://frogs.toulouse.inra.fr/|Yes|HTML/Python/Shell/Other (Galaxy)|All|DADA2/Swarm|ASV/OTU||Sequence similarity|blast|NA|
|`gDAT`|https://github.com/ut-planteco/gDAT/|No|||||||||
|`JAMP`|https://github.com/VascoElbrecht/JAMP/|No|||||||||
|`LotuS2`|https://github.com/hildebra/lotus2/|No(CHECK)|||||||||
|`MetaBarFlow`|https://github.com/evaegelyng/MetaBarFlow/|Yes|R/Python/Shell|Any|DADA2|ASV||Sequence similarity/Sequence composition|blast/custom|LCA|
|`MetaWorks`|https://github.com/terrimporter/MetaWorks/|Yes| C++/Python/shell| COI/rbcL/ITS/SSU rRNA/12S SSU mtDNA|vsearch|ASV/OTU||Sequence composition|rdp|NA|
|`MICCA`|https://github.com/compmetagen/micca/|No | Python|16S rRNA/ITS/18S/28S|other|OTU||Sequence composition/Sequence similarity |blast/rdp||
|`MiFish`|https://mitofish.aori.u-tokyo.ac.jp/mifish/|Yes|Python|12S Mifish|other|OTU||Sequence similarity|blast|NA|
|`OceanOmics-amplicon-nf`|https://github.com/MinderooFoundation/OceanOmics-amplicon-nf|Yes|Nextflow/Python/Groovy/HTML|All|DADA2|ASV||Sequence similarity|blast|LCA|
|`MJOLNIR`|https://github.com/uit-metabarcoding/MJOLNIR/||||||||||
|`MLI`||Yes|||||||||
|`mothur`|https://github.com/mothur/mothur/||||||||||
|`NextITS`|https://github.com/vmikk/NextITS/|No|Nextflow/R/Shell|ITS|vsearch|OTU||Sequence similarity|SH-matcher|mumu|
|`nfcore/ampliseq`|https://nf-co.re/ampliseq/2.9.0/|Yes|||||||||
|`OBITools4`|https://github.com/metabarcoding/obitools4/|No|Go/HTML/Shell/C/JavaScript|All|obiclean|ASV/OTU||Sequence similarity|obitag|LCA|
|`PacMan`|https://github.com/iobis/PacMAN-pipeline/|Yes|Python/R|All|DADA2|ASV||Sequence composition|rdp|LCA|
|`PEMA`|https://github.com/hariszaf/pema/||||||||||
|`PipeCraft2`|https://github.com/pipecraft2/pipecraft/|Yes|||||||||
|`PIPITS`|https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.12399/||||||||||
|`PMiFish`||Yes|||||||||
|`QIIME 2`|https://qiime2.org/ & https://github.com/qiime2/qiime2|Yes(CHECK)|||||||||
|`rainbowbridge`||Yes|||||||||
|`SCATA`|https://scata.mykopat.slu.se/ & https://github.com/mikdur/scata||||||||||
|`Seed2`|https://www.biomed.cas.cz/mbu/lbwrf/seed/|Yes|||||||||
|`Slim`|https://trtcrd.github.io/SLIM/||||||||||
|`Tourmaline`|https://github.com/aomlomics/tourmaline/|Yes|||||||||
|`UNOISE3`||Yes|||||||||
|`USEARCH`|https://cryptick-lab.github.io/NGS-Analysis/_site/usearch-v11.html||||||||||
|`VSEARCH`|https://github.com/torognes/vsearch/||||||||||
|`VTAM`|https://www.sciencedirect.com/science/article/pii/S200103702300034X/ & https://vtam.readthedocs.io/en/stable/content/overview.html||||||||||

## Acknowledgements
This repository was created under the framework of the EU-project [MARCO-BOLO](https://marcobolo-project.eu/). The MARCO-BOLO project is funded by the European Union under the Horizon Europe Programme, Grant Agreement No. 101082021 (MARCO-BOLO). Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the European Union or the European Research Executive Agency (REA). Neither the European Union nor the granting authority can be held responsible for them. UK participants in MARCO-BOLO are supported by the UKRI’s Horizon Europe Guarantee under the Grant No. 10068180 (MS); No. 10063994 (MBA); No. 10048178 (NOC).

![Fig1](figures_readme/MARCO-BOLO_logo_col.png)

## References
Amaral-Zettler, L. A., McCliment, E. A., Ducklow, H. W., Huse, S. M. (2009). A method for studying protistan diversity using massively parallel sequencing of V9 hypervariable regions of small-subunit ribosomal RNA genes. PLoS One 4(7), e6372. https://doi.org/10.1371/journal.pone.0006372.

Asami, H., Aida, M., Watanaba, K. (2005). Accelerated sulfur cycle in coastal marine sediment beneath areas of intensive shellfish aquaculture. Applied Environmental Microbiology 71(6), 2925-2933. https://doi.org/10.1128/AEM.71.6.2925-2933.2005. 

Baker, G. C., Smith, J. J., Cowan, D. A. (2003). Review and re-analysis of domain-specific 16S primers. Journal of Microbiological Methods 55(3), 541-555. https://doi.org/10.1016/j.mimet.2003.08.009.

Balzano, S., Abs, E., Leterme, S. C. (2015). Protist diversity along a salinity gradient in a coastal lagoon. Aquatic Microbial Ecology 74, 263-277 https://doi.org/10.3354/ame01740.

Banos, S., Lentendu, G., Kopf, A., Wubet, T., Glöckner, F. O., Reich, M. (2018). A comprehensive fungi-specific 18S rRNA gene sequence primer toolkit suited for diverse research issues and sequencing platforms. BMC Microbiol 18, 190. https://doi.org/10.1186/s12866-018-1331-4.

Berry, T. E., Osterrieder, S. K., Murray, D. C., Coghlan, M. L., Richardson, A. J., Grealy, A. K., Stat, M., Bejder, L., Bunce, M. (2017). DNA metabarcoding for diet analysis and biodiversity: A case study using the endangered Australian sea lion (*Neophoca cinerea*). Ecology and Evolution 7(14), 5435-5453. https://doi.org/10.1002/ece3.3123.

Bienert, F. De Danieli, S., Miquel, C., Coissac, E., Poillot, C., Brun, J.-J., Taberlet, P. (2012). Tracking earthworm communities from soil DNA. Molecular Ecology 21(8), 2017-2030. https://doi.org/10.1111/j.1365-294X.2011.05407.x.

Caporaso, J. G., Lauber, C. L., Walters, W. A., Berg-Lyons, D., Lozupone, C. A., Turnbaugh, P. J., Fierer, N., Knight, R. (2011). Global patterns of 16S rRNA diversity at a depth of millions of sequences per sample. Proc. Natl. Acad. Sci. U.S.A. 108 (supplement_1), 4516-4522. https://doi.org/10.1073/pnas.1000080107.

Deagle, B. E., Kirkwood, R., Jarman, S. N. (2007). Analysis of Australian fur seal diet by pyrosequencing prey DNA in faeces. Molecular Ecology 18(9), 2022-2038. https://doi.org/10.1111/j.1365-294X.2009.04158.x.

Elbrecht, V. & Leese, F. (2017). Validation and development of COI metabarcoding primers for freshwater macroinvertebrate bioassessment. Frontiers in Environmental Science 5, 11. https://doi.org/10.3389/fenvs.2017.00011.

Epp, L. S., Boessenkool, S., Bellemain, E. P., Haile, J., Esposito, A., Riaz, T., Erséus, C., Gusarov, V. I., Edwards, M. E., Johnsen, A., Stenøien, H. K., Hassel, K., Kauserud, H., Yoccoz, N. G., Bråthen, K. A., Willerslev, E., Taberlet, P., Coissac, E., Brochmann, C. (2012). New environmental metabarcodes for analysing soil DNA: potential for studying past and present ecosystems. Molecular Ecology 21(8), 1821-1833. https://doi.org/10.1111/j.1365-294X.2012.05537.x.

Hardy, C. M., Krull, E. S., Hartley, D. M., Oliver, R. L. (2010). Carbon source accounting for fish using combined DNA and stable isotope analyses in a regulated lowland river weir pool. Molecular Ecology 19(1), https://doi.org/10.1111/j.1365-294X.2009.04411.x.

Fliegerova, K., Tapio, I., Bonin, A., Mrazek, J., Callegari, M. L., Bani, P., Bayat, A., Vilkki, J., Kopečný, J., Shingfield, K. J., Boyer, F., Coissac, E., Taberlet, P., Wallace, R. J. (2014). Effect of DNA extraction and sample preservation method on rumen bacterial population. Anaerobe 29, 80-84. https://doi.org/10.1016/j.anaerobe.2013.09.015.

Geller, J., Meyer, C., Parker, M., & Hawk, H. (2013). Redesign of PCR primers for mitochondrial cytochrome c oxidase subunit I for marine invertebrates and application in all-taxa biotic surveys. Molecular Ecology Resources 13(5), 851-861. https://doi.org/10.1111/1755-0998.12138.

Giguet-Covex, C., Pansu, J., Arnaud, F., Rey, P.-J., Griggo, C., Gielly, L., Domaizon, I., Coissac, E., David, F., Choler, P., Poulenard, J., Taberlet, P. (2014). Long livestock farming history and human landscape shaping revealed by lake sediment DNA. Nature Communications 5, 3211. https://doi.org/10.1038/ncomms4211.

Guardiola, M., Uriz, M. J., Taberlet, P., Coissac, E., Wangensteen, O. S., & Turon, X. (2015). Deep-sea, deep-sequencing: Metabarcoding extracellular DNA from sediments of marine canyons. PLoS One 10(10), e0139633. https://doi.org/10.1371/journal.pone.0139633.

Hadziavdic, K., Lekang, K., Lanzen, A., Jonassen, I., Thompson, E. M., Troedsson, C. (2014). Characterization of the 18S rRNA gene for designing universal eukaryote specific primers. PLoS ONE 9(2), e87624. https://doi.org/10.1371/journal.pone.0087624.

Janssen, P., Bec, S., Fuhr, M., Taberlet, P., Brun, J.-J., Bouget, C. (2017). Present conditions may mediate the legacy effect of past land-use changes on species richness and composition of above- and below-ground assemblages. Journal of Ecology 106(1), 306-318. https://doi.org/10.1111/1365-2745.12808.

Leray, M., Yang, J. Y., Meyer, C. P., Mills, S. C., Agudelo, N., Ranwez, V., Boehm, J. T., & Machida, R. J. (2013). A new versatile primer set targeting a short fragment of the mitochondrial COI region for metabarcoding metazoan diversity: application for characterizing coral reef fish gut contents. Frontiers in Zoology 10, 34. https://doi.org/10.1186/1742-9994-10-34.

Miya, M., Sato, Y., Fukunaga, T., Sado, T., Poulsen, J. Y., Sato, K., Minamoto, T., Yamamoto, S., Yamanaka, H., Araki, H., Kondoh, M., & Iwasaki, W. (2015). MiFish, a set of universal PCR primers for metabarcoding environmental DNA from fishes: Detection of more than 230 subtropical marine species. Royal Society Open Science, 2(7), 150088. https://doi.org/10.1098/rsos.150088.

Parada, A. E., Needham, D. M., Fuhrman, J. A. (2016). Every base matters: assessing small subunit rRNA primers for marine microbiomes with mock communities, time series and global field samples. Environmental Microbiology 18(5), 1403-1414. https://doi.org/10.1111/1462-2920.13023.

Quince, C., Lanzen, A., Davenport, R. J., Turnbaugh, P. J. (2011). Removing noise from pyrosequenced amplicons. BMC Bioinformatics 12, 38. https://doi.org/10.1186/1471-2105-12-38.

Riaz, T., Shehzad, W., Viari, A., Pompanon, F., Taberlet, P., Coissac, E. (2011). ecoPrimers: inference of new DNA barcode markers from whole genome sequence analysis. Nucleic Acids Research 39(21), e145. https://doi.org/10.1093/nar/gkr732.

Sales, N. G., Wangensteen, O. S., Carvalho, D. C., Mariani, S. (2019). Influence of preservation methods, sample medium and sampling time on eDNA recovery in a neotropical river. Environmental DNA 1(2), 119–130. https://doi.org/10.1002/edn3.14.

Schneider, J., Valentini, A., Dejean, T., Montarsi, F., Taberlet, P., Glaizot, O., Fumagalli, L. (2016). Detection of invasive mosquito vectors using environmental DNA (eDNA) from water samples. PLoS ONE 11(9), e0162493. https://doi.org/10.1371/journal.pone.0162493.

Stoeck, T., Bass, D. Nebel, M., Christen, R., Jones, M. D. M., Breiner, H.-W., Richards, T. A. (2010). Multiple marker parallel tag environmental DNA sequencing reveals a highly complex eukaryotic community in marine anoxic water. Molecular Ecology 19(s1), 21-31. https://doi.org/10.1111/j.1365-294X.2009.04480.x.

Taberlet, P., Coissac, E., Pompanon, F., Gielly, L., Miquel, C., Valentini, A., Vermat, T., Corthier, G., Brochmann, C., Willerslev, E. (2007). Power and limitations of the chloroplast trn L (UAA) intron for plant DNA barcoding. Nucleic Acids Research 35(3), e14. https://doi.org/10.1093/nar/gkl938.

Taberlet, P., Bonin, A., Zinger, L., & Coissac, E. (2018). Environmental DNA: For biodiversity research and monitoring. Oxford University Press.

Thomsen, P. F., Møller, P. R., Sigsgaard, E. E., Knudsen, S. W., Jørgensen, O. A., & Willerslev, E. (2016). Environmental DNA from seawater samples correlate with trawl catches of subarctic, deepwater fishes. PLoS One, 11(11), e0165252. https://doi.org/10.1371/journal.pone.0165252.

Valentini, A., Taberlet, P., Miaud, C., Civade, R., Herder, J., Thomsen, P. F., Bellemain, E., Besnard, A., Coissac, E., Boyer, F., Gaboriaud, C., Jean, P., Poulet, N., Roset, N., Copp, G. H., Geniez, P., Pont, D., Argillier C., Baudoin, J.-M., Peroux, T., Crivelli, A. J., Olivier, A., Acqueberge, M., Le Brun, M., Møller, P. R., Willerslev, E., Dejean, T. (2016). Next-generation monitoring of aquatic biodiversity using environmental DNA metabarcoding. Molecular Ecology 25(4), 929-942. https://doi.org/10.1111/mec.13428.

Valsecchi, E., Bylemans, J., Goodman, S. J., Lombardi, R., Carr, I., Castellano, L., Galimberti, A., Galli, P. (2020). Novel universal primers for metabarcoding environmental DNA surveys of marine mammals and other marine vertebrates. Environmental DNA 2(4), 460-476. https://doi.org/10.1002/edn3.72.

Wangensteen, O. S., Palacín, C., Guardiola, M., & Turon, X. (2018). DNA metabarcoding of littoral hard-bottom communities: high diversity and database gaps revealed by two molecular markers. PeerJ 6, e4705. https://doi.org/10.7717/peerj.4705.

Watanabe, K., Kodama, Y., Harayama, S. (2001). Design and evaluation of PCR primers to amplify bacterial 16S ribosomal DNA fragments used for community fingerprinting. Journal of Microbiological Methods 44(3), 253-262. https://doi.org/10.1016/S0167-7012(01)00220-2.

## Questions
If you have questions or issues, email Mads Reinholdt Jensen (mads.jensen@uit.no) or leave a comment on this repository.
