(cltx)=
# CLTX

## 1
### Latent profiles of deceased organ donation registrants and non-registrants in the United States
#### Editors
Machine learning has a guaranteed place in the future of clinical medicine. 

But for now, these authors have failed to offer a compelling place for it in this specific instance. 

A simple logistic regression of all the factors they studied on "registration for organ donation" would help ground their work using methods that are familiar and transparent us. The predictive accuracy of the traditional and transparent vs. "unsupervised" and opaque would be the simplest way to motivate their innovation.

That said, the paper is NOT written in the style a clinical audience expects and deserves. Nothing short of complete redesign of this effort would make this paper appropriate for the journal. 

#### Authors
"Latent profiles of deceased organ donation registrants and non-registrations in the United States" is an innovative paper that seeks to identify factors associated with registration for deceased organ donation.

It uses unsupervised machine learning to uncover three profiles of persons from National Behavioral Health Survey (N=11,083) that have some "meaningful" differences linked to registration as a donor. The differences identified include  access to healthcare services, satisfaction with those services, mental health, and age (but not as a standalone variable).

But several issues make this effort unlikely to benefit readers of the journal. First, the methods are not familiar to the audience and lack the transparency the allows one to be critical. 

Second, the style of reporting isn't for a clinical audience that is familiar with a traditional Table 1 with descriptive characteristics using familiar metrics like median (Interquartile range) or mean (SD) for continuous variables. 

Figure 1 includes metrics that are not familiar or clinically useful (e.g. standard deviations from grand means for healthcare access). 

Table 2. Presents the output (i.e., the latent profiles) and describes them in terms of gender, race, state incentive for living donation, possession of drivers license, and medical insurance status. Without a meaningful conceptualization of the organ donation process (deceased donation vs. living donation), this model will be problematic to readers. 

Furthermore, traditionally used methods such as logistic regression should first be explored so that we  have a benchmark against which to appraise unfamiliar and opaque machine-learning approaches. 

Table 3 presents another table that isn't suitable for a clinical audience, with columns for chi-square statistics, across too many groups for the mind to grapple with. Critically, the p-values emerging from these multiple comparisons are not as meaningful as the authors let off. 

The supplemental material is completely inaccessible to the clinician. 


## 2
(chatgpt)=
### ChatGPT Solving Complex Kidney Transplant Cases: A Comparative Study with Human Respondents
#### Editors

                   1. f(t)
                         \
              2. S(t) -> 4. y:h'(t)=0;t(X'X).X'Y -> 5. b -> 6. SV'
                         /
                         3. h(t)

- $f(t)$ Each mode has its own data properties and pdf
- $S(t)$ Cumulative inputs (i.e., greater data, more modes) is where the edge is
- $ht(t)$ Quicker processesing of a lot of information 
- $(X'X)^T \cdot X'Y$
- $\beta$ Diagnosis as a single word is a tidy token that GPTs were trained to predict
- $SV'$ But "attention" to the context of the key words yields an `unexamined` edge {cite}`vaswani2017attention`

This is a very simple and clearly written analysis of a topical issue. I think its worth publishing, after the authors address the concerns the reviewer raised, as well as the issues I've presented.


#### Authors

![](https://www.economist.com/cdn-cgi/image/width=1424,quality=80,format=auto/content-assets/images/20240803_STD002.jpg)

```{figure} figures/blanche.png
---
width: 1px
height: 1px
---
*AI Mugshot*. to avoid seeming biased towards one-specific industry product, can the authors comment on other chatbots on the market including claude.ai, meta.ai, perplexity.ai, gemini, etc?.{cite}`chatgpt` {cite}`copilot` {cite}`claude` {cite}`metaai` {cite}`perplexity`
```

The authors assessed the accuracy of different versions of ChatGPT (3.5, 4, and 4V) in responding to kidney transplant cases from historical quizzes of the American Society of Nephrology (2015, 2014, 2013). There were two cases for each year, a case summary, lab results, an image (e.g. head CT), and multiple choice answers: for instance, which of the following is the most likely cause of her chest pain and CXR findings? [A] Lung cancer, [B] Recurrent breast cancer, [C] Pneumonia, [D] Sarcoidosis.

Performance was benchmarked to nephrology fellows, transplant program directors, and an audience. Figure 1 offers a very powerful & accessible summary of the findings. GPT-4V almost matched the transplant program directors overall performance across the three years studied.

But visual inspection reveals heterogeneity in the hierarchies across the years (e.g. the fellows outperformed GPT-4V in the 2013 quiz but fell short in the other years). Are the differences in performance witnessed over just a handful of quesionnaire items statistically significant? Are they clinically meaningful? 

Can you comment on multimodal chatbots that are widely available right now. GPT-4o, for instance, is more recent than GPT-4V and can process not only images, but also audio, video, uploaded .PDF or .CSV files, extending utility beyond text and static images. Much more detailed clinical detail can be processed by these newer versions of chatbots by "reading" the entire patient record on file in a matter of seconds or minutes, including all available images, and perhaps even audio records from the physicians. Isn't this study design under-selling the potential edge these chatbots may actually have? And if these approaches are limited by HIPAA, then can the authors address these issues in the revised discussion?{cite}`the_economist_gpt_claude_llama_2024`

Second, to avoid seeming biased towards one-specific industry product, can the authors comment on other chatbots on the market including claude.ai, meta.ai, perplexity.ai, gemini, etc? How would the authors advise a clinician to approach these options? ChatGPT has been an industry leader, but this is a very dynamic and fast-growing area of competition and it would be helpful to place ChatGPT in the broader context

