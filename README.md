# hcv_lineage-awareness

pt.haplotypes.fasta

Haplotypes estimated by CliqueSNV [https://github.com/vtsyvina/CliqueSNV].

Sequence IDs contain the [anonymised patient id]_[days since baseline]_[sample type]_[haplotype id]_[haplotype frequency].

(sample type include: B for baseline, T12 for treatment 12 weeks, PT4 for post-treatment 4 weeks, PT12 for post-treatment 12 weeks, PT24 for post-treatment 24 weeks, BRT for baseline before retreatment, PRT4 for post-retreatment 4 weeks, PRT12for post-retreatment 12 weeks,PRT24 for post-retreatment 24 weeks )

pt_ksteps.gif

These animations contain networks generated using the 1-step and k-step approach introduced in Campo et al. 2014 [DOI: https://doi.org/10.1186/1471-2164-15-S5-S4]

The k parameter is the maximum number of pairwise differences between the haplotypes(nodes) within the connected network. The colour of the nodes indicate the sample that the haplotypes came from.

The one component k value is the minimum k value that links the entire network into one component.

The animations show the changing networks as the current k value increases to the one component k.
