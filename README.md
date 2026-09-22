# Deep Learning for Image-Level Camouflaged Object Detection: A Review of Progress, Challenges and Prospects [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)

🎯 We aim to provide a comprehensive and continuously updated collection of research papers related to Camouflaged Object Detection (COD). We hope this repository will help researchers quickly understand the development of the field.

:handshake: :handshake: As COD research is rapidly evolving, some relevant works may be unintentionally omitted. We warmly welcome researchers to recommend recent or missing studies through Issues or Pull Requests, and we will update this repository regularly.

:running: :running: :running: ***KEEP UPDATING*** (<b>2026/09/28</b>)


------
------


## :open_book: Contents:

1. [Related Surveys](#Related-Surveys)
2. [Preprint Papers](#Preprint-Papers)
3. [Camouflaged Object Detection (COD)](#Camouflaged-Object-Detection)
4. [Weakly-supervised COD](#Weakly-supervised-COD)
5. [Semi-supervised COD](#Semi-supervised-COD)
6. [Unsupervised COD](#Unsupervised-COD)
7. [Multi-modal Methods](#Multi-modal-Methods)
8. [Novel Tasks](#Novel-Tasks)
9. [Datasets](#Datasets)
10. [Reference](#Reference)



------
------


<h2 id="Related-Surveys">📚 1. Related Surveys</h2>

**No.** | **Year** | **Pub.** | <div align="center">Title</div> | **Links** 
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



<h2 id="Camouflaged-Object-Detection">🔥 3. Camouflaged Object Detection (COD)</h2>




------
------



<h2 id="Weakly-supervised-COD">🔥 4. Weakly-supervised COD</h2>

| **No.** | **Year** | **Pub.** | **Model** |      <div align="center">Title</div>              | **Links**                                                    |
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





------
------



<h2 id="Unsupervised-COD">🔥 6. Unsupervised COD</h2>




------
------




<h2 id="Multi-modal-Methods">🔥 7. Multi-modal Methods</h2> 




------
------



<h2 id="Novel-Tasks">✨ 8. Novel Tasks</h2>



------
------



<h2 id="Datasets">📂 9. Datasets</h2>



------
------



<h2 id="Reference">🔗 10. Reference</h2>


------
------

