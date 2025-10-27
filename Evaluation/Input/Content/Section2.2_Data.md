
### In vitro / physico-chemical Data Dextromethorphan <a id="invitro-and-physico-chemical-data Dextromethorphan"></a>

A literature search was performed to collect available information on physicochemical properties of dextromethorphan. The obtained information from literature is summarized in the table below and is used for model building. 

| **Parameter**                 | **Unit** | **Value**  | Source                                     | **Description**                                 |
| :-----------------------------| -------- | ---------- | ------------------------------------------ | ----------------------------------------------- |
| MW                            | g/mol    |   271.41   | [Benet 2011](#main-references)             | Molecular weight                                |
| pK<sub>a</sub>                |          |   9.10     | [Spaggiari 2014](#main-references)         | Acid dissociation constant                      |
| Solubility (pH)               | g/L      |   15.00    | [Benet 2011](#main-references)             | Aqueous Solubility Hydrobromide                 |
| logP                          |          |   4.10     | [Spaggiairi 2014](#main-references)        | Partition coefficient between octanol and water |
| fu                            | %        |   35.00    | [Lutz 2012](#main-references)              | Fraction unbound in plasma                      |
| CYP2D6 K<sub>m</sub> -> dxt   | µmol/L   |   4.65     | [Brown 2007](#main-references)| Michaelis Menten constant|
| CYP2D6 K<sub>cat</sub> -> dxt (PM) | 1/min |  0       | [Brown 2007](#main-references)              | Catalytic rate constant                        |
| CYP3A4 K<sub>m</sub>          | µmol/L   |   176.80   | [Lutz 2012](#main-references)              | Michaelis Menten constant                       |
  
### In vitro / physico-chemical Data Dextrorphan <a id="invitro-and-physico-chemical-data Dextrorphan"></a>

A literature search was performed to collect available information on physicochemical properties of Dextrorphan. The obtained information from literature is summarized in the table below and is used for model building. 

| **Parameter**                 | **Unit** | **Value**  | Source                                     | **Description**                                 |
| :-----------------------------| -------- | ---------- | ------------------------------------------ | ----------------------------------------------- |
| MW                            | g/mol    |   257.37   | [HMDB-a](#main-references),[Wishart 2018](#main-references)           | Molecular weight                                |
| logP|          |  1.38    | [Spaggiari 2014](#main-references)         | Acid dissociation constant                      |
| pK<sub>a</sub> strongest acidic|         |   10.10    | [Spaggiari 2014](#main-references)         | Acid dissociation constant                      |
| logP                          |          |   2.90     | [Kim 2019](#main-references)               | Partition coefficient between octanol and water |
| fu                            | %        |   42.00    | [Watanabe 2018](#main-references)          | Fraction unbound in plasma                      |
| UGT2B15 K<sub>m</sub> -> dxt-glu   | µmol/L | 184.8   | [Lutz 2012](#main-references)              | Michaelis Menten constant                       |
| CYP2D6 K<sub>cat</sub> -> dxt (PM) | 1/min    |  0    | [Brown 2007](#main-references)| Catalytic rate constant|
| CYP3A4 K<sub>m</sub>          | µmol/L   |   910.00   | [Lutz 2012](#main-references)              | Michaelis Menten constant                       |
| CYP3A4 K<sub>cat</sub>        | 1/min    |  7.41      | [Lutz 2012](#main-references)| Catalytic rate constant|

### In vitro / physico-chemical Data Dextrorphan O-glucuronide <a id="invitro-and-physico-chemical-data Dextrorphan O-glucuronide"></a>

A literature search was performed to collect available information on physicochemical properties of Dextrorphan O-glucuronide. The obtained information from literature is summarized in the table below and is used for model building. 

| **Parameter**                 | **Unit** | **Value**  | Source                                     | **Description**                                 |
| :-----------------------------| -------- | ---------- | ------------------------------------------ | ----------------------------------------------- |
| MW                            | g/mol    |   433.5    | [Wishart 2018](#main-references)| Molecular weight|
| logP                          |          |   1.38     | 
 [HMDB-b](#main-references), [Wishart 2018](#main-references)|Partition coefficient between octanol and water|
| pK<sub>a</sub> strongest basic|          |   9.82     | [Wishart 2018](#main-references)           | Acid dissociation constant                      |
| pK<sub>a</sub> strongest acidic|         |   2.85     | [Wishart 2018](#main-references)           | Acid dissociation constant                      |
| Solubility                    | g/L      |   1.20     | [Wishart 2018](#main-references)           | Solubility|
| fu                            | %        |   37.00    | Calculated [Watanabe 2018](#main-references)| Fraction unbound in plasma                     |

### Clinical Data  <a id="clinical-data"></a>

A literature search was performed to collect available clinical data on Dextromethorphan in healthy adults.

#### Base Model Building <a id="base model-building"></a>

The following studies were used for model building (training data):

**| Publication                 | Arm / Treatment / Information used for model building |**
| :-------------------------- | :---------------------------------------------------- |
| [Duedahl 2005](#main-references) | CYP2D6 EM Subjects with an single IV infusion of 0.5 mg/kg for 30 min  |
| [Schadel 1995](#main-references) | CYP2D6 EM and PM Subjects with a single PO dose of 30 mg |
| [Tennezé 1990](#main-references) | CYP2D6 EM subjects with a single PO dose of 80 mg | 

#### Base Model Verification <a id="base model-verification"></a>

The following studies were used for model verification:

**| Publication                 | Arm / Treatment / Information used for model building |**
| :-------------------------- | :---------------------------------------------------- |
| [Feld 2013](#main-references) | CYP2D6 EM subjects with a single PO dose of 60 mg   |
| [AntecipBioventuresLLC](#main-references)| CYP2D6 EM subjects with twice daily PO doses of 60 mg bid|
| [Armani 2017](#main-references)| CYP2D6 EM subjects with a single PO dose of 30 mg sd|
| [Dumond 2010](#main-references)| CYP2D6 EM subjects with a single PO dose of 30 mg sd|              
| [Edwards 2017](#main-references)| CYP2D6 EM subjects with a single PO dose of 30 mg sd| 
| [Ermer 2015](#main-references)| CYP2D6 EM subjects with a single PO dose of 30 mg sd| 
| [Kakuda 2014](#main-references)| CYP2D6 EM subjects with a single PO dose of 30 mg sd|
| [Khalilieh 2018](#main-references)| CYP2D6 EM subjects with a single PO dose of 30 mg sd|
| [Nakashima 2007](#main-references)| CYP2D6 EM subjects with a single PO dose of 50 mg sd|
| [Nyunt 2008](#main-references)| CYP2D6 EM subjects with a single PO dose of 30 mg sd|
| [Sager 2014](#main-references)| CYP2D6 EM subjects with a single PO dose of 30 mg sd|
| [Stage 2018](#main-references)| CYP2D6 EM subjects with a single PO dose of 30 mg sd|

#### DGI Model Building <a id="base model-building"></a>

The following studies were used for model building (training data):

**| Publication                 | Arm / Treatment / Information used for model building |**
| :-------------------------- | :---------------------------------------------------- |
| [Qiu 2016](#main-references) | CYP2D6 NM and IM Subjects with a single PO dose of 15 mg |

#### DGI Model Verification <a id="base model-verification"></a>

The following studies were used for model verification:
**
| Publication                 | Arm / Treatment / Information used for model building |**
| :-------------------------- | :---------------------------------------------------- |
| [Capon 1996](#main-references) | CYP2D6 EM and PM subjects with a single PO dose of 30 mg   |
| [Gazzaz 2018](#main-references)| CYP2D6 NM subjects with a single PO dose of 30 mg sd|
| [Gorski 2004](#main-references)| CYP2D6 EM and PM subjects with a single PO dose of 30 mg sd|              
| [Yamazaki 2017](#main-references)| CYP2D6 NM and IM subjects with a single PO dose of 30 mg sd| 
| [Storelli 2018](#main-references)| CYP2D6 EM subjects with a single PO dose of 5 mg sd| 
| [Zawertailo 2010](#main-references)| CYP2D6 NM subjects with a single PO dose of 3 mg/kg sd|
