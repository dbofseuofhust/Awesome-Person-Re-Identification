# Awesome Person Re-Identification

If you have any problems, suggestions or improvements, please submit the issue or PR.

## Contents
* [Datasets](#datasets)
* [Papers](#papers)


<!-- ### Code
- [[C^3 Framework](https://github.com/gjy3035/C-3-Framework)] An open-source PyTorch code for crowd counting, which is released. -->

<!-- ### Technical blog
- [2019.05] [Chinese Blog] C^3 Framework系列之一：一个基于PyTorch的开源人群计数框架 [[Link](https://zhuanlan.zhihu.com/p/65650998)]
- [2019.04] Crowd counting from scratch [[Link](https://github.com/CommissarMa/Crowd_counting_from_scratch)]
- [2017.11] Counting Crowds and Lines with AI [[Link1](https://blog.dimroc.com/2017/11/19/counting-crowds-and-lines/)] [[Link2](https://count.dimroc.com/)] [[Code](https://github.com/dimroc/count)] -->

<!-- ###  GT generation
- Density Map Generation from Key Points [[Matlab Code](https://github.com/aachenhang/crowdcount-mcnn/tree/master/data_preparation)] [[Python Code](https://github.com/leeyeehoo/CSRNet-pytorch/blob/master/make_dataset.ipynb)] [[Fast Python Code](https://github.com/vlad3996/computing-density-maps)] -->


## Datasets

| Dataset                   | Release time     | # identities | # cameras   | # images |
|---------------------------|------------------|--------------|-------------|----------|
| [VIPeR](https://vision.soe.ucsc.edu/node/178)                     | 2007             | 632          | 2           | 1264     | 
| [ETH1,2,3](http://homepages.dcc.ufmg.br/~william/datasets.html)                  | 2007             | 85, 35, 28     | 1           | 8580     | 
| [QMUL iLIDS](http://www.eecs.qmul.ac.uk/~jason/data/i-LIDS_Pedestrian.tgz)                | 2009             | 119          | 2           | 476      | 
| [GRID](http://personal.ie.cuhk.edu.hk/~ccloy/downloads_qmul_underground_reid.html)                      | 2009             | 1025         | 8           | 1275     | 
| [CAVIAR4ReID](http://www.lorisbazzani.info/caviar4reid.html)               | 2011             | 72           | 2           | 1220     | 
| [3DPeS](http://www.openvisor.org/3dpes.asp)                     | 2011             | 192          | 8           | 1011     | 
| [PRID2011](https://www.tugraz.at/institute/icg/research/team-bischof/lrs/downloads/PRID11/)                  | 2011             | 934          | 2           | 24541    | 
| [V47](https://docs.google.com/leaf?id=0B692grTpU3UNZWZlN2I2NWYtYzdhNi00MWJkLWI0YjYtNTg2Zjk1OGFkMGQ1)                       | 2011             | 47           | 2           | 752      | 
| [WARD](https://github.com/iN1k1/CVPR2012/tree/master/toolbox/Datasets)                      | 2012             | 70           | 3           | 4786     | 
| [SAIVT-Softbio](https://researchdatafinder.qut.edu.au/display/n27416)             | 2012             | 152          | 8           | 64472    |                        |
| [CUHK01](http://www.ee.cuhk.edu.hk/~xgwang/CUHK_identification.html)                    | 2012             | 971          | 2           | 3884     |
| [CUHK02](http://www.ee.cuhk.edu.hk/~xgwang/CUHK_identification.html)                    | 2013             | 1816         | 10(5 pairs) | 7264     | 
| [CUHK03](http://www.ee.cuhk.edu.hk/~xgwang/CUHK_identification.html)                    | 2014             | 1467         | 10(5 pairs) | 13164    | 
| [RAiD](http://cs-people.bu.edu/dasabir/raid.php)                      | 2014             | 43           | 4           | 6920     | 
| [iLIDS-VID](http://www.eecs.qmul.ac.uk/~xiatian/downloads_qmul_iLIDS-VID_ReID_dataset.html)                 | 2014             | 300          | 2           | 42495    |
| [MPR Drone](http://www.eecs.qmul.ac.uk/~rlayne/downloads_qmul_drone_dataset.html)                 | 2014             | 84           | 1           |          | 
| [HDA Person Dataset](http://vislab.isr.ist.utl.pt/hda-dataset/)        | 2014             | 53           | 13          | 2976     |                   |
| [Shinpuhkan Dataset](http://www.mm.media.kyoto-u.ac.jp/en/datasets/shinpuhkan/)        | 2014             | 24           | 16          |          |                      |
| [CASIA Gait Database B](http://www.cbsr.ia.ac.cn/english/Gait%20Databases.asp)     | 2015(*see below) | 124          | 11          |          | 
| [Market1501](http://www.liangzheng.org/Project/project_reid.html)                | 2015             | 1501         | 6           | 32217    |
| [PKU-Reid](https://github.com/charliememory/PKU-Reid-Dataset)                  | 2016             | 114          | 2           | 1824     |
| [PRW](http://www.liangzheng.org/Project/project_prw.html)                       | 2016             | 932          | 6           | 34304    |
| [Large scale person search](http://www.ee.cuhk.edu.hk/~xgwang/PS/dataset.html) | 2016             | 11934s       | -           | 34574    |                    |
| [MARS](http://www.liangzheng.com.cn/Project/project_mars.html)                      | 2016             | 1261         | 6           | 1191003  | 
| [DukeMTMC-reID](http://vision.cs.duke.edu/DukeMTMC/)             | 2017             | 1812         | 8           | 36441    |                       |
| [DukeMTMC4ReID](http://vision.cs.duke.edu/DukeMTMC/)             | 2017             | 1852         | 8           | 46261    |                      |
| [Airport](http://www.northeastern.edu/alert/transitioning-technology/alert-datasets/alert-airport-re-identification-dataset/)                   | 2017             | 9651         | 6           | 39902    |
| [MSMT17](http://www.pkuvmc.com/publications/msmt17.html)                    | 2018             | 4101         | 15          | 126441   | 
| [RPIfield](https://drive.google.com/file/d/1GO1zm7vCAJwXgJtoFyUs367_Knz8Ev0A/view?usp=sharing)   | 2018      | 112       | 12        | 601,581       |

## Papers

### arXiv papers
This section only includes the last ten papers since 2018 in [arXiv.org](arXiv.org). Previous papers will be hidden using  ```<!--...-->```. If you want to view them, please open the [raw file](https://raw.githubusercontent.com/gjy3035/Awesome-Crowd-Counting/master/README.md) to read the source code. Note that all unpublished arXiv papers are not included into [the leaderboard of performance](#performance).

- <a name=""></a> Omni-Scale Feature Learning for Person Re-Identification [[paper](https://arxiv.org/abs/1905.00953)]
- <a name=""></a> Group Re-Identification with Multi-grained Matching and Integration [[paper](https://arxiv.org/abs/1905.07108)]
- <a name=""></a> HPILN: A feature learning framework for cross-modality person re-identification [[paper](https://arxiv.org/abs/1906.03142)]
- <a name=""></a> PAC-GAN: An Effective Pose Augmentation Scheme for Unsupervised Cross-View Person Re-identification [[paper](https://arxiv.org/pdf/1906.01792.pdf)]
- <a name=""></a> Towards better Validity: Dispersion based Clustering for Unsupervised Person Re-identification [[paper](https://arxiv.org/abs/1906.01308)]


  
### Survey
- <a name=""></a> Person Re-identification: Past, Present and Future (**arXiv2016**) [[arxiv](https://arxiv.org/abs/1610.02984)]
- <a name=""></a> A survey of approaches and trends in person re-identification (**Image and Vision Computing 2014**) [[paper](https://www.sciencedirect.com/science/article/pii/S0262885614000262)]
- <a name=""></a> Appearance Descriptors for Person Re-identification: a Comprehensive Review (**arXiv2013**) [[arxiv](https://arxiv.org/abs/1307.574)]

### 2019
- <a name=""></a> Multi-level Similarity Perception Network for Person Re-identification (**TOMM2019**) [[paper](https://dl.acm.org/citation.cfm?id=3309881)]
- <a name=""></a> Discriminative Representation Learning for Person Re-identification via Multi-loss Training (**JVCIR2019**) [[paper](https://www.sciencedirect.com/science/article/pii/S1047320319301749)]

- <a name=""></a> Joint Discriminative and Generative Learning for Person Re-identification (**CVPR2019**)(**Oral**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Zheng_Joint_Discriminative_and_Generative_Learning_for_Person_Re-Identification_CVPR_2019_paper.html)] [[arxiv](https://arxiv.org/pdf/1904.07223.pdf)]
- <a name=""></a> Densely Semantically Aligned Person Re-Identification (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Zhang_Densely_Semantically_Aligned_Person_Re-Identification_CVPR_2019_paper.html)] [[arxiv](https://arxiv.org/pdf/1812.08967.pdf)]


- <a name=""></a> Generalizable Person Re-identification by Domain-Invariant Mapping Network (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Song_Generalizable_Person_Re-Identification_by_Domain-Invariant_Mapping_Network_CVPR_2019_paper.html)]
- <a name=""></a> Re-Identification with Consistent Attentive Siamese Networks (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Zheng_Re-Identification_With_Consistent_Attentive_Siamese_Networks_CVPR_2019_paper.html)] [[arxiv](https://arxiv.org/pdf/1811.07487.pdf)]
- <a name=""></a> Distilled Person Re-identification: Towards a More Scalable System (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Wu_Distilled_Person_Re-Identification_Towards_a_More_Scalable_System_CVPR_2019_paper.html)]
- <a name=""></a> Weakly Supervised Person Re-Identification (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Meng_Weakly_Supervised_Person_Re-Identification_CVPR_2019_paper.html)] [[arxiv](https://arxiv.org/pdf/1904.03832.pdf)]
- <a name=""></a> Unsupervised Person Re-identification by Soft Multilabel Learning (**CVPR2019**)(**Oral**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Yu_Unsupervised_Person_Re-Identification_by_Soft_Multilabel_Learning_CVPR_2019_paper.html)] [[arxiv](https://arxiv.org/pdf/1903.06325.pdf)] [[github](https://github.com/KovenYu/MAR)]
- <a name=""></a> Invariance Matters: Exemplar Memory for Domain Adaptive Person Re-identification (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhong_Invariance_Matters_Exemplar_Memory_for_Domain_Adaptive_Person_Re-Identification_CVPR_2019_paper.html)] [[arxiv](https://arxiv.org/pdf/1904.01990.pdf)] [[github](https://github.com/zhunzhong07/ECN)]
- <a name=""></a> Re-ranking via Metric Fusion for Object Retrieval and Person Re-identification (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Bai_Re-Ranking_via_Metric_Fusion_for_Object_Retrieval_and_Person_Re-Identification_CVPR_2019_paper.html)]
- <a name=""></a> Progressive Pose Attention Transfer for Person Image Generation (**CVPR2019**)(**Oral**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Zhu_Progressive_Pose_Attention_Transfer_for_Person_Image_Generation_CVPR_2019_paper.html)] [[arxiv](https://arxiv.org/pdf/1904.03349.pdf)] [[github](https://github.com/tengteng95/Pose-Transfer)]
- <a name=""></a> Unsupervised Person Image Generation with Semantic Parsing Transformation (**CVPR2019**)(**Oral**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Song_Unsupervised_Person_Image_Generation_With_Semantic_Parsing_Transformation_CVPR_2019_paper.html)] [[arxiv](https://arxiv.org/pdf/1904.03379.pdf)] [[github](https://github.com/SijieSong/person_generation_spt)]
- <a name=""></a> Learning to Reduce Dual-level Discrepancy for Infrared-Visible Person Re-identification (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Wang_Learning_to_Reduce_Dual-Level_Discrepancy_for_Infrared-Visible_Person_Re-Identification_CVPR_2019_paper.html)]
- <a name=""></a> Text Guided Person Image Synthesis (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Zhou_Text_Guided_Person_Image_Synthesis_CVPR_2019_paper.html)] [[arxiv](https://arxiv.org/pdf/1904.05118.pdf)]
- <a name=""></a> Learning Context Graph for Person Search (**CVPR2019**)(**Oral**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Yan_Learning_Context_Graph_for_Person_Search_CVPR_2019_paper.html)] [[arxiv](https://arxiv.org/pdf/1904.01830.pdf)] [[github](https://github.com/sjtuzq/person_search_gcn)]
- <a name=""></a> Query-guided End-to-End Person Search (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Munjal_Query-Guided_End-To-End_Person_Search_CVPR_2019_paper.html)] [[arxiv](https://arxiv.org/pdf/1905.01203.pdf)] [[github](https://github.com/munjalbharti/Query-guided-End-to-End-Person-Search)]
- <a name=""></a> Multi-person Articulated Tracking with Spatial and Temporal Embeddings (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Jin_Multi-Person_Articulated_Tracking_With_Spatial_and_Temporal_Embeddings_CVPR_2019_paper.html)] [[arxiv](https://arxiv.org/pdf/1903.09214.pdf)]
- <a name=""></a> Dissecting Person Re-identification from the Viewpoint of Viewpoint (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Sun_Dissecting_Person_Re-Identification_From_the_Viewpoint_of_Viewpoint_CVPR_2019_paper.html)] [[arxiv](https://arxiv.org/pdf/1812.02162.pdf)] [[github](https://github.com/sxzrt/Dissecting-Person-Re-ID-from-the-Viewpoint-of-Viewpoint)]
- <a name=""></a> Towards Rich Feature Discovery with Class Activation Maps Augmentation for Person Re-Identification (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Yang_Towards_Rich_Feature_Discovery_With_Class_Activation_Maps_Augmentation_for_CVPR_2019_paper.html)]
- <a name=""></a> VRSTC: Occlusion-Free Video Person Re-Identification (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Hou_VRSTC_Occlusion-Free_Video_Person_Re-Identification_CVPR_2019_paper.html)] 
- <a name=""></a> Adaptive Transfer Network for Cross-Domain Person Re-Identification (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Liu_Adaptive_Transfer_Network_for_Cross-Domain_Person_Re-Identification_CVPR_2019_paper.html)]
- <a name=""></a> Pyramidal Person Re-IDentification via Multi-Loss Dynamic Training (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Zheng_Pyramidal_Person_Re-IDentification_via_Multi-Loss_Dynamic_Training_CVPR_2019_paper.html)] [[arxiv](https://arxiv.org/pdf/1810.12193.pdf)]
- <a name=""></a> Interaction-and-Aggregation Network for Person Re-identification (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Hou_Interaction-And-Aggregation_Network_for_Person_Re-Identification_CVPR_2019_paper.html)]
- <a name=""></a> Skin-based identification from multispectral image data using CNNs (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Uemori_Skin-Based_Identification_From_Multispectral_Image_Data_Using_CNNs_CVPR_2019_paper.html)]
- <a name=""></a> Perceive Where to Focus: Learning Visibility-Aware Part-Level Features for Partial Person Re-Identification (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Sun_Perceive_Where_to_Focus_Learning_Visibility-Aware_Part-Level_Features_for_Partial_CVPR_2019_paper.html)] [[github](https://github.com/sxzrt/Dissecting-Person-Re-ID-from-the-Viewpoint-of-Viewpoint)]
- <a name=""></a> Patch-Based Discriminative Feature Learning for Unsupervised Person Re-Identification (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Yang_Patch-Based_Discriminative_Feature_Learning_for_Unsupervised_Person_Re-Identification_CVPR_2019_paper.html)] 
- <a name=""></a> Attribute-Driven Feature Disentangling and Temporal Aggregation for Video Person Re-Identification (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Zhao_Attribute-Driven_Feature_Disentangling_and_Temporal_Aggregation_for_Video_Person_Re-Identification_CVPR_2019_paper.html)] 
- <a name=""></a> DeepFashion2: A Versatile Benchmark for Detection, Pose Estimation, Segmentation and Re-Identification of Clothing Images (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Ge_DeepFashion2_A_Versatile_Benchmark_for_Detection_Pose_Estimation_Segmentation_and_CVPR_2019_paper.html)] 
- <a name=""></a> AANet: Attribute Attention Network for Person Re-Identifications (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Tay_AANet_Attribute_Attention_Network_for_Person_Re-Identifications_CVPR_2019_paper.html)] 
- <a name=""></a> Re-Identification Supervised Texture Generation (**CVPR2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Wang_Re-Identification_Supervised_Texture_Generation_CVPR_2019_paper.html)] [[arxiv](https://arxiv.org/pdf/1904.03385.pdf)]

<!--## Leaderboard
The section is being continually updated. Note that some values have superscript, which indicates their source. 

-->
