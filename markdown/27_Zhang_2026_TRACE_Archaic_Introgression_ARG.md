CORRECTED 11 SEPTEMBER 2026; SEE LAST PAGE 

**RESEARCH ARTICLE SUMMARY** 

![](markdown/images/27_Zhang_2026_TRACE_Archaic_Introgression_ARG/27_Zhang_et_al_2026_TRACE_Archaic_Introgression_ARG.pdf-0001-03.png)

#### **INTROGRESSION** 

# **Recovering signatures of archaic hominin introgression using ancestral recombination graphs** 

![](markdown/images/27_Zhang_2026_TRACE_Archaic_Introgression_ARG/27_Zhang_et_al_2026_TRACE_Archaic_Introgression_ARG.pdf-0001-06.png)

Full article and list of author affiliations: https://doi.org/10.1126/ science.aef8874 

Yulin Zhang*, Arjun Biddanda*, Sarah A. Johnson, Colm O’Dushlaine, Priya Moorjani* 

**INTRODUCTION:** The sequencing of Neanderthal and Denisovan genomes has revealed extensive interbreeding between modern humans and now- extinct archaic hominins, transforming our understanding of human evolutionary history. However, many archaic populations that contributed to modern human ancestry— particularly those lacking preserved fossils or DNA—remain uncharacterized. Existing computational methods cannot detect these contributions as they rely on either an archaic reference genome or an unadmixed outgroup. As a result, the full extent and complexity of archaic introgression remain unknown. 

**RATIONALE:** Ancestral recombination graphs (ARGs) encode the full genealogical history of a set of samples across the genome, providing a record of the ancestral population relationships over time. Gene flow from a deeply divergent archaic source is expected to leave two distinctive signatures in the ARG: (i) unusually deep coalescent branches, reflecting the long evolutionary separation between the introgressing lineage and the recipient population, and (ii) long stretches of the genome over which introgressed lineages persist as contiguous haplotypes, reflecting the limited number of recombination events since the gene flow event. We developed TRACE (Tracking Archaic Contributions via ARG Estimation), a reference- and outgroup- free method that identifies introgressed archaic segments in contemporary genomes by scanning inferred ARGs for these signatures. 

**RESULTS:** We validate TRACE by performing extensive simulations and show that it has high precision and low false discovery rate across a range of demographic scenarios and parameters. Applied to data from the 1000 Genomes Project, TRACE recovers the known signatures of Neanderthal introgression in all non- Africans and Denisovan introgression in Asians and Oceanians, with populationlevel patterns consistent with prior estimates. 

Beyond these established signals, TRACE identifies extensive segments of ghost archaic ancestry—from a previously uncharacterized hominin lineage—in both African and non- African populations. We find ghost ancestry persists within Neanderthal and Denisovan ancestry deserts, genomic regions previously interpreted as depleted of archaic introgression and thought to be specific to _Homo sapiens_ . This challenges the prevailing interpretation of these regions and suggests that selection acting against introgressed ancestry has not been uniform across all archaic sources. In Oceanian populations, TRACE detects a substantial enrichment of unusually deep coalescent lineages within Denisovan ancestry segments compared with Neanderthal segments, consistent with a model of super- archaic gene flow into modern humans through Denisovans. Together, these results point to multiple layers of introgression—both direct and mediated through other archaic groups—that have shaped modern human genomes. 

![](markdown/images/27_Zhang_2026_TRACE_Archaic_Introgression_ARG/27_Zhang_et_al_2026_TRACE_Archaic_Introgression_ARG.pdf-0001-13.png)

<!-- Start of picture text -->
Modern humans Infer ARG Archaic ancestry catalog<br>TRACE<br>No archaic reference<br>No unadmixed outgroup<br>Neanderthal Denisovan Ghost Super-archaic<br>Recover  known archaic Ghost ancestry within Super-archaic gene flow<br>ancestry signals archaic ancestry deserts into Denisovan lineage<br>Previous methods<br>Archaic ancestry desert<br>TRACE<br>Neanderthal Denisovan<br>Matches reference-based Deserts are not Enriched  only within<br>estimates without needing them H. sapiens-specific Denisovan segments (Oceania)<br>Oceania<br>Super-archaic<br>America<br>Denisovan<br>East Asia<br>Neanderthal<br>Europe<br>Africa<br>Ghost<br>1700 830 450 50 Present<br>Time (Kya)<br>Deep lineages<br><!-- End of picture text -->

**TRACE infers archaic ancestry without reference genomes.** (Top) TRACE uses inferred ARGs to characterize archaic ancestry across the genome (Neanderthal, blue; Denisovan, orange; ghost, red; super- archaic, green). (Middle) TRACE recovers known introgression signals, detects ghost ancestry within archaic deserts, and identifies super- archaic gene flow enriched in Oceanian Denisovan segments. (Bottom) Schematic phylogeny of introgression events across the course of human evolution. 

**CONCLUSION:** TRACE is a genealogy- based method for mapping archaic ancestry without the need for archaic reference genomes, revealing hidden layers to our evolutionary past. Using ARGs inferred from modern genomes alone, the method recovers signatures of introgression from archaic hominins for whom no DNA is available, including ghost and super- archaic lineages. With continued progress in ARG reconstruction, TRACE will increasingly advance our understanding of the legacy of extinct populations to present- day human genetic diversity.  

> *Corresponding author. Email: zhangyulin9806@ berkeley. edu (Y.Z.); abiddan1@ jhu. edu (A.B.); moorjani@ berkeley. edu (P.M.) Cite this article as Y. Zhang _et al_ ., _Science_ **393** , eaef8874 (2026). DOI: 10.1126/science.aef8874 

Science 27 August 2026 

**879** 

**ReseaRch aRticle** 

**iNtROGRessiON** 

# **Recovering signatures of archaic hominin introgression using ancestral recombination graphs** 

Yulin Zhang<sup>1</sup> *†, Arjun Biddanda<sup>2,3</sup> *†, Sarah A. Johnson<sup>1</sup> , Colm O’Dushlaine<sup>3</sup> ‡, Priya Moorjani<sup>1,4</sup> * 

Admixture between modern humans and extinct hominins has shaped the genomes of present- day individuals, but reconstructing this history has been constrained by the scarcity of archaic samples and unadmixed outgroup populations. We introduce tRACE, a reference- and outgroup- free approach that uses features of ancestral recombination graphs to identify archaic ancestry. simulations demonstrate that tRACE achieves high precision and low false discovery rates. Applied to 1000 genomes, tRACE recovers known Neanderthal and Denisovan introgression and uncovers ghost admixture from uncharacterized hominins in both Africans and non- Africans. ghost ancestry persists in Neanderthal and Denisovan ancestry deserts, challenging their interpretation as _Homo sapiens_ –specific regions. In Oceanians, tRACE finds that deep lineages are enriched in Denisovan compared with Neanderthal regions, supporting super- archaic introgression. tRACE enables mapping of archaic introgression without archaic reference genomes. 

gene flow and thus may be present in Asians and Oceanians. These histories, however, remain poorly understood as most available methods for studying archaic introgression rely on either sequenced archaic genomes ( _33_ ), an outgroup population without archaic ancestry ( _18_ , _34_ – _36_ ), or both ( _6_ , _37_ ). As the oldest ancient genome from Africa is less than 20,000 years old ( _26_ ) and recovering hominin DNA older than a million years outside of permafrost is improbable ( _38_ ), methods without such requirements are needed. 

With the availability of new methods to reconstruct ancestral recombination graphs (ARGs) ( _39_ – _42_ ), it is now possible to infer the full evolutionary history of a set of sequences in a computationally tractable manner. An ARG provides a complete record of all the coalescence and recombination events and specifies a complete genealogy at each position in the genome ( _43_ – _46_ ). Importantly, gene flow from deeply divergent lineages is expected to leave distinct signatures in the ARG—such as unusually deep coalescent events—that can be used to detect introgression, even in the absence of archaic reference genomes ( _42_ ). 

We introduce TRACE (Tracking Archaic Contributions Via ARG Estimation), a method for identifying footprints of archaic ancestry in modern human genomes by leveraging features of ARGs constructed from contemporary genomes alone, requiring neither an archaic reference genome nor an unadmixed outgroup population. We perform extensive simulations to characterize the reliability of TRACE under a range of demographic scenarios, using true and inferred ARGs. We then apply TRACE to whole- genome sequences of individuals from worldwide populations to reconstruct the evolutionary history and legacy of archaic gene flow in modern humans. 

### **Results** 

#### **TRACE identifies archaic gene flow using ARGs** 

The sequencing of the Neanderthal and Denisovan genomes has transformed our understanding of human evolution, revealing evidence for gene flow between modern humans and archaic hominins ( _1_ – _5_ ). Most non- Africans living today possess 1 to 2% Neanderthal ancestry, whereas Asians and Oceanians harbor ∼0.1 to 5% Denisovan ancestry ( _6_ , _7_ ). Archaic ancestry has had a major impact on human adaptation and disease, contributing to a range of traits such as skin pigmentation, high altitude adaptation, and immune function ( _8_ – _14_ ). To date, however, only six high- coverage archaic genomes have been published—four Neanderthal and two Denisovan—all from Eurasia. Thus, our knowledge of the evolutionary history and impact of archaic ancestry outside Eurasia and at deeper timescales remains incomplete ( _1_ – _3_ , _5_ , _15_ , _16_ ). 

Several studies have posited that gene flow from other unknown archaic hominins—for whom no genomic sequences currently exist— may have occurred both within and outside Africa ( _17_ – _31_ ). Genetic analyses of present- day African populations have identified highly divergent haplotypes that cannot be explained by known demographic histories, hinting at “ghost” introgression ( _17_ – _29_ , _31_ ). At deeper timescales, analysis of the Altai Denisovan genome suggests that they harbor ancestry from a deeply divergent population, referred to as “super- archaic”, that split from modern humans around 0.9 to 1.4 million years ago (Mya) ( _2_ , _3_ , _32_ ). Ghost lineages refer broadly to any unsampled archaic population contributing to modern genomes, whereas super- archaic ancestry specifically denotes contributions from lineages that diverged before the common ancestor of modern humans and Neanderthals/Denisovans. Super- archaic ancestry likely introgressed into modern humans through Denisovan 

> 1Center for Computational Biology, University of California Berkeley, Berkeley, CA, USA. 2Department of Biology, Johns Hopkins University, Baltimore, MD, USA. 354Gene Inc., Washington, D.C., USA.<sup>4</sup> Department of Molecular and Cell Biology, University of California Berkeley, Berkeley, CA, USA. *Corresponding author. Email: zhangyulin9806@ berkeley. edu (Y.Z.); abiddan1@ jhu. edu (A.B.); moorjani@ berkeley. edu (P.M.) †These authors contributed equally to this work. ‡Present address: insitro Inc. South San Francisco, CA, USA. 

TRACE infers archaic ancestry by leveraging genealogical information encoded in ARGs. The central idea is that archaic introgression leaves two characteristic signatures in the sequence of marginal trees within an ARG: long branches and long haplotypes. First, long branches arise because introgression from a deeply divergent population introduces lineages that coalesce much further back in time than nonintrogressed lineages ( _47_ ). In the ARG, this appears as branches with deep coalescence times that span the interval between the divergence time of the archaic and modern lineages ( _Tarchaic_ ) and the time of the admixture event ( _Tadmix_ ) (Fig. 1A) ( _42_ ). Second, because admixture is more recent than divergence, introgressed segments are expected to be longer than those arising from incomplete lineage sorting (ILS), as less time has elapsed since admixture for recombination to break down the ancestry tracts ( _48_ ). 

TRACE is implemented as a hidden Markov model with two states— archaic human and modern human. As input, it uses ARGs inferred from phased whole- genome sequences of contemporary individuals. For each marginal tree and focal haplotype, we examine (i) the length of the branch ancestral to the focal sample at time _t_ and (ii) the number of other coalescent events on the tree that fall within the same time window (Fig. 1B and fig. S1). The parameter _t_ —which defines the time cutoff for identifying “long” branches—is specified by the user and represents the proxy for the divergence time between the introgressing lineages. The optimal performance of TRACE is achieved when _t_ is close to the true divergence time _Tarchaic_ ; if _t_ is set to be much older than _Tarchaic_ , some true signals may be missed if the introgressed archaic lineage coalesces with modern human lineages before _t_ . Alternatively, if _t_ is set too young, archaic inference results can be sensitive to other recent demographic events (fig. S3). 

To validate TRACE, we simulated genome sequences for three populations including Africans, non- Africans and Neanderthals, incorporating an Out- of- Africa (OOA) bottleneck and ∼2% Neanderthal gene flow into non- Africans ( _22_ , _49_ ). We applied TRACE to detect archaic ancestry in non- Africans using true ARGs for non- Africans (target, _n_ = 100) 

Science 27 August 2026 

**1 of 8** 

**ReseaRch aRticle** 

![](markdown/images/27_Zhang_2026_TRACE_Archaic_Introgression_ARG/27_Zhang_et_al_2026_TRACE_Archaic_Introgression_ARG.pdf-0003-03.png)

**Fig. 1. Conceptual overview and validation of TRACE.** ( **A** ) Schematic of local genealogy relating four haplotypes under a demographic scenario of introgression, where introgression affecting the focal haplotype (green dot) creates long branches (orange branch) ancestral to that sample. Specifically, the long branch spans the timepoint of _t_ generations, which is a user- defined timescale to identify archaic events inferred by TRACE, and is shown in the interval between the divergence time of the archaic and modern lineages lineages ( _Tarchaic_ ) and the time of the admixture event ( _Tadmix_ ) in this figure. Individuals without archaic ancestry (black dots) coalesce at the standard rate within the ancestral population, generating coalescent events during the timespan of the orange branch, which is modeled in the single- genealogy emission distribution. Note that time intervals are not drawn to scale. ( **B** ) Illustration of how the tree sequences are related to emission distributions of the focal branch lengths and the number of nonfocal coalescent events. Coalescent events that are incorporated into the emission distribution for each marginal tree are shown in blue (which occur during the span of the orange branch overlapping _t_ ). For simulations of a constant size model (solid line) and an Out- of- Africa (OOA) model (dashed line), we show the precision (purple), recall (pink), and FDR (brown) when applying different haplotype length cutoffs ( _x_ - axis) in TRACE and using ( **C** ) ground- truth ARGs and ( **D** ) SINGER- inferred ARGs. Precision and recall fall between 0 and 1, shown as the “rate” on the left _y_ - axis; FDR falls between 0 and 0.02, shown on the right _y_ - axis. See also supplementary text section S1 to S3. 

and Africans ( _n_ = 100). We constructed ARGs jointly across populations to minimize the impact of population bottlenecks on the inference (figs. S2 to S6). Applying _t_ = 15,000 generations close to the divergence time between Neanderthals and modern humans ( _4_ ) and focusing on ancestry segments longer than 0.05 centi- Morgans (cM) to distinguish introgressed segments from ILS ( _50_ ), we find that TRACE exhibits high accuracy and high recall (92 and 71%, respectively). The false discovery rate is very low (FDR < 0.25%) as shown by applying TRACE to populations without archaic ancestry (Fig. 1C and supplementary text section S1.3). Compared with published archaic inference methods _hmmix_ ( _34_ ), _Sprime_ ( _35_ ), and _IBDmix_ ( _33_ ), TRACE does not require a sequenced archaic genome or an unadmixed 

outgroup. In simulations, we observe that even small amounts of archaic gene flow into the outgroup can bias reference- free methods such as _hmmix_ and _Sprime_ , whereas TRACE maintains high sensitivity and specificity (fig. S7). Reference- based methods such as _IBDmix_ are not applicable to ghost ancestry inference, and can only recover <0.1% ghost ancestry in simulations (table S8). TRACE shows robust performance across a range of additional demographic models and parameters, including varying proportions of Neanderthal ancestry (0.5 to 10%), divergence times (∼9250 to 24,300 generations), introgression times (725 to 5725 generations), target sample sizes (10 to 200), and misspecification of parameter _t_ (figs. S3 to S8 and supplementary text section S2). 

Science 27 August 2026 

**2 of 8** 

**ReseaRch aRticle** 

Next, we applied TRACE to ARGs inferred using two recently published methods, SINGER ( _40_ ) and _Relate_ ( _42_ ). Similar to the performance with true ARGs, TRACE achieves high precision (∼90%) and low FDR (<0.25%) using the inferred ARGs (Fig. 1, C and D, and fig. S9). However, the recall is substantially lower with inferred ARGs compared with true ARGs. For the OOA model (fig. S2B), TRACE recovers less than 10% of true segments using _Relate_ and approximately 50% using SINGER, compared with ∼80% recall using true ARGs (fig. S9). Furthermore, recall decreases under more complex demographic models, though SINGER maintains higher recall than _Relate_ (around 30%) under most demographic scenarios (fig. S10). Thus, we applied TRACE to SINGER- inferred ARGs for subsequent analysis of empirical data (supplementary text section S3 and figs. S9 to S14). 

ancestry—introgression from an archaic lineage more distantly related to Neanderthals and Denisovans—in all modern human populations studied. We detected 0.5 to 1.1% of ghost ancestry on average across populations (Fig. 2A). Most ghost ancestry segments found in non- Africans are shared with sub- Saharan Africans, while both East and West Africans harbor a greater diversity of distinct ghost segments consistent with the reduction in genetic diversity in nonAfricans caused by the OOA bottleneck (Fig. 2B and figs. S23 and S24). Ghost segments exhibit deep divergence in marginal trees and show nearly identical genetic affinity to both sequenced Neanderthal and Denisovan genomes, indicating that they originated from an unsequenced lineage equally related to both archaic groups (Fig. 2C and figs. S17 to S19). The average coalescence time between the ghost and modern human segments, inferred from introgressed segments, is approximately 0.83 Mya (95% CI: 0.83 to 0.84 Mya, table S6). 

#### **Evidence of ghost admixture in modern human populations before the OOA migration** 

Several additional lines of evidence support our results of ghost ancestry in modern humans. First, we find that genomic regions harboring ghost ancestry exhibit elevated heterozygosity levels, a pattern also observed for Neanderthal and Denisovan segments (fig. S25). The elevation in heterozygosity is consistent with a model of introgression from a deeply divergent lineage ( _56_ ) and, notably, suggests that the ghost ancestry signal is not an artifact of ARG inference. Second, across all tested populations, ghost ancestry segments are shorter than Neanderthal and Denisovan segments, reflecting a more ancient introgression event predating Neanderthal gene flow (fig. S26). Additionally, we validated in simulations that in a model lacking ghost introgression, TRACE infers negligible levels of ghost ancestry (0.07%, 95% CI: 0 to 0.3%), markedly below the estimates from empirical data. By contrast, simulations including a ghost lineage produced results that closely matched empirical observations (tables S7 to S9, figs. S27 and S28, and supplementary text section S5). Furthermore, 

We analyzed 503 phased whole- genome sequences from the 1000 Genomes Project (1000G) using SINGER reconstructed ARGs (no archaic genomes included). To identify archaic introgression signals, we applied TRACE with _t_ = 15,000 generations [or 420,000 years, assuming a generation time of 28 years ( _51_ )], close to the estimated divergence time between modern humans and Neanderthals ( _4_ ). To minimize the impact of ILS, we retained archaic segments longer than 50 kilobase pairs (kbp) and 0.05 cM (which translates to FDR < 0.2% in simulations, Fig. 1D). We then compared variants on the inferred archaic segments with four high- coverage sequenced archaic genomes [three Neanderthal ( _2_ , _3_ , _5_ ) and one Denisovan ( _1_ )] to identify the source of archaic ancestry. For comparison, we also applied _IBDmix_ (using the Altai Neanderthal and Altai Denisovan genomes) and _hmmix_ (using 426 sub- Saharan Africans as outgroup) (supplementary text section S4). 

In non- African populations, TRACE identifies 0.8 to 1% Neanderthal ancestry per individual in Europeans, East Asians, and South Asians (Fig. 2A). We recovered minimal Denisovan ancestry in Europeans (0.03%), with higher levels in East and South Asians (0.10% each), consistent with published results ( _35_ , _52_ – _55_ ). More than 90% of Neanderthal and 70% of Denisovan segments identified by TRACE were also inferred by _hmmix_ or _IBDmix_ (table S4). In both West and East Africans, TRACE detects less than 0.1% combined Neanderthal and Denisovan ancestry per individual. Around half of the Neanderthal segments identified in sub-Saharan Africans by TRACE were also inferred by _IBDmix_ (table S4; _hmmix_ was not ap plied as there is no reliable outgroup for sub- Saharan Africans). We note that TRACE recovers less total Neanderthal and Denisovan ancestry compared with some previous studies ( _33_ , _54_ , _55_ ), owing to the lower recall with inferred ARGs, though the recovered segments show no obvious bias relative to those identified by _hmmix_ and _IBDmix_ (supplementary text section S4.3 and S5.2, table S7, figs. S10, S15, and S16). Nevertheless, TRACE robustly reconstructs the major features of Neanderthal and Denisovan introgression across global populations. 

![](markdown/images/27_Zhang_2026_TRACE_Archaic_Introgression_ARG/27_Zhang_et_al_2026_TRACE_Archaic_Introgression_ARG.pdf-0004-08.png)

**Fig 2. Archaic ancestry in global populations.** ( **A** ) Proportion of archaic ancestry per genome recovered by TRACE using _t_ = 15,000 generations that are >50 kbp and >0.05 cM for 1000G populations. Archaic segments are classified as Neanderthal (blue), Denisovan (orange), and ghost (red) based on allele sharing with sequenced Neanderthal and Denisovan genomes (supplementary text section S4.2). ( **B** ) The amount of total (dark) and shared (light) ghost archaic ancestry per genome between West Africans and non- Africans. ( **C** ) Affinity of ghost segments for Neanderthal ( _x_ - axis) and Denisovan ( _y_ - axis) genomes in West Africans, calculated as the proportion of derived mutations on the segment shared with Neanderthal and Denisovan sequences. 

Beyond Neanderthal and Denisovan ancestry, TRACE revealed “ghost” archaic 

Science 27 August 2026 

**3 of 8** 

**ReseaRch aRticle** 

we computed the site frequency spectrum (SFS) and conditional SFS (cSFS) for variants present on archaic segments identified by TRACE (figs. S20 to S22). While Neanderthal and Denisovan segments show the expected “U- shape” ( _17_ ), ghost segments display distinct SFS and cSFS patterns that are consistent with a model of pre–OOA ghost introgression in simulations (fig. S29 and S30). 

Together, these findings suggest that an unknown archaic population, which diverged more than 500,000 years ago, introgressed into the common ancestors of all modern humans prior to the OOA migration, resulting in similar patterns of ghost ancestry in non- Africans and Africans. 

#### **The landscape of ghost ancestry in modern humans** 

To explore the legacy of ghost ancestry in modern humans, we examined the genome- wide distribution of ghost ancestry in global populations. Across all ghost haplotypes identified in all populations (sub- Saharan Africans and non- Africans) by TRACE, we recovered 1548.75 Mbp or 71.54% of the accessible genome (Fig. 3, supplementary text section S6). Broadly, the genome- wide patterns of ghost ancestry segments resemble those expected from hybridization between deeply divergent lineages ( _57_ – _59_ ). We find that ghost ancestry decreases in proximity to functional elements [lower _B_ score ( _60_ ); ρ _Spearman_ = 0.45, _P_ < 10<sup>−5</sup> ] and in regions of low recombination (ρ _Spearman_ = 0.34, _P_ < 10<sup>−5</sup> ), reflecting stronger effects of linked selection in these regions ( _61_ , _62_ ). These patterns mimic those seen in Neanderthal and Denisovan introgression maps ( _6_ , _53_ ) as well as 

patterns of hybridization across nonhuman species ( _59_ ) (fig. S31 and S32, table S10, and supplementary text section S6.1). 

We also scanned for “peaks” of ghost ancestry, defined as regions where the frequency of ghost ancestry exceeded two standard deviations above the population-specific genome-wide average. Across all tested populations, we identified 1932 peaks of ghost ancestry (average length 61 kbp, SD 64 kbp) (supplementary text section S6.2, Fig. 3, and table S13). This result  contrasts with the smaller number of 1155 and 160 peaks of Neanderthal and Denisovan ancestry, respectively (average length 84.97 and 76.54 kbp). We find that ghost ancestry peaks are overrepresented in sub- Saharan African populations relative to nonAfrican populations, which is consistent with the lower genetic diversity in non- Africans (figs. S33 and S34). Several genes intersect with high- frequency peaks of ghost ancestry, such as _CSMD1_ and _RBFOX1_ , with an overall functional enrichment for immune and metabolic complexes, including the major histocompatibility and lipoprotein complexes ( _P_ < 10<sup>−5</sup> using binomial test; figs. S35 and S36). We also identify 97 deserts of ghost ancestry (i.e., regions that are at least 10 Mbp long and have less than 0.1% frequency of ghost ancestry). These deserts are only found in non- African populations, with nearly half (43.3%) shared between different non- African groups, likely formed during the OOA bottleneck (supplementary text section S6.3 and figs. S37 and S38). We do not identify any ghost ancestry deserts in sub- Saharan Africans (though this may depend on the specific frequency and haplotype length thresholds applied). Overall, we find large heterogeneity in the distribution of ghost ancestry tracts across the genome. 

### **A** 

![](markdown/images/27_Zhang_2026_TRACE_Archaic_Introgression_ARG/27_Zhang_et_al_2026_TRACE_Archaic_Introgression_ARG.pdf-0005-09.png)

![](markdown/images/27_Zhang_2026_TRACE_Archaic_Introgression_ARG/27_Zhang_et_al_2026_TRACE_Archaic_Introgression_ARG.pdf-0005-10.png)

<!-- Start of picture text -->
B<br><!-- End of picture text -->

**Fig. 3. Characterizing the distribution of archaic ancestry using TRACE.** ( **A** ) Estimated peaks of archaic ancestry from TRACE—including ghost ancestry—aggregated across all populations. Genomic regions masked as centromeric or genomic regions with no called variants (excluded from ARG inference) are shown in white. Previously estimated deserts of archaic (Neanderthal and Denisovan) ancestry are shown as gray highlights. ( **B** ) Frequency of Neanderthal and Denisovan ancestry across non- African populations and ghost ancestry across all populations within the chromosome 7 archaic desert [shown as dashed gray box in (A)]. The _y_ - axis in the top panel reflects the frequency of Neanderthal and Denisovan ancestry whereas the _y_ - axis in the bottom panel reflects the frequency of ghost ancestry within the region. 

Science 27 August 2026 

**4 of 8** 

**ReseaRch aRticle** 

Neanderthal and Denisovan deserts are often considered candidates of _Homo sapiens_ –specific regions ( _7_ , _63_ ). We examined ghost ancestry in five Neanderthal and Denisovan shared deserts identified by two previous studies (figs. S39 to S45, tables S11 and S12, and supplementary text section S6.4) ( _7_ , _53_ ). We replicate the absence of both ancestries in two deserts but find non- negligible Neanderthal or Denisovan ancestry in some others consistent with recent studies ( _7_ , _53_ , _54_ , _63_ , _65_ ). Nevertheless, all five regions contain substantial ghost ancestry, even after restriction to longer and more confidently inferred segments (>100 kbp; Fig. 3B, figs. S39 and S40, and table S11). For example, the shared archaic desert on chromosome 7 containing the _FOXP2_ gene has a ghost ancestry peak at 13.3% frequency (Fig. 3B), and the Neanderthal desert on chromosome 3 contains a ghost peak of ∼20% frequency overlapping _CSNK2A2IP_ (fig. S40). Our findings suggest that ghost ancestry is often present in previously defined archaic deserts, providing additional context to putative _Homo sapiens_ –specific evolutionary changes. 

#### **Detecting super** **_-_ archaic ancestry in Oceanians** 

Previous studies examining patterns of allele sharing between Neanderthals, Denisovans, and modern humans have suggested Denisovans may harbor ancestry from a super- archaic population ( _1_ , _2_ , _32_ ). Among modern humans, Oceanians and Southeast Asians derive the highest proportion of Denisovan ancestry ( _52_ ). We therefore reasoned that a fraction of super- archaic ancestry may have been inherited through Denisovan gene flow and may persist within Denisovan- introgressed segments in present- day Oceanians. To test this, we analyzed 92 high- coverage wholegenome sequences from Oceanian individuals including 25 individuals from Papuan New Guinea ( _65_ ) and 67 individuals from Vanuatu and 

Santa Cruz Islands ( _52_ ). We reconstructed the ARGs using SINGER along with 1000G YRI individuals and applied TRACE with _t_ = 15,000 generations to detect archaic ancestry (supplementary text section S7.1). 

In Oceanian individuals, TRACE inferred an average of 0.73% Neanderthal, 0.66% Denisovan, and 0.33% ghost ancestry (Fig. 4A), lower than estimates from previous studies ( _52_ ) and from other 1000G nonAfricans (Fig. 2A and fig. S46). Because Neanderthals and Denisovans coalesce with each other [ _t_ = 13,600 to 16,900 ( _2_ )] before coalescing with modern humans, many of the long branches are not detected when using _t_ = 15,000 generations as the time cutoff. The higher archaic introgression proportion further exacerbates this effect, as a larger fraction of coalescent events occur among archaic lineages (supplementary text section S7.2, table S15, and figs. S47 and S57). Simulations mimicking the demographic history of Oceanians replicated this underestimation (supplementary text section S8 and tables S15 and S16). Despite lower recall, more than 90% of the Neanderthal and Denisovan segments detected by TRACE overlap with those from _hmmix_ or _IBDmix_ (table S14). TRACE- detected archaic segments showed consistent archaic affinity patterns (fig. S48) and site frequency spectra (SFS/cSFS, fig. S49) with 1000G data. Furthermore, ghost segments in Oceanians overlapped with those detected in 1000G populations (fig. S50), consistent with a shared origin in modern humans. 

To identify super- archaic introgression, we screened for “superdeep” coalescent events within Denisovan- introgressed segments with _t_ = 31,500 generations (inferred divergence time between the superarchaic lineage and modern humans) ( _32_ ), requiring at least 10 kbp and 0.01 cM to distinguish from ILS, and applied the same analysis to Neanderthal introgressed segments for comparison. We find a 

### **A** 

**C** 

![](markdown/images/27_Zhang_2026_TRACE_Archaic_Introgression_ARG/27_Zhang_et_al_2026_TRACE_Archaic_Introgression_ARG.pdf-0006-10.png)

<!-- Start of picture text -->
B<br><!-- End of picture text -->

**Fig. 4. Super- archaic ancestry detected using TRACE within Oceanian (OCN) genomes.** ( **A** ) Total proportion of Neanderthal, Denisovan, and ghost ancestries across all sampled Oceanian individuals ( **B** ) Detected super- archaic ancestry in the MHC region lying on the background of Denisovan ancestry. ( **C** ) Denisovan segments have a substantially higher proportion of super- deep lineages than Neanderthal segments, a signal reflective of super- archaic ancestry in simulations ( _P_ < 10<sup>−5</sup> , _P_ = 1.00, _P_ < 10<sup>−5</sup> ) for real data OCN, no super- archaic simulation, and super- archaic simulation respectively; using binomial test). 

Science 27 August 2026 

**5 of 8** 

**ReseaRch aRticle** 

significantly higher proportion of super- deep lineages in Denisovan than in Neanderthal segments ( _P_ < 10<sup>−5</sup> using a binomial test; Fig. 4 and supplementary text section S7.3). Simulations show that this pattern is inconsistent with a model lacking super- archaic introgression but is recapitulated by a model including super- archaic introgression into Denisovans (Fig. 4C, figs. S56, S58, and S59, and tables S15 and S16). Furthermore, super- archaic fragments within introgressed Denisovan segments exhibit distinct genetic features that differentiate them from the background Denisovan ancestry, including much deeper coalescence times with modern humans, longer genomic lengths than mean ILS length from Neanderthal deep lineages, and low affinity to both Neanderthal and Denisovan reference genomes (assuming no super- archaic ancestry at the same locus in sequenced Denisovan, supplementary text section S8.4, fig. S60, and table S17). Using these features, we detected super- archaic segments in simulations with 70.2% accuracy (95% CI: 66.4 to 74.1%, supplementary text section S8.5). 

Applied to Oceanian genomes, we infer that the super- archaic segments embedded within Denisovan ancestry tracts range between 20 to 83 kbp (average: 37.6 kbp) and contribute approximately 0.3% of the total detected Denisovan ancestry in Oceanians (table S18 and fig. S51). This estimate constitutes a very conservative lower bound on the true fraction of super- archaic ancestry, as our analysis is restricted to Denisovan- introgressed regions, requires segments of at least 20 kbp, and excludes loci where the sequenced Denisovan carries super- archaic ancestry (figs. S60 and S61 and supplementary text section S7.4). We validated that super-archaic segments exhibit higher nucleotide divergence from both modern humans (sub-Saharan Africans) and Altai Denisovans (compared with other Denisovan- introgressed regions), suggesting the signal is not an artifact of ARG inference (fig. S52). Using the marginal trees from SINGER, we estimate the coalescence time between super- archaic and modern human lineages to be approximately 1.77 Mya (95% CI: 1.69 to 1.83 Mya), consistent with earlier reports ( _2_ , _32_ ). 

We evaluated the potential functional effects of super- archaic segments recovered from Oceanian genomes by characterizing common gene annotations and patterns of functional enrichment (Fig. 4B). Several genic regions harbor high proportions (>70%) of super- archaic tracts such as _RNF39_ , _PPP1R11_ , and _POLR1H_ within the major histocompatibility complex (MHC) (Fig. 4B and fig. S53) and _CYP24A1_ , which is a part of the cytochrome P450 family and a critical regulator of vitamin D degradation in humans (fig. S54) ( _30_ , _66_ – _69_ ). Gene ontology analysis reveals considerable enrichment for several pathways including MHC and activity- related cytoskeleton, after multiple hypothesis testing (fig. S55). 

### **Discussion** 

We introduce TRACE, a framework for detecting archaic introgression from ARGs inferred from contemporary genomes alone. TRACE’s reference- and outgroup- free design enables the reconstruction of introgression histories that are difficult to resolve with existing approaches, including ghost and super- archaic introgression. As with any ARG- based method, TRACE’s performance depends on the accuracy and scalability of the underlying ARG inference, with reduced recall using inferred ARGs relative to ground- truth genealogies. As ARG reconstruction methods continue to advance, the reliability and resolution of TRACE will improve, illuminating episodes of evolutionary history of humans and other species lacking direct genomic references. 

Applied to modern human data, TRACE recovers known Neanderthal and Denisovan ancestry and identifies previously uncharacterized signatures of archaic ancestry at varying time points in human history. We find evidence for at least one ghost introgression predating the OOA expansion that contributed ancestry to all present- day populations. This finding is most consistent with a discrete introgression event as in (17) but extends that model by showing that the event affected all 

modern human populations rather than being localized to West Africans. Given that our inferred ghost lineage diverged around the time of the Neanderthal–modern human split (table S6), it represents a more recent event than the proposed deep structure scenarios, involving a population split (>1.5 Mya) followed by later integration through either a single rejoining event around 300 kya ( _23_ ) or multiple “merger” events ( _27_ ). Finally, we infer deeply diverged lineages embedded within Denisovan ancestry in Oceanians, consistent with an additional, indirect contribution from a super- archaic hominin to modern humans. These results point to multiple layers of introgression—both direct and mediated through other archaic groups—shaping modern human genomes. 

Beyond the timing and demographic context of these introgression events, their hominin sources remain an open question. Archaeological records document numerous archaic forms with unclear amounts, if any, of potential contribution to modern humans ( _30_ , _66_ , _67_ ). The ghost lineage, with a divergence time similar to that of Neanderthals, could plausibly correspond to Middle Pleistocene _Homo_ groups ( _70_ – _72_ ) or African _Homo heidelbergensis_ populations ( _73_ – _75_ ) that directly admixed with modern human ancestors before the OOA dispersal. For the super- archaic lineage, one potential candidate—compatible with the split time of approximately 1.8 Mya—is _Homo erectus_ , as suggested by earlier studies ( _2_ , _16_ , _32_ ). 

TRACE also illuminates the enduring genomic legacy of archaic ancestry in modern humans. Both ghost and super- archaic ancestry are markedly enriched in functional regions highlighting their role in human adaptation. Moreover, ghost ancestry persists within genomic regions previously identified as deserts of Neanderthal and Denisovan introgression. These deserts have often been interpreted as regions intolerant to archaic introgression as a result of positive selection for _Homo sapiens_ –specific variation or strong purifying selection against archaic introgressed alleles ( _57_ – _59_ ). Instead, the persistence of deeply diverged ghost ancestry in these regions suggests lineage- specific selection against Neanderthal and Denisovan introgression, rather than positive selection for modern human variation. This pattern implies that differences in genetic load or epistatic incompatibilities associated with Neanderthal and Denisovan lineages—rather than with divergence time alone—shaped Neanderthal and Denisovan ancestry deserts. 

Several open questions remain: First, the number, timing, and geographic locations of the inferred ghost introgression events are still uncertain; although our results support at least one pre–OOA introgression event affecting all modern human populations, additional episodes of gene flow among structured African populations may have occurred but remain difficult to resolve with present data. Second, the origin and geographic extent of the super- archaic lineage remains unresolved, including whether this ancestry entered modern humans exclusively through Denisovans or also through direct admixture with ancestors of modern humans. We anticipate that future studies, including new Denisovan reference genomes, may help to further pinpoint the timing and origin of these super- archaic sequences ( _75_ ). Finally, while we detect signatures of selection influencing the distribution of ghost ancestry in the genome, the functional impacts of introgressed archaic regions, including their roles in immunity and metabolism, have yet to be fully characterized. Future studies that integrate additional ancient genomes at deep timescales, particularly from Africa and Asia, will be critical for refining the timing, sources, and evolutionary consequences of these introgression events. 

Materials and methods are available in supplementary materials. 

##### **ReFeReNces aND NOtes** 

*(References list omitted for brevity)*

##### **sUPPleMeNtaRY MateRials** 

science.org/doi/10.1126/science.aef8874 Supplementary text; Figs. S1 to S61; Tables S1 to S18; References ( _79_ – _101_ ); Submitted 6 February 2026; accepted 25 June 2026; published online 30 July 2026 

<table><tr><th>10.1126/science.aef8874</th></tr></table>

## **Correction (11 September 2026):** In the originally published version of this article, Fig. 2C contained visual errors (a glitch/bleed effect that, although not affecting the readability of the figure, was still not intended by the author). This 

has been corrected. 

In the SM, the figures present in the initially uploaded version were very low-res; this has also been corrected. 

Science 27 August 2026 

**8 of 8** 

![](markdown/images/27_Zhang_2026_TRACE_Archaic_Introgression_ARG/27_Zhang_et_al_2026_TRACE_Archaic_Introgression_ARG.pdf-0010-01.png)

## **Recovering signatures of archaic hominin introgression using ancestral recombination graphs** 

Yulin Zhang, Arjun Biddanda, Sarah A. Johnson, Colm O’Dushlaine, and Priya Moorjani 

_Science_ **393** (6814), eaef8874.  DOI: 10.1126/science.aef8874 

#### **Editor’s summary** 

Since the sequencing of Neanderthal and Denisovan genomes, extensive gene flow between archaic hominins and humans has become increasingly apparent. However, early episodes of gene flow can obfuscate later signals, and introgression is still difficult to detect without a reference genome. Zhang _et al_ . developed TRACE, a method that uses ancestral recombination graphs to identify introgression in humans without archaic reference genomes. They found introgressed regions from a ghost lineage of hominins in all modern human populations that surprisingly overlapped regions previously identified as lacking Neanderthal and Denisovan introgression, called “deserts.” This work also supported previous evidence of superarchaic ancestry within Denisovan introgressed regions. —Corinne Simonti 

#### **View the article online** 

https://www.science.org/doi/10.1126/science.aef8874 **Permissions** 

https://www.science.org/help/reprints-and-permissions