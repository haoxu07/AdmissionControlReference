In this section we study prior work in systems that handles system overload. 

Admission control for overload management has been studied in databases[ActiveSLA SOCC '11], web services[USITS '03(1), WeChat SoCC2018(3), Taiji SOSP2019(2), Maelstrom OSDI 2018(6),INFOCOMM 2002(7)], networks[FACS-MP 2015]. Taiji SOSP2019(2), Maelstrom OSDI 2018(6). However, most of these previous work are
designed for the specific service architecture and they do not meet our requirement for overload control of in-memory graph database. 
Bouncer distinguishes itself from these works in two major aspects. 
1. Due to the low execution time of the in-memory graph database query, Bouncer makes decisions with low overhead (<<1ms per query).
2. In order to meet the client service requirement, bouncer support different policies targeting on different objectives, including minimum SLO violation, utlization and less queue waiting time. On evaluation method, Bouncer is evaluated in not only in simulation, but also with real-production input considering challenges in real systems. 

[ActiveSLA SOCC '11] proposed the technique of predicting the probability for each query to meet/miss its deadline by query features. Although such mechanism shares some similarity with Bouncer, its machine learning based prediction framework's overhead is higher than our requriement for decison making for a single query. In contrast, Bouncer can act quickly enough with statistical prediction for end-to-end query execution time.

[USITS '03(1)] proposed staged overload control, which partitioned the web services into multiple stages based on service semantics and performed overload control for each stage independently. Each stage is statically allocated with
a resource quota for load constraint. However, Bouncer is admisson framework decoupled from query processing, which making it flexible and highly adaptable to the continuously evolving query features.

The use of Service Level Objective to improve Quality of Service has been investigated by several systems [...]. 
[OSDI 18 Morpheus(17), TUM10(19)] predict SLOs and adopt novel scheduling techniques. 
[DASFAA 2017(20)] proposes a workload estimation method and an efficient migration schedule algorithm to decrease SLO violations. 
[HPDC19(21)] adopt server selection; transiency-aware load-balancing; and using intelligent capacity over-provisioning meet SLOs.Bouncer also focuses on SLO violations reduction. However, Bouncer provide query starvation avoidence on fullfill SLO requirement for different query type and provide variour policy choices to meet different requirements.   
