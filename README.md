# hcv_lineage-awareness

pt.haplotypes.fasta
Haplotypes estimated by CliqueSNV [https://github.com/vtsyvina/CliqueSNV].
Sequence IDs contain the [anonymised patient id]_[days since baseline]_[sample type]_[haplotype id]_[haplotype frequency].
(sample type include: B for baseline, T12 for treatment 12 weeks, PT4 for post-treatment 4 weeks, PT12 for post-treatment 12 weeks, PT24 for post-treatment 24 weeks, BRT for baseline before retreatment, PRT4 for post-retreatment 4 weeks, PRT12for post-retreatment 12 weeks,PRT24 for post-retreatment 24 weeks )

pt_.gif
These files contain networks generated using the 1-step and k-step approach introduced in Campo et al. 2014 [DOI
https://doi.org/10.1186/1471-2164-15-S5-S4]
The k parameter is the number of pairwise difference between the haplotypes(nodes) within the network.

