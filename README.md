# vax-letters-rdd-sweden
Code and documentation for evaluating the effectiveness of pre-booked COVID-19 vaccination appointment letters on vaccine uptake across sociodemographic groups in Sweden, using a regression discontinuity design.

**Manuscript Title:**
Effect of COVID-19 Vaccination Appointment Letters on Uptake by Sociodemographic Characteristics: A Regression Discontinuity Analysis in Sweden, December 2020 to September 2021. 
Georgios Varotsis, MSc, Ulf Hammar, BSc, Carl Bonander, PhD, Per Lundmark, PhD, Beatrice Kennedy, PhD, Maria F. Gomez, MD, Mats Martinell, MD, Oliver J. Dyar, MD, Anna Sarkadi, MD, Robert Kristiansson, MD, Helena Svaleryd, PhD, Tove Fall, PhD

**Abstract**

**Background** Ensuring high vaccination coverage is vital, particularly during a pandemic. While pre-booked appointment letters have shown promise in vaccination campaigns, their effectiveness in specific sociodemographic groups remains to be explored. Our study evaluated the effect of pre-booked appointment letters on COVID-19 vaccine uptake within different sociodemographic groups using a quasi-experimental methodology.

**Methods** In Uppsala County, Sweden, residents born between 1962-1971 received pre-booked COVID-19 vaccination letters starting May 24, 2021, while younger residents received SMS prompts for self-booking starting June 7, 2021. Through a Regression Discontinuity Design, we used the intervention cutoff at birth year 1971 to assess the effectiveness of the letters in increasing vaccine uptake compared to the SMS campaign. Our analysis included 96 194 individuals born between 1962-1981, examining vaccination within 90 days post-eligibility as primary outcome. We investigated effects within sociodemographic groups, assessed household spillover effects, and performed negative control analyses using neighboring counties.

**Results** Adults just above the cutoff had an odds ratio of 1.3 (95% CI 1.10–1.53) of being vaccinated than those just below, with a 1.97 percentage point increase (95% CI: 0.45-3.50) from a baseline of 91.95%. The intervention showed effectiveness within most sociodemographic strata. No effects were found in negative control counties, nor household spillover effects.

**Conclusion** Pre-booked appointment letters are effective at boosting vaccination uptake, even in diverse sociodemographic groups. While our findings come from COVID-19 vaccination, they align with evidence from various immunisation programs, suggesting that personalised communications can achieve equitable vaccine coverage across different healthcare settings.

**Keywords** COVID-19; Immunization Programs; Appointments and Schedules; Sociodemographic Factors; Regression Analysis;


These are the files used for the analysis of the paper "Effect of COVID-19 Vaccination Appointment Letters on Uptake by Sociodemographic Characteristics: A Regression Discontinuity Analysis in Sweden, December 2020 to September 2021."

**Varotsis_et_al_Vaccination_Letter_Data_Processing_Table1.R** This file contains all data processing and preparation, as well as the code for generating Table 1.

**Varotsis_et_al_Vaccination_Letter_Primary_Secondary_Sensitivity_Analysis.R** This file includes the code for the primary, secondary, and sensitivity analyses. It also contains the code for generating Figure 1, Figure 2, Figure 3, Supplementary Table 1, Supplementary Table 2, and Supplementary Table 3. To obtain the results for the negative control analysis for the neighboring counties, use the file Varotsis_et_al_Vaccination_Letter_Primary_Secondary_Sensitivity_Analysis.R In line 50, set the variable ‘County_selection’ to ‘Gävle’ to get the results for Gävleborg County or to ‘Stockholm’ to get the results for Stockholm County.

**Varotsis_et_al_Vaccination_Letter_Spillover_Analysis.R**: This file further processes the data for the spillover analysis and generates the results of the spillover analysis.
