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
