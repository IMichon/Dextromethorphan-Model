### Absorption <a id="model-parameters-and-assumptions-absorption"></a>

The dissolution of tablets were implemented via an empirical Weibull dissolution capsule; The final Weibull shape parameters and Weibull time parameters (50% dissolved) for the cocktail capsule formulation used in the PBPK model are given in [Section 2.2](#methods-data).

Although dextromethorphan is rapidly absorbed from the intestine, time to reach peak plasma concentration Cmax (tmax) often occurs as late as 4h after oral administration. This phenomenon likely occurs due to lysosomal trapping of dextromethorphan in the intestinal mucosa. However, other processes, such as renal excretion may also be affected by lysosomal trapping in the respective tissue. In short, lipophilic amines (logP > 1, acid dissociation constant (pKa) > 6) accumulate in lysosomes due to rapid diffusion across the lysosomal membrane in unionized form. Subsequently, due to the acidic environment in lysosomes (pH 4–5), the amine is then ionized and thus unable to
permeate back into the cytosol. The information necessary to physiologically implement lysosomal trapping (i.e. relative abundances of lysosomes in relevant tissues and diffusion constants for permeation across lysosomal membranes) are not yet available in the literature. Hence, intestinal lysosomal trapping was implemented as follows: First, a surrogate protein binding partner was expressed in high abundances (500 μmol/L) in the relevant tissues (duodenum, upper jejunum, lower jejunum, upper ileum and lower ileum, each 100% of relative expression). Secondly, a corresponding protein binding process was implemented for dextromethorphan. Finally, the relevant parameters
for the binding process - dissociation rate constant (k<sub>off</sub>) and dissociation constant (K<sub>D</sub>) - were informed by parameter optimization. For a comprehensive explanation on the process of lysosomal trapping under physiological circumstances, please refer to [Kazmi 2013](#main-references). The final parameters for K<sub>D</sub> and k<sub>off</sub> are given in [Section 2.2](#methods-data).

### Distribution <a id="model-parameters-and-assumptions-distribution"></a>

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim, observed Dextromethorphan and dextrorphan clinical data was best described by choosing the partition coefficient calculation by `Berezhkovskiy` and cellular permeability calculation by `PK-Sim Standard`. For the dextrorphan O-clinical clinical data was best described by choosing the partition coefficient calculation by `Berezhkovskiy` and cellular permeability calculation by `Charge dependent Schmitt`.

### Metabolism and Elimination <a id="model-parameters-and-assumptions-metabolism-and-elimination"></a>

Dextromethorphan-O-demethylation via CYP2D6 leads to the formation of the major active metabolite dextrorphan. Dextrorphan subsequently undergoes rapid glucuronidation via uridine diphosphate-glucuronosyltransferases 2B (UGT2Bs), namely UGT2B15, or N-demethylation via CYP3A4. **Figure 1** shows the implemented metabolic pathways.

**Figure** **1: Implemented dextromethorphan metabolic pathways.**
![Figure 1](images/Figure_1.PNG)

Alternatively, dextromethorphan is N-demethylated by CYP3A4, which was found to be the main pathway of dextromethorphan metabolism in CYP2D6 PMs. Depending on the CYP2D6 phenotype, up to 50% of orally administered dextromethorphan is excreted unchanged in urine. The principal pathway of dextromethorphan metabolism is the CYP2D6-mediated O-demethylation, leading to the formation of dextrorphan. This pathway was implemented using Michaelis-Menten kinetics. Cytochrome P450 2D6 (CYP2D6) was implemented in accordance with literature, using the PK-Sim® expression database to define their relative expression in the different organs of the body [PK-Sim Ontogeny Database Version 7.3](#main-references). The CYP2D6, CYP3A4 and UGT2B15 expression profiles are based on high-sensitive real-time RT-PCR [Nishimura 2013](#main-references). The t1/2 for CYP3A4 was decreased from the default 37h to 36h and the reference concentration for UGT2B15 was increased from 1 µmol/L to 2.48 µmol/L for a better fit of the clinical data.

Because the CYP2D6 gene is prone to genetic alterations, dextromethorphan pharmacokinetics is subject to considerable drug-gene interaction (DGI) effects.
 For DGI modeling, the CYP2D6 Michaelis-Menten constant(K<sub>M</sub>) values for the dextromethorphan O-demethylation were kept constant over the whole range of modeled activity scores [Rüdesheim 2020](#main-references). CYP2D6 k<sub>cat</sub> values were optimized separately for each activity score. CYP2D6 poor metabolizers (PMs) (activity score = 0) were assumed to show no CYP2D6 activity (0%), whereas populations with two wildtype alleles (activity score = 2) were assumed to possess normal CYP2D6 activity (100%). Activity scores were assigned according to Caudle et al. 2017 [Caudle 2017](#main-references), see also table below. IM = intermediate metabolizers, NM = normal metabolizers and UM = ultra rapid metabolizer.

| Activity Score  | Projected | k<sub>cat</sub> -> dxt | k<sub>cat</sub> percentage of |
|                 | Phenotype | (1/min)           | Reference (AS = 2) (%) |
| --------------- | --------- | ----------------- | ---------------------- |
| 0               | PM        | 0.0               | 0                      |
| --------------- | --------- | ----------------- | ---------------------- |
| 0.25            |           | 5.3               | 2                      |
| 0.5             | IM        | 32.9              | 14                     |
| 1               |           | 96.6              | 40                     |      
| --------------- |---------- | ----------------- | ---------------------- |
| 1.25            |           | 115.2             | 48                     |
| 1.5             | NM        | 151.8             | 63                     |
| 2               |           | 242.5             | 100                    |
| --------------- | --------- | ----------------- | ---------------------- |
| 3               | UM        | 413.2             | 170                    |
