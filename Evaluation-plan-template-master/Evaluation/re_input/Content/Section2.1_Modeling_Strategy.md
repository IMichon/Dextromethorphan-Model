The general concept of building a PBPK model has previously been described by Kuepfer et al. ([Kuepfer 2016](#5-references)) Regarding the relevant anthropometric (height, weight) and physiological parameters (e.g. blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in adults was gathered from the literature and has been previously published ([PK-Sim Ontogeny Database Version 7.3](#5-references)). The information was incorporated into PK-Sim® and was used as default values for the simulations in adults.

The  applied activity and variability of plasma proteins and active processes that are integrated into PK-Sim® are described in the publicly available PK-Sim® Ontogeny Database Version 7.3 ([Schlender 2016](#5-references)) or otherwise referenced for the specific process.

The dextromethorphan PBPK model was developed using a total of 28 clinical studies where dextromethorphan was administered as an intravenous infusion (one study), orally in single (26 studies), or multiple doses (one study), alone (17 studies) or as part of a phenotyping cocktail (11 studies). Doses ranged between 5 and 80 mg of administered dextromethorphan.
The PBPK model was built based on data from healthy individuals, using the reported sex, ethnicity and mean values for age, weight and height from each study protocol. If no demographic information was provided, the following default values were substituted: male, European, 30 years of age, 73 kg body weight and 176 cm body height (characteristics from the PK-Sim® population database). CYP2D6 was implemented in accordance with literature, using the
PK-Sim® expression database to define their relative expression in the different organs of the body.
First a base model was built using clinical data from a study where dextromethorphan was administered as an intravenous infusion ([Duedahl 2004](#5-references)) and oral administration from 3 clinical studies. The base model was further verified using 12 additional clinical studies. Next, the model was further develped using a DGI training dataset consisting of four studies that reported CYP2D6 activity scores or genotypes of theirrespective study populations. To complement these studies, 24 individual plasma concentration-time profiles were included. Overall, activity scores in the DGI model training dataset ranged from 0 (poor metabpolizer PM) to 3 (ultrarapid metabolizer UR) and covered a total of eight activity scores. This dataset was used to optimize population kcat values for the activity scores of the respective studies or individual profiles



Unknown parameters (see below) were identified using the Parameter Identification module provided in PK-Sim®. Structural model selection was mainly guided by visual inspection of the resulting description of data and biological plausibility.

Once the appropriate structural model was identified, additional parameters for tablet formulations were identified. 

The model was then verified by simulating:

- ...

Details about input data (physicochemical, *in vitro* and clinical) can be found in  [Section 2.2](#methods-data).

Details about the structural model and its parameters can be found in  [Section 2.3](#model-parameters-and-assumptions).

