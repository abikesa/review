# Reviews

## 1

### Increasing equity in Kidney Transplantation: Results of the Kidney Transplant Fast Track Study

###### Question 1, 2, 3 
- Is Kidney Transplant Fast Track (KTFT) associated with a higher likelihood of waitlisting and kidney transplantation?
   - Why not report absolute risks for scenarios?
   - This would allow description of median time-to-event
   - Increase and decrease in that time is more intuitive than "likelihood"  

###### Findings 4
- In this prospective comparative cohort trial of 1118 end-stage kidney disease (ESKD) patients and a historical control group of 1152 ESKD patients undergoing evaluation for kidney transplantation, KTFT patients were 40% more likely to be waitlisted and 21% more likely to be transplanted than historical controls. Unlike the historical control group, after KTFT, there were no significant race differences in kidney transplantation.
   - We much rather describe a 6-month reduction in time than a 21% increase in likelihood (which is wrong, since its exponential scale)
      - Table 1. Should be restricted to baseline characteristics
         - Test-statistic and p-value columns are meaningless distractions and should be removed
         - No table should summarize "time-to-event" (any waitlist status or transplant); these fail to account for missing information through censoring
         - Instead, restrict this to Kaplan-Meier survival functions
   - No race differences after KTFT (unlike historical control group) 

###### Meaning 5, 6
- KTFT was associated with a higher likelihood of waitlisting and kidney transplantation, and may help reduce race disparities.
   - The relative risk isn't `meaningful`


##

1. Title: Increasing equity in kidney transplantation: kidney transplant fast track study
   - Is kidney transplant fast track associated with a higher likelihood of waitlisting and transplant?
   - A simple metric to answer this question would be median time-to-composite event for historical cohort vs. fast-track

2. Abstract
   - Outcome measure is reported as time-to-waitlisting and receipt of transplant
   - Results are reported as 40% greater chance of being placed on the active waitlist and 21% greater chance of receiving a transplant
   - This is problematic in two ways.
      - First, 40% better "chance" and sHR=1.40 do not correlate. It would be more accurate to say 1.4-fold higher sub-hazards 
         - When you flip the reference groups its clear that there is no symmetry on this scale
         - If they authors wish to talk of % better chance, then they should do the calculations on the log sub-hazards scale
      - Second, the hazard ratios say very little about how the "time-to-event" is reduced by the intervention
         - What was the median survival in the historical cohort? And how was this reduced
         - In a multivariable setting, this can be accomplished by using clinical scenarios
         - Alternatively, a matched study design and non-parametric cumulative incidence function could yield the "promised" outcome 
   - Conclusions: Reduction in disparities in KT is ambiguous if the authors aren't explicit about deceased vs. living donation and what exactly they studied
4. Introduction
5. Methods
6. Results
7. Discussion
8. Tables
9. Figures
10. Bibliography
