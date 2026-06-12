This ReadMe_Hua.txt file was generated on 2025-12-09 by Jason Hua.

This ReadMe_Hua.txt file was updated on 2026-03-05 by Jason Hua.


---------------------------------------
GENERAL INFORMATION
---------------------------------------

Title of Dataset: TITLE

Contributor information:

Jason B.X. Hua 
University of Iowa - Department of Civil & Environmental Engineering
Iowa Superfund Research Program (ISRP)
bao-hua@uiowa.edu
ORCID: 0000-0003-1888-2796

Rachel F. Marek, PhD
University of Iowa - Department of Civil & Environmental Engineering
Iowa Superfund Research Program (ISRP)
rachel-f-marek@uiowa.edu
ORCID: 0000-0002-7898-2900

Lillian Montabon
University of Iowa - Department of Civil & Environmental Engineering
Iowa Superfund Research Program (ISRP)
lillian-montabon@uiowa.edu
ORCID: 

Keri C. Hornbuckle, PhD
University of Iowa - Department of Civil & Environmental Engineering
Iowa Superfund Research Program (ISRP)
keri-hornbuckle@uiowa.edu
ORCID: 0000-0002-3478-3221

Principal Investigator: Keri C Hornbuckle
Principal Investigator email: keri-hornbuckle@uiowa.edu

Date of data collection <YYY-MM-DD>: 202X-XX-XX - 2025-XX-XX

This study is supported by the Department of Environmental Conservation of the State of Vermont, the Vermont Environmental Public Health Tracking Program funded by the Centers for Disease Control and Prevention (Cooperative Agreement: NUE1EH001361-05), and by the National Institute of Environmental Health Sciences of the National Institutes of Health (NIEHS/NIH) under award number P42ES013661. The CDC and NIEHS/NIH did not have any role in study design; in collection, analysis, and/or interpretation of data; in creation of the dataset; and/or in the decision to submit this data for publication or deposit it in a repository.

Subject: PUF-PES, emissions, schools, building materials, semivolatile organic compounds, persistent organic pollutants, legacy compounds, Aroclors, indoor air, PCBs

--------------------------
SHARING/ACCESS INFORMATION
--------------------------

Licenses/restrictions placed on the data, or limitations of reuse: 
This dataset is made available under the Open Data Commons Attribution License (v1.0). You are free to share (to copy, distribute and use the dataset), to create (to produce works from the dataset), to adapt (to modify, transform and build upon the dataset) as long as you attribute (you must attribute any public use of the dataset, or works produced from the dataset, in the manner specified in the license. For any use or redistribution of the dataset, or works produced from it, you must make clear to others the license of the dataset and keep intact any notices on the original dataset). For full license please see here, https://opendatacommons.org/licenses/by/1-0/.

Recommended citation for the data:

Hua, J.B.X.; Marek, R.F.; Hornbuckle, K.C. "TITLE" Iowa Research Online. 2026. https://doi.org/

Citation for and links to publications that cite or use the data:

Hua, J.B.X.; Marek, R.F.; Hornbuckle, K.C. "TITLE" Iowa Research Online. 202X. https://doi.org/10.XXXXXX

--------
ABSTRACT
--------

This dataset describes.... 

--------------------
DATA & FILE OVERVIEW
--------------------

"ReadMe_Hua.txt" is this readme file.

"blankMass.csv" (174 columns x XXX rows) - Mass in field blanks (FB) and lab blanks (LB) in ng for individual PCB congeners or co-eluting congeners obtained from 31 field blanks and 73 lab blanks PUF analyzed as samples using GC-MS/MS. These masses have been corrected by surrogate standards. The total mass for each blank is included in the last column called "sum".

"sampleMass.csv" (175 columns x XXX rows) - Mass in air samples and emission samples in ng for individual PCB congeners or co-eluting congeners obtained from 78 air and 133 emission PUF analyzed as samples using GC-MS/MS. These masses were corrected by surrogate standards. The total mass for each sample is included in the last column called "sum".

"concentrations.csv" (175 columns x XXX rows) - Concentrations for each air sample in ng m-3 for individual PCB congeners or co-eluting congeners. These were calculated by dividing the congener mass by the product of the sampler surface (m2) and the deployment time (d).The total concentration for each sample is included in the last column called "sum".

"emissions.csv" (175 columns x XXX rows) - Emissions for each emission sample in ng m-2 d-1 for individual PCB congeners or co-eluting congeners. These were calculated by dividing the congener mass by the product of the sampler surface (m2) and the deployment time (d).The total emissions for each sample is included in the last column called "sum".

"pcb_identifiers.csv" (7 columns x 210 rows) - Names and identifiers for individual congeners.

"recoveries.csv" (11 columns x XXX rows) - Surrogate recovery percentages for each field blank, lab blank, air sample, and emission sample.

[edit] "sampleType.csv" (10 columns x 255 rows) - Location and material descriptions for each sample. "bid" is the batch identification code used during sample extraction. "sid" is the unique sample identification code. "sample.type" denotes whether the sample was an air sample, emission sample, field blank, or lab blank. "room" contains room names assigned at the time of sampling. "materials" specifies the air or surface type where samplers were placed. "schid" is an identification code assigned to each school at the time of analysis. "samplingRound" denotes during which sampling round samples were deployed and collected at a particular school. "remediation" denotes the state of the air or surface (pre, interim, post) at the time of sampling. Pre: pre-remediation, the original material is still in place and no major corrective actions have been performed. Interim: some corrective action have been performed as a temporary measure prior to full remediation work. Post: post-remediation, major work has been completed including deep cleaning, complete removal of sources, and encapsulation. "samplingStart" is the date of sampler deployment given as YYYY-MM-DD. "samplingEnd" is the date samplers were collected given as YYYY-MM-DD. 

"FILE.csv" (XX columns x YY rows) - [material type descriptions/summary?]



--------------------
ABBREVIATIONS
--------------------

°C: degrees Celsius
µm: micrometer
13C: carbon 13 labeled
Cl: chlorine
CMU: concrete masonry unit
d: day
DEC: Department of Environmental Conservation
FB: field blank
GC: gas chromatography
ID: identification number or code
LB: lab blank
LOQ: limit of quantification
m: meter
m2: meters squared
m3: meters cubed
mg: milligram
min: minute
mL: milliliter
mm: millimeter
MRM: multiple reaction monitoring
MS: mass spectrometry
ng: nanogram
PCB: polychlorinated biphenyl
psi: pounds per square inch
PUF: polyurethane foam
PUF-PAS: polyurethane foam passive air sampler
PUF-PES: polyurethane foam passive emission sampler
RM: room
rm_id: room identification code
RRF: relative response factor
Rs: sampling rate
s: seconds
S###: sample ID unique for each sample - letter "S" followed by three digits
SCH: school
sch_id: school identification code
sid: sample identification code 
ss: surrogate standard
UHP: ultra high purity (99.999%)
UI: University of Iowa
Veff: effective volume
VT: Vermont

--------------------------
METHODOLOGICAL INFORMATION
--------------------------

Description of methods used for collection/generation of data: 

Sample media precleaning:

Before deployment, we cleaned each PUF (Tisch Environmental, Cleves, Ohio, Part # TE-1014) with 1:1 hexane acetone solution and wrapped it in aluminum foil once dry to preserve for deployment in a 4°C refrigerator used only for storing cleaned sample media.

Sample collection:

We collected samples at 16 Vermont schools. Ninety-eight classrooms were sampled for airborne PCBs and PCB emissions. We used Harner style double dome polyurethane foam passive air samplers (PUF-PAS) and polyurethane foam passive emission samplers (PUF-PES) to sample for gas phase PCBs inside the school and PCB emissions from surfaces in classrooms. We deployed each sampler for 2 - 5 weeks.

Sample extraction and instrument analysis:

We used accelerated solvent extraction with acetone and hexane (1:1 v/v) to extract PCBs from PUF samples. During ASE preparation, 9.84 ng of surrogate standard 13C labeled PCBs (3, 15, 31, 52, 118, 153, 180, 194, 206, 209; Wellington Labs, Guelph, Ontario) were added to the PUF to allow for corrections due to analytical losses and variability. Recoveries of 13C labeled surrogate standards were used to correct masses of corresponding homologs. Turbulent evaporation with nitrogen (Biotage TurboVap II Automated Solvent Evaporation System) was used to concentrate extracts. Extracts were cleaned by sulfuric acid silica gel columns. Samples were then concentrated again, transferred to 2 mL glass autosampler vials, and spiked with 10.06 ng of internal standard d-PCB 30 (2,4,6-trichlorobiphenyl-2’,3’,4’,5’,6’-d5, C/D/N Isotopes, Pointe-Claire, Quebec) and internal standard PCB 204 (2,2’,3,4,4’,5,6,6’-octachlorobiphenyl, AccuStandard, New Haven, Connecticut). Gas chromatography tandem mass spectrometry (Agilent 7000 Triple Quad with Agilent 7890A GC and Agilent 7693 autosampler) in multiple reaction monitoring mode (MRM) was used for identiﬁcation and quantiﬁcation of 209 PCBs as 173 chromatographic peaks. Information about the GC and MS instrument parameters are in the Supporting Information. We quantified PCBs using a calibration standard (AccuStandard) containing all 209 PCBs (25 ng mL-1 of mono- through trichlorinated congeners, 50 ng mL-1 tetra- through heptachlorinated congeners, and 75 ng mL-1 octa- through decachlorinated congeners) and the surrogate (13C PCB 3, 15, 31, 52, 118, 153, 180, 194, 206, 209) and internal (d-PCB 30 and PCB 204) standard. We used hexane blanks pre- and post-calibration run and after sample runs to ensure no carryover. We identified PCBs by comparing samples with the same MRM transition according to retention time (+/- 0.07 min) except where peak shape or surrogate standard shift dictated otherwise.

The GC was equipped with a Supelco SPB-Octyl capillary column (Poly(50% n-octyl/50% methyl siloxane, 30 m × 0.25 mm ID, 0.25 µm film thicknesses)) with UHP helium as the carrier gas (0.8 mL/min) and UHP nitrogen as the collision gas (1.5 mL/min). The GC operated in solvent vent injection mode at the following injection conditions: initial temperature 45 °C, initial time 0.06 min, ramp 600 °C/min to inlet temperature 325 °C at 4.4 psi. The GC oven temperature program was 45 °C for 2 min, 45 to 75 °C at 100 °C/min and hold for 5 min, 75 to 150 °C at 15 °C/min and hold for 1 min, 150 to 280 at 2.5 °C/min and final hold 5 min (total run time 70.86 min). The triple quadrupole MS electron ionization source was set to 260 °C. The MS-MS operated with the precursor-product transitions in Table 1.

Table 1. PCB precursor and product masses of unlabeled and deuterated calibration standards used in multiple reaction monitoring (MRM) mode on the triple quadrupole mass spectrometer.

Cl homolog	Precursor Mass	Product Mass
mono		188		153.1
di		222		152.1
tri		256		186
tetra		291.9		222
penta		325.9		255.9
hexa		359.8		289.9
hepta		393.8		323.9
octa		429.8		359.8
nona		463.7		393.8
deca		497.7		427.7
D5 tri		261		191.1
13C mono	200.1		165.1
13C di		234		164.1
13C tri		268		191.8
13C tetra	304		234
13C penta	337.9		268
13C hexa	371.9		301.9
13C hepta	405.8		335.9
13C octa	429.8		359.8
13C nona	475.8		405.8
13C deca	509.7		439.8

Method for Processing the Raw Data:

Raw data were collected as ".D" data files generated by Agilent Mass Hunter Data Acquisition software version 10.1.49 (2021), processed using Agilent Qualitative Analysis version 10.0 (2018) by manual drawing of each chromatogram peak's baseline and the software's subsequent automatic calculation of peak areas.

Peak areas were transformed into mass using a congener-specific relative response factor (RRF) as follows:

RRF for each congener=(mass in calibration standard/peak area in calibration standard)/(mass of internal standard in calibration standard/peak area of internal standard in calibration standard)

mass in sample for each congener=RRF*peak area in sample*(mass of internal standard in sample/peak area of internal standard in sample)

Internal standard d-PCB30 was used in RRF and mass calculations for chlorine homologs 1-5, and internal standard PCB204 was used in RRF and mass calculations for chlorine homologs 6-10.

Quality Assurance/Quality Control:

We assessed the quality of our data by considering measures of accuracy, precision, reproducibility, representativeness, and comparability. LOQ was calculated as the upper limit of the 99th confidence interval of the log 10 transformed blank masses: average congener mass in blank PUF samples plus 2.325 times the standard deviation divided by the square root of n. Method blanks (n=XX) and field blanks (n=XX), which approximated a log normal distribution, are included in calculations of the LOQ. Congener masses are reported as measured and not replaced with different values when below LOQ. LOQ values ranged from 0.003 to 0.4 ng per congener. Accuracy of our methods were assessed using standard reference material analysis of certified PCB concentrations in house dust sprinkled on PUF (NIST, SRM 2585, Gaithersburg, Maryland). We corrected sample masses for surrogate recoveries below 100%. 

Sample Volume:

Effective sampling volume is the volume of air passing through the PUF during the time of deployment. Congener-specific effective sampling volumes (V_eff, m3) were calculated as a function of the partitioning coefficient (KPUF, unitless), the volume of the PUF (VPUF, m3), the deployment time (t, d), and the sampling rate (Rs, m3 d-1).

V_eff=(V_PUF K_PUF )[1-e^(-(R_s V_PUF K_PUF )t) ] (eq. 1)

R_S=(f_on √(〖WS〗_on )+f_off √(〖WS〗_off ))(1/√(MW)) 10^[0.0012T+c] (eq. 2)

The indoor Rs is a function of the molecular weight of the compound (MW, g mol-1), the air temperature (T, °C), the fraction of the day when ventilation is on or off (fon/foff), the windspeed when the ventilation is on or off (WSon/WSoff), and the empirical constant of double-dome Harner style samplers (c). Room temperatures were measured in rooms 203 and 205 to estimate the average temperature over the deployment period (TSI Q-TRAK 7575) and averaged 30°C. We assumed a fon = 0.36 and a c = 1.326.5 WSon (0.11 m s-1) and WSoff (0.07 m s-1). The deployment time was t = 34 days. KPUF was averaged for coeluting congeners and temperature corrected according to Shoeib 2002, and Herkert 2016. Airborne PCBs are almost completely in the gas phase. However, the PUF-PAS method captures both gas phase and fine particles. The V_eff applies to both phases.

Emissions are calculated as the the sum of the ss corrected masses divided by the product of the PUF-PES area (A, 0.0153 m2) and the deployment time (t, 34 days).

E = mass/(A * t) (eq. 3)

Additional People Involved with Sample Collection, Processing, Analysis and/or Submission:
We thank Patricia Coppolino, Eben Pendleton, and school personnel for their assistance in conducting this study. We thank Gabi Fiedor and Matt Rosonke for their assistance in the laboratory and data handling. We thank Lab Manager Dr. Chris Knutson for his technical and compliance support of our facilities and equipment.

References:

Herkert, N. J.; Martinez, A.; Hornbuckle, K. C. A Model Using Local Weather Data to Determine the Effective Sampling Volume for PCB Congeners Collected on Passive Air Samplers. Environmental Science & Technology 2016, 50 (13), 6690-6697. DOI: 10.1021/acs.est.6b00319.

Hua, J. B. X.; Marek, R. F.; Hornbuckle K. c. Polyurethane Foam Emission Samplers to Identify Soruces of Airborne Polychlorinated Biphenyls from Glass-Block Windows and Other Room Surfaces in a Vermont School. Environmental Science & Technology 2023, 57, 14310-14318. DOI: 10.1021/acs.est.3c05195

Shoeib, M.; Harner, T. Characterization and Comparison of Three Passive Air Samplers for Persistent Organic Pollutants. Environmental Science & Technology 2002, 36 (19), 4142-4151. DOI: 10.1021/es020635t.

Rushneck, D. R.; Beliveau, A.; Fowler, B.; Hamilton, C.; Hoover, D.; Kaye, K.; Berg, M.; Smith, T.: Telliard, W. A.; Roman, H.; Ruder, E.; Ryan, L. Concentrations of Dioxin-Like PCB Congeners in Unweathered Aroclors by HRGC/HRMS Using EPA Method 1668A. Chemosphere 2004, 54 (1), 79 - 87. DOI: 10.1016/S0045-6535(03)00664-7

