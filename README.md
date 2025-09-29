<h1 align="center">Survey of AI-Powered Approaches for Osteoporosis Diagnosis in Medical Imaging</h1>
<p align="center">
  Authors:
  <a href="https://scholar.google.com/citations?user=PqoNrmIAAAAJ&hl=en">Abdul Rahman</a>,
  <a href="https://scholar.google.com/citations?user=maY0q9IAAAAJ&hl=en">Bumshik Lee</a>
</p>

## A curated survey of AI for osteoporosis in medical imaging

This repository accompanies a comprehensive survey of AI for osteoporosis in medical imaging, spanning X-ray, CT, and DXA. We organize the field by task (diagnosis, fracture detection, fracture-risk prediction), method family (classical ML, CNNs, Transformers, self-supervised learning, explainability), and chronology, and highlight datasets, evaluation practices, and open challenges for clinical adoption. We aim to update entries as new work and open-source implementations appear.

We encourage authors to promote their work by submitting a PR with the paper, venue/year, modality, task, and any open-source implementation. Small fixes and additions are also appreciated.

## Taxonomy
<p align="center">
  <img src="/Overview.png">
  <br>
  <em>Overview of AI-based osteoporosis detection across imaging modalities, methodologies, and clinical tasks.</em>
</p>

# Osteoporosis Classification

**A hierarchical opportunistic screening model for osteoporosis using machine learning applied to clinical data and CT images**<br>
*Liyu Liu1, Meng Si2, Hecheng Ma, Menglin Cong, Quanzheng Xu, Qinghua Sun, Weiming Wu, Cong Wang, Michael J. Fagan, Luis A. J. Mur, Qing Yang and Bing Ji*<br>
 [[Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-022-04596-z)]

**Prediction of femoral osteoporosis using machine-learning analysis with radiomics features and abdomen-pelvic CT: A retrospective single center preliminary study**<br>
*Hyun Kyung Lim, Hong Il Ha, Sun-Young Park, Junhee Han*<br>
 [[Paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0247330)]

**Application of machine learning model to predict osteoporosis based on abdominal computed tomography images of the psoas muscle: a retrospective study**<br>
*Cheng‑bin Huang, Jia‑sen Hu, Kai Tan, Wei Zhang, Tian‑hao Xu, and Lei Yang*<br>
 [[Paper](https://bmcgeriatr.biomedcentral.com/articles/10.1186/s12877-022-03502-9)]

**Diagnosis of Osteoporosis using modified U-net architecture with attention unit in DEXA and X-ray images**<br>
*S.M. Nazia Fathima, R. Tamilselvi, M. Parisa Beham, D. Sabarinathan*<br>
 [[Paper](https://journals.sagepub.com/doi/abs/10.3233/XST-200692)] [[Dataset1](https://sethu.ac.in/dexsit/)] [[Dataset2](https://sethu.ac.in/xsitray-a-database-for-the-detection-of-osteoporosis-condition/)]

**Deep Learning for Osteoporosis Classification Using Hip Radiographs and Patient Clinical Covariates**<br>
*Norio Yamamoto, Shintaro Sukegawa, Akira Kitamura, Ryosuke Goto, Tomoyuki Noda, Keisuke Nakano, Kiyofumi Takabatake, Hotaka Kawai, Hitoshi Nagatsuka, Keisuke Kawasaki, Yoshihiko Furuki, Toshifumi Ozaki*<br>
 [[Paper](https://www.mdpi.com/2218-273X/10/11/1534)]

**Deep learning of lumbar spine X-ray for osteopenia and osteoporosis screening: A multicenter retrospective cohort study**<br>
*Bin Zhang, Keyan Yu, Zhenyuan Ning, Ke Wang, Yuhao Dong, Xian Liu, Shuxue Liu, Jian Wang, Cuiling Zhu, Qinqin Yu, Yuwen Duan, Siying Lv, Xintao Zhang, Yanjun Chen, Xiaojia Wang, Jie Shen, Jia Peng, Qiuying Chen, Yu Zhang, Xiaodong Zhang, Shuixing Zhang*<br>
 [[Paper](https://www.sciencedirect.com/science/article/pii/S8756328220303410)]

**Prediction of osteoporosis from simple hip radiography using deep learning algorithm**<br>
*Ryoungwoo Jang, Jae Ho Choi, Namkug Kim, Jae Suk Chang, Pil WhanYoon, Chul‑Ho Kim*<br>
 [[Paper](https://www.nature.com/articles/s41598-021-99549-6)]

**Deep learning for screening primary osteopenia and osteoporosis using spine radiographs and patient clinical covariates in a Chinese population**<br>
*Liting Mao, Ziqiang Xia, Liang Pan, Jun Chen, Xian Liu, Zhiqiang Li, Zhaoxian Yan, Gengbin Lin, Huisen Wen, Bo Liu*<br>
 [[Paper](https://www.frontiersin.org/journals/endocrinology/articles/10.3389/fendo.2022.971877/full)]

**Development and validation of a machine learning‑derived radiomics model for diagnosis of osteoporosis and osteopenia using quantitative computed tomography**<br>
*Qianrong Xie, Yue Chen, Yimei Hu, Fanwei Zeng, Pingxi Wang, Lin Xu, Jianhong Wu, Jie Li, Jing Zhu, Ming Xiang, Fanxin Zeng*<br>
 [[Paper](https://bmcmedimaging.biomedcentral.com/articles/10.1186/s12880-022-00868-5)]

**Application of Deep Convolutional Neural Networks in the Diagnosis of Osteoporosis**<br>
*Róza Dzierzak, Zbigniew Omiotek*<br>
 [[Paper](https://www.mdpi.com/1424-8220/22/21/8189)]

**Automated bone mineral density prediction and fracture risk assessment using plain radiographs via deep learning**<br>
*Chen-I Hsieh, Kang Zheng, Chihung Lin, Ling Mei, Le Lu , Weijian Li, Fang-Ping Chen, Yirui Wang, Xiaoyun Zhou, Fakai Wang, Guotong Xie, Jing Xiao, Shun Miao, Chang-Fu Kuo*<br>
 [[Paper](https://www.nature.com/articles/s41467-021-25779-x)] [[Dataset](https://zenodo.org/records/5216219)]

**Prediction of osteoporosis using MRI and CT scans with unimodal and multimodal deep-learning models**<br>
*Yasemin Kucukciloglu, Boran Sekeroglu, Terin Adali, Niyazi Senturk*<br>
 [[Paper](https://dirjournal.org/articles/doi/dir.2023.232116)] [[Code](https://github.com/BoranSekeroglu/OSTEO_MODELS)]

**Effect of Patient Clinical Variables in Osteoporosis Classification Using Hip X-rays in Deep Learning Analysis**<br>
*Norio Yamamoto, Shintaro Sukegawa, Kazutaka Yamashita, Masaki Manabe, Keisuke Nakano, Kiyofumi Takabatake, Hotaka Kawai, Toshifumi Ozaki, Keisuke Kawasaki, Hitoshi Nagatsuka, Yoshihiko Furuki, Takashi Yorifuji*<br>
 [[Paper](https://www.mdpi.com/1648-9144/57/8/846)]

**Automatic Segmentation of Periapical Radiograph Using Color Histogram and Machine Learning for Osteoporosis Detection**<br>
*Rini Widyaningrum, Enny Itje Sela, Reza Pulungan, Anindita Septiarini*<br>
 [[Paper](https://onlinelibrary.wiley.com/doi/10.1155/2023/6662911)]

**Machine Learning for Opportunistic Screening for Osteoporosis from CT Scans of the Wrist and Forearm**<br>
*Ronnie Sebro, Cynthia De la Garza-Ramos*<br>
 [[Paper](https://www.mdpi.com/2075-4418/12/3/691)]

**Machine learning for the prediction of osteopenia/osteoporosis using the CT attenuation of multiple osseous sites from chest CT**<br>
*Ronnie Sebro, Cynthia De la Garza-Ramos*<br>
 [[Paper](https://www.sciencedirect.com/science/article/pii/S0720048X22003242)]

**Machine Learning Model to Predict Osteoporotic Spine with Hounsfield Units on Lumbar Computed Tomography**<br>
*Kyoung Hyup Nam, Il Seo, Dong Hwan Kim, Jae Il Lee, Byung Kwan Choi, In Ho Han*<br>
 [[Paper](https://jkns.or.kr/journal/view.php?doi=10.3340/jkns.2018.0178)]

**Deep Learning-Based Hip X-ray Image Analysis for Predicting Osteoporosis**<br>
*Shang-Wen Feng, Szu-Yin Lin, Yi-Hung Chiang, Meng-Han Lu, Yu-Hsiang Chao*<br>
 [[Paper](https://www.mdpi.com/2076-3417/14/1/133)]

**A Hybrid Attention-Driven Deep Learning Model for Osteoporosis Detection in Knees**<br>
*Ishaq Muhammad, Bumshik Lee*<br>
 [[Paper](https://ieeexplore.ieee.org/document/10920829)] [[Dataset](https://www.kaggle.com/datasets/stevepython/osteoporosis-knee-xray-dataset)]

**End to End Multitask Joint Learning Model for Osteoporosis Classification in CT Images**<br>
*Kun Zhang, Pengcheng Lin, Jing Pan, Peixia Xu, Xuechen Qiu, Danny Crookes, Liang Hua, Lin Wang*<br>
 [[Paper](https://europepmc.org/article/MED/36970245)]

**Computer-aided osteoporosis detection from DXA imaging**<br>
*Dildar Hussain, Seung-Moo Han*<br>
 [[Paper](https://www.sciencedirect.com/science/article/pii/S0169260719300495)]

**Osteoporosis prediction in lumbar spine X-ray images using the multi-scale weighted fusion contextual transformer network**<br>
*Linyan Xue, Geng Qin, Shilong Chang, Cheng Luo, Ya Hou, Zhiyin Xia, Jiacheng Yuan, Yucheng Wang, Shuang Liu, Kun Liu, Xiaoting Li, Sibei Wu, Qingliang Zhao, Wenshan Gao, Kun Yang*<br>
 [[Paper](https://www.sciencedirect.com/science/article/pii/S0933365723001537)]

**Efficient Detection of Knee Osteoporosis Using the Swin Transformer on X-ray Images**<br>
*Rahat Sultana, Muhammad Zaman, Nikola Ivkovic, Korhan Cengiz, Iqra Rafaqat, Adnan Akhunzada*<br>
 [[Paper](https://ieeexplore.ieee.org/document/10928051)] [[Dataset](https://www.kaggle.com/datasets/mrmann007/osteoporosis)]

**Opportunistic Osteoporosis Diagnosis via Texture-Preserving Self-Supervision, Mixture of Experts and Multi-Task Integration**<br>
*Jiaxing Huang, Heng Guo, Le Lu, Fan Yang, Minfeng Xu, Ge Yang, Wei Luo*<br>
 [[Paper](https://arxiv.org/abs/2506.20282)]

**Computer-Aided Osteoporosis Diagnosis Using Transfer Learning with Enhanced Features from Stacked Deep Learning Modules**<br>
*AYESHA SIDDIQUA, RAKIBUL HASAN, ANICHUR RAHMAN, ABU SALEH MUSA MIAH*<br>
 [[Paper](https://arxiv.org/abs/2412.09330)]

**Image-based Machine Learning Approaches for the Early Detection of Osteoporosis: A Predictive Model Development and Evaluation Study**<br>
*S Saranya, S Christy, V Sheeja Kumari*<br>
 [[Paper](https://ieeexplore.ieee.org/document/10985225)] [[Dataset](https://www.ncbi.nlm.nih.gov/projects/gap/cgi-bin/study.cgi?study_id=phs000373.v1.p1)]

**A few-shot learning framework for the diagnosis of osteopenia and osteoporosis using knee X-ray images**<br>
*Hua Xie1, Chenqi Gu, Wenchao Zhang, Jiacheng Zhu, Jin He, Zhou Huang, Jinzhou Zhu, Zhonghua Xu*<br>
 [[Paper](https://journals.sagepub.com/doi/10.1177/03000605241274576)] [[Dataset](https://data.mendeley.com/datasets/rscbjbr9sj/3)]

**Osteoporosis Prediction from Hand X-ray Images Using Segmentation-for-Classification and Self-Supervised Learning**<br>
*Ung Hwang, Chang-Hun Lee, Kijung Yoon*<br>
 [[Paper](https://arxiv.org/abs/2412.05345)]

**Incorporating Improved Sinusoidal Threshold-based Semi-supervised Method and Diffusion Models for Osteoporosis Diagnosis**<br>
*Wenchi Ke, Hu Chen, Yi Zhang, Xiong Deng*<br>
 [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10889899)]

**Multi-View Computed Tomography Network for Osteoporosis Classification**<br>
*DONG HWAN HWANG, SO HYEON BAK, TAE-JUN HA, YOON KIM, WOO JIN KIM, HYUN-SOO CHOI*<br>
 [[Paper](https://ieeexplore.ieee.org/document/10058497)]

## Fracture Detection

**Deep-Learning-Based Detection of Vertebral Fracture and Osteoporosis Using Lateral Spine X-Ray Radiography**<br>
*Namki Hong, Sang Wouk Cho, Sungjae Shin, Seunghyun Lee, Seol A Jang, Seunghyun Roh,Young Han Lee, Yumie Rhee, Steven R. Cummings, Hwiyoung Kim, Kyoung Min Kim*<br>
 [[Paper](https://academic.oup.com/jbmr/article/38/6/887/7512425)] [[Code](https://github.com/nkhong84/YUHS-VERTE-X)]

**Vision transformer and deep learning based weighted ensemble model for automated spine fracture type identification with GAN generated CT images**<br>
*Sindhura D.N., Radhika M. Pai, Shyamasunder N. Bhat, Manohara M. M. Pai*<br>
 [[Paper](https://www.nature.com/articles/s41598-025-98518-7)]

# Fracture Risk Prediction

**Prediction of osteoporotic hip fracture in postmenopausal women through patient-specific FE analyses and machine learning**<br>
*E. Villamor, C. Monserrat, L. Del Río, J.A. Romero-Martín, M.J. Rupérez*<br>
 [[Paper](https://www.sciencedirect.com/science/article/pii/S0169260720301826)]

**Risk Assessment of Hip Fracture Based on Machine Learning**<br>
*Alessio Galassi, José D. Martín-Guerrero, Eduardo Villamor, Carlos Monserrat, María José Rupérez*<br>
 [[Paper](https://onlinelibrary.wiley.com/doi/10.1155/2020/8880786)]

**A Novel Fracture Prediction Model Using Machine Learning in a Community-Based Cohort**<br>
*Sung Hye Kong, Daehwan Ahn, Buomsoo (Raymond) Kim, Karthik Srinivasan, Sudha Ram, Hana Kim, A Ram Hong, Jung Hee Kim, Nam H Cho, Chan Soo Shin*<br>
 [[Paper](https://academic.oup.com/jbmrplus/article/4/3/e10337/7499075)]

**Development of a Spine X-Ray-Based Fracture Prediction Model Using a Deep Learning Algorithm**<br>
*Sung Hye Kong, Jae-Won Lee, Byeong Uk Bae, Jin Kyeong Sung, Kyu Hwan Jung, Jung Hee Kim, Chan Soo Shin*<br>
 [[Paper](https://e-enm.org/journal/view.php?doi=10.3803/EnM.2022.1461)]

**Transformer-based deep learning model for predicting osteoporosis in patients with cervical cancer undergoing external-beam radiotherapy**<br>
*Jin Huang, Jianyao Gao, Jiazhi Li, Shanyan Gao, Fangxiao Cheng, Yuzi Wang*<br>
 [[Paper](https://www.sciencedirect.com/science/article/pii/S0957417425003380)]

**Classification of Fracture Risk in Fallers Using Dual-Energy X-Ray Absorptiometry (DXA) Images and Deep Learning-Based Feature Extraction**<br>
*Damith Senanayake, Sachith Seneviratne, Mahdi Imani, Christel Harijanto, Myrla Sales, Peter Lee, Gustavo Duque, David C. Ackland*<br>
 [[Paper](https://onlinelibrary.wiley.com/doi/10.1002/jbm4.10828)]

**A CT-based Deep Learning Model for Predicting Subsequent Fracture Risk in Patients with Hip Fracture**<br>
*Yisak Kim, Young-Gon Kim, Jung-Wee Park, Byung Woo Kim, Youmin Shin, Sung Hye Kong, Jung Hee Kim, Young-Kyun Lee, Sang Wan Kim, Chan Soo Shin*<br>
 [[Paper](https://pubs.rsna.org/doi/full/10.1148/radiol.230614)] [[Code](https://github.com/Medical-Vision-Lab/SubsequentFracturePrediction)]

**Prediction of subsequent osteoporotic vertebral compression fracture on CT radiography via deep learning**<br>
*Xiao Hu, Yanjing Zhu, Yadong Qian, Ruiqi Huang, Shuai Yin, Zhili Zeng, Ning Xie, Bin Ma, Yan Yu, Qing Zhao, Zhourui Wu, Jianjie Wang, Wei Xu, Yilong Ren, Chen Li, Rongrong Zhu, Liming Cheng*<br>
 [[Paper](https://onlinelibrary.wiley.com/doi/full/10.1002/VIW.20220012)]
