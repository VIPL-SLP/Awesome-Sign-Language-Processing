# Awesome Sign Language Processing     

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 

A curated list of sign language procesing (e.g., sign language recognition, sign language translation) and related area (e.g., speech translation, motion generation) resources. The [old version](README_old.md) can be found here.

- [Wiki] [Sign Language](https://en.wikipedia.org/wiki/Sign_language)
- [Wiki] [Sign Language Recognition](https://en.wikipedia.org/wiki/Sign_language_recognition)
- [Wiki] [Gesture_recognition](https://en.wikipedia.org/wiki/Gesture_recognition)
- [Wiki] [Sign Language Tranlsation](https://en.wikipedia.org/wiki/Machine_translation_of_sign_languages)
- [Resource] [jinwchoi/awesome-action-recognition](https://github.com/jinwchoi/awesome-action-recognition)
- [Resource] [xinghaochen/awesome-hand-pose-estimation](https://github.com/xinghaochen/awesome-hand-pose-estimation)
- [Resource] [OpenHuman-ai/awesome-gesture_generation](https://github.com/OpenHuman-ai/awesome-gesture_generation)
- [Resource] [zzw922cn/awesome-speech-recognition-speech-synthesis-papers](https://github.com/zzw922cn/awesome-speech-recognition-speech-synthesis-papers)

## Contents
- [Conference Paper](#conference-paper)
  - [Sign Language Recognition](#sign-language-recognition)
  - [Sign Language Translation](#sign-language-translation)
  - [Sign Language Production](#sign-language-production)
  - [Other Sign Language Topic](#other-sign-language-topic)
  - [Co-speech Gesture Generation](#co-speech-gesture-generation)
  - [Gesture Recognition](#gesture-recognition)
- [Sign Language Workshop](#sign-language-workshop)
- [Dataset](#dataset)

## Conference Paper

### Sign Language Recognition
- [ICLR 2026 Submission] BANZ-FS: BANZSL FINGERSPELLING DATASET. [[paper]](https://openreview.net/forum?id=GMR9BUsPbq)     
*Submission15125 Authors*
- [ICLR 2026 Submission] EmoSign: A Multimodal Dataset for Understanding Emotions in American Sign Language. [[paper]](https://openreview.net/forum?id=khHNHzRjMy)      
*Submission14816 Authors*
- [ICLR 2026 Submission] LexSign: Learning Sign Language from Lexical Descriptions. [[paper]](https://openreview.net/forum?id=mOFGOK6Vmo)     
*Submission7787 Authors*
- [EMNLP 2025] Logos as a Well-Tempered Pre-train for Sign Language Recognition. [[paper]](https://aclanthology.org/2025.emnlp-main.1238/)    
*Ilya Ovodov, Petr Surovtsev, Karina Kvanchiani, Alexander Kapitanov, Alexander Nagaev*
- [EMNLP Findings 2025] Rethinking Sign Language Translation: The Impact of Signer Dependence on Model Evaluation. [[paper]](https://aclanthology.org/2025.findings-emnlp.997/)    
*Keren Artiaga, Sabyasachi Kamila, Haithem Afli, Conor Lynch, Mohammed Hasanuzzaman*
- [ICCV 2025] Cross-View Isolated Sign Language Recognition via View Synthesis and Feature Disentanglement. [[paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Shen_Cross-View_Isolated_Sign_Language_Recognition_via_View_Synthesis_and_Feature_ICCV_2025_paper.html)    
*Xin Shen, Xinyu Wang, Lei Shen, Kaihao Zhang, Xin Yu*
- [CVPR 2025] VSNet: Focusing on the Linguistic Characteristics of Sign Language. [[paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Li_VSNet_Focusing_on_the_Linguistic_Characteristics_of_Sign_Language_CVPR_2025_paper.html)     
*YuHao Li, Xinyue Chen, Hongkai Li, Xiaorong Pu, Peng Jin, Yazhou Ren*
- [OpenReview]  Representing Signs as Signs: One-Shot ISLR to Facilitate Functional Sign Language Technologies. [[paper]](https://openreview.net/forum?id=flgrH5nK4H)    
  *Toon Vandendriessche, Mathieu De Coster, Annelies Lejon, Joni Dambre*
- [NeurIPS 2024] MM-WLAuslan: Multi-View Multi-Modal Word-Level Australian Sign Language Recognition Dataset. [[paper]](https://openreview.net/forum?id=tPsw4NeLZx)     
*Xin Shen, Heming Du, Hongwei Sheng, Shuyun Wang, Hui Chen, Huiqiang Chen, Zhuojie Wu, Xiaobiao Du, Jiaying Ying, Ruihan Lu, Qingzheng Xu, Xin Yu*
- [EMNLP 2024]  SignCLIP: Connecting Text and Sign Language by Contrastive Learning. [[paper]](https://aclanthology.org/2024.emnlp-main.518/)    
  *Zifan Jiang, Gerard Sant, Amit Moryossef, Mathias Müller, Rico Sennrich, Sarah Ebling*
- [EMNLP 2024]  Towards Online Continuous Sign Language Recognition and Translation. [[paper]](https://aclanthology.org/2024.emnlp-main.619/)    
  *Ronglai Zuo, Fangyun Wei, Brian Mak*
- [CVPR 2024]  SignGraph: A Sign Sequence is Worth Graphs of Nodes. [[paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Gan_SignGraph_A_Sign_Sequence_is_Worth_Graphs_of_Nodes_CVPR_2024_paper.html) [[code]](https://github.com/gswycf/SignGraph/tree/main)    
  *Shiwei Gan, Yafeng Yin, Zhiwei Jiang, Hongkai Wen, Kang Xia, Lei Xie, Sanglu Lu*
- [EMNLP Findings 2023]  Handshape-Aware Sign Language Recognition: Extended Datasets and Exploration of Handshape-Inclusive Methods. [[paper]](https://aclanthology.org/2023.findings-emnlp.198/)    
  *Xuan Zhang, Kevin Duh*
- [Complete List of Sign Language Recognition](./complete_list/sign_language_recognition.md)

### Sign Language Translation
- [ICLR 2026 Submission]T2G-Reasoner: Deep Reasoning for Text-to-Gloss Translation. [[paper]](https://openreview.net/forum?id=9CS4Fy8j6Y)     
*Submission23323 Authors*
- [ICLR 2026 Submission] Sigma: Semantically Informative Pre-training for Skeleton-based Sign Language Understanding. [[paper]](https://openreview.net/group?id=ICLR.cc/2026/Conference#tab-active-submissions)      
*Submission11776 Authors*
- [EMNLP 2025] PoseStitch-SLT: Linguistically Inspired Pose-Stitching for End-to-End Sign Language Translation. [[paper]](https://aclanthology.org/2025.emnlp-main.698/)     
*Abhinav Joshi, Vaibhav Sharma, Sanjeet Singh, Ashutosh Modi*
- [WMT 2025] SONAR-SLT: Multilingual Sign Language Translation via Language-Agnostic Sentence Embedding Supervision. [[paper]](https://aclanthology.org/2025.wmt-1.18/)     
*Yasser Hamidullah, Shakib Yazdani, Cennet Oguz, Josef Van Genabith, Cristina España-Bonet*
- [NeurIPS 2025] Geo-Sign: Hyperbolic Contrastive Regularisation for Geometrically Aware Sign Language Translation. [[paper]](https://openreview.net/forum?id=WkUzrUsqR9)     
*Edward Fish, Richard Bowden*
- [NeurIPS 2025] Bridging Sign and Spoken Languages: Pseudo Gloss Generation for Sign Language Translation. [[paper]](https://openreview.net/forum?id=p6Huickfj7)     
*Jianyuan Guo, Peike Li, Trevor Cohn*
- [ICCV 2025] Leveraging the Power of MLLMs for Gloss-Free Sign Language Translation. [[paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Kim_Leveraging_the_Power_of_MLLMs_for_Gloss-Free_Sign_Language_Translation_ICCV_2025_paper.html)     
*Jungeun Kim, Hyeongwoo Jeon, Jongseong Bae, Ha Young Kim*
- [ACM MM 2025] Gloss Matters: Unlocking the Potential of Non-Autoregressive Sign Language Translation. [[paper]](https://dl.acm.org/doi/10.1145/3746027.3755319)     
*Zhihao Wang, Shiyu Liu, Zhiwei He, Kangjie Zheng, Liangying Shao, Junfeng Yao, Jinsong Su*
- [BMVC 2025] Beyond Gloss: A Hand-Centric Framework for Gloss-Free Sign Language Translation. [[paper]](https://arxiv.org/abs/2507.23575)     
*Sobhan Asasi, Mohamed Ilyas Lakhal, Ozge Mercanoglu Sincan, Richard Bowden*
- [ACL 2025] SHuBERT: Self-Supervised Sign Language Representation Learning via Multi-Stream Cluster Prediction. [[paper]](https://aclanthology.org/2025.acl-long.1397/)     
*Shester Gueuwou, Xiaodan Du, Greg Shakhnarovich, Karen Livescu, Alexander H. Liu*
- [ACL 2025] Multilingual Gloss-free Sign Language Translation: Towards Building a Sign Language Foundation Model. [[paper]](https://aclanthology.org/2025.acl-short.43/)     
*Sihan Tan, Taro Miyazaki, Kazuhiro Nakadai*
- [ACL Findings 2025] SignMusketeers: An Efficient Multi-Stream Approach for Sign Language Translation at Scale. [[paper]](https://aclanthology.org/2025.findings-acl.1157/)     
*Shester Gueuwou, Xiaodan Du, Greg Shakhnarovich, Karen Livescu*
- [Complete List of Sign Language Translation](./complete_list/sign_language_translation.md)

### Sign Language Production
- [ICLR 2026 Submission] SignAligner: Harmonizing Complementary Pose Modalities for Coherent Sign Language Generation. [[paper]](https://openreview.net/forum?id=LnKLT5apxB)     
*Submission1706 Authors*
- [NeurIPS 2025] Advanced Sign Language Video Generation with Compressed and Quantized Multi-Condition Tokenization. [[paper]](https://openreview.net/forum?id=6FHvr5hJdd)   
  *Cong Wang, Zexuan Deng, Zhiwei Jiang, Yafeng Yin, Fei Shen, Zifeng Cheng, Shiping Ge, Shiwei Gan, Qing Gu*
- [ICCV 2025] GReg: Geometry-Aware Region Refinement for Sign Language Video Generation. [[paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Shi_GReg_Geometry-Aware_Region_Refinement_for_Sign_Language_Video_Generation_ICCV_2025_paper.html)   
  *Tongkai Shi, Lianyu Hu, Fanhua Shang, Liqing Gao, Wei Feng*
- [ICCV 2025] Signs as Tokens: A Retrieval-Enhanced Multilingual Sign Language Generator. [[paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Zuo_Signs_as_Tokens_A_Retrieval-Enhanced_Multilingual_Sign_Language_Generator_ICCV_2025_paper.html)   
  *Ronglai Zuo, Rolandos Alexandros Potamias, Evangelos Ververas, Jiankang Deng, Stefanos Zafeiriou*
- [CVPR 2025] Discrete to Continuous: Generating Smooth Transition Poses from Sign Language Observations. [[paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Tang_Discrete_to_Continuous_Generating_Smooth_Transition_Poses_from_Sign_Language_CVPR_2025_paper.html)   
  *Shengeng Tang, Jiayi He, Lechao Cheng, Jingjing Wu, Dan Guo, Richang Hong*
- [EMNLP Findings 2024] Word-Conditioned 3D American Sign Language Motion Generation. [[paper]](https://aclanthology.org/2024.findings-emnlp.584/)   
  *Lu Dong, Xiao Wang, Ifeoma Nwogu*
- [ECCV 2024] A Simple Baseline for Spoken Language to Sign Language Translation with 3D Avatars. [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06499.pdf)   
  *Ronglai Zuo, Fangyun Wei, Zenggui Chen, Brian Mak, Jiaolong Yang, Xin Tong*
- [ECCV 2024] Pose Guided Fine-Grained Sign Language Video Generation. [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/09947.pdf)   
  *Tongkai Shi, Lianyu Hu, Fanhua Shang, Jichao Feng, liu peidong, Wei Feng*
- [ECCV 2024] SignGen: End-to-End Sign Language Video Generation with Latent Diffusion. [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06988.pdf)   
  *Fan Qi, Yu Duan, Changsheng Xu, Huaiwen Zhang*
- [ACL 2024] T2S-GPT: Dynamic Vector Quantization for Autoregressive Sign Language Production from Text. [[paper]](https://aclanthology.org/2024.acl-long.183/)     
  *Aoxiong Yin, Haoyuan Li, Kai Shen, Siliang Tang, Yueting Zhuang*
- [ACL Findings 2024] MS2SL: Multimodal Spoken Data-Driven Continuous Sign Language Production. [[paper]](https://aclanthology.org/2024.findings-acl.432/)     
  *Jian Ma, Wenguan Wang, Yi Yang, Feng Zheng*
- [Complete List of Sign Language Production](./complete_list/sign_language_production.md)

### Other Sign Language Topic
- [WMT 2025] Meaningful Pose-Based Sign Language Evaluation. [[paper]](https://aclanthology.org/2025.wmt-1.4/)   
  *Zifan Jiang, Colin Leong, Amit Moryossef, Oliver Cory, Maksym Ivashechkin, Neha Tarigopula, Biao Zhang, Anne Göhring, Annette Rios, Rico Sennrich, Sarah Ebling*
- [EMNLP 2025] Improving Handshape Representations for Sign Language Processing: A Graph Neural Network Approach. [[paper]](https://aclanthology.org/2025.emnlp-main.1483/)     
*Alessa Carbo, Eric Nalisnick*
- [EMNLP Findings 2025] Investigating Dictionary Expansion for Video-based Sign Language Dictionaries. [[paper]](https://aclanthology.org/2025.findings-emnlp.1243/)     
*Aashaka Desai, Daniela Massiceti, Richard Ladner, Hal Daumé Iii, Danielle Bragg, Alex Xijie Lu*
- [ACM MM 2025] Sentence-level Segmentation for Long Sign Language Videos with Captions. [[paper]](https://dl.acm.org/doi/10.1145/3746027.3755080)     
*Bowen Guo, Shiwei Gan, Yafeng Yin, Xiao Liu, Zhiwei Jiang, Shunmei Meng*
- [ACL Findings 2025] Sign2Vis: Automated Data Visualization from Sign Language. [[paper]](https://aclanthology.org/2025.findings-acl.918/)     
*Yao Wan, Yang Wu, Zhen Li, Guobiao Zhang, Hongyu Zhang, Zhou Zhao, Hai Jin, April Wang*
- [ACL Findings 2025] 2M-BELEBELE: Highly Multilingual Speech and American Sign Language Comprehension Dataset. [[paper]](https://aclanthology.org/2025.findings-acl.569/)     
*Marta R. Costa-jussà, Bokai YU, Pierre Andrews, Belen Alastruey, Necati Cihan Camgoz, Joe Chuang, Jean Maillard, Christophe Ropers, Arina Turkatenko, Carleigh Wood*
- [ACL Findings 2025] Large Language Models as Sign Language Interfaces: Mitigating the Requests of Deaf Users of LLMs in a Hearing-Centric World. [[paper]](https://openreview.net/forum?id=8HGvHrfFDx)     
*Mert Inan, Anthony Sicilia, Malihe Alikhani*
- [EMNLP Findings 2024] Gloss2Text: Sign Language Gloss translation using LLMs and Semantically Aware Label Smoothing.  [[paper]](https://aclanthology.org/2024.findings-emnlp.947/)   
  *Pooya Fayyazsanavi, Antonios Anastasopoulos, Jana Kosecka*
- [EMNLP 2024] Unsupervised Discrete Representations of American Sign Language.  [[paper]](https://aclanthology.org/2024.emnlp-main.1104/)   
  *Artem Abzaliev, Rada Mihalcea*
- [EMNLP 2024] Studying and Mitigating Biases in Sign Language Understanding Models.  [[paper]](https://aclanthology.org/2024.emnlp-main.17/)   
  *Katherine Atwell, Danielle Bragg, Malihe Alikhani*
- [ECCV 2024] Uncertainty-aware sign language video retrieval with probability distribution modeling.  [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06074.pdf)   
  *Xuan Wu, Hongxiang Li, yuanjiang luo, Xuxin Cheng, Xianwei Zhuang, Meng Cao, Keren Fu*
- [ECCV 2024] SignAvatars: A Large-scale 3D Sign Language Holistic Motion Dataset and Benchmark.  [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/00653.pdf)   
  *Zhengdi Yu, Shaoli Huang, yongkang cheng, Tolga Birdal*
- [ACL 2024] Semi-Supervised Spoken Language Glossification. [[paper]](https://aclanthology.org/2024.acl-long.504/)    
  *Huijie Yao, Wengang Zhou, Hao Zhou, Houqiang Li*
- [ACL 2024] American Sign Language Handshapes Reflect Pressures for Communicative Efficiency. [[paper]](https://aclanthology.org/2024.acl-long.839/)    
  *Kayo Yin, Terry Regier, Dan Klein*
- [EMNLP Findings 2023] Enhancing Accessible Communication: from European Portuguese to Portuguese Sign Language. [[paper]](https://aclanthology.org/2023.findings-emnlp.766/)    
  *Catarina Sousa, Luisa Coheur, Mara Moita*
- [CVPR 2023]  CiCo: Domain-Aware Sign Language Retrieval via Cross-Lingual Contrastive Learning. [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Bao_CiCo_Domain-Aware_Sign_Language_Retrieval_via_Cross-Lingual_Contrastive_Learning_CVPR_2023_paper.html)[[code]](https://github.com/FangyunWei/SLRT/tree/main/CiCo)     
*Yiting Cheng, Fangyun Wei, Jianmin Bao, Dong Chen, Wenqiang Zhang*
- [CVPR 2023]  Ham2Pose: Animating Sign Language Notation into Pose Sequences. [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Arkushin_Ham2Pose_Animating_Sign_Language_Notation_Into_Pose_Sequences_CVPR_2023_paper.html)     
*Rotem Shalev Arkushin, Amit Moryossef, Ohad Fried*

### Co-speech Gesture Generation
- [NeurIPS 2025] PyraMotion: Attentional Pyramid-Structured Motion Integration for Co-Speech 3D Gesture Synthesis. [[paper]](https://openreview.net/forum?id=QJSrgYcf4b)     
*Zhizhuo Yin, Yuk Hang Tsui, Pan Hui*
- [ICCV 2025] Democratizing High-Fidelity Co-Speech Gesture Video Generation. [[paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Yang_Democratizing_High-Fidelity_Co-Speech_Gesture_Video_Generation_ICCV_2025_paper.html)    
*Xu Yang, Shaoli Huang, Shenbo Xie, Xuelin Chen, Yifei Liu, Changxing Ding*
- [ICCV 2025] GestureHYDRA: Semantic Co-speech Gesture Synthesis via Hybrid Modality Diffusion Transformer and Cascaded-Synchronized Retrieval-Augmented Generation. [[paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Yang_GestureHYDRA_Semantic_Co-speech_Gesture_Synthesis_via_Hybrid_Modality_Diffusion_Transformer_ICCV_2025_paper.html)    
*Quanwei Yang, Luying Huang, Kaisiyuan Wang, Jiazhi Guan, Shengyi He, Fengguo Li, Hang Zhou, Lingyun Yu, Yingying Li, Haocheng Feng, Hongtao Xie*
- [ICCV 2025] GestureLSM: Latent Shortcut based Co-Speech Gesture Generation with Spatial-Temporal Modeling. [[paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Liu_GestureLSM_Latent_Shortcut_based_Co-Speech_Gesture_Generation_with_Spatial-Temporal_Modeling_ICCV_2025_paper.html)    
*Pinxin Liu, Luchuan Song, Junhua Huang, Haiyang Liu, Chenliang Xu*
- [ICCV 2025] SemGes: Semantics-aware Co-Speech Gesture Generation using Semantic Coherence and Relevance Learning. [[paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Liu_SemGes_Semantics-aware_Co-Speech_Gesture_Generation_using_Semantic_Coherence_and_Relevance_ICCV_2025_paper.html)    
*Lanmiao Liu, Esam Ghaleb, asli ozyurek, Zerrin Yumak*
- [ACM MM 2025] Contextual Gesture: Co-Speech Gesture Video Generation through Context-aware Gesture Representation [[paper]](https://dl.acm.org/doi/10.1145/3746027.3755140)    
*Pinxin Liu, Pengfei Zhang, Hyeongwoo Kim, Pablo Garrido, Ari Shapiro, Kyle Olszewski*
- [CVPR 2025] Retrieving Semantics from the Deep: an RAG Solution for Gesture Synthesis. [[paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Mughal_Retrieving_Semantics_from_the_Deep_an_RAG_Solution_for_Gesture_CVPR_2025_paper.html)    
  *Muhammad Hamza Mughal, Rishabh Dabral, Merel CJ Scholman, Vera Demberg, Christian Theobalt*
- [CVPR 2025] Co-Speech Gesture Video Generation with Implicit Motion-Audio Entanglement. [[paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Li_Co-Speech_Gesture_Video_Generation_with_Implicit_Motion-Audio_Entanglement_CVPR_2025_paper.html)    
  *Xinjie Li, Ziyi Chen, Xinlu Yu, Iek-Heng Chu, Peng Chang, Jing Xiao*
- [CVPR 2025] HOP: Heterogeneous Topology-based Multimodal Entanglement for Co-Speech Gesture Generation. [[paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Cheng_HOP_Heterogeneous_Topology-based_Multimodal_Entanglement_for_Co-Speech_Gesture_Generation_CVPR_2025_paper.html)    
  *Hongye Cheng, Tianyu Wang, guangsi shi, Zexing Zhao, Yanwei Fu*
- [ACM MM 2025] Realistic-Gesture: Co-Speech Gesture Video Generation through Semantic-aware Gesture Representation. [[paper]](https://openreview.net/forum?id=EXsiGFkwV6)    
  *Pinxin Liu, Pengfei Zhang, Hyeongwoo Kim, Pablo Garrido, Ari Shapiro, Kyle Olszewski*
- [Complete List of Co-speech Gesture Generation](./complete_list/co_speech_gesture_generation.md)

### Gesture Recognition
- [NeurIPS 2025] Doodle to Detect: A Goofy but Powerful Approach to Skeleton-based Hand Gesture Recognition. [[paper]](https://openreview.net/forum?id=u8SXX5ITE6)     
*Sang Hoon Han, Seonho Lee, Hyeok Nam, Jae Hyeon Park, Min Hee Cha, Min Geol Kim, Hyunse Lee, Sangyeon Ahn, Chae moon ju, Sung In Cho*
- [CVPR 2025] Ges3ViG: Incorporating Pointing Gestures into Language-Based 3D Visual Grounding for Embodied Reference Understanding. [[paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Mane_Ges3ViG__Incorporating_Pointing_Gestures_into_Language-Based_3D_Visual_Grounding_CVPR_2025_paper.html)      
*Atharv Mahesh Mane, Dulanga Weerakoon, Vigneshwaran Subbaraju, Sougata Sen, Sanjay Sarma, Archan Misra*
- [CVPR 2025] SocialGesture: Delving into Multi-person Gesture Understanding. [[paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Cao_SocialGesture_Delving_into_Multi-person_Gesture_Understanding_CVPR_2025_paper.html)      
*Xu Cao, Pranav Virupaksha, Wenqi Jia, Bolin Lai, Fiona Ryan, Sangmin Lee, James Rehg*
- [OpenReview] Revisiting Noise Resilience Strategies in Gesture Recognition: Short-Term Enhancement in Surface Electromyographic Signal Analysis. [[paper]](https://openreview.net/forum?id=B7eHRsuTSh)      
*Weiyu Guo, Ziyue Qiao, Ying Sun, Hui Xiong*
- [ICCV 2023] Learning Robust Representations with Information Bottleneck and Memory Network for RGB-D-based Gesture Recognition. [[paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Li_Learning_Robust_Representations_with_Information_Bottleneck_and_Memory_Network_for_ICCV_2023_paper.html)      
*Yunan Li, Huizhou Chen, Guanwen Feng, Qiguang Miao*
- [ICCV 2023] Data-Free Class-Incremental Hand Gesture Recognition. [[paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Aich_Data-Free_Class-Incremental_Hand_Gesture_Recognition_ICCV_2023_paper.html)      
*Shubhra Aich, Jesus Ruiz-Santaquiteria, Zhenyu Lu, Prachi Garg, K J Joseph, Alvaro Fernandez Garcia, Vineeth N Balasubramanian, Kenrick Kin, Chengde Wan, Necati Cihan Camgoz, Shugao Ma, Fernando De la Torre*
- [BMVC 2022] Towards more efficient few-shot learning based human gesture recognition via dynamic vision sensors. [[paper]](https://bmvc2022.mpi-inf.mpg.de/0938.pdf)    
*Linglin Jing, Yifan Wang, Tailin Chen, Shirin Dora, Zhigang Ji, Hui Fang*    
- [BMVC 2022] Continuous Hand Gesture Recognition using Deep Coarse
and Fine Hand Features. [[paper]](https://bmvc2022.mpi-inf.mpg.de/1055.pdf)        
*Hazem Wannous, Jean-Philippe Vandeborre* 
- [CVPR 2022] LD-ConGR: A Large RGB-D Video Dataset for Long-Distance Continuous Gesture Recognition. [[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Liu_LD-ConGR_A_Large_RGB-D_Video_Dataset_for_Long-Distance_Continuous_Gesture_CVPR_2022_paper.html)     
  *Dan Liu; Libo Zhang; Yanjun Wu*
- [AAAI 2022] Learning Unseen Emotions from Gestures via Semantically-Conditioned Zero-Shot Perception with Adversarial Autoencoders. [[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Ahuja_Low-Resource_Adaptation_for_Personalized_Co-Speech_Gesture_Generation_CVPR_2022_paper.html)    
  *Abhishek Banerjee, Uttaran Bhattacharya, Aniket Bera*
- [Complete List of Gesture Recognition](./complete_list/gesture_recognition.md)

## Sign Language Workshop
- [[CVPR SLRTP 2025]](https://slrtpworkshop.github.io) Sign language recognition, translation & production.
- [[ECCV SLRTP 2022]](https://slrtp-2022.github.io/) Sign language recognition, translation & production.
- [[ECCV SLRTP 2020]](https://slrtp.com/) Sign language recognition, translation & production. [[Accepted papers]](SLRTP_acccepted_list.md)
- [[WWW CV-SLR 2025]](https://uq-cvlab.github.io/MM-WLAuslan-Dataset/docs/en/www) Cross-View Isolated Sign Language Recognition Challenge
- [[ICCV MSLR 2025]](https://multimodal-sign-language-recognition.github.io/ICCV-2025/) 1st Multimodal Sign Language Recognition Workshop
- [[ICCV ACVR 2023]](https://iplab.dmi.unict.it/acvr2023/program) Eleventh International Workshop on Assistive Computer Vision and Robotics
- [[CVPR ChaLearn-SLR 2021]](https://chalearnlap.cvc.uab.cat/workshop/42/description/) 2021 ChaLearn Looking at People Sign Language Recognition in the Wild Workshop at CVPR
- [[ACL LoResMT 2024]](https://www.loresmt.org/) The Seventh Workshop on Technologies for Machine Translation of Low-Resource Languages

## Dataset

|    Dataset   |          | Task |            | Modality |       | Statistic |        |            |
|:------------:|:--------:|:--------:|:----------:|:--------:|:-----:|:---------:|:------:|:----------:|
| Name | Language | Isolated | Continuous |    RGB   | Depth |  #Signers | #Vocab | #Sequences |
|  DGS Kinect  |    DGS   |     √    |            |     √    |   √   |     15    |   40   |    3,000   |
|    ASLLVD    |    ASL   |     √    |            |     √    |       |     6     |  2,742 |    9,794   |
|  DEVISIGN-L  |    CSL   |     √    |            |     √    |   √   |     8     |  2,000 |   24,000   |
|    CSL-500   |    CSL   |     √    |            |     √    |       |     50    |   500  |   125,000  |
|     MSASL    |    ASL   |     √    |            |     √    |       |    222    |  1,000 |   25,513   |
|   WLASL2000  |    ASL   |     √    |            |     √    |       |    119    |  2,000 |   21,083   |
|     AUTSL    |    TSL   |     √    |            |     √    |   √   |     43    |   226  |   38,336   |
|    SIGNUM    |    DGS   |          |      √     |     √    |   √   |     9     |   455  |    2,340   |
|   Phoenix14  |    DGS   |          |      √     |     √    |       |     9     |  1,200 |    6,841   |
|     KETI     |    KSL   |          |      √     |     √    |       |     14    |   524  |   15,672   |
|      GSL     |    GSL   |          |      √     |     √    |   √   |     7     |   310  |   10,290   |
|    CSL-100   |    CSL   |          |      √     |     √    |       |     50    |  2,000 |   25,000   |
|   CSL-Daily  |    CSL   |          |      √     |     √    |       |     10    |  2,000 |   20,654   |
|    BSL-1K    |    BSL   |          |      √     |     √    |       |     40    |  1,064 |    273K    |
|   VRT-NEWS   |    VGT   |          |      √     |     √    |       |     9     |  6,325 |    7,174   |
|   How2Sign   |    BSL   |          |      √     |     √    |   √   |     11    | 15,686 |   35,191   |
|     BOBSL    |    BSL   |          |      √     |     √    |       |     39    |  2,281 |    452K    |
|    OpenASL   |    ASL   |          |      √     |     √    |       |    220    | 33,549 |   98,417   |
|  YouTube-ASL |    ASL   |          |      √     |     √    |       |   >2519   |   60K  |   11,093   |
