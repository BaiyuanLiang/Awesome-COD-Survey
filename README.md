# Deep Learning for Image-Level Camouflaged Object Detection: A Review of Progress, Challenges and Prospects [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)

🎯 We aim to provide a comprehensive and continuously updated collection of research papers related to **Camouflaged Object Detection (COD)**. We hope this repository will help researchers quickly understand the development of the field.

:handshake: :handshake: As COD research is rapidly evolving, some relevant works may be unintentionally omitted. We warmly welcome researchers to recommend recent or missing studies through Issues or Pull Requests, and we will update this repository regularly.

:running: :running: :running: ***KEEP UPDATING*** (<b>2026/09/28</b>)


------
------


## :open_book: Contents:

1. [Related Surveys](#Related-Surveys)
2. [Preprint Papers](#Preprint-Papers)
3. [Fully Supervised COD](#Camouflaged-Object-Detection)
4. [Weakly supervised COD](#Weakly-supervised-COD)
5. [Semi-supervised COD](#Semi-supervised-COD)
6. [Unsupervised COD](#Unsupervised-COD)
7. [Multi-modal Methods](#Multi-modal-Methods)
8. [Novel Tasks](#Novel-Tasks)
9. [Datasets](#Datasets)
10. [Reference](#Reference)



------
------


<h2 id="Related-Surveys">📚 1. Related Surveys</h2>

| **No.** | **Year** | **Pub.** | <div align="center">Title</div> | **Links** | 
:-: | :-: | :-:  | :-  | :-: 
05 | 2024 | CAAI AIR | A Survey of Camouflaged Object Detection and Beyond <br> <sup><sub>*Fengyang Xiao, Sujie Hu, Yuqi Shen, Chengyu Fang, Jinfa Huang, Chunming He, Longxiang Tang, Ziyun Yang, Xiu Li*</sub></sup> |[Paper](https://www.sciopen.com/article/10.26599/AIR.2024.9150044)/[Project](https://github.com/ChunmingHe/awesome-concealed-object-segmentation) 
04 | 2024 | Neucom | A systematic review of image-level camouflaged object detection with deep learning <br> <sup><sub>*Yanhua Liang, Guihe Qin, Minghui Sun, Xinchao Wang, Jie Yan, Zhonghan Zhang*</sub></sup> |[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231223011736)/[Project](https://github.com/Liangyh18/COD_survey)
03 | 2024 | MulSys | A survey on deep learning-based camouflaged object detection <br> <sup><sub>*Junmin Zhong, Anzhi Wang, Chunhong Ren & Jintao Wu*</sub></sup> | [Paper](https://link.springer.com/article/10.1007/s00530-024-01478-7)
02 | 2023 | VI | Advances in Deep Concealed Scene Understanding <br> <sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Peng Xu, Ming-Ming Cheng, Christos Sakaridis, Luc Van Gool*</sub></sup> | [Paper](https://link.springer.com/article/10.1007/s44267-023-00019-6)/[Project](https://github.com/DengPingFan/CSU) 
01 | 2021 | TCSVT | Rethinking Camouflaged Object Detection: Models and Datasets <br><sup><sub>*Hongbo Bi, Cong Zhang, Kang Wang, Jinghui Tong, Feng Zheng*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/9598866)



------
------


<h2 id="Preprint-Papers">📝 2. Preprint Papers</h2>




------
------



<h2 id="Camouflaged-Object-Detection">🔥 3. Fully Supervised COD</h2>




------
------



<h2 id="Weakly-supervised-COD">🔥 4. Weakly supervised COD</h2>

 **No.** | **Year** | **Pub.** | **Model** |      <div align="center">Title</div>              | **Links**                                                     
| :-----: | :------: | :------: | :-------: | :------------------------------------------------ | :----------------------------------------------------------- |  
| | 2026 | CVPR | **FCL-COD** | FCL-COD: Weakly Supervised Camouflaged Object Detection with Frequency-aware and Contrastive Learning <br> <sup><sub>*Jingchen Ni, Quan Zhang, Dan Jiang, Keyu Lv, Ke Zhang, Chun Yuan*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2026F/html/Ni_FCL-COD_Weakly_Supervised_Camouflaged_Object_Detection_with_Frequency-aware_and_Contrastive_CVPRF_2026_paper.html)\|Code
| | 2025 | TBD | **SAM-RNet** | Weakly-supervised Camouflaged Object Detection via SAM-guided Resolution Iteration Learning   <br> <sup><sub>*Y Ge, Y Zhong, Q Zhang, H Bi, T-Z Xiang*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/11216034)\|[Code](https://github.com/ZX123445/SAM-RNet)
| | 2025 | ACM MM | **PRLNet** | Progressive Representation Learning for Weakly-Supervised Camouflaged Object Detection  <br> <sup><sub>*Shuyong Gao, Qianyu Guo, Yu'ang Feng, Chunyuan Chen, Xujun Wei, Yan Wang, Wenqiang Zhang*</sub></sup>  | [Paper](https://dl.acm.org/doi/abs/10.1145/3746027.3754737)\|[Code](https://github.com/shuyonggao/PRLNet) | 
| | 2025 | TIP | **MSST**| UpGen: Unleashing Potential of Foundation Models for Training-Free Camouflage Detection via Generative Models  <br> <sup><sub>*Ji Du; Jiesheng Wu; Desheng Kong; Weiyun Liang; Fangwei Hao; Jing Xu; Bin Wang; Guiling Wang; Ping Li*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/11131534)\|Code  
| | 2025 | ECAI | **FCT-SAM** | Scribble-based Weakly Supervised Camouflaged Object Detection via SAM-guided Feature Correlation Transformer  <br> <sup><sub>*Zi-Jie Wu, Rongrong Gao and Tian-Zhu Xiang*</sub></sup>  | [Paper](https://ebooks.iospress.nl/volumearticle/75733)\|[Code](https://github.com/farewellIamLoser/FCT-SAM-WSCOD) 
| | 2025 |  NN  | **LRDNet** | Long-range diffusion for weakly camouflaged object segmentation <br>   <sup><sub>*Rui Wang, Caijuan Shi, Weixiang Gao, Changyu Duan, Ao Cai, Fei Yu, Yunchao Wei*</sub></sup>  | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0893608025007968)\|[Code](https://github.com/Ray3417/LRDNet)  
| | 2025 | KBS | **PPL**| Weakly supervised camouflaged object detection as Progressive Perception Learning   <br> <sup><sub>*Tianxin Han, Xingwei Wang, Qing Dong, Min Huang, Jie Jia, Fu Zhang*</sub></sup>  | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S095070512501038X)\|[Code](https://github.com/NGI-vision/PPL) 
| | 2025 | TCSVT | **SAM-COD+** | SAM-COD+: SAM-Guided Unified Framework for Weakly-Supervised Camouflaged Object Detection   <br> <sup><sub>*Huafeng Chen; Pengxu Wei; Guangqian Guo; Shan Gao*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/10789225)\|Code  
| | 2025 | CVIU | **SCNet** | Adaptive context mining for camouflaged object detection with scribble supervision   <br> <sup><sub>*Dongdong Zhang, Chunping Wang, Huiying Wang, Qiang Fu, Zhaorui Li*</sub></sup>  | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S1077314225001535)\|[Code](https://github.com/zcc0616/SCNet)  
| | 2024 | MM | **MiNet** | MiNet: Weakly-Supervised Camouflaged Object Detection through Mutual Interaction between Region and Edge Cues   <br> <sup><sub>*Yuzhen Niu, Lifen Yang, Rui Xu, Yuezhou Li, Yuzhong Chen*</sub></sup>  | [Paper](https://dl.acm.org/doi/10.1145/3664647.3680891)\|Code 
| | 2024 | ECCV | **WSSCOD** | Learning Camouflaged Object Detection from Noisy Pseudo Label   <br> <sup><sub>*Jin Zhang, Ruiheng Zhang, Yanjiao Shi, Zhe Cao, Nian Liu, Fahad Shahbaz Khan*</sub></sup>  | [Paper](https://arxiv.org/abs/2407.13157)\|Code 
| | 2024 | ECCV | **SAM-COD** | SAM-COD: SAM-guided Unified Framework for Weakly-Supervised Camouflaged Object Detection     <br> <sup><sub>*Huafeng Chen, Pengxu Wei, Guangqian Guo, Shan Gao*</sub></sup>  | [Paper](https://www.arxiv.org/abs/2408.10760)\|[Code](https://github.com/2231122/SAM-COD)
| | 2023 | NeurIPS | **WS-SAM** | Weakly-Supervised Concealed Object Segmentation with SAM-based Pseudo Labeling and Multi-scale Feature Grouping   <br> <sup><sub>*Chunming He, Kai Li, Yachao Zhang, Guoxia Xu, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li*</sub></sup>  | [Paper](https://arxiv.org/abs/2305.11003)\|[Code](https://github.com/ChunmingHe/WS-SAM)
| | 2023 | AAAI | **CRNet** | Weakly-Supervised Camouflaged Object Detection with Scribble Annotations  </sub> <br> <sup><sub>*Ruozhen He, Qihua Dong, Jiaying Lin, Rynson W.H. Lau*</sub></sup>  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25156)\|[Code](https://github.com/dddraxxx/Weakly-Supervised-Camouflaged-Object-Detection-with-Scribble-Annotations)



------
------



<h2 id="Semi-supervised-COD">🔥 5. Semi-supervised COD</h2>

| **No.** | **Year** | **Pub.** | **Model** |      <div align="center">Title</div>              | **Links**                                                    | 
| :-----: | :------: | :------: | :-------: | :------------------------------------------------ | :----------------------------------------------------------- |  
| | 2025 | TPAMI | <sup>`SEE`</sup>  | Segment Concealed Objects with Incomplete Supervision   <br> <sup><sub>*Chunming He, Kai Li, Yachao Zhang, Ziyun Yang, Youwei Pang, Longxiang Tang, Chengyu Fang, Yulun Zhang, Linghe Kong, Xiu Li, Sina Farsiu*</sub></sup>  | [Paper](https://arxiv.org/abs/2506.08955)\|[Code](https://github.com/ChunmingHe/SEE) 
| | 2025 | ACMMM | <sup>`ST-SAM`</sup> | ST-SAM: SAM-Driven Self-Training Framework for Semi-Supervised Camouflaged Object Detection   <br> <sup><sub>*Xihang Hu, Fuming Sun, Jiazhe Liu, Feilong Xu, Xiaoli Zhang*</sub></sup>  | [Paper](https://arxiv.org/abs/2507.23307)\|[Code](https://github.com/hu-xh/ST-SAM)
| | 2025 | ICASSP | <sup>`SILNet`</sup> | Semi-supervised Iterative Learning Network for Camouflaged Object Detection   <br> <sup><sub>*Guowen Yue; Ge Jiao; Jiahao Xiang*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/10890224)\|Code
| | 2024 | ACMMM | <sup>`-`</sup> | Semi-supervised Camouflaged Object Detection from Noisy Data `SS COD`  <br> <sup><sub>*Yuanbin Fu, Jie Ying, Houlei Lv, Xiaojie Guo*</sub></sup>  | [Paper](https://dl.acm.org/doi/abs/10.1145/3664647.3680645)\|Code 
| | 2024 | ECCV | <sup>`CamoTeacher`</sup> | CamoTeacher: Dual-Rotation Consistency Learning for Semi-Supervised Camouflaged Object Detection  <br> <sup><sub>*Xunfa Lai, Zhiyu Yang, Jie Hu, Shengchuan Zhang, Liujuan Cao, Guannan Jiang, Zhiyu Wang, Songan Zhang, Rongrong Ji*</sub></sup>  | [Paper](https://arxiv.org/abs/2408.08050)\|Code
| | 2024 | ECCV  | <sup>`WSSCOD`</sup> | Learning Camouflaged Object Detection from Noisy Pseudo Label  `WSSCOD`  <br> <sup><sub>*Jin Zhang, Ruiheng Zhang, Yanjiao Shi, Zhe Cao, Nian Liu, Fahad Shahbaz Khan*</sub></sup>  | [Paper](https://arxiv.org/abs/2407.13157)\|[Code](https://github.com/zhangjinCV/Noisy-COD) 




------
------



<h2 id="Unsupervised-COD">🔥 6. Unsupervised COD</h2>

| **No.** | **Year** | **Pub.** | **Model** |      <div align="center">Title</div>              | **Links**                                                    | 
| :-----: | :------: | :------: | :-------: | :------------------------------------------------ | :----------------------------------------------------------- |  
| | 2026 | CVPR | <small><sup>`--`</sup></small> | Beyond Weak Supervision: MLLMs-Guided Graded Knowledge Distillation for Unsupervised Camouflaged Object Detection <br> <sup><sub>*Huafeng Chen, Chenguang Zhu, Yueming Lyu, Caifeng Shan*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Chen_Beyond_Weak_Supervision_MLLMs-Guided_Graded_Knowledge_Distillation_for_Unsupervised_Camouflaged_CVPR_2026_paper.html)\|Code
| | 2026 | CVPR | <small><sup>`EReCu`</sup></small> | EReCu: Pseudo-label Evolution Fusion and Refinement with Multi-Cue Learning for Unsupervised Camouflage Detection <br> <sup><sub>*Shuo Jiang, Gaojia Zhang, Min Tan, Yufei Yin, Gang Pan*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Jiang_EReCu_Pseudo-label_Evolution_Fusion_and_Refinement_with_Multi-Cue_Learning_for_CVPR_2026_paper.html)\|Code
| | 2026 | ICML | <small><sup>`DualUCOD`</sup></small> | Unsupervised Camouflaged Object Detection with Dual-Eigenvector Spectral Pseudo-Labeling and Contrastive Refinement <br> <sup><sub>*Pingzhu Liu, Chunming He, Zunnan Xu, Chao Hao, Bo Zhao, Xingyu Shao, Jun Zhou, Zitong Yu, Xiu Li*</sub></sup> | [Paper](https://icml.cc/virtual/2026/poster/63384)\|Code
| | 2026 | TIP | <small><sup>`--`</sup></small> | Self-Anchored Progressive Framework With Noise Mitigation for Unsupervised Camouflaged Object Detection <br> <sup><sub>*Shijie Liu, Binwei Xu, Tuo Shen, Guanghui Yue, Qiuping Jiang*</sub></sup> | [Paper](https://doi.org/10.1109/tip.2026.3678379)\|Code
| | 2025 | ICCV | <sup>`RISE`</sup> | Beyond Single Images: Retrieval Self-Augmented Unsupervised Camouflaged Object Detection    <br> <sup><sub>*Ji Du, Xin Wang, Fangwei Hao, Mingyang Yu, Chunyuan Chen, Jiesheng Wu, Bin Wang, Jing Xu, Ping Li*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Du_Beyond_Single_Images_Retrieval_Self-Augmented_Unsupervised_Camouflaged_Object_Detection_ICCV_2025_paper.html)\|[Code](https://github.com/xiaohainku/RISE) | 
| | 2025 | CVPR | <sup>`UCOD-DPL`</sup> | UCOD-DPL: Unsupervised Camouflaged Object Detection via Dynamic Pseudo-label Learning   <br> <sup><sub>*Weiqi Yan, Lvhai Chen, Huaijia Kou, Shengchuan Zhang, Yan Zhang, Liujuan Cao*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Yan_UCOD-DPL_Unsupervised_Camouflaged_Object_Detection_via_Dynamic_Pseudo-label_Learning_CVPR_2025_paper.html)\|[Code](https://github.com/Heartfirey/UCOD-DPL) 
| | 2025 | CVPR | <sup>`EASE`</sup> | Shift the Lens: Environment-Aware Unsupervised Camouflaged Object Detection  <br> <sup><sub>*Ji Du, Fangwei Hao, Mingyang Yu, Desheng Kong, Jiesheng Wu, Bin Wang, Jing Xu, Ping Li*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Du_Shift_the_Lens_Environment-Aware_Unsupervised_Camouflaged_Object_Detection_CVPR_2025_paper.html)\|[Code](https://github.com/xiaohainku/EASE) 
| | 2025 | AAAI |  <sup>`SdalsNet`</sup> | SdalsNet: Self-Distilled Attention Localization and Shift Network for Unsupervised Camouflaged Object Detection  <br> <sup><sub>*Peiyao Shou, Yixiu Liu, Wei Wang, Yaoqi Sun, Zhigao Zheng, Shangdong Zhu, Chenggang Yan*</sub></sup>  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32742)\|Code
| | 2023 | ICCVW | <sup>`UCOS-DA`</sup>	| Unsupervised Camouflaged Object Segmentation as Domain Adaptation   <br> <sup><sub>*Yi Zhang; Chengyi Wu*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/ICCV2023W/OODCV/html/Zhang_Unsupervised_Camouflaged_Object_Segmentation_as_Domain_Adaptation_ICCVW_2023_paper.html)\|[Code](https://github.com/YeeZ93/UCOS-DA)



------
------




<h2 id="Multi-modal-Methods">🔥 7. Multi-modal Methods</h2> 

| **No.** | **Year** | **Pub.** | **Model** |      <div align="center">Title</div>              | :**Links**  :                                                  | 
| :-----: | :------: | :------: | :-------: | :------------------------------------------------ | :----------------------------------------------------------- | 
| | 2026 | CVPR | <small><sup>`DepthSAM`</sup></small> | Beyond Appearance: Camouflaged Object Detection via Geometric Structure <br> <sup><sub>*Jinyu Han, Changguang Wu, Fuming Sun, Jinhui Tang*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Han_Beyond_Appearance_Camouflaged_Object_Detection_via_Geometric_Structure_CVPR_2026_paper.html)\|Code
| | 2026 | ECCV | <small><sup>`VCP-DCN`</sup></small> | VCP-DCN: Beyond Visual Concealed Property via Depth Collaborative Network for Camouflaged Object Detection <br> <sup><sub>*Songsong Duan, Xi Yang, Nannan Wang*</sub></sup> | [Paper](https://arxiv.org/abs/2607.27843)\|Code
| | 2026 | TMM | <small><sup>`--`</sup></small> | Depth-Assisted Camouflaged Object Segmentation via Frequency-Domain Fusion and High-Order Interaction <br> <sup><sub>*Peng Ren, Cheng Jiang, Fuming Sun, Tian Bai*</sub></sup> | [Paper](https://doi.org/10.1109/tmm.2026.3668692)\|Code
| | 2025 | ICCV | <small><sup>`SAM-COD`</sup></small> | Improving SAM for Camouflaged Object Detection via Dual Stream Adapters <br> <sup><sub>*Jiaming Liu, Linghe Kong, Guihai Chen*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Liu_Improving_SAM_for_Camouflaged_Object_Detection_via_Dual_Stream_Adapters_ICCV_2025_paper.html)\|Code
| | 2024 | MM | <small><sup>`DSAM`</sup></small> | Exploring Deeper! Segment Anything Model with Depth Perception for Camouflaged Object Detection <br> <sup><sub>*Zhenni Yu, Xiaoqin Zhang, Li Zhao, Yi Bin, Guobao Xiao*</sub></sup> | [Paper](https://arxiv.org/abs/2407.12339)\|[Code](https://github.com/guobaoxiao/DSAM)
| | 2024 | CVPR | <small><sup>`RISNet`</sup></small> | Depth-Aware Concealed Crop Detection in Dense Agricultural Scenes <sub>![Static Badge](https://img.shields.io/badge/ACOD--12K-grey)</sub> <br> <sup><sub>*Liqiong Wang, Jinyu Yang, Yanfu Zhang, Fangyi Wang, Feng Zheng*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Wang_Depth-Aware_Concealed_Crop_Detection_in_Dense_Agricultural_Scenes_CVPR_2024_paper.html)\|[Code](https://github.com/Kki2Eve/RISNet)
| | 2023 | MM | <small><sup>`DaCOD`</sup></small> | Depth-aided Camouflaged Object Detection <br> <sup><sub>*Qingwei Wang, Jinyu Yang, Xiaosheng Yu, Fangyi Wang, Peng Chen, Feng Zheng*</sub></sup> | [Paper](https://dl.acm.org/doi/10.1145/3581783.3611874)\|[Code](https://github.com/qingwei-wang/DaCOD)
| | 2023 | ICCV | <small><sup>`PopNet`</sup></small> | Source-free Depth for Object Pop-out <br> <sup><sub>*Zongwei Wu, Danda Pani Paudel, Deng-Ping Fan, Jingjing Wang, Shuo Wang, Cedric Demonceaux, Radu Timofte, Luc Van Gool*</sub></sup> | [Paper](https://arxiv.org/abs/2212.05370)\|[Code](https://github.com/Zongwei97/PopNet)
| | 2021 | arXiv | <small><sup>`-`</sup></small> | Exploring Depth Contribution for Camouflaged Object Detection <br> <sup><sub>*Mochu Xiang, Jing Zhang, Yunqiu Lv, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2106.13217v3)\|Code
| | 2026 | TCSVT | <small><sup>`--`</sup></small> | Visible-Infrared Camouflaged Object Detection <br> <sup><sub>*Cheng Liu, Zheng Wang, Xinyu Yan, Meijun Sun, Qinghua Hu*</sub></sup> | [Paper](https://doi.org/10.1109/tcsvt.2025.3608933)\|Code
| | 2026 | TMM | <small><sup>`--`</sup></small> | Band-Mixed Edge-Aware Interaction Learning for RGB-T Camouflaged Object Detection <br> <sup><sub>*Ruiheng Zhang, Kaizheng Chen, Lu Li, Daming Zhou, Yunqiu Xu, Zheng Lin, Lixin Xu, Weitao Song*</sub></sup> | [Paper](https://doi.org/10.1109/tmm.2026.3703589)\|Code
| | 2025 | EAAI | <small><sup>`HIPFNet`</sup></small> | Polarization-based Camouflaged Object Detection with high-resolution adaptive fusion Network  <br> <sup><sub>*Xin Wang, Junfeng Xu, Jiajia Ding*</sub></sup>   | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0952197625002453)\|[Code](https://github.com/CVhfut/HIPFNet)
| | 2024 | EAAI | <small><sup>`IPNet`</sup></small> | IPNet: Polarization-based Camouflaged Object Detection via dual-flow network   <sub>![Static Badge](https://img.shields.io/badge/PCOD_1200-grey)</sub>   <br> <sup><sub>*Xin Wang, Jiajia Ding, Zhao Zhang, Junfeng Xu, Jun Gao*</sub></sup>   | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0952197623014872)\|[Code](https://github.com/CVhfut/PCOD_1200) 
| | 2023 | PRL | <small><sup>`PolarNet`</sup></small> | Polarization-based Camouflaged Object Detection  <sub>![Static Badge](https://img.shields.io/badge/PCOD-grey)</sub>  <br> <sup><sub>*Xin Wang, Zhao Zhang, Jun Gao*</sub></sup>   | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0167865523002532)\|[Code](https://github.com/CVhfut/Polar-COD)




------
------



<h2 id="Novel-Tasks">✨ 8. Novel Tasks</h2>

| **No.** | **Year** | **Pub.** | **Model** |      <div align="center">Title</div>              | **Links**                                                    | 
| :-----: | :------: | :------: | :-------: | :------------------------------------------------ | :----------------------------------------------------------- |  
| | 2026 | TCSVT | <small><sup>`--`</sup></small> | Beyond Semantics: Multiscale Interaction Network for Referring Camouflaged Object Detection <br> <sup><sub>*Xiandong Wang, Tianqi Guo, Fengqin Yao, Qi Guo, Shengke Wang, Qing Cai, Junyu Dong, Guoqiang Zhong*</sub></sup> | [Paper](https://doi.org/10.1109/tcsvt.2026.3670168)\|Code
| | --  | arXiv | <sup>`MLKG`</sup> | Large Model Based Referring Camouflaged Object Detection   <br> <sup><sub>*Shupeng Cheng, Ge-Peng Ji, Pengda Qin, Deng-Ping Fan, Bowen Zhou, Peng Xu*</sub></sup>  | [Paper](https://arxiv.org/abs/2311.17122)\|Code   
| | 2025  | TIP | <sup>`UAT`</sup> | Uncertainty-Aware Transformer for Referring Camouflaged Object Detection  <br> <sup><sub>*Ranwan Wu, Tian-Zhu Xiang, Guo-Sen Xie, Rongrong Gao, Xiangbo Shu, Fang Zhao, Ling Shao*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/11080234)\|[Code](https://github.com/CVL-hub/UAT)
| | 2025 | WACV | <sup>`CIRCOD`</sup> | CIRCOD: Co-Saliency Inspired Referring Camouflaged Object Discovery  <br> <sup><sub>*Avi Gupta; Koteswar Rao Jerripothula; Tammam Tillo*</sub></sup>  | [Paper](https://www.computer.org/csdl/proceedings-article/wacv/2025/108300i320/25KnoFtUNIA)\|[Code](https://github.com/avigupta2798/CIRCOD/)    
| | 2025  | TPAMI | <sup>`R2CNet`</sup> | Referring Camouflaged Object Detection  <sub>![Static Badge](https://img.shields.io/badge/R2C7K-grey)</sub>  <br> <sup><sub>*Xuying Zhang, Bowen Yin, Zheng Lin, Qibin Hou, Deng-Ping Fan, Ming-Ming Cheng*</sub></sup>  | [Paper](https://arxiv.org/abs/2306.07532)\|[Code](https://github.com/zhangxuying1004/RefCOD)   
| | 2024 | ICME | <sup>`RPMA`</sup> | Reference Prompted Model Adaptation for Referring Camouflaged Object Detection   <br> <sup><sub>*Xuewei Liu; Shaofei Huang; Ruipu Wu; Hengyuan Zhao; Duo Xu; Xiaoming Wei, Jizhong Han, Si Liu*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/10687557)\|Code


------
------



<h2 id="Datasets">📂 9. Datasets</h2>



------
------



<h2 id="Reference">🔗 10. Reference</h2>


------
------
# 👏👏👏 Thanks to the above authors for their excellent work！
