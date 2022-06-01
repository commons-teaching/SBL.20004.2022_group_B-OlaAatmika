# Metabolomics analysis report
SBL.20004 

18.05.2022

----
Group X
- Abdelrahman Ola
- Brave Aatmika
----


## Introduction

Some words on the backgorund of your projects.
Which plants did you select and why ?

Project: Metabolomics of 15 Gesneriaceae species 

Aim: We aim to perfrom metabolomics on Gesneriaceae family to find the medicinal bio-active substances


## Material & Methods

### Sample collection

- Where we the plants collected ? 
- Which species were collected ? 
- Link to the iNaturalist entries of your species.

You can link a csv that you upload on github.
Go to the export link of the DBGI project on inaturalist https://www.inaturalist.org/observations/export?projects=digital-botanical-gardens-initiative
Apply eventual filters (fo rexample by username)
Save the csv and upload to github.

Sampling 
* We cut around 2 small leaves from each plant (15 plants)
* We put the samples in coffee filter and sealed them in ziplock bags
* We used silica gel for drying and kept them for 2 weeks.

Sample details: 

sample name                                Weight
Saintpaulia ionantha                        52 mg
Saintpaulia grotei                          50 mg 
Streptocarpus sp.2007- 547- 626             51 mg
Kohleria hirsuta                            49 mg
Streptocarpus sp.433                        52 mg
Streptocarpus caulescens                    55 mg
Columnea hirta                              54 mg 
Columnea microcalyx                         51 mg
Episcia punctate                            50 mg
Aeschynanthus longicaulis                   55 mg
Aeschynanthus fulgens                       49 mg 
Aeschynanthus radicans                      53 mg
Sinningia cardinalis                        51 mg
Sinningia leucotricha                       53 mg
Kohleria digitaliflora                      50 mg

Example see [table X](https://github.com/commons-teaching/SBL.20004.2022/blob/main/data/observations-238383.csv) 

### Sample preparation

A Solid Liquid extraction was performed to the dried samples using solvents mixture of Methanol : H2O : Formic Acid (80 : 20 : 0.1). We weighed ~ 50 mg of each sample and put it in a clean 2 ml Eppendorf tubes, then 3 metal beads were put per sample tube, in addition to one empty tube which was considered as a blank. the samples were completely freezed using liquid nitrogen before grinding them with Retsch mixer mill at 30 Hz for 3 mins. 1.7 ml of Methanol : H2O : Formic Acid (80 : 20 : 0.1) were added to each tube, the samples were mixed with the solvent mixture for using Retsch mixer mill for 3 minutes at 30 Hz. We centrifuged the extracts at 14000 rpm for 3 mins, the supernatants (~ 1.3 ml) were transferred carefully to clean labelled glass vials, we covered the vials with slotted screw caps, and Stored them in -80° C degrees. 

### LCMS Analysis

The samples were injected on Liquid Chromatography coupled with Mass Spectrometry system as follows:

* LC part conditions:
---- Overview ----
Name: New Instrument Method
Comment: 
Run time: 12.000 [min]
Instrument: Vanquish on qexactiveplus
Description: 
---- Script ----
initial     Instrument Setup
            ColumnComp.PrehtLeft.ReadyTempDelta: 1.00 [°C]
            ColumnComp.PrehtLeft.TempCtrl: On
            ColumnComp.PrehtLeft.Temperature.Nominal: 40.00 [°C]
            ColumnComp.PrehtLeft.EquilibrationTime: 1.0 [min]
            ColumnComp.CC.Mode: StillAir
            ColumnComp.CC.ReadyTempDelta: 1.00 [°C]
            ColumnComp.CC.TempCtrl: On
            ColumnComp.CC.Temperature.Nominal: 40.00 [°C]
            ColumnComp.CC.EquilibrationTime: 1.0 [min]
            ColumnComp.Column_A.SystemPressure: "Pump"
            ColumnComp.Column_B.ActiveColumn: No
            ColumnComp.Column_B.SystemPressure: "Pump"
            ColumnComp.Column_C.ActiveColumn: No
            ColumnComp.Column_C.SystemPressure: "Pump"
            ColumnComp.Column_D.ActiveColumn: No
            ColumnComp.Column_D.SystemPressure: "Pump"
            SamplerModule.Sampler.PunctureOffset: 0 [µm]
            SamplerModule.Sampler.WashSpeed: 10.0 [µl/s]
            SamplerModule.Sampler.InjectWashMode: Both
            SamplerModule.Sampler.WashTime: 2.0 [s]
            SamplerModule.Sampler.DispenseSpeed: 5.000 [µl/s]
            SamplerModule.Sampler.DrawSpeed: 5.000 [µl/s]
            SamplerModule.Sampler.Pump: "Pump"
            SamplerModule.TempCtrl: On
            SamplerModule.Temperature.Nominal: 10.0 [°C]
            PumpModule.Pump.%B_Selector: %B1
            PumpModule.Pump.%A_Selector: %A1
            PumpModule.Pump.%A1_Equate: "H2O"
            PumpModule.Pump.%A2_Equate: "%A2"
            PumpModule.Pump.%A3_Equate: "%A3"
            PumpModule.Pump.%B1_Equate: "ACN"
            PumpModule.Pump.%B2_Equate: "%B2"
            PumpModule.Pump.%B3_Equate: "%B3"
            PumpModule.Pump.Pressure.LowerLimit: 0 [bar]
            PumpModule.Pump.Pressure.UpperLimit: 1000 [bar]
            PumpModule.Pump.MaximumFlowRampUp: 6.00 [ml/min²]
            PumpModule.Pump.MaximumFlowRampDown: 6.00 [ml/min²]
0.000 [min] Inject Preparation
            Wait ColumnComp.Ready And SamplerModule.Sampler.Ready And PumpModule.Pump.Ready
0.000 [min] Inject
            SamplerModule.Sampler.Inject 
0.000 [min] Start Run
            ColumnComp.CC_Temp.AcqOn 
            ColumnComp.PrehtLeft_Temp.AcqOn 
            PumpModule.Pump.Pump_Pressure.AcqOn 
0.000 [min] Run
            PumpModule.Pump.Flow.Nominal: 0.600 [ml/min]
            PumpModule.Pump.%B.Value: 5.0 [%]
            PumpModule.Pump.Curve: 5
6.000 [min]
            PumpModule.Pump.Flow.Nominal: 0.600 [ml/min]
            PumpModule.Pump.%B.Value: 100.0 [%]
            PumpModule.Pump.Curve: 5
8.000 [min]
            PumpModule.Pump.Flow.Nominal: 0.600 [ml/min]
            PumpModule.Pump.%B.Value: 100.0 [%]
            PumpModule.Pump.Curve: 5
8.100 [min]
            PumpModule.Pump.Flow.Nominal: 0.600 [ml/min]
            PumpModule.Pump.%B.Value: 5.0 [%]
            PumpModule.Pump.Curve: 5
10.000 [min]
            PumpModule.Pump.Flow.Nominal: 0.600 [ml/min]
            PumpModule.Pump.%B.Value: 5.0 [%]
            PumpModule.Pump.Curve: 5
12.000 [min] Stop Run
            ColumnComp.CC_Temp.AcqOff 
            ColumnComp.PrehtLeft_Temp.AcqOff 
            PumpModule.Pump.Pump_Pressure.AcqOff 


- MS conditions: 
Method of Q Exactive Plus
 
OVERALL METHOD SETTINGS
 
Global Settings
Use lock masses                                                         best 
Lock mass injection                                                        ― 
Chrom. peak width (FWHM)                                                   5 s
Time
Method duration                                                         8.00 min
Customized Tolerances (+/-)
Lock Masses                                                                ― 
Inclusion                                                                  ― 
Exclusion                                                                  ― 
Neutral Loss                                                               ― 
Mass Tags                                                                  ― 
Dynamic Exclusion                                                          ― 
 
 
                                   Experiment
 
FULL MS / DD-MS² (TOPN)
General
Runtime                                                               0 to 8 min
Polarity                                                            positive 
In-source CID                                                            0.0 eV
Default charge state                                                       1 
Inclusion                                                                  ― 
Exclusion                                                                  ― 
Tags                                                                       ― 
Full MS
Microscans                                                                 1 
Resolution                                                            35,000 
AGC target                                                               3e6 
Maximum IT                                                               100 ms
Number of scan ranges                                                      1 
Scan range                                                       100 to 1200 m/z
Spectrum data type                                                  Centroid 
dd-MS² / dd-SIM
Microscans                                                                 1 
Resolution                                                            17,500 
AGC target                                                               1e5 
Maximum IT                                                                50 ms
Loop count                                                                 4 
MSX count                                                                  1 
TopN                                                                       4 
Isolation window                                                         1.0 m/z
Isolation offset                                                         0.0 m/z
Scan range                                                       200 to 2000 m/z
Fixed first mass                                                           ― 
(N)CE / stepped (N)CE                                        nce: 15, 30, 45 
Spectrum data type                                                  Centroid 
dd Settings
Minimum AGC target                                                    8.00e3 
Intensity threshold                                                    1.6e5 
Apex trigger                                                               ― 
Charge exclusion                                                           ― 
Multiple charge states                                                   all 
Peptide match                                                              ― 
Exclude isotopes                                                          on 
Dynamic exclusion                                                        2.0 s
If idle ..                                                do not pick others 
 
                                     Setup
 
TUNEFILES
General
Switch Count  0
Base Tunefile C:\Xcalibur\methods\600_default.mstune
 
CONTACT CLOSURE
General
Used            False 
Start in Closed  True 
Switch Count        0 
 
SYRINGE
General
Used                  False 
Start in OFF           True 
Stop at end of run    False 
Switch Count              0 
Pump setup
Syringe type       Hamilton 
Flow rate             3.000 µL/min
Inner diameter        2.303 mm
Volume                  250 µL
 
DIVERT VALVE A
General
Used         False 
Start in 1-2  True 
Switch Count     0 
 
DIVERT VALVE B
General
Used         False 
Start in 1-2  True 
Switch Count     0 
 
LOCK MASSES
    1 entry
     Mass Polarity Start   End Comment
    [m/z]          [min] [min] 
391.28429 Positive             
 
INCLUSION LIST
   (no entries)
 
EXCLUSION LIST
    128 entries
     Mass Formula Species  CS Polarity Start   End Comment
    [m/z]     [M]         [z]          [min] [min] 
100.07620                     Positive             
102.01340                     Positive             
103.95580                     Positive             
107.06080                     Positive             
108.06860                     Positive             
110.02030                     Positive             
110.07160                     Positive             
111.02050                     Positive             
111.09200                     Positive             
112.01820                     Positive             
112.08720                     Positive             
113.07120                     Positive             
113.96400                     Positive             
114.09160                     Positive             
116.96640                     Positive             
121.06420                     Positive             
122.07150                     Positive             
123.07960                     Positive             
124.08710                     Positive             
128.95090                     Positive             
130.00810                     Positive             
130.96650                     Positive             
131.53360                     Positive             
135.07940                     Positive             
136.08700                     Positive             
137.98730                     Positive             
138.99530                     Positive             
139.96350                     Positive             
139.98220                     Positive             
139.98790                     Positive             
140.08190                     Positive             
141.95870                     Positive             
143.03960                     Positive             
144.98220                     Positive             
145.98540                     Positive             
146.98030                     Positive             
149.02330                     Positive             
149.02330                     Positive             
149.05980                     Positive             
149.08220                     Positive             
149.95270                     Positive             
154.99020                     Positive             
156.99060                     Positive             
158.00290                     Positive             
158.15400                     Positive             
158.96140                     Positive             
161.08230                     Positive             
162.90700                     Positive             
162.99810                     Positive             
163.09780                     Positive             
163.13280                     Positive             
167.01290                     Positive             
167.97710                     Positive             
170.09650                     Positive             
171.14920                     Positive             
171.99290                     Positive             
174.12780                     Positive             
176.10580                     Positive             
180.98990                     Positive             
181.98810                     Positive             
182.02910                     Positive             
182.98520                     Positive             
182.98530                     Positive             
183.07830                     Positive             
184.98560                     Positive             
186.95630                     Positive             
186.98100                     Positive             
190.99310                     Positive             
193.98920                     Positive             
195.99360                     Positive             
199.18060                     Positive             
199.98800                     Positive             
201.00840                     Positive             
204.13850                     Positive             
210.02410                     Positive             
217.95960                     Positive             
219.19550                     Positive             
223.98850                     Positive             
224.07610                     Positive             
224.12820                     Positive             
226.01210                     Positive             
226.95150                     Positive             
228.19580                     Positive             
229.05510                     Positive             
236.16760                     Positive             
236.22210                     Positive             
244.19070                     Positive             
246.24280                     Positive             
252.07100                     Positive             
256.26330                     Positive             
266.12300                     Positive             
273.25370                     Positive             
274.27410                     Positive             
279.09340                     Positive             
279.15910                     Positive             
282.27910                     Positive             
284.91090                     Positive             
287.88880                     Positive             
290.26900                     Positive             
298.31050                     Positive             
302.30540                     Positive             
310.31040                     Positive             
314.30530                     Positive             
322.22240                     Positive             
326.34170                     Positive             
328.91540                     Positive             
338.34170                     Positive             
342.33670                     Positive             
352.23310                     Positive             
368.42520                     Positive             
371.31570                     Positive             
382.24360                     Positive             
386.25380                     Positive             
387.19890                     Positive             
393.29740                     Positive             
412.25420                     Positive             
414.35780                     Positive             
442.26470                     Positive             
472.27530                     Positive             
476.32920                     Positive             
502.28580                     Positive             
604.38460                     Positive             
607.39360                     Positive             
609.33970                     Positive             
625.31340                     Positive             
632.41570                     Positive             
663.45350                     Positive             
680.48010                     Positive             
 
NEUTRAL LOSSES
   (no entries)
 
MASS TAGS
   (no entries)
© 2022 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About


### Data treatment

- Describe the software and parameters used.

## Results


### MS1

How many features could you clean in your final peak list ?
A link to the final feature list (uploaded to github).

### Molecular Network

Screenshots of your molecular network and of some clusters of interest.
Link to the GNPS job.
Link to the GNPS identification table.


## Conclusion

Some conclusion that you could get out of this preliminary study.

# References

Note that you can make a footnot like this [^1]

[^1]: Ref X
