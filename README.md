# West Nile Virus Infection in mice treated with vehicle or various antibiotics

Mice were cohoused for 2 weeks prior to separation into individual cages (Day -14). After 2 weeks, mice were individually caged (Day 0). A fecal pellet was taken prior to antibiotics treatment (Day 0) and subsequently after treatment at Days 3, 7, 13, 16 and 18. Mice were infected with West Nile Virus (WNV2000) at Day 14.

Antibiotics tested:

1) Metronidazole
2) Ampicillin
3) Combination Ampicillin + Metronidazole

Vehicle control mice were allowed to drink kool aid, which is mixed with all of the antibiotics treatments to aid in mouse consumption of poor tasting antibiotics water.

For all analysis, the Day -14 data has been removed. Cohousing was performed in a different animal facility than the actual treatments on individually caged mice. Elimination of the Day -14 data removes this confounding facility effect.

An additional set of uninfected mice were analyzed in parallel. Ultimately, only infected mice were focused on for the study, so these samples are not investigated in the RMarkdown documents here.

Amplicon sequences were resolved using dada2 (full workflow: wnv_antibiotics_preprocessing.Rmd). Samples were spread across two independente MiSeq runs, therefore dada2 sequence resolution was performed indepdenetly for each run, and the results combined prior to generation of unique amplicon sequence variants (ASV), taxonomic assignment and phylogenetic tree construction. Taxonomy was assigned to multiple reference databases:

1) GreenGenes
2) RDP
3) Silva
4) HitDB

In addition, species level assignment to Silva and RDP was supplemented to the taxonomic assignment procedure. 






