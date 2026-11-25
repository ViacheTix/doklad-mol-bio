**protocol** 

# **Single-stranded DNA library preparation for the sequencing of ancient or damaged DNA** 

### **Marie-Theres Gansauge & Matthias Meyer** 

Department of Evolutionary Genetics, Max Planck Institute for Evolutionary Anthropology, Leipzig, Germany. Correspondence should be addressed to M.-T.G. (marie_gansauge@eva.mpg.de) and M.M. (mmeyer@eva.mpg.de). 

Published online 14 March 2013; corrected after print 15 May 2013; doi:10.1038/nprot.2013.038 

**this protocol describes a method for converting short single-stranded and double-stranded Dna into libraries compatible with high-throughput sequencing using Illumina technology. this method has primarily been developed to improve sequence retrieval from ancient Dna, but it is also applicable to the sequencing of short or degraded Dna from other sources, and it can also be used for sequencing oligonucleotides. single-stranded library preparation is performed by ligating a biotinylated adapter oligonucleotide to the 3** ′ **ends of heat-denatured Dna. the resulting strands are then immobilized on streptavidin-coated beads and copied with a polymerase. a second adapter is attached by blunt-end ligation, and library preparation is completed by pcr amplification. We estimate that intact Dna strands are recovered in the library with ~50% efficiency. libraries can be generated from up to 12 Dna or oligonucleotide samples in parallel within 2 d.** 

#### **IntroDuctIon** 

#### **Background** 

High-throughput DNA sequencing technologies have enabled major advances in the retrieval of sequences from ancient biological samples, including the generation of entire genomes from samples thousands of years old<sup>1–4</sup> . Besides offering massive throughput, generating billions of sequences per run, these technologies have transformed the sample preparation process in a way that is eminently suitable for the sequencing of ancient DNA. The most widely used high-throughput technologies require the conversion of DNA fragments into DNA libraries before sequencing<sup>5–8</sup> . This is achieved by attaching artificial DNA segments (adapters) to both ends of the fragments. These adapters enable the priming of the sequencing reaction and, importantly, the amplification of the DNA library by PCR. By amplifying all fragments that were successfully converted into library molecules, the library is effectively immortalized. Thus, the same library is available for both whole-genome shotgun sequencing and for enriching genomic regions of interest via hybridization capture<sup>9–12</sup> . 

Until recently, only two methods have been used for library preparations from ancient DNA. Both use double-stranded DNA and were originally developed for high-throughput sequencing of modern DNA. The first method was developed by 454 Life Sciences and is based on the ligation of two different adapters to blunt end–repaired double-stranded DNA<sup>5</sup> . The second method, first suggested by Illumina, uses a single, Y-shaped adapter with a T-overhang that is ligated to both ends of DNA fragments that have been manipulated to carry A-overhangs<sup>6</sup> . The single-stranded library preparation method described here was specifically developed for the sequencing of ancient DNA. It accounts for the fact that ancient DNA is usually highly fragmented and present only in trace amounts. 

Single-stranded library preparation offers several advantages over library preparation from double-stranded DNA. First, through the initial biotinylation of the ancient molecules, all reaction steps are carried out while the DNA is tightly bound to streptavidin-coated beads. This strategy avoids the loss of molecules in DNA purification steps using silica spin columns or carboxylated beads<sup>13</sup> that are integral parts of the double-stranded library preparation methods described above. Second, DNA molecules with single-strand 

breaks on both strands may be present in ancient biological samples. Such molecules are entirely lost in double-stranded library preparation, whereas with the single-stranded method they are disassembled into multiple fragments upon heat denaturation, and each fragment has an independent chance of being recovered in the library. Third, end modifications located on one strand of a double-stranded molecule may completely inhibit adapter ligation during double-stranded library preparation. In the single-strand library approach, the strand opposite to that containing such a modification can still be retrieved. 

The effectiveness of the single-stranded library preparation method was recently demonstrated by sequencing the genome of an extinct archaic human to 30-fold coverage<sup>14</sup> . In this study, we estimated that single-stranded library preparation increased the sequence yield at least sixfold compared with the 454-type doublestranded method that was used to generate the draft genome sequence (1.9-fold coverage) from the same DNA extracts. Preliminary results from ongoing work with other samples confirm that library yields are consistently higher with the single-stranded method. It should be noted, however, that our comparisons have not included the Illumina-type library preparation method. In our experience, this method is less suitable for the generation of libraries from highly degraded DNA because standard implementations of the method (e.g., Illumina’s TruSeq DNA sample preparation kit, no. 15026486 Rev. A, or NEB’s NEBNext ultra DNA library prep kit, v1.1) require size-selective DNA purification steps with carboxylated beads to remove adapter dimers formed during ligation. Compared with the silica-based purification steps used in the 454-type method, purification with carboxylated beads leads to the loss of a larger fraction of library molecules with short inserts, which often contain a substantial proportion of the surviving genetic information. Unbiased comparisons of library yield among all three library preparation methods would therefore require prior optimization of the purification steps in the Illumina-type method. 

#### **Description of the method** 

Single-stranded library preparation comprises the following stages ( **Fig. 1** ). Before heat denaturation, DNA is treated with a heat-labile 

**nature protocols** | VOL.8 NO.4 | 2013 | **737** 

**protocol** 

![](markdown/images/04_Gansauge_Meyer_2013_ssDNA_Library_Prep/04_Gansauge_Meyer_2013_ssDNA_Library_Prep.pdf-0002-02.png)

<!-- Start of picture text -->
5′ 3′<br>Pho U<br>3′ 5′ 3′ 5′ Pho<br>Steps 1–4<br>5′ 3′ 5′ 3′<br>U  5′ 3′ 5′ 3′<br>Pho 5′ x xxxxxxxxx 3′ Btn Steps 5–7<br>5′ x xxxxxxxxx 3′Btn<br>3′<br>5′<br>Steps 8–15<br>5′ x xxxxxxxxx 3′ Btn<br>A<br>3′ Steps 16–19 Pho A 35′′ x xxxxxxxxx Btn3′<br>5′<br>5′ x xxxxxxxxx 3′ Btn<br>3′ Pho 5′<br>5′ 3′ x xxxxxxxxx Btn<br>3′ 5′ Pho Steps 20–24 3′<br>5′ 3′ 5′ 3′<br>x xxxxxxxxx Btn<br>3′ Pho 5′<br>x xxxxxxxxx Btn<br>Step 25 3′<br>5′ 3′<br>5′ 3′ x xxxxxxxxx Btn<br>3′ 5′<br>Steps 26–29 Steps 30–32<br>(qPCR) (Indexing)<br>5′ 3′<br>5′<br>3′ N NNNNN N<br>3′ 5′<br>5′ 3′<br>NNNNNN N<br>NNNNNN N<br>3′ 5′<br><!-- End of picture text -->

**Figure 1**<sup>**|**</sup> Schematic overview of single-stranded library preparation, exemplified by one strand of a double-stranded DNA molecule containing a uracil and a singlestrand break. A, deoxyadenine; Btn, biotin; Pho, <u>phosphate; U, deoxyuracil.</u> 

phosphatase to remove residual phosphate groups from the 5′ and 3′ ends of the DNA strands, the presence of which would otherwise render self-circularization possible or prevent adapter ligation ( **Fig. 1** , Steps 1–4 of the PROCEDURE). At this stage, deoxyuracils derived from cytosine deamination may also be removed from the DNA strands (see Experimental design). Next, a 5′-phosphorylated adapter oligonucleotide, consisting of 10 nucleotides and a long 3′-biotinylated spacer arm, is ligated to the 3′ ends of the DNA strands using CircLigase II ( **Fig. 1** , Steps 5–7). The adapter-ligated molecules, as well as excess adapter molecules, are immobilized on streptavidin beads, and a 5′-tailed primer complementary to the adapter is used to copy the template strand ( **Fig. 1** , Steps 8–15). This reaction is performed using Bst polymerase 2.0, a truncated homolog of _Bacillus stearothermophilus_ DNA polymerase I, which, owing to a lack of 3′–5′ exonuclease activity, leaves 3′ overhangs. As primer and adapter hybridize only weakly, wash steps at slightly elevated temperature are sufficient to remove excess primers, including primers bound to unligated adapter molecules, which would otherwise participate in a later ligation step and cause the 

formation of adapter dimers ( **Fig. 1** , Steps 16–19). After removal of 3′ overhangs using T4 DNA polymerase, a second adapter is joined to the newly synthesized strands by blunt-end ligation with T4 DNA ligase ( **Fig. 1** , Steps 20–24). To prevent ligation between adapters, only one adapter strand is ligatable, whereas the other is blocked by a 3′-terminal dideoxy modification. After washing away excess adapter, the library molecules are released from the beads by heat denaturation ( **Fig. 1** , Step 25). This denaturation step also releases a fraction of the biotinylated molecules, including the original template strands. However, these molecules lack priming sites and do not serve as template during subsequent amplification. After library preparation, the yield of library molecules is estimated by qPCR ( **Fig. 1** , Steps 26–29), and full-length adapter sequences, including sample bar codes, are added through amplification with tailed primers ( **Fig. 1** , Steps 30–32) using AccuPrime Pfx polymerase (an enzyme that was found to introduce relatively little PCR bias<sup>15</sup> ). The library may then be sequenced directly or be used in downstream target-enrichment experiments. 

#### **Applications and limitations of single-stranded library preparation** 

Although the approach described herein was developed specifically to enhance the retrieval of sequences from ancient DNA, a number of additional potential applications exist. For example, single-stranded library preparation could be highly useful for the sequencing of relatively modern DNA samples that have been stored under damaging conditions. The method seems particularly suited to the processing of formalin-fixed samples, which often contain highly fragmented DNA that is cross-linked to proteins<sup>16</sup> . Although formation of these cross-links can be partially reversed via heat treatment<sup>17</sup> , heating these samples will cause denaturation of the DNA strands and will thus interfere with conventional library preparation methods. 

An additional application of single-stranded library preparation is the sequencing of oligonucleotides, for which no straightforward method currently exists. This approach could be implemented for the purpose of quality control, for example, for testing complex mixtures of oligonucleotides synthesized on arrays. On the basis of a positive control using an artificial oligonucleotide ( **Box 1** and **Fig. 2** ), we estimate that between 30 and 70% of all undamaged DNA strands are successfully converted to library molecules (if they do not carry modifications). For double-stranded DNA, this translates into a likelihood of 51–91% of retrieving at least one of the two complementary strands. The efficiency of the protocol described herein may also make it attractive for the preparation of libraries from very small amounts of high-quality modern DNA, such as DNA extracted from single cells. However, this DNA would have to be sheared to small fragments, and it is unclear whether there would be any advantage to this approach over implementing multiple displacement amplification, which has proven to be highly effective for this purpose<sup>18</sup> . 

Finally, all other methods for preparing DNA libraries cause the loss of the original ends of molecules, because they either involve blunt-end repair or enzymatic fragmentation of DNA<sup>19</sup> . With the single-stranded method, adapters are joined without removing nucleotides from the DNA strands, which enables the determination of DNA fragmentation patterns in high resolution and in principle even enables the reconstruction of both strands of DNA fragments. 

**738** | VOL.8 NO.4 | 2013 | **nature protocols** 

**protocol** 

## **Box 1 | Determining the efficiency of library** **<u>preparation</u>** 

In each experiment, one library should be prepared using an oligonucleotide, CL104, as template. The 60-nt sequence of this oligonucleotide ( **table 1** ) is derived from pUC19. A qPCR standard identical in sequence to libraries prepared from this oligonucleotide can be generated by amplifying pUC19 DNA with a pair of 5′-tailed primers (Reagent Setup). This standard is then used in two qPCR assays. The first assay uses a pair of primers, IS7 and IS8, which binds to the adapter sequences and provides an estimate of the number of library molecules that were generated. The second assay uses a primer pair, CL107 and CL107, which is specific to CL104, to determine the number of oligonucleotide molecules that went into library preparation (see **Fig. 2** for a graphical scheme). The ratio of these numbers (assay 2/assay 1) provides an estimate of library preparation efficiency, which typically ranges from 30 to 70% (variation in these estimates is probably due to dilution and qPCR errors). 

One limitation of the current protocol is that it was developed using only adapter sequences compatible with Illumina sequencing platforms. Furthermore, one of the adapters is truncated by five bases to enable the incorporation of a terminal dideoxy cytosine nucleotide, which requires the use of a custom-designed primer in one of the sequencing reads (a comparison of adapter sequences is provided in **Supplementary Fig. 1** ). Exchanging the sequencing primer is trivial if an Illumina sequencer is accessible in the laboratory, but it may be inconvenient if external sequencing services are used. It should be noted, however, that libraries prepared with the single-stranded method can be loaded along with other standard libraries on the same flow cell. 

A general limitation of the method is that it is suitable only for the sequencing of relatively short molecules, because the efficiency of single-stranded ligation decreases for molecules longer than 120 bp (ref. 20). The majority of DNA fragments in ancient specimens are typically well below this size, but for samples preserved under very favorable conditions, for instance in the permafrost environment, double-stranded library preparation may be a more suitable approach. It should also be noted that single-stranded library preparation is more costly and time-consuming than doublestranded library preparation. Thus, if there are few restrictions on the amount of material that can be used for destructive sampling, for instance if several grams of material can be removed from large animal bones, it may be preferable to proceed with doublestranded library preparation at the expense of using more material. A detailed protocol of the 454-type method that would be suitable for this purpose is provided elsewhere<sup>21,22</sup> . 

#### **Experimental design** 

The protocol as presented contains optional steps and controls that may be included according to the requirements of the application. First, a decision must be made as to whether deoxyuracils, which constitute the only type of miscoding damage that occurs frequently in ancient DNA<sup>23,24</sup> , should be removed during library preparation using uracil-DNA glycosylase (UDG) and endonuclease VIII. Removal of deoxyuracils has been found to improve sequence accuracy without substantially reducing sequence yield<sup>25</sup> . However, in some cases, it may be advantageous to preserve damage patterns, for example, when authenticating DNA sequences from hominin remains<sup>26,27</sup> . By deviating from the first description of the single-stranded library preparation method<sup>14</sup> , we now recommend the use of UDG isolated from _Archaeoglobus fulgidus_ (Afu) instead of _Escherichia coli_ , a change that improves the efficacy of uracil removal from the 3′ ends of DNA strands ( **Supplementary Fig. 2** ). 

The second consideration is the amount of input DNA that is to be used for library preparation. Optimal results are obtained with 

input amounts between 1 femtomole and 1 picomole of singlestranded DNA. This range corresponds to between ~3 × 10<sup>8</sup> and ~3 × 10<sup>11</sup> double-stranded DNA molecules or, with an average fragment size of 40 bp, between ~13 pg and ~13 ng of DNA. With higher amounts of DNA, the efficiency of single-stranded ligation decreases. If too little DNA is used, the libraries will be dominated by artifacts, because single-stranded library preparation, similar to other methods, generates a background of library molecules even if no sample DNA is added. This background typically corresponds to around 1 × 10<sup>8</sup> molecules, which are mostly derived from adapter dimers and synthesis artifacts present in the adapter oligonucleotide. This background should be assessed by including a water control in each library preparation experiment. It is important to note that libraries that are dominated by artifacts may still contain billions of sample library molecules and remain fully amenable to target enrichment by hybridization capture. However, if whole-genome shotgun sequencing is desired, the excess artifacts should be removed by size fractionation after library amplification (e.g., on a polyacrylamide gel, as described elsewhere<sup>14</sup> ). 

We routinely extract DNA from 10–50 mg of ancient bones or teeth and then use 20% of the extracts in an initial library preparation experiment; we do this without making any preventive attempts to determine DNA concentrations, which are often too low for direct quantification. By following this scheme, we have only rarely obtained libraries containing more than 10<sup>11</sup> molecules, a molecule count that may indicate the beginning of saturation with input DNA (note that large amounts of microbial DNA may be present in DNA extracts even if the preservation of endogenous DNA is poor). When such high molecule counts are observed, before converting the remaining extract into libraries, it is advisable to perform a titration experiment using different volumes of the DNA extract in independent preparations to determine the highest volume of extract that still yields a linear increase in the number of library molecules. The same strategy can also be used to test for the presence of inhibitory substances in DNA extracts, another factor that may lead to a nonlinear input-output relationship of DNA and library molecules. By using different versions of silica-based DNA extraction<sup>28</sup> on several ancient bone samples, we have not observed any inhibition of library preparation unless the DNA was extracted from large amounts of bone ( >300 mg) or the silica matrix was not properly desalted before DNA elution. The latter problem can be identified by preparing 

![](markdown/images/04_Gansauge_Meyer_2013_ssDNA_Library_Prep/04_Gansauge_Meyer_2013_ssDNA_Library_Prep.pdf-0003-11.png)

<!-- Start of picture text -->
CL104 P5 adapter CL104 P7 adapter<br>Positive control oligo Library from positive control oligo<br>qPCR 1 qPCR 2<br><!-- End of picture text -->

<table><tr><th>qPCR 1</th><th></th><th>qPCR 2</th></tr></table>

**Figure 2**<sup>**|**</sup> Schematic representation of the qPCR amplification schemes. 

**nature protocols** | VOL.8 NO.4 | 2013 | **739** 

## **protocol** 

libraries from a synthetic oligonucleotide both with and without the spike-in of an extract generated without input of sample material, followed by comparing library yields by qPCR. 

When working with ancient DNA or other sensitive genetic material, established guidelines should be followed to minimize the risk of contamination with DNA from exogenous sources, such as amplification products or human DNA<sup>29</sup> . Similarly, sensible controls should be performed throughout all experiments. In addition to a water sample and a positive control that uses a synthetic oligonucleotide ( **Box 1** ), these should also include a blank control that is carried through the DNA extraction process, library preparation and all downstream steps into sequencing, such as library amplification and target enrichment. The level of contamination introduced during DNA extraction and library 

preparation cannot be reliably assessed from the molecule counts of the control libraries, because, unless contamination is very severe, it will contribute fewer molecules to the library than the background artifacts. 

The protocol provided here is fully compatible with sample multiplexing on the Illumina platform. It is important to recognize in this context that false assignment of sequences to samples will confound experiments as much as physical cross-contamination in the laboratory. The protocol offers the choice of including one or two bar codes (‘indexes’) within the adapter sequences of each sample. As false-assignment rates of up to 0.3% have been found with single-indexed sequencing<sup>22</sup> , we strongly urge readers to double-index—or to keep samples separate during sequencing— if conclusions are to be based on a small number of sequences. 

#### **MaterIals** 

##### **REAGENTS** 

- Ancient or damaged DNA or oligonucleotide sample to be sequenced. To give an idea of the amount of DNA needed to perform this protocol, we routinely extract DNA from 10–50 mg of ancient bones or teeth and then collect 20% of the resulting extracts for use in the PROCEDURE, without attempting to estimate their DNA concentration 

- Oligonucleotide solutions for library preparation and amplification ( **Table 1** )  **crItIcal** We strongly recommend checking the synthesis quality using acrylamide gel electrophoresis (an exemplary gel picture is provided in **Supplementary Fig. 3** ). Synthesis artifacts and impurities will lower the yield of library preparation. Moreover, incomplete single-stranded adapter oligonucleotides may serve as template for library preparation, causing artifact formation. 

- Ice-water bath 

- Water, HPLC grade (Sigma-Aldrich, cat. no. 270733) 

- NaCl solution, 5 M (Sigma-Aldrich, cat. no. S5150-1L) 

- EDTA solution, pH 8.0, 0.5 M (AppliChem, cat. no. A4892,1000) 

- SDS solution, 20% (wt/vol; Ambion, cat. no. AM9820) 

- SSC buffer, 20× (Ambion, cat. no. AM9770) 

- Tris-HCl solution, pH 8.0, 1 M (AppliChem, cat. no. A4577,0500) 

- Tween 20 (Sigma-Aldrich, cat. no. P5927-100ML); also prepare a 1% (vol/vol) dilution in water 

- Bead-binding and wash buffers (Reagent Setup) 

- _A. fulgidus_ uracil-DNA glycosylase (Afu UDG, NEB, cat. no. M0279L) 

- Endonuclease VIII (NEB, cat. no. M0299L) 

- FastAP thermosensitive alkaline phosphatase (Thermo Scientific, cat. no. EF0651) 

- CircLigase II ssDNA ligase (Epicentre, cat. no. CL9025K), including 10× reaction buffer and 50 mM MnCl2 solution 

- PEG-4000 solution, 50% (wt/vol) (Sigma-Aldrich, cat. no. 89782-100ML-F) 

- Dynabeads MyOne streptavidin C1 (Life Technologies, cat. no. 65001) 

- Bst 2.0 DNA polymerase (NEB, cat. no. M0537L), including 10× isothermal amplification buffer 

- dNTP mix, 25 mM each dNTP (Thermo Scientific, cat. no. R1121) 

- T4 DNA polymerase (Thermo Scientific, cat. no. EP0062) 

- Buffer Tango, 10× (Thermo Scientific, cat. no. BY5) 

- T4 DNA ligase (Thermo Scientific, cat. no. EL0012), including 50% PEG-4000 solution and 10× T4 Ligation buffer 

- Maxima SYBR Green qPCR Master Mix (Thermo Scientific, cat. no. K0252) 

- AccuPrime Pfx DNA polymerase (Life Technologies, cat. no. 12344-024), including 10× AccuPrime reaction mix 

- MinElute PCR purification kit (Qiagen, cat. no. 28006) or Agencourt AMPure XP-PCR purification kit (Beckman Coulter, cat. no. A63880) 

- pUC19 vector (NEB, cat. no. N3041S) 

- SYBR Gold nucleic acid gel stain (Life Technologies, cat. no. S-11494) 

- • 20/100 Ladder (IDT) 

##### **EQUIPMENT** 

- LoBind tubes, 1.5 ml (Eppendorf, cat. no. 0030 108.116) 

LoBind tubes, 0.5 ml (Eppendorf, cat. no. 0030 108.094) 

• Single-capped PCR strip tubes (e.g., Eppendorf, cat. no. 0030 124.359) • PCR plate with optical strip caps, 96-well (e.g., Applied Biosystems, cat. no. 403012) 

- Conical tubes, 50 ml (e.g., Genaxxon, cat. no. I2204.0320) 

Racks for 0.5-ml tubes and 1.5-ml tubes 

- Microcentrifuges for 0.5-ml tubes, 1.5-ml tubes and 8-strip PCR tubes 

- • Plate centrifuge for 96-well PCR plates 

- Tube rack for ice-water bath, 0.5 ml (e.g., Biozym, cat. no. 730091) 

- Magnetic rack for 96-well PCR plates (e.g., Agencourt, cat. no. A29164) 

- • Magnetic rack for 1.5-ml tubes (e.g., Life Technologies, cat. no. 123-21D) • Thermal cyclers with lid heating; one for 0.2-ml PCR tubes and one for 0.5-ml tubes (e.g., DNA Engine thermal cycler PTC-200, MJ Research) 

Rotator for 1.5-ml tubes (e.g., VWR, cat. no. 13916-822) 

- Vortex mixer (e.g., Scientific Industries, cat. no. SI-0256) 

- Cooling ThermoMixer MKR13 (HLC/Ditabis) (optional, see Reagent Setup for alternative incubation strategies) 

- Mx3005P qPCR system (Stratagene) or any other system compatible with SYBR Green qPCR kits 

- Agilent DNA 1000 kit (Agilent Technologies, cat. no. 5067-1504) 

- Bioanalyzer 2100 (Agilent Technologies) 

- Criterion TBE-urea gel 10% (wt/vol; Bio-Rad, cat. no. 345-0089) 

- Criterion cell and PowerPac basic power supply (Bio-Rad, cat. no. 165-6019) 

• Illumina sequencing instrument (e.g., HiSeq, MiSeq) and related sequencing chemistry 

##### **REAGENT SETUP** 

 **crItIcal** If the buffers and solutions are prepared in the volumes indicated below, they will suffice for at least 25 reactions. 

**Bead-binding buffer (10 ml)** Combine 7.63 ml of water (here and elsewhere, use the HPLC-grade water listed in Reagents), 2 ml of 5 M NaCl, 100 µl of 1 M Tris-HCl (pH 8.0), 20 µl of 0.5 M EDTA (pH 8.0), 5 µl of Tween 20 and 250 µl of 20% (wt/vol) SDS.  **crItIcal** Add SDS only immediately before use, as this buffer has no shelf life after the addition of SDS. 

**Wash buffer A (50 ml)** Combine 47.125 ml of water, 1 ml of 5 M NaCl, 500 µl of 1 M Tris-HCl (pH 8.0), 100 µl of 0.5 M EDTA (pH 8.0), 25 µl of Tween 20 and 1.25 ml of 20% (wt/vol) SDS. This buffer can be stored at room temperature (22 °C) safely for at least 1 month. 

**Wash buffer B (50 ml)** Combine 48.375 ml of water, 1 ml of 5 M NaCl, 500 µl of 1 M Tris-HCl (pH 8.0), 100 µl of 0.5 M EDTA (pH 8.0) and 25 µl of  Tween 20. This buffer can be stored at room temperature safely for at least 1 year. **Stringency wash buffer (50 ml)** Combine 49.5 ml of water, 250 µl of 20% (wt/vol) SDS and 250 µl of 20× SSC buffer. This buffer can be stored at room temperature (22 °C) safely for at least 1 month. 

**Stop solution (100** m **l)** Combine 98 µl of 0.5 M EDTA (pH 8.0) and 2 µl of Tween 20. This buffer can be stored at room temperature safely for at least 1 year. **TE buffer (50 ml)** Combine 49.4 ml of water, 500 µl of 1 M Tris-HCl (pH 8.0) and 100 µl of 0.5 M EDTA (pH 8.0). This buffer can be stored at room temperature safely for at least 1 year. 

**740** | VOL.8 NO.4 | 2013 | **nature protocols** 

**protocol** 

**table 1**<sup>**|**</sup> Sequences of oligonucleotides required for single-stranded DNA library preparation and amplification. 

<table><tr><th>Name</th><th>Description</th><th>Sequence (5′–3′)</th><th>Concentration of<br/>stock/working dilution<br/>[M]</th></tr><tr><td>Library</td><td>preparation oligonucleotides (dissolve and dilute</td><td>in TE buffer)</td><td></td></tr><tr><td>CL9</td><td>Extension primer</td><td>GTGACTGGAGTTCAGACGTGTGCTCTTCCGATCT</td><td>100/ —</td></tr><tr><td>CL53</td><td>Double-stranded adapter, strand 1</td><td>CGACGCTCTTC-ddC (ddC = dideoxycytidine)</td><td>500/ —</td></tr><tr><td>CL73</td><td>Double-stranded adapter, strand 2</td><td>[Phosphate]GGAAGAGCGTCGTGTAGGGAAAGAG*T*G*T*A<br/>(* = phosphothioate linkage)</td><td>500/ —</td></tr><tr><td>CL78</td><td>Single-stranded adapter</td><td>[Phosphate]AGATCGGAAG[C3Spacer]10[TEG-biotin]</td><td>100/10</td></tr><tr><td>Positive</td><td>control template (dissolve and dilute in TET</td><td>(TEG = triethylene glycol spacer)<br/>buffer)</td><td></td></tr><tr><td>CL104</td><td>Synthetic template DNA</td><td>[Phosphate]TCGTCGTTTGGTATGGCTTCATTCAGCTCCGG</td><td>100/0.1</td></tr><tr><td></td><td></td><td>TTCCCAACGATCAAGGCGAGTTACATGA[Phosphate]</td><td></td></tr><tr><td>Library</td><td>amplification primers (dissolve and dilute in</td><td>water)</td><td></td></tr><tr><td>IS4</td><td>P5 primer without index</td><td>AATGATACGGCGACCACCGAGATCTACACTCTTTCCCTACAC<br/>GACGCTCTT</td><td>100/10</td></tr><tr><td></td><td>P5- and P7-indexing primers</td><td>See Supplementary Table 2</td><td>100/10</td></tr><tr><td>Oligonucleotides</td><td>used for preparing the qPCR standard</td><td>(dissolve and dilute in water)</td><td></td></tr><tr><td>CL105</td><td>Forward primer</td><td>ACACTCTTTCCCTACACGACGCTCTTCCTCGTCGTTTGGTAT<br/>GGCTTC</td><td>100/10</td></tr><tr><td>CL106</td><td>Reverse primer</td><td>GTGACTGGAGTTCAGACGTGTGCTCTTCCGATCTTCATGTAA</td><td>100/10</td></tr><tr><td>Oligonucleotides</td><td>used in qPCR (dissolve and dilute in</td><td>CTCGCCTTGATCGT<br/>water)</td><td></td></tr><tr><td>CL107</td><td>qPCR primer</td><td>TCATGTAACTCGCCTTGATCGT</td><td>100/10</td></tr><tr><td>CL108</td><td>qPCR primer</td><td>TCGTCGTTTGGTATGGCTTC</td><td>100/10</td></tr><tr><td>IS7</td><td>qPCR primer</td><td>ACACTCTTTCCCTACACGAC</td><td>100/10</td></tr><tr><td>IS8</td><td>qPCR primer</td><td>GTGACTGGAGTTCAGACGTGT</td><td>100/10</td></tr><tr><td>Sequencing</td><td>primer (dissolve and dilute in water)</td><td></td><td></td></tr><tr><td>CL72</td><td>Sequencing primer</td><td>ACACTCTTTCCCTACACGACGCTCTTCC</td><td>100/ —</td></tr></table>

All oligonucleotides should be synthesized on a 0.2-µmole scale and purified by reverse-phase HPLC (e.g., by Sigma-Aldrich), with the exception of CL78, which requires dual purification by ion-exchange HPLC. 

**TET buffer (50 ml)** Combine 49.375 ml of water, 500 µl of 1 M Tris-HCl, 100 µl of 0.5 M EDTA and 25 µl of Tween 20. This buffer can be stored at room temperature safely for at least 1 year. 

**Double-stranded adapter** Set up the following hybridization reaction mixture in a PCR tube. Combine 9.5 µl of TE buffer, 0.5 µl of 5 M NaCl, 20 µl of 500 µM oligonucleotide CL53 and 20 µl of 500 µM oligonucleotide CL73. Incubate the reaction mixture in a thermal cycler for 10 s at 95 °C and slowly decrease the temperature at the rate of 0.1 °C per second until reaching 14 °C. Add 50 µl of TE buffer to the hybridized adapter to obtain a concentration of 100 µM in a total volume of 100 µl. The resulting solution can be stored at  − 20 °C for at least 1 year. 

**Standard dilution series for qPCR** Use pUC19 DNA and the primer pair CL105/ CL106 in a conventional PCR assay to generate a 122-bp PCR product. Purify the product using the MinElute PCR purification kit or AmPure XP SPRI beads and determine its concentration using the Bioanalyzer 2100. Prepare a tenfold dilution series of the PCR product in TET buffer, ranging from 10<sup>9</sup> to 10<sup>2</sup> copies of the PCR product per microliter. The dilution can be stored at  − 20 °C for at least 1 year. **Decontamination of reagents** For experiments that are highly sensitive to contamination with DNA from humans or domesticated animals, we recommend UV decontamination of all chemicals that are used throughout Steps 1 to 6 (excluding enzymes and adapter; for further instructions regarding UV decontamination, see Champlot _et al._<sup>30</sup> ). 

**nature protocols** | VOL.8 NO.4 | 2013 | **741** 

## **protocol** 

##### **EQUIPMENT SETUP** 

**Performing reaction and wash steps involving magnetic beads** Settling of the magnetic beads should be avoided during all reaction steps (i.e., Steps 14, 18 and 22) by briefly vortexing the bead suspensions every 5 min and immediately placing the tubes back in the device that is used for maintaining reaction temperature. This device can either be a thermal cycler with a block for 0.5-ml tubes (which for this purpose sufficiently controls temperature also in loosely fitted 1.5 ml tubes), or a thermal shaker. We have found the cooling ThermoMixer MKR13 to be ideally suited for this protocol, because it enables 

flexible programming and offers interval shaking, which eliminates the need for manual vortexing and reduces hands-on time. Recommended settings for this device are listed in **Supplementary Table 1** . When you are vortexing bead suspensions, care should be taken to avoid spilling of the liquid. Before returning the bead suspensions to the magnet rack, all of the liquid should be collected at the bottom of the tubes by performing a quick spin in a microcentrifuge. Beads must not be allowed to dry after removal of the supernatant. Proper resuspension of beads is best performed by vortexing for several seconds, and the homogeneity of the suspension should be visually verified. 

#### **proceDure** 

#### **uracil excision and Dna cleavage at abasic sites** ● **tIMInG 1.5 h** 

**1|** For each sample (no more than twelve are recommended, including controls), prepare the following reaction mixture with a total volume of 42 µl in 0.5-ml tubes. Mix by flicking the tubes with a finger and spin the tubes briefly in a microcentrifuge. 

 **crItIcal step** Always include a blank control using water instead of DNA extract and a positive control using 1 µl of a 0.1 µM solution of oligonucleotide CL104 in TET. UDG treatment is optional, but endonuclease VIII should be included because it cleaves DNA at abasic sites if present. Low concentrations of Tris-HCl, EDTA and Tween 20 in DNA extracts <u>(e.g., TET buffer) will not interfere with the reaction.</u> 

<table><tr><th>Reagent</th><th>Volume (l) per sample</th><th>Final concentration in reaction (in this step/in Step 5)</th></tr><tr><th>Water (to 42 µl)</th><th>×</th><th></th></tr><tr><td>CircLigase buffer II (10×)</td><td>8</td><td>1.9×/1×</td></tr><tr><td>MnCl2 (50 mM)</td><td>4</td><td>4.8 mM/2.5 mM</td></tr><tr><td>DNA extract (max. 29 µl)</td><td>×</td><td></td></tr><tr><td>Endonuclease VIII (10 U µl − 1)</td><td>0.5</td><td>0.12 U µl − 1/inactive</td></tr><tr><td>Optional: Afu UDG (2 U µl − 1)</td><td>0.5</td><td>0.02 U µl − 1/inactive</td></tr></table>

**2|** Incubate the reactions in a thermal cycler with a heated lid for 1 h at 37 °C. 

#### **Dephosphorylation and heat denaturation** ● **tIMInG 20 min** 

**3|** Add 1 µl of FastAP (1 U) to each reaction mixture prepared in Step 1 and mix by flicking the tubes with your finger. Spin the tubes briefly in a microcentrifuge. The total reaction volume is now 43 µl. 

**4|** Incubate the reactions in a thermal cycler with a heated lid for 10 min at 37 °C, and then at 95 °C for 2 min. While the thermal cycler is still at 95 °C, quickly transfer the tubes into an ice-water bath. Let the reaction mix cool down for at least 1 min. Spin the tubes briefly in a microcentrifuge and place them in a tube rack at room temperature. 

#### **ligation of the first adapter** ● **tIMInG 2 h** 

**5|** Add the following components to the reaction mixtures to obtain a final reaction volume of 80 µl. Mix the contents of the tubes by vortexing before adding CircLigase II; mix vigorously by flicking the tube with a finger thereafter. Spin the tubes briefly in a microcentrifuge. 

<table><tr><th>Reagent</th><th>Volume (l) per sample</th><th>Final concentration in reaction</th></tr><tr><td>PEG-4000 (50%)</td><td>32</td><td>20%</td></tr><tr><td>Adapter oligo CL78 (10 µM)</td><td>1</td><td>0.125 µM</td></tr><tr><td>CircLigase II (100 U µl − 1)</td><td>4</td><td>5 U µl − 1</td></tr></table>

 **crItIcal step** PEG solution is highly viscous. Pipette it slowly and ensure that all components are properly mixed. 

**6|** Incubate the reaction mixtures in a thermal cycler with a heated lid for 1 h at 60 °C. 

**742** | VOL.8 NO.4 | 2013 | **nature protocols** 

**protocol** 

**7|** Add 2 µl of stop solution to each reaction mixture. Mix the contents by vortexing and spin the tubes in a microcentrifuge.  **pause poInt** Ligation products can be stored safely at  − 20 °C for several days. 

#### **Immobilization of ligation products on beads** ● **tIMInG 1 h** 

**8|** Resuspend the stock of MyOne C1 beads by vortexing. For each sample, transfer 20 µl of the bead suspension into a 1.5-ml tube (e.g., 80 µl for four reactions). Pellet the beads using a magnetic rack, discard the supernatant and wash the beads twice with 500 µl of bead-binding buffer. Resuspend the beads in a volume of bead-binding buffer corresponding to the number of samples times 250 µl (e.g., 1 ml for four samples). Per sample, transfer an aliquot of 250 µl of bead suspension to a 1.5-ml tube. 

**9|** Incubate the ligation reactions from Step 7 for 1 min at 95 °C in a thermal cycler with a heated lid. While the thermal cycler is still at 95 °C, quickly transfer the tubes into an ice-water bath. Let the reaction mixture cool down for at least 1 min. Spin the tubes briefly in a microcentrifuge and add the ligation reactions to the bead suspensions prepared in Step 8. 

**10|** Rotate the tubes for 20 min at room temperature. 

**11|** Spin the tubes briefly in a microcentrifuge. Pellet the beads using a magnetic rack and discard the supernatant. Wash the beads once with 200 µl of wash buffer A and once with 200 µl of wash buffer B (see Equipment Setup for instructions on how to perform bead washes). 

#### **primer annealing and extension** ● **tIMInG 1 h** 

**12|** Prepare a master mix for the required number of reactions (47 µl per reaction). 

<table><tr><th>Reagent</th><th>Volume (l) per sample</th><th>Final concentration in reaction</th></tr><tr><td>Water</td><td>40.5</td><td></td></tr><tr><td>Isothermal amplification buffer (10×)</td><td>5</td><td>1×</td></tr><tr><td>dNTP mix (25 mM each)</td><td>0.5</td><td>250 µM each</td></tr><tr><td>Extension primer CL9 (100 µM)</td><td>1</td><td>2 µM</td></tr></table>

**13|** Pellet the beads using a magnetic rack and discard the wash buffer. Add the 47-µl reaction mixture to the pelleted beads and resuspend the beads by vortexing. Incubate the tubes in a thermal shaker for 2 min at 65 °C. Place the tubes in an ice-water bath for 1 min, and then immediately transfer the tubes to a thermal cycler precooled to 15 °C (leave the lid open). While the tubes are placed on the thermal cycler, add 3 µl of Bst 2.0 polymerase (24 U) to each reaction mixture. Mix the tubes briefly by vortexing and return them to the thermal cycler. 

**14|** Incubate the reaction mixtures by increasing the temperature by 1 °C per minute, ramping it up from 15 °C to 37 °C. Implement a final incubation step of 5 min at 37 °C (see Equipment Setup for instructions on how to keep the beads suspended during incubation). 

**15|** Spin the tubes briefly in a microcentrifuge. Pellet the beads using a magnetic rack and discard the supernatant. Wash the beads once with 200 µl of wash buffer A. Resuspend the beads in 100 µl of stringency wash buffer and incubate the bead suspensions for 3 min at 45 °C in a thermal shaker. Pellet the beads using a magnetic rack and discard the supernatant. Wash the beads once with 200 µl of wash buffer B. 

#### **blunt-end repair** ● **tIMInG 1 h** 

**16|** Prepare a master mix for the required number of reactions (99 µl per reaction). 

<table><tr><th>Reagent Volume</th><th>(l) per sample</th><th>Final concentration in reaction</th></tr><tr><td>Water</td><td>86.1</td><td></td></tr><tr><td>Buffer Tango (10×)</td><td>10</td><td>1×</td></tr><tr><td>Tween 20 (1%)</td><td>2.5</td><td>0.025%</td></tr><tr><td>dNTP (25 mM each)</td><td>0.4</td><td>100 µM each</td></tr></table>

**nature protocols** | VOL.8 NO.4 | 2013 | **743** 

## **protocol** 

**17|** Pellet the beads using a magnetic rack and discard the wash buffer. Add 99 µl of the reaction mixture from Step 16 to the pelleted beads and resuspend the beads by vortexing. Add 1 µl of T4 DNA polymerase (5 U). Mix the tubes briefly by vortexing. **? troublesHootInG** 

**18|** Incubate the reaction mixtures for 15 min at 25 °C in a thermal shaker. Keep the beads suspended during incubation (see Equipment Setup for instructions on how to keep the beads suspended during incubation). 

**19|** Add 10 µl of EDTA (0.5 M) to each reaction mixture and mix by vortexing. Pellet the beads using a magnetic rack and discard the supernatant. Wash the beads with wash buffer A, stringency wash buffer (with incubation at 45 °C) and wash buffer B, exactly as described in Step 15. 

**ligation of second adapter and library elution** ● **tIMInG 2 h** 

**20|** Prepare a master mix for the required number of reactions (98 µl per reaction). 

<table><tr><th>Reagent</th><th>Volume (l) per sample</th><th>Final concentration in reaction</th></tr><tr><td>Water</td><td>73.5</td><td></td></tr><tr><td>T4 DNA ligase buffer (10×)</td><td>10</td><td>1×</td></tr><tr><td>PEG-4000 (50%)</td><td>10</td><td>5%</td></tr><tr><td>Tween 20 (1%)</td><td>2.5</td><td>0.025%</td></tr><tr><td>Double-stranded adapter (100 µM)</td><td>2</td><td>2.5 µM</td></tr></table>

**21|** Pellet the beads using a magnetic rack and discard the wash buffer. Add 98 µl of the reaction mixture from Step 20 to the pelleted beads and resuspend the beads by vortexing. Add 2 µl of T4 DNA ligase (10 U). Mix the contents briefly by vortexing. 

**22|** Incubate the reaction mixtures for 1 h at room temperature. Keep the beads suspended during incubation (see Equipment Setup for instructions on how to keep beads suspended during incubation). 

**23|** Pellet the beads using a magnetic rack and discard the supernatant. Wash the beads with wash buffer A, stringency wash buffer (with incubation at 45 °C) and wash buffer B exactly as described in Step 15. 

**24|** Pellet the beads using a magnetic rack and discard the supernatant. Add 25 µl of TET buffer to the pelleted beads, resuspend the beads by vortexing and transfer the bead suspension to 0.2-ml PCR strip tubes. Spin the tubes briefly in a microcentrifuge. 

**25|** Incubate the bead suspensions for 1 min at 95 °C in a thermal cycler with a heated lid. Immediately transfer the PCR strip tubes to a 96-well magnetic rack. Transfer the supernatant, which contains the library molecules, to a fresh 0.5-ml tube. 

#### **Determining library preparation efficiency and library quantities** ● **tIMInG 3.5 h** 

**26|** In separate tubes, dilute 1 µl of each DNA library in 19 µl of TET buffer. In addition, prepare a 1:500 dilution from 0.1 µM CL104 in TET buffer. 

**27|** Prepare two qPCR master mixtures for two assays (A and B) as shown below. Assay A should include replicate measurements of the qPCR standard dilutions (10<sup>9</sup> to 10<sup>2</sup> ), all library dilutions and a water control. Assay B should include replicate measurements of the qPCR standard dilutions, the CL104 dilution and a water control. For each measurement, pipette 24 µl of master mix to a well of a 96-well PCR plate and add 1 µl of sample. Close the wells with optical strip caps and mix them briefly by vortexing. 

<table><tr><th>Reagent</th><th>Volume (l) per sample</th><th>Final concentration in reaction</th></tr><tr><td>Water (to 25 µl)</td><td>10.5</td><td></td></tr><tr><td>Maxima SYBR Green qPCR master mix (2×)</td><td>12.5</td><td>1×</td></tr><tr><td>Either IS7 (for assay A) or CL107 (for assay B) (both 10 µM)</td><td>0.5</td><td>0.2 µM</td></tr><tr><td>Either IS8 (for assay A) or CL108 (for assay B) (both 10 µM)</td><td>0.5</td><td>0.2 µM</td></tr><tr><td>Sample</td><td>1</td><td></td></tr></table>

**744** | VOL.8 NO.4 | 2013 | **nature protocols** 

**protocol** 

**28|** Spin the PCR plate in a centrifuge for 1 min at 2,000 _g_ at room temperature. Place the plate into a qPCR cycler and begin cycling using a profile consisting of an initial activation step at 95 °C for 10 min, followed by 40 cycles at 95 °C for 30 s, 60 °C for 30 s and 72 °C for 30 s. Carry out fluorescence measurements at the end of each extension step.  **crItIcal step** Keep DNA library dilutions for further experiments, for instance if a repetition of qPCR becomes necessary.  **pause poInt** Library stock solutions and dilutions can be safely stored at  − 20 °C for several months. 

**29|** Use the software provided with the qPCR system to calculate the number of molecules in each library and to determine the efficiency of library preparation ( **box 1** ). 

**? troublesHootInG** 

#### **library amplification and indexing** ● **tIMInG 4.5 h** 

**30|** Prepare the following PCR mix, using a unique combination of indexing primers for each sample (see **supplementary table 2** for a list of indexing primers). P5 indexing primers are required for double indexing, but may be replaced by primer IS4 if double-indexed sequencing is not desired (it should be noted, however, that double-indexed libraries remain fully compatible with single-indexed sequencing). 

<table><tr><th>Reagent</th><th>Volume (l) per sample</th><th>Final concentration in reaction</th></tr><tr><td>Water (to 100 µl)</td><td>57</td><td></td></tr><tr><td>AccuPrime Pfx reaction mix (10×)</td><td>10</td><td>1×</td></tr><tr><td>P7 indexing primer (10 µM)</td><td>4</td><td>400 nM</td></tr><tr><td>P5 indexing primer or IS4 (10 µM)</td><td>4</td><td>400 nM</td></tr><tr><td>Library</td><td>24</td><td></td></tr><tr><td>AccuPrime Pfx polymerase (2.5 U µl − 1)</td><td>1</td><td>0.025 U µl − 1</td></tr></table>

**31|** Incubate the reactions in a thermal cycler with the following thermal profile. Initial denaturation should be carried out at 95 °C for 2 min. Follow this by a selected number of PCR cycles, involving denaturation for 15 s at 95 °C, annealing for 30 s at 60 °C and primer extension for 1 min at 68 °C. 

 **crItIcal step** The optimal number of PCR cycles for each sample should be determined from the amplification plots obtained in Step 29 (see **supplementary Fig. 4** for an example of how this is done). If libraries are amplified beyond the point at which PCR starts saturating, heteroduplexes will form because of the cross-hybridization of different library molecules via their adapter sequences, thereby preventing the determination of fragment size distribution and DNA concentration by gel electrophoresis (using the Bioanalyzer 2100 or any other electrophoresis-based system). However, amplifying the libraries into saturation may be desirable if highly concentrated libraries are needed for hybridization capture. 

**32|** Purify amplified libraries using the MinElute PCR purification kit or AMPure XP SPRI beads according to the manufacturer’s instructions. Elute the DNA in 20 µl of TE buffer. 

**33|** Determine the fragment size distributions and concentrations of the DNA libraries by running the Agilent Bioanalyzer 2100 with a DNA 1000 chip. 

**? troublesHootInG** 

#### **sequencing** ● **tIMInG 1–14 d** 

**34|** For sequencing, follow the protocols and instructions for multiplex sequencing provided by Illumina. Make sure to replace the sequencing primer of the first read by the custom primer CL72. Freshly prepare a ready-to-use dilution of CL72 before sequencing by mixing 10 µl from the 100 µM stock solution with 1,990 µl of hybridization buffer (provided with the sequencing reagents). 

**nature protocols** | VOL.8 NO.4 | 2013 | **745** 

**protocol** 

#### **? troublesHootInG** 

Troubleshooting advice can be found in **table 2** . 

**table 2**<sup>**|**</sup> Troubleshooting table. 

<table><tr><th>Step</th><th>Problem</th><th>Possible reason</th><th>Solution</th></tr><tr><td>17</td><td>Beads appear clumpy</td><td>Not known</td><td>This phenomenon is occasionally observed, but it does<br/>not affect library yield</td></tr><tr><td>29</td><td>The relationship between input vol-<br/>ume of DNA extract and output of<br/>library molecules is not linear</td><td>Too much DNA is used for<br/>library preparation, which<br/>only occurs if library mol-<br/>ecule counts exceed 1011<br/>molecules</td><td>Reduce input volume of DNA extract</td></tr><tr><td></td><td></td><td>DNA extract contains too<br/>much salt</td><td>Test whether library preparation is inhibited by salts<br/>present in the DNA extracts. This can be done by prepar-<br/>ing libraries from oligonucleotide CL104 with and without<br/>a spike-in of blank extract</td></tr><tr><td></td><td></td><td>Substances that inhibit<br/>library preparation were<br/>co-extracted from the sample</td><td>Reduce input of DNA extract until input and output show<br/>a linear relationship</td></tr><tr><td></td><td>Molecule count from the library<br/>preparation blank control is very<br/>high ( &gt;1 × 109)</td><td>Too many adapter dimers<br/>have formed, the single-<br/>stranded adapter oligonu-<br/>cleotide contains impurities,<br/>or contaminants are present<br/>in the chemicals used in the<br/>procedure</td><td>Inspect fragment size distribution of the library blank<br/>obtained from chip electrophoresis<br/>Sharp peaks at exactly 129 bp (double-indexed library) or<br/>122 bp (single-indexed library) indicate excessive forma-<br/>tion of adapter dimers. Wash beads more thoroughly in<br/>the next experiment<br/>A sharp peak at greater size indicates the presence of<br/>impurities or synthesis artifacts in the single-stranded<br/>adapter. In this case, repeat library preparation with a<br/>newly synthesized adapter oligonucleotide<br/>If the fragment size distribution appears as a wide smear,<br/>then massive contamination occurred during handling<br/>(e.g., cross-contamination or contamination with human<br/>DNA), or contaminants are present in the chemicals.<br/>Successively replace all chemicals and run a series of<br/>blank library preparations until the source of contamina-<br/>tion is identified or eliminated</td></tr><tr><td></td><td>Molecule count from the sample<br/>library is similar to that of the library<br/>preparation blank control</td><td>The DNA sample contains<br/>very little DNA</td><td>If possible, use a larger volume of sample for library<br/>preparation. Libraries dominated by artifacts can be<br/>directly used for target enrichment experiments, but they<br/>should be fractionated on a gel if whole-genome shotgun<br/>sequencing is desired (e.g., as described in Meyer et al.14)</td></tr><tr><td></td><td>Efficiency of the control library<br/>preparation is too low (&lt;30%)</td><td>Inefficiency in one of the<br/>reaction steps</td><td>Make sure the reagents are properly mixed in all reactions<br/>and the beads are properly suspended. Replace all rea-<br/>gents or test their performance in independent assays</td></tr><tr><td>33</td><td>Fragment size distribution shows<br/>unexpectedly long library molecules</td><td>Heteroduplexes have formed</td><td>Re-amplify libraries with primers IS5/IS6 (ref. 21), this<br/>time without reaching the saturation phase of PCR</td></tr></table>

#### ● **tIMInG** 

(For 12 samples) Steps 1 and 2, uracil removal: 1.5 h Steps 3 and 4, dephosphorylation and heat denaturation: 20 min 

**746** | VOL.8 NO.4 | 2013 | **nature protocols** 

**protocol** 

Steps 5–7, ligation of the first adapter: 2 h Steps 8–11, immobilization of ligation products on beads: 1 h Steps 12–15, primer annealing and extension with polymerase: 1 h Steps 16–19, blunt-end repair: 1 h Steps 20–25, ligation of second adapter and library elution: 2 h Steps 26–29, determining library preparation efficiency and library quantities: 3.5 h Steps 30–33, library amplification and indexing: 4.5 h Step 34, sequencing: 1–14 d 

#### **antIcIpateD results** 

A typical outcome of single-stranded library preparation, together with a set of analyses recommended for quality control, is provided in the following example from an unpublished study (M.-T.G. and M.M., unpublished data). We extracted DNA from 30 mg of bone from a Neanderthal hominin. We prepared libraries both with and without UDG treatment using 5 µl of DNA extract (from a total volume of 50 µl). These libraries were amplified (double-indexed) and sequenced together with other samples on a MiSeq run. We performed overlap merging of paired-end reads to reconstruct full-length molecule sequences<sup>31</sup> , which we then aligned against the human reference genome using Burrows-Wheeler Aligner<sup>32</sup> . According to qPCR, the sample libraries yielded 1.5 × 10<sup>10</sup> and 1.4 × 10<sup>10</sup> molecules for the UDG-treated and UDG-untreated samples, respectively. More than 20 times fewer molecules (6.2 × 10<sup>8</sup> ) were produced in the blank control reaction (amplification plots are shown in **supplementary Fig. 4** ). Consequently, the fragment size distributions obtained from chip electrophoresis show small peaks of artifacts ( **supplementary Fig. 2** ). If whole-genome shotgun sequencing is desired, these artifacts—as well as other short library molecules—could be removed by gel-size fractionation after library amplification<sup>14</sup> . Sequences from the library prepared without UDG treatment show an excess of C-to-T substitutions close to the ends of molecules. This signal is almost entirely absent in the UDG-treated library, confirming the success of uracil removal ( **supplementary Fig. 2** ). The GC content of aligned sequences is close to 40%, indicating that there is no substantial bias in base composition. In summary, all parameters confirm the success of library preparation, and the libraries are ready to be used for downstream experiments. Because in this example the fraction of endogenous DNA (i.e., the fraction of mapped reads) is very low ( **supplementary Fig. 2** ), these libraries are not ideal candidates for whole-genome shotgun sequencing, but may rather be used to target specific parts of the Neanderthal genome by hybridization enrichment. Artifacts and very short molecules that do not carry information will be removed during this process. 

_Note: Supplementary information is available in the online version of the paper._ 

**acknoWleDGMents** We thank I. Glocke for help in the lab; B. Höber, M. Kircher, S. Pääbo and U. Stenzel for helpful discussions; J. Dabney and S. Sawyer for comments on the manuscript; and S. Tüpke for help with the figures. This work was funded by the Max Planck Society. 

**autHor contrIbutIons** M.-T.G. and M.M. developed the protocol and wrote the paper. 

##### **coMpetInG FInancIal Interests** 

The authors declare no competing financial interests. 

Reprints and permissions information is available online at http://www.nature. com/reprints/index.html. 

In the version of this article initially published, the sequence of oligonucleotide CL78 reported in Table 1 as “(AGATCGGAAG[C3Spacer]10[TEG-biotin] (TEG = triethylene glycol spacer))” is incorrect. The correct sequence is “[Phosphate]AGATCGGAAG[C3Spacer]10[TEG-biotin] (TEG = triethylene glycol spacer)”. The error has been corrected in the HTML and PDF versions of the article. 

**nature protocols**