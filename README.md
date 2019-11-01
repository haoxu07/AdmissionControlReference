## 1. Adaptive Overload Control for Busy Internet Servers 
#### Internally monitoring the performance of the service, which is decomposed into a set of event-driven stages connected with request queues. By controlling the rate at which each stage admits requests, the service can perform focused overload management, for example, by filtering only those requests that lead to resource bottlenecks.
@inproceedings{welsh2003adaptive,
  title={Adaptive Overload Control for Busy Internet Servers.},
  author={Welsh, Matt and Culler, David E},
  booktitle={USENIX Symposium on Internet Technologies and Systems},
  pages={4--4},
  year={2003},
  organization={Seattle, WA}
}
## 2.Taiji: managing global user traffic for large-scale internet services at the edge
#### Policy, assigning traffic objects at the edge to the data centers to satisfy service-level objectives. Taiji uses a constraint optimization solver to generate an optimal routing table that specifies the fractions of traffic each edge node will distribute to different data centers.
@inproceedings{chou2019taiji,
  title={Taiji: managing global user traffic for large-scale internet services at the edge},
  author={Chou, David and Xu, Tianyin and Veeraraghavan, Kaushik and Newell, Andrew and Margulis, Sonia and Xiao, Lin and Ruiz, Pol Mauri and Meza, Justin and Ha, Kiryong and Padmanabha, Shruti and others},
  booktitle={Proceedings of the 27th ACM Symposium on Operating Systems Principles},
  pages={430--446},
  year={2019},
  organization={ACM}
}
## 3.Overload Control for Scaling WeChat Microservices
#### It manages overload at the microservice granule such that each microservice monitors its load status in real time and triggers load shedding in a collaborative manner among its relevant services when overload is detected. 
   @inproceedings{zhou2018overload,
  title={Overload Control for Scaling WeChat Microservices},
  author={Zhou, Hao and Chen, Ming and Lin, Qian and Wang, Yong and She, Xiaobin and Liu, Sifan and Gu, Rui and Ooi, Beng Chin and Yang, Junfeng},
  booktitle={Proceedings of the ACM Symposium on Cloud Computing},
  pages={149--161},
  year={2018},
  organization={ACM}
}

## 4.Admission control of API requests in OpenStack
#### We confirmed that admission control could improve the performance of OpenStack services by more than 50% in an overloaded situation. We also proposed a heuristic algorithm that adaptively tuned the concurrent connection limit by monitoring the statistics of the completed API requests obtained from a proxy server. Our experimental evaluation revealed that our algorithm helped avoid severe performance degradation in OpenStack.
@inproceedings{matsuki2017admission,
  title={Admission control of API requests in OpenStack},
  author={Matsuki, Tatsuma and Iwamatsu, Noboru},
  booktitle={2017 IFIP/IEEE Symposium on Integrated Network and Service Management (IM)},
  pages={10--18},
  year={2017},
  organization={IEEE}
}

## 5.WebQ: A Virtual Queue For Improving User Experience During Web Server Overload
#### TokenGen and TokenCheck, that together shape incoming load to match server capacity. 
@article{sureshwebq,
  title={WebQ: A Virtual Queue For Improving User Experience During Web Server Overload},
  author={Suresh, Murali and Mondal, Ravi Shankar and Thomas, Stanly and Vutukuru, Mythili}
}


## 6.Maelstrom: Mitigating Datacenter-level Disasters by Draining Interdependent Traffic Safely and Efficiently
#### Maelstrom provides a traffic management framework with modular, reusable primitives that can be composed to safely and efficiently drain the traffic of interdependent services from one or more failing datacenters to the healthy ones. Maelstrom ensures safety by encoding inter-service dependencies and resource constraints. Maelstrom uses health monitoring to implement feedback control so that all specified constraints are satisfied by the traffic drains and recovery procedures executed during disaster mitigation. Maelstrom exploits parallelism to drain and restore independent traffic sources efficiently.
@inproceedings{veeraraghavan2018maelstrom,
  title={Maelstrom: Mitigating datacenter-level disasters by draining interdependent traffic safely and efficiently},
  author={Veeraraghavan, Kaushik and Meza, Justin and Michelson, Scott and Panneerselvam, Sankaralingam and Gyori, Alex and Chou, David and Margulis, Sonia and Obenshain, Daniel and Padmanabha, Shruti and Shah, Ashish and others},
  booktitle={13th $\{$USENIX$\}$ Symposium on Operating Systems Design and Implementation ($\{$OSDI$\}$ 18)},
  pages={373--389},
  year={2018}
}

## 7.Session-based overload control in QoS aware Web servers
#### the QoS-aware session-based admission control by exploiting the dependencies of sessions to improve the service quality during service overload. However, these techniques favor long-lived sessions, making them unsuitable for the WeChat application which incorporates tremendous short-lived and medium-lived sessions.
@inproceedings{chen2002session,
  title={Session-based overload control in qos-aware web servers},
  author={Chen, Huamin and Mohapatra, Prasant},
  booktitle={Proceedings. Twenty-First Annual Joint Conference of the IEEE Computer and Communications Societies},
  volume={2},
  pages={516--524},
  year={2002},
  organization={IEEE}
}

## 8. Distributed Resource Management Across Process Boundaries
#### A framework for building SOAs that transparently adapts rate limiters and request schedulers systemwide according to operator policies to satisfy end-to-end goals while responding to changing system conditions.  Trace driven evaluation. 
@inproceedings{suresh2017distributed,
  title={Distributed resource management across process boundaries},
  author={Suresh, Lalith and Bodik, Peter and Menache, Ishai and Canini, Marco and Ciucu, Florin},
  booktitle={Proceedings of the 2017 Symposium on Cloud Computing},
  pages={611--623},
  year={2017},
  organization={ACM}
}

## 9. An Admission Control Scheme for Predictable Server Response Time for Web Accesses
#### provide different levels of services based on the server workload characteristics. Service quality is ensured by periodical allocation of system resources based on the estimation of request rate and service requirements of prioritized tasks. Admission of lower priority tasks is restricted during high load periods to prevent denial-of-services to high priority tasks. A doublequeue structure is implemented to reduce the eects of estimation inaccuracy and to utilize the spare capacity of the server, thus increasing the system throughput. Response delays of the high priority tasks are bounded by the length of the prediction period.
@inproceedings{chen2001admission,
  title={An admission control scheme for predictable server response time for web accesses.},
  author={Chen, Xiangping and Mohapatra, Prasant and Chen, Huamin},
  booktitle={WWW},
  pages={545--554},
  year={2001},
  organization={Citeseer}
}

## 10. QoS-Aware Admission Control and Resource Allocation in Underlay Device-to-Device Spectrum-Sharing Networks
#### we introduce an objective that combines the access rate and the network sum rate and then maximize it subject to users’ quality-of-service requirements and resource allocation constraints. Due to its mixed combination, we focus on designing cost-efficient and easyto-implement algorithms instead of finding globally optimal but exponentially complex solutions. By decomposition, we first devise two novel mode selection criteria and an admission-prioritized partner assignment scheme and obtain closed-form solutions for both admission control and power allocation.
@article{li2016qos,
  title={QoS-aware admission control and resource allocation in underlay device-to-device spectrum-sharing networks},
  author={Li, Yuzhou and Jiang, Tao and Sheng, Min and Zhu, Yiting},
  journal={IEEE Journal on selected areas in communications},
  volume={34},
  number={11},
  pages={2874--2886},
  year={2016},
  publisher={IEEE}
}

## 11. FACS-MP: A fuzzy admission control system with many priorities for wireless cellular networks and its performance evaluation
#### considering the priority of the on-going connections. We called this system FACS-P. In FACS-P, as priority parameter, we considered only one parameter (service request). We extended our work by adding different priorities. We call this system FACS-MP. In this paper, we evaluate by simulations the performance of the proposed system. From the simulation results, we conclude that the FACS-MP makes a good differentiation of different services and has better behaviour than FACS-P.
@article{matsuo2015facs,
  title={FACS-MP: a fuzzy admission control system with many priorities for wireless cellular networks and its performance evaluation},
  author={Matsuo, Keita and Elmazi, Donald and Liu, Yi and Sakamoto, Shinji and Mino, Gjergji and Barolli, Leonard},
  journal={Journal of High Speed Networks},
  volume={21},
  number={1},
  pages={1--14},
  year={2015},
  publisher={IOS Press}
}

## 12. Joint admission control and routing via approximate dynamic programming for streaming video over software-defined networking
####  Optimization problem of joint admission control and routing for the video streaming service in wired software-defined networking (SDN).
@article{yang2016joint,
  title={Joint admission control and routing via approximate dynamic programming for streaming video over software-defined networking},
  author={Yang, Jian and Zhu, Kunjie and Ran, Yongyi and Cai, Weizhe and Yang, Enzhong},
  journal={IEEE Transactions on Multimedia},
  volume={19},
  number={3},
  pages={619--631},
  year={2016},
  publisher={IEEE}
}

## 13. Admission control in cloud computing using game theory
#### the concept of game theory in admission control for Cloud requests. A model has been proposed and its performance study is done by simulating it in CloudSim simulator. Results are encouraging and may suggest for its possible inclusion in the Cloud middleware.
@article{baranwal2016admission,
  title={Admission control in cloud computing using game theory},
  author={Baranwal, Gaurav and Vidyarthi, Deo Prakash},
  journal={The Journal of Supercomputing},
  volume={72},
  number={1},
  pages={317--346},
  year={2016},
  publisher={Springer}
}

## 14. SLA-based admission control for a Software-as-a-Service provider in Cloud computing environments
#### we propose innovative admission control and scheduling algorithms for SaaS providers to effectively utilise public Cloud resources to maximize profit by minimizing cost and improving customer satisfaction level. Furthermore, we conduct an extensive evaluation study to analyse which solution suits best in which scenario to maximize SaaS provider’s profit. Simulation results show that our proposed algorithms provide substantial improvement (up to 40% cost saving) over reference ones across all ranges of variation in QoS parameters.
@article{wu2012sla,
  title={SLA-based admission control for a Software-as-a-Service provider in Cloud computing environments},
  author={Wu, Linlin and Garg, Saurabh Kumar and Buyya, Rajkumar},
  journal={Journal of Computer and System Sciences},
  volume={78},
  number={5},
  pages={1280--1299},
  year={2012},
  publisher={Elsevier}
}

## 15. Q-Cop: Avoiding bad query mixes to minimize client timeouts under heavy loads
#### we show that the response times of different types of queries can vary significantly depending not just on the number of queries being processed but on the mix of other queries that are running simultaneously. We develop a model of expected query execution times that accounts for the mix of queries being executed and integrate this model into a three-tiered system to make admission control decisions. Our results show that this approach makes more informed decisions about which queries to reject and as a result significantly reduces the number of requests that time out.
@inproceedings{tozer2010q,
  title={Q-Cop: Avoiding bad query mixes to minimize client timeouts under heavy loads},
  author={Tozer, Sean and Brecht, Tim and Aboulnaga, Ashraf},
  booktitle={2010 IEEE 26th International Conference on Data Engineering (ICDE 2010)},
  pages={397--408},
  year={2010},
  organization={IEEE}
}

## 16. A Method for Transparent Admission Control and Request Scheduling in E-Commerce Web Sites
#### Our method externally observes execution costs of requests online, distinguishing different request types, and performs overload protection and preferential scheduling using relatively simple measurements and a straightforward control mechanism.
@inproceedings{elnikety2004method,
  title={A method for transparent admission control and request scheduling in e-commerce web sites},
  author={Elnikety, Sameh and Nahum, Erich and Tracey, John and Zwaenepoel, Willy},
  booktitle={Proceedings of the 13th international conference on World Wide Web},
  pages={276--286},
  year={2004},
  organization={ACM}
}

## Morpheus: Towards Automated SLOs for Enterprise Clusters
#### 1) codifies implicit user expectations as explicit Service Level Objectives (SLOs), inferred from historical data, 2) enforces SLOs using novel scheduling techniques that isolate jobs from sharing-induced performance variability, and 3) mitigates inherent performance variance (e.g., due to failures) by means of dynamic reprovisioning of jobs.
@inproceedings{jyothi2016morpheus,
  title={Morpheus: Towards automated slos for enterprise clusters},
  author={Jyothi, Sangeetha Abdu and Curino, Carlo and Menache, Ishai and Narayanamurthy, Shravan Matthur and Tumanov, Alexey and Yaniv, Jonathan and Mavlyutov, Ruslan and Goiri, {\'I}{\~n}igo and Krishnan, Subru and Kulkarni, Janardhan and others},
  booktitle={12th $\{$USENIX$\}$ Symposium on Operating Systems Design and Implementation ($\{$OSDI$\}$ 16)},
  pages={117--134},
  year={2016}
}
