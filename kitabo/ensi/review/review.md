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
   - With a focus on time-to-event, we'd then understand explicityly that time-zero is first referral
   - Here it becomes immediately clear to the reader that you are NOT concerned with disparities from non-referral from dialysis centers

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
   - The authors motivate their study by stating that ESKD in black patients is four times greater than in white patients, but black patients are less than half as likely to undergo transplantation. But the reader can't get any sense as to whether the chief bottleneck for black patients is pre-referral from dialysis or post-referral, after first evaluation for transplant.
   - In general, the introduction at five paragraphs is too long and doesn't help the reader grasp any scientific question.
6. Methods. From my reading, the clearest version of the study hypothesis is burried in the fourth paragraph of the methods: does completion of most or all testing on the same day of first pre-transplant appointment vs. providing patients with a list of tests to be completed on their own with their referring physician reduce time-to-event (composite of waitlisting or transplant). This should be articulated very early in the introduction. And supporting literature should focus on clarifying why its an important question.
   - Have the authors considered looking at the composite outcome time-to-event (waitlisting or transplant)
   - Among demographic and clinical characteristics at baseline, do the authors have access to "potential living donor candidates considered"?
   - While the authors state that "to visualize the probability of events, we calculated and plotted adjusted cumulative incidence functions for time from evaluation to waitlisting or transplant", I believe these adjusted graphs should also yield median time-to-event so that a simple interpretation such as "median time was reduced from XX to YY" in a given clinical scenario from the multivariable model. Their sHRs should be used to generate this curves. But a reader doesn't get an intuitive sense of the "fast-track" or "reduction" in time with a sHR=1.40
   - Did the authors assess whether proportionality of hazards assumption was fulfilled by their models. My concern is that disparities are best captured by non-parametric survival curves that make no assumption about proportional hazards. It is entirely possible the two survival curves can criss-cross and yield a HR=1 (yet there are obvious disparities in early times). With non-parametric curves that would be easy to see. With semi-parametric curves, they are "forced" to be proportionately seperated at each time point. Not very compelling in the complex clinical setting under study, where pre-emptive living donation occur rather early after referral and mortality is quite high.
8. Results
   - Reporting sHR 1.40 and 1.20 as 40% and 20% more likely to be transplanted is very misleading since these percent differences aren't performed on a log-scale. A log SHR of 1.40 yields 1.14, which is 14% "more likely" not 40% "more likely". Neither tell us how much "quicker" the fast-track leads to the outcome
   - You promised to report the probabilities of waitlisting and transplantation and these are not delivered. Those come from the "adjusted" cumulative incidence functions. Even better, a standard probability "parameter" is the median survival time. Its very simple and intuitive and anyone can understand what "fast-track" is if, say, the median survival time is reduced from 3.5 years to 2.5 years. We can visualize it in a figure and appreciate its clinical significance, as contrasted with a sHRS of 1.40
     
10. Discussion
11. Tables
12. Figures
13. Bibliography
