# Vaginal-microbiome-and-hpv
Here I describe the analysis of vaginal samples from 36 Kenyan women living with HIV, 18 being positive for high-risk HPV and the other 18 negative. 16S rRNA sequencing of the V3-V4 region was performed to characterise the vaginal microbiomes of the study population. The aim of the project is to identify the bacterial profiles associated with HPV infection in women living with HIV and assess whether there is a statistical significance in alpha diversity between the cases (HPV positive) and controls (HPV negative). Sequence analysis and data visualisation is being done using the DADA2 and Phyloseq Bioconductor packages in R 4.4.0.

Some of the key findings from the analysis are: 
1. Firmicutes and Actinobacteria are the most abundant phyla regardsless of HPV status. Firmicutes had a relative abundance of 48% whereas Actinobacteria had a relative abundance of 26%. This is vastly different from the healthy vaginal microbiome composition whereby Actinobacteria usually aren't as abundant as in this case, indicating vaginal dysbiosis.
2. The alpha diversity between HPV positive and HPV negative women with HIV isn't statistically significant. In this cohort Shannon's diversity index ranged from 4-7 indicating very high bacterial diversity. The healthy vaginal microbiome has low diversity with Shannon's diversity ranging from 0.1-1.5 due to Lactobacillus dominance. This high bacterial diversity could be driven by the women's HIV status.
3. Both HIV and HPV infection is associated with vaginal dysbiosis. Gardnerella was the most abundant genus (1091 sequences) followed by Lactobacillus(982 sequences), Sneathia(504 sequences), Prevotella (458 sequences), Atopobium (358 sequences). All these genera, except Lactobacillus are associated with bacterial vaginosis, a state of vaginal microbial imbalance. Prevotella has been found to be associated with HIV infection. Sneathia is as emerging vaginal pathogen of interest, correlated with adverse reproductive and pregnancy outcomes. 3 STI-associated genera were also identified including: Mycoplasma(112 sequences), Ureaplasma (25 sequences) and Treponema_2(18 sequences). 56 sequences of Escherichia/Shigella were also identified, which could be attributed to poor hygiene and intravaginal cleaning.
4. The vaginal microbiome composition of both HPV positive and HPV negative women with HIV is similar. Non-metric multidimensional scaling of Bray-Curtis distances revealed relatively little dissimilarity in the beta diversity between the 2 groups of women. This shows that there is no difference in the vaginal microbiomes of HIV positive women regardless of HPV status.

 ![Relative abundance by HPV status](https://github.com/SophMN/Vaginal-microbiome-and-hpv/assets/145765029/a3f21232-3d8a-4887-8402-7349460d9efc)
 ![Abundance by Phyla between HPV- and HPV+ Women](https://github.com/SophMN/Vaginal-microbiome-and-hpv/assets/145765029/90e9593d-2959-487a-a257-cb67bb09caae)
 ![alpha diversity](https://github.com/SophMN/Vaginal-microbiome-and-hpv/assets/145765029/246328d3-83b4-4795-b8c4-2b655ecb6449)
![Bray Curtis NMDS](https://github.com/SophMN/Vaginal-microbiome-and-hpv/assets/145765029/56fdc5a3-859c-4e68-a499-e3fe1d56db51)




