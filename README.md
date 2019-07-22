# OCS-Right-Heart-Catheterization

This case study is part of the [OpenCaseStudies](https://opencasestudies.github.io) project.
This work is licensed under the Creative Commons Attribution-NonCommercial 3.0, 
[CC BY-NC 3.0](https://creativecommons.org/licenses/by-nc/3.0/us/) United States License.

## Association between Right Heart Catheterization and Death in 30 days of enrollment


Right heart catheterization (RHC), also known as pulmonary artery 
catheterization, is an invasive test that mainly checks the working 
state of the heart by guiding a pulmonary artery (PA) catheter 
(a small and hollow tube) through the pulmonary artery and into 
the right chambers of the heart. By this way, the catheter can measure 
the functions of the heart such as blood pressure, cardiac output, etc.,
including other measures in connection to heart problems such as 
diurnal respiratory instability according to one study by Kumagai, et al. (2018).
In turn, these measurements are used to treat and manage heart 
conditions such as heart failure, congenital heart disease, 
cardiomyopathy, pulmonary hypertension, etc. Thus, many cardiologists
and critical care physicians believe that the direct measurements of
the cardiac functions by RHC is necessary to the management of 
treating critically ill patients and that such management will
theoretically lead to better health outcomes according to Connors, et al. (1996).
However, due to the severity of the cardiac conditions of the patients 
as well as the invasive procedure of RHC with no guarantee of 
any beneficial outcomes, data measuring the benefits of the RHC 
procedure cannot easily be collected in a randomized control trial (RCT). 
To make up for this, observational studies were used to evaluate
the effectiveness of the RHC procedure. Although, these studies are
susceptible to treatment selection bias as physicians can make the 
decision to use or withhold RHC in the treatment of their patients.

The purpose of this study is to reproduce the statistical analysis 
of the objective of the research, The Effectiveness of Right Heart 
Catheterization in the Initial Care, using the data it collected from
a large group of critically ill patients and in predefined patient 
subgroups in order to determine how valid is the association between
the use of the right heart catheterization during the first 24 hours
of an ICU stay with subsequent survival, length of stay, 
intensity of care, and cost of care.




## Data

This dataset was used in Connors et al. (1996): The effectiveness 
of RHC in the initial care of critically ill patients. 
J American Medical Association 276:889-897. The dataset pertains to day 1 of hospitalization, i.e.,
the "treatment" variable swang1 is whether or not a patient 
received a RHC (also called the Swan-Ganz catheter) on the first day
in which the patient qualified for the SUPPORT study (see above). 
The dataset is suitable for use in papers submitted in response to
the call for papers on causal inference, by the journal Health Services
and Outcomes Research Methodology. The original analysis by Connors et al. 
used binary logistic model to develop a propensity score that was then used
for matching RHC patients with non-RHC patients. A sensitivity analysis 
was also done. The results provided some evidence that patients receiving 
RHC had decreased survival time, and the sensitivity analysis indicated 
that any unmeasured confounder would have to be somewhat strong to explain
away the results. See Lin DY, Psaty BM, Kronmal RA (1998): 
Assessing the sensitivity of regression results to unmeasured confounders 
in observational studies. Biometrics 54:948-963 for useful methods 
for sensitivity analysis, one of which was applied to the RHC results.

You can find the description of the data 
[here](http://biostat.mc.vanderbilt.edu/wiki/pub/Main/DataSets/rhc.html)

## Files

In the `doc` folder, plots created by ourselves are saved there.
We also write a Bibtex file which is used to automatically generate 
citations and a bibliography in a number of styles. More details
can be found [here](https://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html)  
