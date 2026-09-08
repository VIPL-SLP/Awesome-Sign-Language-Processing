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
- [Awesome Sign Language Processing](#awesome-sign-language-processing)
  - [Contents](#contents)
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
- [BMVC 2026] Recognising BSL Fingerspelling in Continuous Signing Sequences. [[paper]](https://arxiv.org/abs/2603.19523) [[code]](https://github.com/chan-alyssa/Fingerspelling-Recognition)  
*Alyssa Chan, Taein Kwon, Andrew Zisserman*
- [BMVC 2026] RAIDAL: Redundancy-Aware Information Density Active Learning for CTC-Based Continuous Sign Language Recognition. [[paper pending]](https://bmvc2026.bmva.org/programme/accepted_papers/)  
*Full author list pending.*
- [BMVC 2026] SMART: MLLM-guided Temporal Alignment for Unifying Sign Language Recognition and Spotting. [[paper]](https://arxiv.org/abs/2608.25493)  
*Eunjee Choi, JungHoon Sung, Seongwhan Cho, Chu Xin, Younggeun Choi*
- [ICLR 2026] BANZ-FS: BANZSL FINGERSPELLING DATASET. [[paper]](https://openreview.net/forum?id=GMR9BUsPbq)     
*Xin Shen, Yan Ke, Xinyu Wang, Xin Yu*
- [EMNLP 2025] Logos as a Well-Tempered Pre-train for Sign Language Recognition. [[paper]](https://aclanthology.org/2025.emnlp-main.1238/) [[code]](https://github.com/ai-forever/Logos)    
*Ilya Ovodov, Petr Surovtsev, Karina Kvanchiani, Alexander Kapitanov, Alexander Nagaev*
- [EMNLP Findings 2025] Rethinking Sign Language Translation: The Impact of Signer Dependence on Model Evaluation. [[paper]](https://aclanthology.org/2025.findings-emnlp.997/)    
*Keren Artiaga, Sabyasachi Kamila, Haithem Afli, Conor Lynch, Mohammed Hasanuzzaman*
- [ICCV 2025] Cross-View Isolated Sign Language Recognition via View Synthesis and Feature Disentanglement. [[paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Shen_Cross-View_Isolated_Sign_Language_Recognition_via_View_Synthesis_and_Feature_ICCV_2025_paper.html)    
*Xin Shen, Xinyu Wang, Lei Shen, Kaihao Zhang, Xin Yu*
- [CVPR 2025] VSNet: Focusing on the Linguistic Characteristics of Sign Language. [[paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Li_VSNet_Focusing_on_the_Linguistic_Characteristics_of_Sign_Language_CVPR_2025_paper.html) [[code]](https://github.com/atinyboy/VSNet)     
*YuHao Li, Xinyue Chen, Hongkai Li, Xiaorong Pu, Peng Jin, Yazhou Ren*
- [NeurIPS 2024] MM-WLAuslan: Multi-View Multi-Modal Word-Level Australian Sign Language Recognition Dataset. [[paper]](https://openreview.net/forum?id=tPsw4NeLZx)     
*Xin Shen, Heming Du, Hongwei Sheng, Shuyun Wang, Hui Chen, Huiqiang Chen, Zhuojie Wu, Xiaobiao Du, Jiaying Ying, Ruihan Lu, Qingzheng Xu, Xin Yu*
- [EMNLP 2024]  SignCLIP: Connecting Text and Sign Language by Contrastive Learning. [[paper]](https://aclanthology.org/2024.emnlp-main.518/) [[code]](https://github.com/J22Melody/fairseq/tree/main/examples/MMPT)    
  *Zifan Jiang, Gerard Sant, Amit Moryossef, Mathias Müller, Rico Sennrich, Sarah Ebling*
- [EMNLP 2024]  Towards Online Continuous Sign Language Recognition and Translation. [[paper]](https://aclanthology.org/2024.emnlp-main.619/) [[code]](https://github.com/FangyunWei/SLRT/tree/main/Online)    
  *Ronglai Zuo, Fangyun Wei, Brian Mak*
- [CVPR 2024]  SignGraph: A Sign Sequence is Worth Graphs of Nodes. [[paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Gan_SignGraph_A_Sign_Sequence_is_Worth_Graphs_of_Nodes_CVPR_2024_paper.html) [[code]](https://github.com/gswycf/SignGraph/tree/main)    
  *Shiwei Gan, Yafeng Yin, Zhiwei Jiang, Hongkai Wen, Kang Xia, Lei Xie, Sanglu Lu*
- [EMNLP Findings 2023]  Handshape-Aware Sign Language Recognition: Extended Datasets and Exploration of Handshape-Inclusive Methods. [[paper]](https://aclanthology.org/2023.findings-emnlp.198/) [[code]](https://github.com/Este1le/slr_handshape)    
  *Xuan Zhang, Kevin Duh*
- [Complete List of Sign Language Recognition](./complete_list/sign_language_recognition.md)

### Sign Language Translation
- [ECCV 2026] Q-BridgeNet: A Quantization Network for Cross-Lingual Sign Language Translation. [[paper]](https://arxiv.org/abs/2607.11215)  
*Liqian Feng, Lintao Wang, Xiaochen Liu, Anusha Withana, Ken-Tye Yong, Dehui Kong, Zhiyong Wang, Kun Hu*
- [ECCV 2026] Video-Text Alignment Model for Sign Language Translation. [[paper]](https://arxiv.org/abs/2607.09126) [[code]](https://github.com/junyi2005/vtamo)  
*Junyi Hu, Zhewen He, Haomian Huang, Yi Fang, Aoxiang Yang*
- [ECCV 2026] SIGNET: Motion-Level Knowledge Transfer for Cross-Language Sign Language Translation. [[paper]](https://arxiv.org/abs/2606.28626) [[code]](https://github.com/elsobhano/SIGNET)  
*Sobhan Asasi, Ozge Mercanoglu Sincan, Richard Bowden*
- [ECCV 2026] SignBind-LLM: Multi-Stage Modality Fusion for Sign Language Translation. [[paper]](https://arxiv.org/abs/2509.00030)  
*Marshall Thomas, Edward Fish, Richard Bowden*
- [ECCV 2026] Event Stream-based Sign Language Translation: A High-Definition Benchmark Dataset and A Novel Baseline. [[paper]](https://arxiv.org/abs/2408.10488) [[code]](https://github.com/Event-AHU/OpenESL/tree/main/EvSLT)  
*Shiao Wang, Xiao Wang, Duoqing Yang, Yao Rong, Fuling Wang, Jianing Li, Lin Zhu, Bo Jiang*
- [ACL 2026] SAME: Signer-Aware Mixture-of-Experts for Test-Time Adaptation in Sign Language Translation. [[paper]](https://aclanthology.org/2026.acl-long.973/)  
*Lujia Yang, Weicai Yan, Yongbo He, Qifei Zhang, Tao Jin, Jinshan Zhang, Meng Xi, Jianwei Yin*
- [ACL Findings 2026] Can Small Vision–Language Models Perform Sign Language Translation? [[paper]](https://aclanthology.org/2026.findings-acl.1609/) [[code]](https://github.com/Analroy/vlm4slt)  
*Anal Roy Chowdhury, Debarshi Kumar Sanyal*
- [ACL Findings 2026] J-Shuwa: A Large-Scale Web-Collected Japanese Sign Language-Japanese Parallel Corpus. [[paper]](https://aclanthology.org/2026.findings-acl.1821/) [[code]](https://github.com/SpaJune/J-Shuwa)  
*Junwen Mo, MinhDuc Vo, Noriki Nishida, Shin’ichi Satoh, Hideki Nakayama*
- [ACL 2026] Think in Latent Thoughts: A New Paradigm for Gloss-Free Sign Language Translation. [[paper]](https://aclanthology.org/2026.acl-long.454/) [[code]](https://github.com/fletcherjiang/SignThought)     
*Yiyang Jiang, Li Zhang, Xiao-Yong Wei, Li Qing*
- [ACL 2026] Selective Contrastive Learning For Gloss Free Sign Language Translation. [[paper]](https://aclanthology.org/2026.acl-long.2116/)     
*Chang Hao Lai, Rui Zhao, Xuewen Zhong, Jinsong Su, Yidong Chen*
- [CVPR 2026] Learning Effective Sign Features without Text for Gloss-free Sign Language Translation. [[paper]](https://cvpr.thecvf.com/virtual/2026/poster/39809)     
*Shiwei Gan, Xiao Liu, Yafeng Yin, Nan Liu, Kuizhuang Liu, Desibieer Tuerdaken, Zhiwei Jiang, Lei Xie, Sanglu Lu, Hongkai Wen*
- [CVPR 2026] BoostSLT: Boosting Sign Language Translation via a Plug-and-Play Diffusion-Based Semantic Enhancer. [[paper]](https://cvpr.thecvf.com/virtual/2026/oral/40375) [[code]](https://github.com/K1sna/BoostSLT)     
*Changzhou Han, Wanlun Ma, XI TANG, Kun Hu, Sheng Wen, Yang Xiang*
- [WACV 2026] Large Sign Language Models: Toward 3D American Sign Language Translation. [[paper]](https://openaccess.thecvf.com/content/WACV2026/papers/Zhang_Large_Sign_Language_Models_Toward_3D_American_Sign_Language_Translation_WACV_2026_paper.pdf)     
*Sen Zhang, Xiaoxiao He, Di Liu, Zhaoyang Xia, Mingyu Zhao, Chaowei Tan, Vivian Li, Bo Liu, Dimitris N. Metaxas, Mubbasir Kapadia*
- [NeurIPS 2025] MixSignGraph: A Sign Sequence is Worth Mixed Graphs of Nodes. [[paper]](https://openreview.net/forum?id=YjZYMHvlRs) [[code]](https://github.com/gswycf/SignLanguage/tree/main/MixSignGraph)     
*Shiwei Gan, Yafeng Yin, Zhiwei Jiang, Lei Xie, Sanglu Lu, Hongkai Wen*
- [EMNLP 2025] PoseStitch-SLT: Linguistically Inspired Pose-Stitching for End-to-End Sign Language Translation. [[paper]](https://aclanthology.org/2025.emnlp-main.698/) [[code]](https://github.com/Exploration-Lab/PoseStich-SLT)     
*Abhinav Joshi, Vaibhav Sharma, Sanjeet Singh, Ashutosh Modi*
- [WMT 2025] SONAR-SLT: Multilingual Sign Language Translation via Language-Agnostic Sentence Embedding Supervision. [[paper]](https://aclanthology.org/2025.wmt-1.18/)     
*Yasser Hamidullah, Shakib Yazdani, Cennet Oguz, Josef Van Genabith, Cristina España-Bonet*
- [NeurIPS 2025] Geo-Sign: Hyperbolic Contrastive Regularisation for Geometrically Aware Sign Language Translation. [[paper]](https://openreview.net/forum?id=WkUzrUsqR9) [[code]](https://github.com/ed-fish/Geo-Sign)     
*Edward Fish, Richard Bowden*
- [NeurIPS 2025] Bridging Sign and Spoken Languages: Pseudo Gloss Generation for Sign Language Translation. [[paper]](https://openreview.net/forum?id=p6Huickfj7)     
*Jianyuan Guo, Peike Li, Trevor Cohn*
- [ICCV 2025] Leveraging the Power of MLLMs for Gloss-Free Sign Language Translation. [[paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Kim_Leveraging_the_Power_of_MLLMs_for_Gloss-Free_Sign_Language_Translation_ICCV_2025_paper.html) [[code]](https://github.com/hwjeon98/MMSLT)     
*Jungeun Kim, Hyeongwoo Jeon, Jongseong Bae, Ha Young Kim*
- [ACM MM 2025] Gloss Matters: Unlocking the Potential of Non-Autoregressive Sign Language Translation. [[paper]](https://dl.acm.org/doi/10.1145/3746027.3755319) [[code]](https://github.com/XMUDeepLIT/GLevT)     
*Zhihao Wang, Shiyu Liu, Zhiwei He, Kangjie Zheng, Liangying Shao, Junfeng Yao, Jinsong Su*
- [BMVC 2025] Beyond Gloss: A Hand-Centric Framework for Gloss-Free Sign Language Translation. [[paper]](https://bmvc2025.bmva.org/proceedings/626/) [[code]](https://github.com/elsobhano/BeyondGloss)     
*Sobhan Asasi, Mohamed Ilyes Lakhal, Ozge Mercanoglu Sincan, Richard Bowden*
- [ACL 2025] SHuBERT: Self-Supervised Sign Language Representation Learning via Multi-Stream Cluster Prediction. [[paper]](https://aclanthology.org/2025.acl-long.1397/) [[code]](https://github.com/ShesterG/SHuBERT)     
*Shester Gueuwou, Xiaodan Du, Greg Shakhnarovich, Karen Livescu, Alexander H. Liu*
- [ACL 2025] Multilingual Gloss-free Sign Language Translation: Towards Building a Sign Language Foundation Model. [[paper]](https://aclanthology.org/2025.acl-short.43/) [[code]](https://github.com/Claire874/Gloss-free-MLSLT)     
*Sihan Tan, Taro Miyazaki, Kazuhiro Nakadai*
- [ACL Findings 2025] SignMusketeers: An Efficient Multi-Stream Approach for Sign Language Translation at Scale. [[paper]](https://aclanthology.org/2025.findings-acl.1157/)     
*Shester Gueuwou, Xiaodan Du, Greg Shakhnarovich, Karen Livescu*
- [Complete List of Sign Language Translation](./complete_list/sign_language_translation.md)

### Sign Language Production
- [BMVC 2026] SignFML: Gloss-Free Sign Language Production via Multi-Scale Latent Flow Matching. [[paper pending]](https://bmvc2026.bmva.org/programme/accepted_papers/)  
  *Kieu Vo, Tho Quan*
- [BMVC 2026] M3T: Discrete Multi-Modal Motion Tokens for Sign Language Production. [[paper]](https://arxiv.org/abs/2603.23617)  
  *Alexandre Symeonidis-Herzig, Jianhe Low, Ozge Mercanoglu Sincan, Richard Bowden*
- [BMVC 2026] SignRR: Retrieve and Refine Real Motion for Sign Language Production. [[paper]](https://arxiv.org/abs/2608.28568)  
  *Fidel Omar Tito Cruz, Angie Sanchez Marquina, Summy Farfan, Gissella Bejarano*
- [ECCV 2026] SignSparK: Efficient Multilingual Sign Language Production via Sparse Keyframe Learning. [[paper]](https://arxiv.org/abs/2603.10446) [[code]](https://github.com/JianHe0628/SignSparK)  
  *Jian He Low, Alexandre Symeonidis-Herzig, Maksym Ivashechkin, Ozge Mercanoglu Sincan, Richard Bowden*
- [ECCV 2026] SignRefine: Adapting Foundational Video Models for Sign Language Generation. [[paper pending]](https://eccv.ecva.net/virtual/2026/poster/4976)  
  *Anton Pelykh, Edward Fish, Ozge Mercanoglu Sincan, Richard Bowden*
- [ECCV 2026] SIGNER: Temporally Grounded Sign Language Generation via Time-Resolved Conditioning. [[paper]](https://arxiv.org/abs/2506.07460)  
  *Taeryung Lee, Hyeongjin Nam, Gyeongsik Moon, Kyoung Mu Lee*
- [ACL 2026] Hybrid Autoregressive-Diffusion Model for Real-Time Sign Language Production. [[paper]](https://aclanthology.org/2026.acl-long.31/)  
  *Maoxiao Ye, Xinfeng Ye, Sathiamoorthy Manoharan*
- [ACL 2026] Stable Signer: Hierarchical Sign Language Generative Model. [[paper]](https://aclanthology.org/2026.acl-long.659/)  
  *Sen Fang, Yalin Feng, Hongbin Zhong, Yanxin Zhang, Dimitris N. Metaxas*
- [WACV 2026] DexAvatar: 3D Sign Language Reconstruction with Hand and Body Pose Priors. [[paper]](https://openaccess.thecvf.com/content/WACV2026/papers/Kundu_DexAvatar_3D_Sign_Language_Reconstruction_with_Hand_and_Body_Pose_WACV_2026_paper.pdf) [[code]](https://github.com/kaustesseract/DexAvatar)   
  *Kaustubh Kundu, Hrishav Bakul Barua, Lucy Robertson-Bell, Zhixi Cai, Kalin Stefanov*
- [CVPR 2026] Focal–General Diffusion Model with Semantic Consistent Guidance for Sign Language Production. [[paper]](https://cvpr.thecvf.com/virtual/2026/poster/39783) [[code]](https://github.com/yuyiheng-eu/FGDM-main)   
  *Yiheng Yu, Sheng Liu, Yuan Feng, Zhelun Jin, Yining Jiang, Min Xu*
- [CVPR 2026] SignPR: A Progressive Vector-Quantized Diffusion Framework for Sign Language Production. [[paper]](https://cvpr.thecvf.com/virtual/2026/poster/38631)   
  *Xiao Liu, Shiwei Gan, Yafeng Yin, Bowen Guo, Zhiwei Jiang, Shunmei Meng, Lei Xie, Sanglu Lu*
- [WACV 2026] Disentangle and Regularize: Sign Language Production with Articulator-Based Disentanglement and Channel-Aware Regularization. [[paper]](https://arxiv.org/abs/2504.06610)   
  *Sumeyye Meryem Tasyurek, Tugce Kiziltepe, Hacer Yalim Keles*
- [NeurIPS 2025] Advanced Sign Language Video Generation with Compressed and Quantized Multi-Condition Tokenization. [[paper]](https://openreview.net/forum?id=6FHvr5hJdd) [[code]](https://github.com/umnooob/signvip)   
  *Cong Wang, Zexuan Deng, Zhiwei Jiang, Yafeng Yin, Fei Shen, Zifeng Cheng, Shiping Ge, Shiwei Gan, Qing Gu*
- [ICCV 2025] GReg: Geometry-Aware Region Refinement for Sign Language Video Generation. [[paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Shi_GReg_Geometry-Aware_Region_Refinement_for_Sign_Language_Video_Generation_ICCV_2025_paper.html)   
  *Tongkai Shi, Lianyu Hu, Fanhua Shang, Liqing Gao, Wei Feng*
- [ICCV 2025] Signs as Tokens: A Retrieval-Enhanced Multilingual Sign Language Generator. [[paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Zuo_Signs_as_Tokens_A_Retrieval-Enhanced_Multilingual_Sign_Language_Generator_ICCV_2025_paper.html) [[code]](https://github.com/2000ZRL/SOKE)   
  *Ronglai Zuo, Rolandos Alexandros Potamias, Evangelos Ververas, Jiankang Deng, Stefanos Zafeiriou*
- [CVPR 2025] Discrete to Continuous: Generating Smooth Transition Poses from Sign Language Observations. [[paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Tang_Discrete_to_Continuous_Generating_Smooth_Transition_Poses_from_Sign_Language_CVPR_2025_paper.html)   
  *Shengeng Tang, Jiayi He, Lechao Cheng, Jingjing Wu, Dan Guo, Richang Hong*
- [EMNLP Findings 2024] Word-Conditioned 3D American Sign Language Motion Generation. [[paper]](https://aclanthology.org/2024.findings-emnlp.584/) [[code]](https://github.com/dongludeeplearning/wsigngen)   
  *Lu Dong, Xiao Wang, Ifeoma Nwogu*
- [ECCV 2024] A Simple Baseline for Spoken Language to Sign Language Translation with 3D Avatars. [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06499.pdf) [[code]](https://github.com/FangyunWei/SLRT/tree/main/Spoken2Sign)   
  *Ronglai Zuo, Fangyun Wei, Zenggui Chen, Brian Mak, Jiaolong Yang, Xin Tong*
- [ECCV 2024] Pose Guided Fine-Grained Sign Language Video Generation. [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/09947.pdf)   
  *Tongkai Shi, Lianyu Hu, Fanhua Shang, Jichao Feng, liu peidong, Wei Feng*
- [ECCV 2024] SignGen: End-to-End Sign Language Video Generation with Latent Diffusion. [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06988.pdf) [[code]](https://github.com/mingtiannihao/SignGen)   
  *Fan Qi, Yu Duan, Changsheng Xu, Huaiwen Zhang*
- [ACL 2024] T2S-GPT: Dynamic Vector Quantization for Autoregressive Sign Language Production from Text. [[paper]](https://aclanthology.org/2024.acl-long.183/)     
  *Aoxiong Yin, Haoyuan Li, Kai Shen, Siliang Tang, Yueting Zhuang*
- [ACL Findings 2024] MS2SL: Multimodal Spoken Data-Driven Continuous Sign Language Production. [[paper]](https://aclanthology.org/2024.findings-acl.432/)     
  *Jian Ma, Wenguan Wang, Yi Yang, Feng Zheng*
- [Complete List of Sign Language Production](./complete_list/sign_language_production.md)

### Other Sign Language Topic
- [BMVC 2026] SignMatch: Matching Dictionary Signs to Continuous Sign Language Video. [[paper]](https://arxiv.org/abs/2609.01886)  
*Ryan Wong, Youngjoon Jang, Liliane Momeni, Gül Varol, Andrew Zisserman*
- [ECCV 2026] SignNet-1M: Large-Scale Multilingual Sign Language Video Dataset with Downstream Benchmarks. [[paper]](https://arxiv.org/abs/2606.24361) [[code]](https://github.com/openhe-hub/SignNet-1M)  
*Zhewen He, Junyi Hu, Haomian Huang, Zhenhua Li, Yushen Liu, Yi Fang*
- [ECCV 2026] BackTranslation2.0 - A Linguistically Motivated Metric to Assess Sign Language Production. [[paper]](https://eccv.ecva.net/virtual/2026/poster/4935)  
*Oliver Cory, Maksym Ivashechkin, Oline Ranum, Jian He Low, Edward Fish, Anton Pelykh, Karahan Sahin, Ozge Mercanoglu Sincan, Richard Bowden*
- [ACL 2026] Semantic Hardness Is Not Visual Hardness: Sign-Aware Hard Negative Mining for Sign Language Retrieval. [[paper]](https://aclanthology.org/2026.acl-long.1302/) [[code]](https://github.com/joonmy/SAN)  
*Junmyeong Lee, Chan Hur, ChangSu Choi, Sukmin Cho, Fitsum Gaim, Eui Jun Hwang, Hoyun Song, KyungTae Lim*
- [ACL 2026] Segment, Embed, and Align: A Universal Recipe for Aligning Subtitles to Signing. [[paper]](https://aclanthology.org/2026.acl-long.1401/) [[code]](https://github.com/J22Melody/SEA)  
*Zifan Jiang, Youngjoon Jang, Liliane Momeni, Gül Varol, Sarah Ebling, Andrew Zisserman*
- [ACL 2026] The Visual Iconicity Challenge: Evaluating Vision-Language Models on Sign Language Form–Meaning Mapping. [[paper]](https://aclanthology.org/2026.acl-long.1907/) [[code]](https://github.com/kelesonur/Visual_Iconicity_Challenge)  
*Onur Keleş, Asli Ozyurek, Gerardo Ortega, Kadir Gökgöz, Esam Ghaleb*
- [ACL 2026] Sign-Language Datasets at Scale: A Comprehensive Survey on Resources, Benchmarks, and Annotation Standards. [[paper]](https://aclanthology.org/2026.acl-long.1928/)  
*Yiming Ni, Zhi-Qi Cheng, Jiayu Li, Wei Cheng*
- [OpenReview] LexSign: Learning Sign Language from Lexical Descriptions. [[paper]](https://openreview.net/forum?id=mOFGOK6Vmo)     
*Honggang Zou, Yuecong Min, Peiqi Jiao, Xilin Chen*
- [ACL 2026] CNSL-bench: Benchmarking the Sign Language Understanding Capabilities of MLLMs on Chinese National Sign Language. [[paper]](https://aclanthology.org/2026.acl-long.1896/)     
*Rui Zhao, Xuewen Zhong, Xiaoyun Zheng, Jinsong Su, Yidong Chen*
- [CVPR 2026] OpenFS: Multi-Hand-Capable Fingerspelling Recognition with Implicit Signing-Hand Detection and Frame-Wise Letter-Conditioned Synthesis. [[paper]](https://arxiv.org/abs/2602.22949) [[code]](https://github.com/AIRC-KETI/OpenFS)     
*Junuk Cha, Jihyeon Kim, Han-Mu Park*
- [CVPR 2026] Text-Driven 3D Hand Motion Generation from Sign Language Data. [[paper]](https://arxiv.org/abs/2508.15902) [[code]](https://github.com/leorebensabath/HandMDM)     
*Léore Bensabath, Mathis Petrovich, Gül Varol*
- [WMT 2025] Meaningful Pose-Based Sign Language Evaluation. [[paper]](https://aclanthology.org/2025.wmt-1.4/) [[code]](https://github.com/sign-language-processing/pose-evaluation)   
  *Zifan Jiang, Colin Leong, Amit Moryossef, Oliver Cory, Maksym Ivashechkin, Neha Tarigopula, Biao Zhang, Anne Göhring, Annette Rios, Rico Sennrich, Sarah Ebling*
- [EMNLP 2025] Improving Handshape Representations for Sign Language Processing: A Graph Neural Network Approach. [[paper]](https://aclanthology.org/2025.emnlp-main.1483/)     
*Alessa Carbo, Eric Nalisnick*
- [EMNLP Findings 2025] Investigating Dictionary Expansion for Video-based Sign Language Dictionaries. [[paper]](https://aclanthology.org/2025.findings-emnlp.1243/)     
*Aashaka Desai, Daniela Massiceti, Richard Ladner, Hal Daumé Iii, Danielle Bragg, Alex Xijie Lu*
- [ACM MM 2025] Sentence-level Segmentation for Long Sign Language Videos with Captions. [[paper]](https://dl.acm.org/doi/10.1145/3746027.3755080)     
*Bowen Guo, Shiwei Gan, Yafeng Yin, Xiao Liu, Zhiwei Jiang, Shunmei Meng*
- [ACL Findings 2025] Sign2Vis: Automated Data Visualization from Sign Language. [[paper]](https://aclanthology.org/2025.findings-acl.918/)     
*Yao Wan, Yang Wu, Zhen Li, Guobiao Zhang, Hongyu Zhang, Zhou Zhao, Hai Jin, April Wang*
- [ACL Findings 2025] 2M-BELEBELE: Highly Multilingual Speech and American Sign Language Comprehension Dataset. [[paper]](https://aclanthology.org/2025.findings-acl.569/) [[code]](https://github.com/facebookresearch/belebele/tree/main/2M-belebele)     
*Marta R. Costa-jussà, Bokai YU, Pierre Andrews, Belen Alastruey, Necati Cihan Camgoz, Joe Chuang, Jean Maillard, Christophe Ropers, Arina Turkatenko, Carleigh Wood*
- [ACL Findings 2025] Large Language Models as Sign Language Interfaces: Mitigating the Requests of Deaf Users of LLMs in a Hearing-Centric World. [[paper]](https://openreview.net/forum?id=8HGvHrfFDx)     
*Mert Inan, Anthony Sicilia, Malihe Alikhani*
- [EMNLP Findings 2024] Gloss2Text: Sign Language Gloss translation using LLMs and Semantically Aware Label Smoothing.  [[paper]](https://aclanthology.org/2024.findings-emnlp.947/) [[code]](https://github.com/pooyafayyaz/Gloss2Text)   
  *Pooya Fayyazsanavi, Antonios Anastasopoulos, Jana Kosecka*
- [EMNLP 2024] Unsupervised Discrete Representations of American Sign Language.  [[paper]](https://aclanthology.org/2024.emnlp-main.1104/) [[code]](https://github.com/MichiganNLP/discrete_asl)   
  *Artem Abzaliev, Rada Mihalcea*
- [EMNLP 2024] Studying and Mitigating Biases in Sign Language Understanding Models.  [[paper]](https://aclanthology.org/2024.emnlp-main.17/)   
  *Katherine Atwell, Danielle Bragg, Malihe Alikhani*
- [ECCV 2024] Uncertainty-aware sign language video retrieval with probability distribution modeling.  [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06074.pdf) [[code]](https://github.com/xua222/UPRet)   
  *Xuan Wu, Hongxiang Li, yuanjiang luo, Xuxin Cheng, Xianwei Zhuang, Meng Cao, Keren Fu*
- [ECCV 2024] SignAvatars: A Large-scale 3D Sign Language Holistic Motion Dataset and Benchmark.  [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/00653.pdf) [[code]](https://github.com/ZhengdiYu/SignAvatars)   
  *Zhengdi Yu, Shaoli Huang, yongkang cheng, Tolga Birdal*
- [ACL 2024] Semi-Supervised Spoken Language Glossification. [[paper]](https://aclanthology.org/2024.acl-long.504/) [[code]](https://github.com/yaohj11/S3LG)    
  *Huijie Yao, Wengang Zhou, Hao Zhou, Houqiang Li*
- [ACL 2024] American Sign Language Handshapes Reflect Pressures for Communicative Efficiency. [[paper]](https://aclanthology.org/2024.acl-long.839/) [[code]](https://github.com/kayoyin/asl-efficiency)    
  *Kayo Yin, Terry Regier, Dan Klein*
- [EMNLP Findings 2023] Enhancing Accessible Communication: from European Portuguese to Portuguese Sign Language. [[paper]](https://aclanthology.org/2023.findings-emnlp.766/) [[code]](https://github.com/lcoheur/EP2LGP5.0)    
  *Catarina Sousa, Luisa Coheur, Mara Moita*
- [CVPR 2023]  CiCo: Domain-Aware Sign Language Retrieval via Cross-Lingual Contrastive Learning. [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Bao_CiCo_Domain-Aware_Sign_Language_Retrieval_via_Cross-Lingual_Contrastive_Learning_CVPR_2023_paper.html)[[code]](https://github.com/FangyunWei/SLRT/tree/main/CiCo)     
*Yiting Cheng, Fangyun Wei, Jianmin Bao, Dong Chen, Wenqiang Zhang*
- [CVPR 2023]  Ham2Pose: Animating Sign Language Notation into Pose Sequences. [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Arkushin_Ham2Pose_Animating_Sign_Language_Notation_Into_Pose_Sequences_CVPR_2023_paper.html) [[code]](https://github.com/rotem-shalev/Ham2Pose)     
*Rotem Shalev Arkushin, Amit Moryossef, Ohad Fried*

### Co-speech Gesture Generation
- [ECCV 2026] CtrlCoMo: Controllable Co-Speech Motion Generation with Gesture–Action Disentanglement. [[paper pending]](https://eccv.ecva.net/virtual/2026/poster/5059)  
*Xinghan Wang, Ming Zhou, Yanbo Zheng, Youjiang Xu, Yuan Zhang, Mingyuan Gao, Nan Zhuang, Yadong Mu*
- [ECCV 2026] HolisticSemGes: Semantic Grounding of Holistic Co-Speech Gesture Generation with Contrastive Flow-Matching. [[paper]](https://arxiv.org/abs/2603.26553)  
*Lanmiao Liu, Esam Ghaleb, Aslı Özyürek, Zerrin Yumak*
- [ECCV 2026] RoboGesture: Real-Time Semantic-aligned Co-Speech Gestures Generation for Humanoid Interaction. [[paper]](https://arxiv.org/abs/2608.28693)  
*Zifan Wang, Ziang Ren, Pengyang Shi, Zirui Wang, Chenghuai Lin, Tianze Wang, Zekun Qi, Liangliang Zhao, He Wang, Li Yi*
- [ECCV 2026] SICAGE: Speaker-Independent Culture-Aware Gesture Generation using TED4C-L Dataset. [[paper]](https://arxiv.org/abs/2606.30001) [[code]](https://github.com/arielgj95/SICAGE)  
*Ariel Gjaci, Antonio Sgorbissa, Vittorio Murino*
- [ECCV 2026] StreamTalk: Streaming Co-Speech Gesture Generation with Key-Pose Anchoring. [[paper]](https://arxiv.org/abs/2608.01643) [[code]](https://github.com/Xiangyue-Zhang/StreamTalk)  
*Jianfang Li, Xiangyue Zhang, Jiaxu Zhang, Kaixing Yang, Steven Hoi*
- [AAAI 2026] Streaming Generation of Co-Speech Gestures via Accelerated Rolling Diffusion. [[paper]](https://arxiv.org/abs/2503.10488) [[code]](https://github.com/andrewbo29/co-speech-gestures-rolling-diffusion)     
*Evgeniia Vu, Andrei Boiarov, Dmitry Vetrov*
- [CVPR 2026] CoordSpeaker: Exploiting Gesture Captioning for Coordinated Caption-Empowered Co-Speech Gesture Generation. [[paper]](https://cvpr.thecvf.com/virtual/2026/poster/39470)     
*Fengyi Fang, Sicheng Yang, Wenming Yang*
- [CVPR 2026] LiveGesture Streamable Co-Speech Gesture Generation Model. [[paper]](https://arxiv.org/abs/2604.10927)     
*Muhammad Usama Saleem, Mayur Jagdishbhai Patel, Ekkasit Pinyoanuntapong, Zhongxing Qin, Li Yang, Hongfei Xue, Ahmed Helmy, Chen Chen, Pu Wang*
- [NeurIPS 2025] PyraMotion: Attentional Pyramid-Structured Motion Integration for Co-Speech 3D Gesture Synthesis. [[paper]](https://openreview.net/forum?id=QJSrgYcf4b) [[code]](https://github.com/Williamy946/PyraMotion)     
*Zhizhuo Yin, Yuk Hang Tsui, Pan Hui*
- [ICCV 2025] Democratizing High-Fidelity Co-Speech Gesture Video Generation. [[paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Yang_Democratizing_High-Fidelity_Co-Speech_Gesture_Video_Generation_ICCV_2025_paper.html) [[code]](https://github.com/MPI-Lab/Democratizing-CSG)    
*Xu Yang, Shaoli Huang, Shenbo Xie, Xuelin Chen, Yifei Liu, Changxing Ding*
- [ICCV 2025] GestureHYDRA: Semantic Co-speech Gesture Synthesis via Hybrid Modality Diffusion Transformer and Cascaded-Synchronized Retrieval-Augmented Generation. [[paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Yang_GestureHYDRA_Semantic_Co-speech_Gesture_Synthesis_via_Hybrid_Modality_Diffusion_Transformer_ICCV_2025_paper.html) [[code]](https://github.com/hlyyyyy/GestureHydra)    
*Quanwei Yang, Luying Huang, Kaisiyuan Wang, Jiazhi Guan, Shengyi He, Fengguo Li, Hang Zhou, Lingyun Yu, Yingying Li, Haocheng Feng, Hongtao Xie*
- [ICCV 2025] GestureLSM: Latent Shortcut based Co-Speech Gesture Generation with Spatial-Temporal Modeling. [[paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Liu_GestureLSM_Latent_Shortcut_based_Co-Speech_Gesture_Generation_with_Spatial-Temporal_Modeling_ICCV_2025_paper.html) [[code]](https://github.com/andypinxinliu/GestureLSM)    
*Pinxin Liu, Luchuan Song, Junhua Huang, Haiyang Liu, Chenliang Xu*
- [ICCV 2025] SemGes: Semantics-aware Co-Speech Gesture Generation using Semantic Coherence and Relevance Learning. [[paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Liu_SemGes_Semantics-aware_Co-Speech_Gesture_Generation_using_Semantic_Coherence_and_Relevance_ICCV_2025_paper.html) [[code]](https://github.com/marcos452/SemGes)    
*Lanmiao Liu, Esam Ghaleb, asli ozyurek, Zerrin Yumak*
- [ACM MM 2025] Contextual Gesture: Co-Speech Gesture Video Generation through Context-aware Gesture Representation [[paper]](https://dl.acm.org/doi/10.1145/3746027.3755140)    
*Pinxin Liu, Pengfei Zhang, Hyeongwoo Kim, Pablo Garrido, Ari Shapiro, Kyle Olszewski*
- [CVPR 2025] Retrieving Semantics from the Deep: an RAG Solution for Gesture Synthesis. [[paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Mughal_Retrieving_Semantics_from_the_Deep_an_RAG_Solution_for_Gesture_CVPR_2025_paper.html) [[code]](https://github.com/m-hamza-mughal/RAG-Gesture)    
  *Muhammad Hamza Mughal, Rishabh Dabral, Merel CJ Scholman, Vera Demberg, Christian Theobalt*
- [CVPR 2025] Co-Speech Gesture Video Generation with Implicit Motion-Audio Entanglement. [[paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Li_Co-Speech_Gesture_Video_Generation_with_Implicit_Motion-Audio_Entanglement_CVPR_2025_paper.html) [[code]](https://github.com/abcdvzz/imae-open-source)    
  *Xinjie Li, Ziyi Chen, Xinlu Yu, Iek-Heng Chu, Peng Chang, Jing Xiao*
- [CVPR 2025] HOP: Heterogeneous Topology-based Multimodal Entanglement for Co-Speech Gesture Generation. [[paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Cheng_HOP_Heterogeneous_Topology-based_Multimodal_Entanglement_for_Co-Speech_Gesture_Generation_CVPR_2025_paper.html) [[code]](https://github.com/Chenghyyy/HOP-Heterogeneous-Topology-based-Multimodal-Entanglement-for-Co-Speech-Gesture-Generation)    
  *Hongye Cheng, Tianyu Wang, guangsi shi, Zexing Zhao, Yanwei Fu*
- [ACM MM 2025] Realistic-Gesture: Co-Speech Gesture Video Generation through Semantic-aware Gesture Representation. [[paper]](https://openreview.net/forum?id=EXsiGFkwV6)    
  *Pinxin Liu, Pengfei Zhang, Hyeongwoo Kim, Pablo Garrido, Ari Shapiro, Kyle Olszewski*
- [Complete List of Co-speech Gesture Generation](./complete_list/co_speech_gesture_generation.md)

### Gesture Recognition
- [ECCV 2026] Amplify, Aggregate, and Adjust: VideoMAE-based Holistic-Subtle Aggregation for Micro-Action Recognition. [[paper pending]](https://eccv.ecva.net/virtual/2026/poster/4219)  
*Yan Zhang, Nan Pu, Wenjing Li, Zhun Zhong, Meng Wang*
- [ECCV 2026] Beyond Language: Grounding Referring Expressions with Hand Pointing in Egocentric Vision. [[paper]](https://arxiv.org/abs/2603.26646)  
*Ling Li, Bowen Liu, Zinuo Zhan, Peng Jie, Jianhui Zhong, Kenglun Chang, Zhidong Deng*
- [ECCV 2026] BiCE-HG: A Bi-Conditional Egocentric Hand Gesture Dataset for Intelligent Reality Systems. [[paper pending]](https://eccv.ecva.net/virtual/2026/poster/5982)  
*Awfa Dakheel, Charith Abhayaratne*
- [ECCV 2026] Recognizing Co-Speech Gestures in-the-Wild. [[paper]](https://arxiv.org/abs/2605.31589) [[code]](https://github.com/Sindhu-Hegde/grw)  
*Sindhu Hegde, K R Prajwal, Andrew Zisserman*
- [ECCV 2026] S2Gest: Split-Scan State Space Models for Dynamic Hand Gesture Recognition. [[paper pending]](https://eccv.ecva.net/virtual/2026/poster/3811)  
*KeFan Chen, Yong Gu, Bo Li, Longjie Huang, Jiajun Zhang*
- [CVPR 2026] SHANDS: A Multi-View Dataset and Benchmark for Surgical Hand-Gesture and Error Recognition Toward Medical Training. [[paper]](https://arxiv.org/abs/2603.26400)     
*Le Ma, Thiago Freitas dos Santos, Nadia Magnenat-Thalmann, Katarzyna Wac*
- [CVPR 2026] Active Inference for Micro-Gesture Recognition: EFE-Guided Temporal Sampling and Adaptive Learning. [[paper]](https://arxiv.org/abs/2603.07559)     
*Weijia Feng, Jingyu Yang, Ruojia Zhang, Fengtao Sun, Qian Gao, Chenyang Wang, Tongtong Su, Jia Guo, Xiaobai Li, Minglai Shao*
- [ICCV 2025] Understanding Co-speech Gestures in-the-wild. [[paper]](https://openaccess.thecvf.com/content/ICCV2025/papers/Hegde_Understanding_Co-speech_Gestures_in-the-wild_ICCV_2025_paper.pdf) [[code]](https://github.com/Sindhu-Hegde/jegal)     
*Sindhu B Hegde, K R Prajwal, Taein Kwon, Andrew Zisserman*
- [NeurIPS 2025] Doodle to Detect: A Goofy but Powerful Approach to Skeleton-based Hand Gesture Recognition. [[paper]](https://openreview.net/forum?id=u8SXX5ITE6) [[code]](https://github.com/capableofanything/SKETCH)     
*Sang Hoon Han, Seonho Lee, Hyeok Nam, Jae Hyeon Park, Min Hee Cha, Min Geol Kim, Hyunse Lee, Sangyeon Ahn, Chae moon ju, Sung In Cho*
- [CVPR 2025] Ges3ViG: Incorporating Pointing Gestures into Language-Based 3D Visual Grounding for Embodied Reference Understanding. [[paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Mane_Ges3ViG__Incorporating_Pointing_Gestures_into_Language-Based_3D_Visual_Grounding_CVPR_2025_paper.html) [[code]](https://github.com/AtharvMane/Ges3ViG)      
*Atharv Mahesh Mane, Dulanga Weerakoon, Vigneshwaran Subbaraju, Sougata Sen, Sanjay Sarma, Archan Misra*
- [CVPR 2025] SocialGesture: Delving into Multi-person Gesture Understanding. [[paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Cao_SocialGesture_Delving_into_Multi-person_Gesture_Understanding_CVPR_2025_paper.html) [[code]](https://github.com/IrohXu/SocialGesture)      
*Xu Cao, Pranav Virupaksha, Wenqi Jia, Bolin Lai, Fiona Ryan, Sangmin Lee, James Rehg*
- [OpenReview] Revisiting Noise Resilience Strategies in Gesture Recognition: Short-Term Enhancement in Surface Electromyographic Signal Analysis. [[paper]](https://openreview.net/forum?id=B7eHRsuTSh)      
*Weiyu Guo, Ziyue Qiao, Ying Sun, Hui Xiong*
- [ICCV 2023] Learning Robust Representations with Information Bottleneck and Memory Network for RGB-D-based Gesture Recognition. [[paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Li_Learning_Robust_Representations_with_Information_Bottleneck_and_Memory_Network_for_ICCV_2023_paper.html)      
*Yunan Li, Huizhou Chen, Guanwen Feng, Qiguang Miao*
- [ICCV 2023] Data-Free Class-Incremental Hand Gesture Recognition. [[paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Aich_Data-Free_Class-Incremental_Hand_Gesture_Recognition_ICCV_2023_paper.html) [[code]](https://github.com/humansensinglab/dfcil-hgr)      
*Shubhra Aich, Jesus Ruiz-Santaquiteria, Zhenyu Lu, Prachi Garg, K J Joseph, Alvaro Fernandez Garcia, Vineeth N Balasubramanian, Kenrick Kin, Chengde Wan, Necati Cihan Camgoz, Shugao Ma, Fernando De la Torre*
- [BMVC 2022] Towards more efficient few-shot learning based human gesture recognition via dynamic vision sensors. [[paper]](https://bmvc2022.mpi-inf.mpg.de/0938.pdf)    
*Linglin Jing, Yifan Wang, Tailin Chen, Shirin Dora, Zhigang Ji, Hui Fang*    
- [BMVC 2022] Continuous Hand Gesture Recognition using Deep Coarse
and Fine Hand Features. [[paper]](https://bmvc2022.mpi-inf.mpg.de/1055.pdf)        
*Hazem Wannous, Jean-Philippe Vandeborre* 
- [CVPR 2022] LD-ConGR: A Large RGB-D Video Dataset for Long-Distance Continuous Gesture Recognition. [[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Liu_LD-ConGR_A_Large_RGB-D_Video_Dataset_for_Long-Distance_Continuous_Gesture_CVPR_2022_paper.html) [[code]](https://github.com/Diananini/LD-ConGR-CVPR2022)     
  *Dan Liu; Libo Zhang; Yanjun Wu*
- [AAAI 2022] Learning Unseen Emotions from Gestures via Semantically-Conditioned Zero-Shot Perception with Adversarial Autoencoders. [[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Ahuja_Low-Resource_Adaptation_for_Personalized_Co-Speech_Gesture_Generation_CVPR_2022_paper.html)    
  *Abhishek Banerjee, Uttaran Bhattacharya, Aniket Bera*
- [Complete List of Gesture Recognition](./complete_list/gesture_recognition.md)

## Sign Language Workshop
- [[CVPR GenSign 2026]](https://genai4sl.github.io/) Generative AI for Sign Language.
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
|     Slovo    |    RSL   |     √    |            |     √    |       |    194    |  1,000 |   20,400   |
|  MM-WLAuslan |   ASULAN |     √    |            |     √    |   √   |    73     |  3,215 |   282,000  |
|NationalCSL-DP|    CSL   |     √    |            |     √    |       |    10     |  6,707 |   67,070   |

