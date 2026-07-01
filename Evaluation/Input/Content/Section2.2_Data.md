
### In vitro / physico-chemical Data Dextromethorphan

A literature search was performed to collect available information on physicochemical properties of dextromethorphan. The obtained information from literature is summarized in the table below and is used for model building. 

| **Parameter**| **Unit** | **Value** | **Source** | **Description**|
| :-----------------------------| -------- | ---------- | ------------------------------------------ | ----------------------------------------------- |
| MW                            | g/mol    |   271.41   | [Benet 2011](#references)             | Molecular weight                                |
| pK<sub>a</sub>                |          |   9.10     | [Spaggiari 2014](#references)         | Acid dissociation constant                      |
| Solubility (pH)               | g/L      |   15.00    | [Benet 2011](#references)             | Aqueous Solubility Hydrobromide                 |
| logP                          |          |   4.10     | [Spaggiari 2014](#references)        | Partition coefficient between octanol and water |
| fu                            | %        |   35.00    | [Lutz 2012](#references)              | Fraction unbound in plasma                      |
| CYP2D6 K<sub>m</sub> -> dxt   | µmol/L   |   4.65     | [Brown 2007](#references) [Lutz 2012](#references)| Michaelis Menten constant|
| CYP2D6 K<sub>cat</sub> -> dxt (PM) | 1/min |  0       | [Brown 2007](#references)              | Catalytic rate constant                        |
| CYP3A4 K<sub>m</sub>          | µmol/L   |   176.80   | [Lutz 2012](#references)              | Michaelis Menten constant                       |
  
### In vitro / physico-chemical Data Dextrorphan <a id="invitro-and-physico-chemical-data-dextrorphan"></a>

A literature search was performed to collect available information on physicochemical properties of dextrorphan. The obtained information from literature is summarized in the table below and is used for model building. 

| **Parameter**| **Unit** | **Value** | **Source** | **Description**|
| :-----------------------------| -------- | ---------- | ------------------------------------------ | ----------------------------------------------- |
| MW                            | g/mol    |   257.37   | [HMDB-a](#references),[Wishart 2018](#references)           | Molecular weight                                |
| pK<sub>a</sub> strongest acidic|         |   10.10    | [Spaggiari 2014](#references)         | Acid dissociation constant                      |
| logP                          |          |   2.90     | [Kim 2019](#references)               | Partition coefficient between octanol and water |
| fu                            | %        |   42.00    | [Watanabe 2018](#references)          | Fraction unbound in plasma                      |
| UGT2B15 K<sub>m</sub> -> dxt-glu   | µmol/L | 184.8   | [Lutz 2012](#references)              | Michaelis Menten constant                       |
| CYP3A4 K<sub>m</sub>          | µmol/L   |   910.00   | [Lutz 2012](#references)              | Michaelis Menten constant                       |
| CYP3A4 K<sub>cat</sub>        | 1/min    |  7.41      | [Lutz 2012](#references)| Catalytic rate constant|

### In vitro / physico-chemical Data Dextrorphan O-glucuronide <a id="invitro-and-physico-chemical-data-dextrorphan O-glucuronide"></a>

A literature search was performed to collect available information on physicochemical properties of dextrorphan O-glucuronide. The obtained information from literature is summarized in the table below and is used for model building. 

| **Parameter**| **Unit** | **Value** | **Source** | **Description**|
| :-----------------------------| -------- | ---------- | ------------------------------------------ | ----------------------------------------------- |
| MW                            | g/mol    |   433.5    | [Wishart 2018](#references)| Molecular weight|
| logP                          |          |   0.29     | [HMDB-b](#references), [Wishart 2018](#references) | Partition coefficient between octanol and water |
| pK<sub>a</sub> strongest basic|          |   9.82     | [Wishart 2018](#references)           | Acid dissociation constant                      |
| pK<sub>a</sub> strongest acidic|         |   2.85     | [Wishart 2018](#references)           | Acid dissociation constant                      |
| Solubility                    | g/L      |   1.20     | [Wishart 2018](#references)           | Solubility|
| fu                            | %        |   37.00    | Calculated [Watanabe 2018](#references)| Fraction unbound in plasma                     |

### Clinical Data  <a id="clinical-data"></a>

A literature search was performed to collect available clinical data on dextromethorphan in healthy adults.

#### Base Model Building <a id="base-model-building"></a>

The following studies were used for model building (training data):

| **Publication** | **Study description**|
| :-------------------------- | :----------------------- |
| [Duedahl 2005](#references) | CYP2D6 EM Subjects with an single IV infusion of 0.5 mg/kg for 30 min  |
| [Schadel 1995](#references) | CYP2D6 EM and PM Subjects with a single PO dose of 30 mg |
| [Tennezé 1999](#references) | CYP2D6 EM subjects with a single PO dose of 80 mg | 

EM: extensive
metabolizer, PM: poor metabolizer, PO: oral administration.

#### Base Model Verification <a id="base-model-verification"></a>

The following studies were used for model verification:

| **Publication** | **Study description**|
| :-------------------------- | :----------------------- |
| [Feld 2013](#references) | CYP2D6 EM subjects with a single PO dose of 60 mg   |
| [AntecipBioventuresLLC](#references)| CYP2D6 EM subjects with twice daily PO doses of 60 mg bid|
| [Armani 2017](#references)| CYP2D6 EM subjects with a single PO dose of 30 mg |
| [Dumond 2010](#references)| CYP2D6 EM subjects with a single PO dose of 30 mg |              
| [Edwards 2017](#references)| CYP2D6 EM subjects with a single PO dose of 30 mg | 
| [Ermer 2015](#references)| CYP2D6 EM subjects with a single PO dose of 30 mg | 
| [Kakuda 2014](#references)| CYP2D6 EM subjects with a single PO dose of 30 mg |
| [Khalilieh 2018](#references)| CYP2D6 EM subjects with a single PO dose of 30 mg |
| [Nakashima 2007](#references)| CYP2D6 EM subjects with a single PO dose of 30 mg |
| [Nyunt 2008](#references)| CYP2D6 EM subjects with a single PO dose of 30 mg |
| [Sager 2014](#references)| CYP2D6 EM subjects with a single PO dose of 30 mg |
| [Stage 2018](#references)| CYP2D6 EM subjects with a single PO dose of 30 mg |

EM: extensive
metabolizer, PO: oral administration.

#### DGI Model Building <a id="dgi-model-building"></a>

The following studies were used for model building (training data):

| **Publication** | **Study description**|
| :-------------------------- | :----------------------- |
| [Qiu 2016](`#references`) | CYP2D6 NM and IM Subjects with a single PO dose of 15 mg |

IM: intermediate
metabolizer, NM: normal metabolizer, PO: oral administration.

#### DGI Model Verification <a id="dgi-model-verification"></a>

The following studies were used for model verification:

| **Publication** | **Study description**|
| :-------------------------- | :----------------------- |
| [Capon 1996](#references) | CYP2D6 EM and PM subjects with a single PO dose of 30 mg   |
| [Gazzaz 2018](#references)| CYP2D6 NM subjects with a single PO dose of 30 mg|
| [Gorski 2004](#references)| CYP2D6 EM and PM subjects with a single PO dose of 30 mg|              
| [Yamazaki 2017](#references)| CYP2D6 NM and IM subjects with a single PO dose of 30 mg| 
| [Storelli 2018](#references)| CYP2D6 EM subjects with a single PO dose of 5 mg| 
| [Zawertailo 2010](#references)| CYP2D6 NM subjects with a single PO dose of 3 mg/kg|

EM: extensive
metabolizer, NM: normal metabolizer, PM:
poor metabolizer, UM: ultrarapid metabolizer, PO: oral administration.
