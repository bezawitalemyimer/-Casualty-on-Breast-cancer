 # Industry - Casualty
 
 ## Introduction

A common frustration in the industry, especially when it comes to getting business insights from tabular data, is that the most interesting questions (from their perspective) are often not answerable with observational data alone. These questions can be similar to: “What will happen if I halve the price of my product?” “Which clients will pay their debts only if I call them?” Judea Pearl and his research group have developed in the last decades a solid theoretical framework to deal with that, but the first steps toward merging it with mainstream machine learning are just beginning.

The causal graph is a central object in the framework mentioned above, but it is often unknown, subject to personal knowledge and bias, or loosely connected to the available data.

# Statistical Language - Correlation and Causation

What are correlation and causation and how are they different?
Two or more variables considered to be related, in a statistical context, if their values change so that as the value of one variable increases or decreases so does the value of the other variable (although it may be in the opposite direction).

For example, for the two variables "hours worked" and "income earned" there is a relationship between the two if the increase in hours worked is associated with an increase in income earned. If we consider the two variables "price" and "purchasing power", as the price of goods increases a person's ability to buy these goods decreases (assuming a constant income).
Correlation is a statistical measure (expressed as a number) that describes the size and direction of a relationship between two or more variables. A correlation between variables, however, does not automatically mean that the change in one variable is the cause of the change in the values of the other variable.
 
Causation indicates that one event is the result of the occurrence of the other event; i.e. there is a causal relationship between the two events. This is also referred to as cause and effect.
 
Theoretically, the difference between the two types of relationships are easy to identify — an action or occurrence can cause another (e.g. smoking causes an increase in the risk of developing lung cancer), or it can correlate with another (e.g. smoking is correlated with alcoholism, but it does not cause alcoholism). In practice, however, it remains difficult to clearly establish cause and effect, compared with establishing correlation.

# What is Causality?
Causality is an influence by which one event, process, state or object contributes to the production of another event, process, state or object where the cause is partly responsible for the effect, and the effect is partly dependent on the cause.

# Why Causality?

Many questions in Data Science are fundamentally causal in that our objective is to learn the effect of some exposure, randomized or not, on an outcome of interest. Even studies that are seemingly non-causal, such as those with the goal of prediction or prevalence estimation, have causal elements, including differential censoring or measurement.
We need to consider the underlying causal mechanisms that gave rise to the data, rather than simply the pattern or association observed in those data. 

The goal is trying to learn causality from data (what was the cause and what was the effect). However, causal inference would enable us to go one step further and figure out what would happen if we decide to change some of the underlying assumptions in our model.

Understanding cause and effect would make existing AI systems smarter and more efficient. For instance, “think about a robot that understands that dropping things causes them to break would not need to toss dozens of vases onto the floor to see what happens to them” .

Furthermore, the ability to understand causality would help us create business models as well as new startups specialized in helping companies better understand their data. For instance, we are going to start a project  on trying to diagnose breast cancer by diagnosing and utilizing characteristics of individual cells, obtained from a minimally invasive fine needle aspirate, to discriminate benign from malignant breast lumps using the data set sources. We believe that causality would help in identify new 
Literature review

How can causation be established?

# Causality is the area of statistics that is commonly misunderstood and misused by people in the mistaken belief that because the data shows a correlation that there is necessarily an underlying causal relationship

The use of a controlled study is the most effective way of establishing causality between variables. In a controlled study, the sample or population is split in two, with both groups being comparable in almost every way. The two groups then receive different treatments, and the outcomes of each group are assessed.

For example, in medical research, one group may receive a placebo while the other group is given a new type of medication. If the two groups have noticeably different outcomes, the different experiences may have caused the different outcomes.
Due to ethical reasons, there are limits to the use of controlled studies; it would not be appropriate to use two comparable groups and have one of them undergo a harmful activity while the other does not. To overcome this situation, observational studies are often used to investigate correlation and causation for the population of interest. The studies can look at the groups' behaviours and outcomes and observe any changes over time. 
The objective of these studies is to provide statistical information to add to the other sources of information that would be required for the process of establishing whether or not causality exists between two variables. 
 
Different Research and their perspectives 
1,”Causal inference and counterfactual prediction in machine learning for actionable healthcare”
Big data, high-performance computing, and (deep) machine learning are increasingly becoming key to precision medicine—from identifying disease risks and taking preventive measures, to making diagnoses and personalizing treatment for individuals. Precision medicine, however, is not only about predicting risks and outcomes, but also about weighing interventions. Interventional clinical predictive models require the correct specification of cause and effect, and the calculation of so-called counterfactuals, that is, alternative scenarios. In biomedical research, observational studies are commonly affected by confounding and selection bias. Without robust assumptions, often requiring a priori domain knowledge, causal inference is not feasible. Data-driven prediction models are often mistakenly used to draw causal effects, but neither their parameters nor their predictions necessarily have a causal interpretation. Therefore, the premise that data-driven prediction models lead to trustable decisions/interventions for precision medicine is questionable. When pursuing intervention modelling, the bio-health informatics community needs to employ causal approaches and learn causal structures. Here we discuss how target trials (algorithmic emulation of randomized studies), transportability (the licence to transfer causal effects from one population to another) and prediction invariance (where a true causal model is contained in the set of all prediction models whose accuracy does not vary across different settings) are linchpins to developing and testing intervention models.


# code 


































Techniques used to perform causal inference

































Insights derived from analysis carried out




















References

1,https://en.wikipedia.org/wiki/Causality
2,https://arxiv.org/abs/1809.02408
3,https://www.abs.gov.au/websitedbs/D3310114.nsf/home/statistical+language+-+correlation+and+causation
4,https://microsoft.github.io/dowhy/example_notebooks/DoWhy-The%20Causal%20Story%20Behind%20Hotel%20Booking%20Cancellations.html#Step-1.-Create-a-Causal-Graph
5,
























# Code

