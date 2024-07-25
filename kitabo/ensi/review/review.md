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
   - Competing risks frame-work is unnecessarily complex because it asks academic questions that aren't as relevant to the patient as investigator
   - The authors say fast-track patients were 40% "more likely" to be waitlisted amd 21% "more likely" to be transplanted
      - Are these % based based on comparing sub-hazard ratios or log-hazard ratios
      - If they are based on sHRs, then they are misleading since sHR of 0.5 and 2 would represent 50% lower and 100% higher
      - Yet if the reference groups were flipped, the interpretation would be different. The log sHR scale is the correct one
      - But this is also not very intuitive: for "fast-track" a reader would want to know the reduction in time-to-event
2. Abstract
3. Introduction
4. Methods
5. Results
6. Discussion
7. Tables
8. Figures
9. Bibliography
