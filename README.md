## Modeling-Micturation

Here is presented the computational method underlying a simulation of human urination behavior for providing context for biomonitoring studies used in environmental exposure and drug testing. The modeling and simulation was conducted in RStudio and this repository contains the R Markdown files and data. The purpose of this modeling was to develop estimates of within- and between-person variability in voiding characteristics to enable simulation of voiding behavior over a timescale of days to weeks.

The largest repository of human urine void characteristics is CDC-NHANES. As part of CDC-NHANES program, up to three urine voids are collected from each individual and the void volumes and void intervals recorded (https://wwwn.cdc.gov/nchs/nhanes/search/datapage.aspx?Component=Laboratory&CycleBeginYear=2017). 

Whilst measurements from a large number of individuals comprise these data, their value for understanding void volume and interval over multi-day periods is unclear. NHANES participants self-reported the void interval prior to the first sample and supplied up to three voids “to ensure sufficient total volume for various analyses.” The CDC website also notes: “Analysts should examine the data distribution and use their subject-matter knowledge to decide whether to include, trim, or exclude any potential outliers in their analyses.”

The majority of participants in NHANES provide only a single spot urine sample. If an individual’s first sample is insufficient for the number of assays performed, the individual is asked to wait until they can provide a second sample and, if needed, a third. The NHANES sample consists of 41,247 individuals, 20269 men and 20978 women; of these 
2357 men and 3877 provided two samples; 76 men and 211 women provided 3 samples. 

Urine voiding follows a circadian rhythm. An individual's daytime void volumes and intervals are determined by a number of factors including recent fluid consumption, personal circumstances such as driving, hormonal factors, and likely others. The NHANES data contains no information about the circadian rhythmicity or the frequency of voiding. These data, howver, provide a large database from which to obtain data on within- and between-person variation in daytime void volume, void interval and urine production rate. 

Information on nightime voiding behavior as well as additional information was developed from clinical studies that used bladder diaries and one other study that followed four couples for an entire week with all voids collected.
