# Integration of Negative Data Into Benchmarking Databases: Application to Nuclear Receptors
### What does negativity stands for ? 
{: style="text-align: justify"} 
Today, we deplore the lack of negative data reported in litterature and public databases. If most screening results are analysed through a "sensitivity" point of view (i.e. how many true positives are selected), the inclusion of true negative confers weight to the "specificity" point of view (i.e. how many true negatives are rejected). This means that we could not only bring answers to **"what is responsible for the ligand/protein affinity/activity ?"**, but also to **"which features impede the interaction/ impede triggering a specific activity ?"**

<img style="width:95%" src="assets/images/PR_ago_antago.png" alt="PR structures: ago-bound vs. antago-bound"><br>

{: style="text-align: justify"} 
The concept of negative data is relative to the studied system and the intended results. In the case of NRs, we may want to find agonists of a specific NR; an evident type of negative data are the molecules that did not show any experimental binding affinity against the NR. 
However, binders can ellicit different kind of activities depending on their pharmacological profile (i.e. agonist, antagonist, partial agonist/antagonist, inverse agonist). In this case, **only** agonists should be considered in the true positif set, while molecules displaying non wanted pharmacological profiles can be considered in the negative set. This implies that a sharp annotation step is necessary prior to library screening.

### Why do we study Nuclear Receptors (NRs) ?
{: style="text-align: justify"} 
The NRs constitute an important family of transcription factors (TFs), with a total of 48 human NRs. NRs regulate gene expression in various physiological processes through their interactions with small hydrophobic molecules. Their implication in various diseases (obesity, diabetes, metabolic syndromes, impaired reproductive system development etc.) make them important class of targets for drugs. Many efforts are put in identifying NRs modulators with reduced side effects.

{: style="text-align: justify"} 
Additionally, experimental studies show that NRs are also targeted by endocrine disrupting chemicals (EDCs) that mimic and replace the endogenous ligands. Inappropriate exposures to EDCs can impair key physiological functions and lead to dramatic impact on human and wildlife health.

{: style="text-align: justify"} 
Thanks to the amount of published data concerning NRs, it is possible to build prediction models to assist scientists from various research fields in identifying NRs ligands in drug design campaign, or in understanding EDCs mode of action. Nonetheless, high data quality is required to generate reliable models. 

{: style="text-align: justify"} 
Gathering quality data with documented annotations and including negative data was the first big challenge of my thesis at the GBA, CNAM.

### Creation of the NR-DBIND (Nuclear Receptors DataBase Including Negative Data)
{: style="text-align: justify"} 
In a previous work, <a href="https://pubs.acs.org/doi/abs/10.1021/jm500132p">Lagarde et al</a> created the <a href="http://nrlist.drugdesign.fr">**NRLiSt BDB**</a>, a robust NR-focused benchmarking database that aimed to correct and complete annotation errors found in ChEMBL. This database mainly contains activity values (IC50 and EC50) collected through a manual literature
review, including their corresponding "agonist" or "antagonist" pharmacological profile annotation.
To complete information brought by the NRLiSt BDB with more affinity data, more diversity in pharmacological profile annotations, more experimental details, and particularly to include negative data, we constructed the **Nuclear Receptors DataBase Including Negative Data (**<a href="http://nr-dbind.drugdesign.fr">**NR-DIND**</a>**)**

{: style="text-align: justify"} 
To the best of our knowledge, the NR-DBIND is the most exhaustive database that contains small molecules affinity and activity data for NRs. In total, it provides **15116 positive** and negative interactions data for 28 NRs together with 599 PDB structures.
Each interaction is documented with the small molecule SMILES, IUPAC name and additional identifiers (ZINC, CHEMBL) when available, its associated activity and affinity assay types and values, the corresponding references from the literature, and when avaiable, the percentage of activity, the associated pharmacological profile.

The entire NR-DBIND is freely available at <a href="http://nr-dbind.drugdesign.fr">**http://nr-dbind.drugdesign.fr**</a>. Different subsets can be selected and dynamic tables allow custom selection, download and visualization of data.


### Applications
{: style="text-align: justify"} 
The NR-DBIND can be used as a reliable source of data for researchers from different fields trying to understand and modulate NRs functions. The NR-DBIND datasets are notably suited for in silico studies using structure- and ligand-based methods.

Among our multiple projects, we are exploring the impact of structure choice in the performance of docking tools applied on datasets fully composed of true positive and true negative ligands.


# Theranalpha Project (Theranostic TNFa inhibitors)
{: style="text-align: justify"} 
The global objective of this project is to design and evaluate *in vitro* and *in vivo* theranostic small molecule inhibitors of TNFa to further provide inexpensive anti-TNFa therapies administered orally.<br>

{: style="text-align: justify"} 
Project coordinator : Marc Port, <a href="http://cmgpce.cnam.fr/cm-presentation-de-l-equipe-contacts-et-acces-703730.kjsp">Laboratoire de Chimie Moléculaire</a>, CNAM<br>
The project is supported by an ANR grant: <a href="http://www.agence-nationale-recherche.fr/Project-ANR-17-CE18-0024">Read the full ANR project</a>
### Collaborators
- Laboratoire CM (Chimie Moléculaire), CNAM, Paris
- Laboratoire GBA (Génomique, Bioinformatique et Applications), CNAM, Paris
- Laboratoire SATIE (Laboratoire des Systèmes et Applications des Technologies de l'Information et de l'Energie) 
- PEPTINOV SAS
