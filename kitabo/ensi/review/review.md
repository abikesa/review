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

