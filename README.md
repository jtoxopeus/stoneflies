# stoneflies
These data files and code are associated with the scientific article 
"The cold tolerance of an adult winter-active stonefly: How Allocapnia pygmaea (Plecoptera: Capniidae) avoids freezing in Nova Scotian winters."<br>
This material is under the same copyright protections as the article itself.

# RCode file
The code can be run in R v4.2.2, and was used to conduct statistical analysis  from the data files below. 


# Data files
These are used for statistical analysis and figure generation in the RCode file.

## SCP.csv
This reports supercooling point (SCP) for stoneflies during a gradual cooling protocol. Each row pertains to a different individual, with information provided for each variable (column heading), as described below.

VARIABLE:                         DESCRIPTION <br>
#StoneflyID:                      Unique stonefly identifier<br>
#Mass:                            Weight of the stonefly in grams<br>
#SCP:                             Supercooling point (SCP) in degrees Celcius, the temperature at which internal ice formation begins. NA indicates SCP not recorded, either because freezing did not occur or due to lack of data (malfunction of temperature recording)<br>
#Alive:                           Whether the stonefly was alive (Yes) or not (No) following thawing<br>

## CTmin.csv
This reports critical thermal minimum (CTmin) for stoneflies during a gradual cooling protocol. Each row pertains to a different individual, with information provided for each variable (column heading), as described below.

VARIABLE:                         DESCRIPTION <br>
#StoneflyID:                      Unique stonefly identifier<br>
#Mass:                            Weight of the stonefly in grams<br>
#CTmin:                           Critical thermal minimum (CTmin) in degrees Celcius, the temperature at which the insect lost neuromuscular coordination<br>

## Cryoprotectants.csv
This reports concentrations of putative cryoprotectants for stoneflies that were field-collected or experienced a cold shock and recovery period in the laboratory. Concentrations were determined from whole-body homogenates using spectrophotometric assays, and expressed as µmol/g wet mass. Each row pertains to a different individual, with information provided for each variable (column heading), as described below.

VARIABLE:                         DESCRIPTION <br>
#StoneflyID:                      Unique stonefly identifier<br>
#Treatment:                       Whether the stonefly was treated directly after field collection (Field-Collected), or exposed to a cold shock and recovery period (Cold-Shocked) prior to measuring cryoprotectant concentrations<br>
#Mass:                            Weight of the stonefly in grams<br>
#Proline:                         Concentration of Proline (µmol/g wet mass)<br>
#Inositol:                        Concentration of myo-Inositol (µmol/g wet mass)<br>
#Glycerol:                        Concentration of Glycerol (µmol/g wet mass)<br>
#Trehalose:                       Concentration of Trehalose (µmol/g wet mass)<br>
#Glucose:                         Concentration of Glucose (µmol/g wet mass)<br>
