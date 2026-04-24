# Medicaid Coverage and Healthcare Utilization

Replication of Finkelstein et al. (2012), which investigates the causal effects of expanding 
Medicaid coverage on health outcomes, healthcare utilization, and financial well-being. The 
paper exploits a randomized lottery system in Oregon, where the opportunity to apply for 
Medicaid was randomly allocated, creating a natural experiment to estimate the effects of 
insurance coverage.

The analysis covers three main components. First, descriptive evidence on insurance take-up 
rates and the relationship between insurance status and healthcare utilization using OLS. 
Second, validity checks through balance tests on pre-randomization characteristics across 
lottery winners and losers, assessment of survey attrition, and first-stage regression 
evaluating instrument strength. Third, causal effect estimation using both an intent-to-treat 
(ITT) approach — exploiting random lottery assignment — and an instrumental variables (IV) 
approach, where OHP insurance at 12 months is instrumented by lottery selection.

## Files
- `Finkelstein et al. (2012)_Replication.Rmd` — R Markdown source file containing all code and analysis
- `Finkelstein et al. (2012)_Replication.html` — rendered HTML output
- `Finkelstein et al. (2012)_Replication.pdf` — **final knitted output, recommended for viewing**

All analysis conducted in R using R Markdown. Methods: OLS, ITT, IV/2SLS, balance checks, 
first-stage regression.

**Paper:** Finkelstein, A. et al. (2012). *The Oregon Health Insurance Experiment: Evidence 
from the First Year.* The Quarterly Journal of Economics, 127(3): 1057–1106.
