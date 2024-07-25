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
    - The first paragraph of the discussion has a misleading statement: we sould to test the advantage of using ... fast-track kidney transplant evaluation for ESKD patients". This isn't a study of ESKD patients! Its a study of the subset of ESKD patients on their first referral for KT. So, again, this study says nothing about the relative disparities before referral for KT vs. after referral for KT. It only addresses the latter. We still do not know which of these drives disparities more. So the authors should revised and clarify their language throughout their manuscrkpt.
    - The discussion, like the introduction, isn't very focused on discussing the results of their analysis. It talks of "the intervention removing the burden from patients and instead focuses on the healthcare system". This very general misleads the reader. This study focuses on the transplant system, not the healthcare system. We don't know anything about dialysis to transplant referral from this analysis. And the relative importance of that aspect of the healthcare system. So general platitudes should be avoided and a focus on methodology and inferences instead.
    - Its noteworthy that "there were no significant difference in waitlisting adn KT between fast-track black and white patients"; however, these inferences are based on a sHR rather than the cumualtive incidence functions, which could tell a better story especially in presence of "competing" outcomes such as living donation (often within 1st year of transplant) nad mortality (high among dialysis patients, many of whom never get referred for transplant or make it to the study). Fine and Gray methods for competing risks are most helpful when one wants to estimate cumulative incidence functions. But if descriptive cause-specific effects (death vs. transplant) are of interest, Cox regression may yield more meaningful HRs (reference #58 Lau B AJE 2009)
    - New references to literature are introduced in the conclusion and this doesn't help synthesize the authors work very well. These perhaps belong to the introduction. And the Schold et al. citation in the conclusion talking of "rates of waitlisting following ESKD onset", not waitling following transplant referral. This fundamental difference isn't appropriately distinguished by the authors in this manuscript and leads to very ambiguous inferences about "the healthcare system"
12. Tables.
    - Table 1. The columns for test-statistic and p-value in Table 1 are not at all informative. The authors perform multivariable regression and that should be sufficient. The readers should be allowed to focus on the two column of the study arms
    - All outcome reporting should be excluded from Table 1, which is traditionally one that helps the reader get a general view of the study population at baseline. In any case, outcomes such as "days from evaluation to any waitlisting" are always incomplete since there is censoring. For this reason, the authors should use standard matrics such as "median time to waitlisting or transplant". This relies on methods that account for censoring of events (e.g. administrative censoring before any outcomes are observed)
14. Figures. These figures can only be "trusted" if the authors have assessed proportionality of hazards assumption in their model. The curves don't look compelling in light of the differential likelihoods of living donation and death on the waitlist across racial groups. I'd expect surves with different shapes, which might require the authors to incorporate a time-interaction term in their model. Was this explored?
    Fig 2A. The figure shows a "leveling-off" as early as 5 years after evaluation. This is a reminder that more traditional reporting of median time-to-event may be more instructive, informative, and much simpler for clinicians and patients to digest
15. Bibliography. The authors cite 65 studies in the references. But this mostly reflects a lack of focus on a clear clinical or policy question. 
