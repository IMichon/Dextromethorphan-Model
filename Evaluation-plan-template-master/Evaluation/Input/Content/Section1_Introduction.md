
Dextromethorphan is a widely used over-the-counter cough suppressant and a common ingredient of cold medicines marketed toward children and adults.

Dextromethorphan is typically administered as its hydrobromide salt, which is considered a Biopharmaceutics Drug Disposition Classification System (BDDCS) class I drug with high solubility and permeability. After oral administration, dextromethorphan is rapidly absorbed. Dextromethorphan undergoes an extensive first-pass metabolism, predominately mediated by CYP2D6, reducing the bioavailability to 1%–2% in CYP2D6 extensive metabolizers (EMs) and 80% in CYP2D6 poor metabolizers (PMs). 

The herein presented model building and evaluation report evaluates the performance of the PBPK model for Dextromethorphan in (healthy) adults published by Rüdesheim et al. 2025 ([Rüdesheim 2025](#5-References)). 
A whole-body PBPK model of dextromethorphan and its metabolites dextrorphan and dextrorphan O-glucuronide was developed and evaluated to predict drug plasma concentrations over a wide dosing range (5–80mg).
Dextromethorphan is mainly metabolized via CYP2D6 and to a lesser extend  by CYP3A4. A CYP2D6 activity score-dependent metabolism of dextromethorphan was implemented to describe the effect of CYP2D6 drug-gene interaction (DGI) on the PK of the modeled compounds. 
Although dextromethorphan is rapidly absorbed from the intestine, time to reach peak plasma concentration Cmax (tmax) often occurs as late as 4h after oral administration. This phenomenon likely occurs due to lysosomal trapping of dextromethorphan in the intestinal mucosa. To emulate the effect of lysosomal trapping in the gastrointestinal mucosa, a surrogate protein binding partner was included in the model. 


Model features include:

Dextromethorphan:
metabolism by CYP2D6 and formation of the primary metabolite dextrorphan
metabolism by CYP3A4
passive glomerular filtration
lysosomal trapping mimicked by surrogate protein binding

Primary metabolite Dextrorphan:
metabolism by UGT2B15 into Dextrorphan-O-glucuronide
metabolism by CYP3A4

Secondary metabolite Dextrorphan-O-glucuronide:
passive glomerular filtration 
active secretion to urine

The presented COMPOUND PBPK model as well as the respective evaluation plan and evaluation report are provided open-source ([https://github.com/Open-Systems-Pharmacology/COMPOUND-Model](https://github.com/Open-Systems-Pharmacology/COMPOUND-Model)).

