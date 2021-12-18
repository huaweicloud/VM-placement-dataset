# VM Placements Datasets

## Overview

The *VM Placements Datasets* is published by Huawei Group. By providing the standard datasets of virtual machine scheduling, it can help researchers better study and train the virtual machine scheduling algorithms.
We are open source based on [CC-BY-NC](https://github.com/santisoler/cc-licenses/blob/master/LICENSE-CC-BY-NC-SA). Please follow the [open source protocol](https://github.com/santisoler/cc-licenses/blob/master/LICENSE-CC-BY-NC-SA) when using datasets.

So far, one dataset has been released:

* *Huawei-East-1* includes about 125429 data, which is formed with 5 attributes:vmid,cpu,memory,time and type. The Huawei-East-1 is the first standard dataset for virtual machine scheduling which can help different scheduling algorithms. To see more about this dataset, see related documents ([Huawei-East-1](./Huawei-East-1/README.md)). 

We encourage anyone to use the datasets for study or research purposes, and if you had any question when using the datasets, please file an issue on Github. Filing an issue is recommanded as the discussion would help all the community. Note that the more clearly you ask the question, the more likely you would get a clear answer.

It would be much appreciated if you could tell us once any publication using our datasets is available, as we are maintaining a list of related publicatioins for more researchers to better communicate with each other.

In future, we will try to release new datasets, please stay tuned.

## Motivation

The project has created the first standard data set of virtual machine scheduling in China. The project aims to achieve the following three objectives:


1. **Increase industry influence and promote industry development**. After creating the virtual machine scheduling standard datasets, it can continuously optimize and iterate the virtual machine scheduling algorithms under various scenarios, and increase efficiency increase with lower cost.

2. **Help Huawei's cloud development**. By promoting the development of virtual machine scheduling algorithms, the understanding of scheduling problems can be continuously deepened. Meanwhile, it can develop the platform for industry-university research cooperation , and increase sales persuasion, which attachs great importance for [HUAWEI Cloud](https://www.huaweicloud.com).


3. **Attract talents and experts to pay attention to scheduling problems**. At present, there is no standard datasets for virtual machine scheduling. This project hopes that after creating the standard datasets, it can stimulate academic cooperation, and attract more talents and experts to pay attention to scheduling problems.If you had any idea in your mind, please file an issue.

## Outcomes from the datasets

The original intention of our standard datasets for virtual machine scheduling is to provide more algorithms and projects as standards for training, so as to better promote the development of the industry. It is a huge encouragement to us to see more works using our data. 

### Projects using VM Placement Datasets

* [VMAgent](https://github.com/mail-ecnu/VMAgent), is a platform for exploiting Reinforcement Learning (RL) on Virtual Machine (VM) scheduling tasks. It is developed by the [Multi-Agent Artificial Intelligence Lab (MAIL)](https://mail-ecnu.cn) in East China Normal University and [Algorithm Innovation Lab](https://www.huaweicloud.com/lab/algorithm/home.html) in [**HUAWEI Cloud**](https://www.huaweicloud.com).VMAgent is constructed based on one month real VM scheduling dataset called [*Huawei-East-1*](https://vmagent.readthedocs.io/en/latest/simulator/dataset.html) from HUAWEI Cloud and it contains multiple practicle VM scheduling scenarios (such as Fading, Rcovering, etc).

### Papers using VM Placement Datasets

* Junjie Sheng, Shengliang Cai, Haochuan Cui, Wenhao Li, Yun Hua, Bo Jin, Wenli Zhou, Yiqiu Hu, Lei Zhu, Qian Peng, Hongyuan Zha and Xiangfeng Wang, [VMAgent: Scheduling Simulator for Reinforcement Learning](https://arxiv.org/abs/2112.04785). arXiv preprint arXiv:2112.04785, 2021.
* Junjie Sheng, Yiqiu Hu, Wenli Zhou, Lei Zhu, Bo Jin, Jun Wang and Xiangfeng Wang, [Learning to Schedule Multi-NUMA Virtual Machines via Reinforcement Learning](https://www.sciencedirect.com/science/article/abs/pii/S0031320321004349), Pattern Recognition, 121, 2021, pp.108254.


## LISCENCE
Licensed under the [CC-BY-NC](https://github.com/santisoler/cc-licenses/blob/master/LICENSE-CC-BY-NC-SA) License.

## Future works

More datasets will be released in future.