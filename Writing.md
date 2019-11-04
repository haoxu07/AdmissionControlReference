In this section we study prior work in systems that handles system overload. We group prior
approaches into two major categories, i.e., admission control systems and methodology.

Admission control for overload management has been studied in databases[ActiveSLA SOCC '11], web services[USITS '03(1), WeChat SoCC2018(3), Taiji SOSP2019(2), Maelstrom OSDI 2018(6),INFOCOMM 2002(7)], networks[FACS-MP 2015]. Taiji SOSP2019(2), Maelstrom OSDI 2018(6). However, most of these previous work are
designed for the specific service architecture and they do not meet our requirement for overload control of in-memory graph database. 
Bouncer distinguishes itself from these works in two major aspects. 
1. Due to the low execution time of the in-memory graph database query, Bouncer makes decisions with low overhead (<<1ms per query).
2. In order to meet the client service requirement, bouncer support different policies targeting on different objectives, including minimum SLO violation, utlization and less queue waiting time. 

Simulation Based admission evaluation. 


[ActiveSLA SOCC '11] proposed the technique of predicting the probability for each query to meet/miss its deadline by query features. Although such mechanism shares some similarity with Bouncer, its machine learning based prediction framework's overhead is higher than our requriement for decison making for a single query. In contrast, Bouncer can act quickly enough with statistical prediction for end-to-end query execution time.

Service agnostic

The use of Service Level Objective to improve Quality of Service has been investigated by several systems [...]. 
Predict SLOs and adopt novel scheduling techniques[OSDI 18 Morpheus(17), TUM10(19)].  
Workload estimation method and an efficient migration schedule algorithm [DASFAA 2017(20)]
server selection; transiency-aware load-balancing; and using intelligent capacity over-provisioning meet SLOs[HPDC19(21)]. However, Bouncer focus on the 
