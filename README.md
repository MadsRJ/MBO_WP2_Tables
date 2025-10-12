# MBO_WP2_Tables
Three tables generated as part of MBO WP2's work on identifying primers, reference databases and pipelines used for metabarcoding studies. The first table serves as an excellent starting point for ctrl+F searches for given primer sequences, e.g. when comparing across studies. The second table identifies key reference databases often encountered in the literature, with specific details associated with each of them. The third table is a comprehensive (but likely incomplete) list of pipelines for processing metabarcoding data, providing external links to where to find more information about each of them.

### Table 1: An incomplete overview of empirically tested and/or frequently used metabarcoding primers and their target groups

|Primer&nbsp;combination&nbsp;name|Individual&nbsp;primer&nbsp;names|F-primer (5′-3′) <br> F-primer (3′-5′)|R-primer (5′-3′) <br> R-primer (3′-5′)|Marker|Target&nbsp;group|Fragment&nbsp;size&nbsp;(bp)|Reference(s)|Random&nbsp;usage&nbsp;notes|
|-----------|------------|--------------------------------------|--------------------------------------|------|------------|------------------|------------|-----|
|`18S_allshorts`|||||||||
|`18S_allshorts (mod. “Euka02”)`|||||||||
|`Aves01`|||||||||
|`Arch01`|||||||||
|`Baci01`|||||||||
|`Bact02`|||||||||
|`Bact03`|||||||||
|`Bact04`|||||||||
|`BACTB`|||||||||
|`Balzano`|||||||||
|`Banos`|||||||||
|`Batr01`|||||||||
|`BF1/BR1`|||||||||
|`Bryo01`|||||||||
|`Caporaso`|||||||||
|`Cole01`|||||||||
|`Coll01`|||||||||
|`Culi01`|||||||||
|`Cyan01`|||||||||
|`Elas02`|||||||||
|`Ench01`|||||||||
|`Euka01`|||||||||
|`Euka03`|||||||||
|`Euk1391f-EukBr`|||||||||
|`Fung01`|||||||||
|`Fung02`|||||||||
|`Inse01`|||||||||
|`Isop01`|||||||||
|`Leray`|||||||||
|`Leray-XT`|||||||||
|`Lumb01`|||||||||
|`Lumb02`|||||||||
|`Mamm01`|||||||||
|`Mamm02`|||||||||
|`MarVer1`|||||||||
|`MarVer2`|||||||||
|`MarVer3`|||||||||
|`Meta01`|||||||||
|`MiFish-E`|**F:** MiFish-E-F <br> **R:** MiFish-E-R|GTTGGTAAATCTCGTGCCAGC <br> CGACCGTGCTCTAAATGGTTG|CATAGTGGGGTATCTAATCCTAGTTTG <br> GTTTGATCCTAATCTATGGGGTGATAC|12S|Fishes/vertebrates|170–185|Miya et al. (2015)|Elasmobranch-optimized.|
|`MiFish-U`|**F:** MiFish-U-F <br> **R:** MiFish-U-R|GTCGGTAAAACTCGTGCCAGC <br> CGACCGTGCTCAAAATGGCTG|CATAGTGGGGTATCTAATCCCAGTTTG <br> GTTTGACCCTAATCTATGGGGTGATAC|12S|Fishes/vertebrates|163–185|Miya et al. (2015)|Universal version.|
|`MiFish-U (UiT mod.)`|**F:** MiFish-U-F (UiT mod.) <br> **R:** MiFish-U-R|GCCGGTAAAACTCGTGCCAGC <br> CGACCGTGCTCAAAATGGCCG|CATAGTGGGGTATCTAATCCCAGTTTG <br> GTTTGACCCTAATCTATGGGGTGATAC|12S|Fishes/vertebrates|163–185|Miya et al. (2015), Sales et al. (2019)|Note that the second base in the F primer has been replaced compared to the original.|
|`Poly01`|||||||||
|`Riaz1`|||||||||
|`Riaz2 (12S-V5)`|||||||||
|`Sper01`|||||||||
|`Stoeck`|||||||||
|`Tele01`|||||||||
|`Tele02`|**F:** Tele02-F <br> **R:** Tele02-R|AAACTCGTGCCAGCCACC <br> CCACCGACCGTGCTCAAA|GTTTGACCCTAATCTATGGG <br> GGGTATCTAATCCCAGTTTG|12S|Fishes/vertebrates|129-209|Taberlet et al. (2018), Thomsen et al. (2016)|F-primer first described as "V05F_898" from Thomsen et al. (2016).|
### Table 2: An overview of frequently used reference databases
|Database|Target group|Download link|Marker|Deficiencies|Notes|
|-----------|------------|--------------------------------------|------|------------|------------------|
|`BOLD`||||||
|`EMBL`||||||
|`GreenGenes`||||||
|`MIDORI`||||||
|`NCBI nr`||||||
|`NCBI nt`||||||
|`NCBI RefSeq`||||||
|`PR2`||||||
|`Silva`||||||
|`UNITE`||||||
|`+++++`||||||

### Table 3: An alphabetically ordered, incomplete overview of existing metabarcoding pipelines
|Pipeline|Primary software used|Language|Clustering|Link|Notes|
|-----------|------------|--------------------------------------|------|------------|------------------|
|`AMPtk`||||||
|`Anacapa`||||||
|`APSCALE`||||||
|`Banzai`||||||
|`Barque`||||||
|`BIOCOM-PIPE`||||||
|`Cascabel`||||||
|`CoMA`||||||
|`DADA2`||||||
|`Dadaist2`||||||
|`dadasnake`||||||
|`DAnIEL`||||||
|`eDNAflow`||||||
|`FROGS`||||||
|`gDAT`||||||
|`JAMP`||||||
|`LotuS2`||||||
|`MetaBarFlow`||||||
|`MetaWorks`||||||
|`MetaWorksSite`||||||
|`MiFish`||||||
|`MICCA`||||||
|`MJOLNIR`||||||
|`mothur`||||||
|`NextITS`||||||
|`nfcore/ampliseq`||||||
|`OBITools3`||||||
|`PacMan`||||||
|`PEMA`||||||
|`PipeCraft2`||||||
|`PIPITS`||||||
|`QIIME 2`||||||
|`SCATA`||||||
|`Seed2`||||||
|`Slim`||||||
|`Tourmaline`||||||
|`USEARCH`||||||
|`VSEARCH`||||||
|`VTAM`||||||

## Acknowledgements
This repository was created under the framework of the EU-project [MARCO-BOLO](https://marcobolo-project.eu/). The MARCO-BOLO project is funded by the European Union under the Horizon Europe Programme, Grant Agreement No. 101082021 (MARCO-BOLO). Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the European Union or the European Research Executive Agency (REA). Neither the European Union nor the granting authority can be held responsible for them. UK participants in MARCO-BOLO are supported by the UKRI’s Horizon Europe Guarantee under the Grant No. 10068180 (MS); No. 10063994 (MBA); No. 10048178 (NOC).

![Fig2](figures_readme/MARCO-BOLO_logo_col.png)

## References 
Geller, J., Meyer, C., Parker, M., & Hawk, H. (2013). Redesign of PCR primers for mitochondrial cytochrome c oxidase subunit I for marine invertebrates and application in all-taxa biotic surveys. Molecular Ecology Resources 13(5), 851-861. https://doi.org/10.1111/1755-0998.12138.

Leray, M., Yang, J. Y., Meyer, C. P., Mills, S. C., Agudelo, N., Ranwez, V., Boehm, J. T., & Machida, R. J. (2013). A new versatile primer set targeting a short fragment of the mitochondrial COI region for metabarcoding metazoan diversity: application for characterizing coral reef fish gut contents. Frontiers in Zoology 10, 34. https://doi.org/10.1186/1742-9994-10-34.

Wangensteen, O. S., Palacín, C., Guardiola, M., & Turon, X. (2018). DNA metabarcoding of littoral hard-bottom communities: high diversity and database gaps revealed by two molecular markers. PeerJ 6, e4705. https://doi.org/10.7717/peerj.4705.

++++

## Questions
If you have questions or issues, email Mads Reinholdt Jensen (mads.jensen@uit.no) or leave a comment on this repository.
