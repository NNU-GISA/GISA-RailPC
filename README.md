# RailPC: A Large-Scale Railway Point Cloud Semantic Segmentation Dataset

This is the official repository of the **RailPC** dataset. For details, please refer to:<br />
**RailPC: A Large-Scale Railway Point Cloud Semantic Segmentation Dataset** <br />
Tengping Jiang, Shiwei Li, Qinyu Zhang, Guangshuai Wang, Zequn Zhang, Fankun Zeng, Peng An, Xin Jin, Shan Liu, Yongjun Wang.<br />


Semantic segmentation in the context of 3D point clouds for the railway environment holds significant economic value, 
but its development is severely hindered by the lack of suitable and specific datasets. 
Additionally, the models trained on existing urban road point cloud datasets demonstrate poor generalization on railway data due to a large domain gap caused by non-overlapping special/rare categories, 
e.g., rail track, track bed, etc. To harness the potential of supervised learning methods in the domain of 3D railway semantic segmentation, we introduce RailPC, 
a new point cloud benchmark. RailPC provides a large-scale dataset with rich annotations for semantic segmentation in the railway environment. 
Notably, RailPC contains twice the number of annotated points compared to the largest available mobile laser scanning (MLS) point cloud dataset and is the first railway-specific 3D dataset for semantic segmentation. 
It covers a total of nearly 25 km railway in two different scenes (urban and mountain), with 3 billion points that are finely labeled as 16 most typical classes w.r.t railway, 
and the data acquisition process is completed in China by MLS systems. Through extensive experimentation, 
we evaluate the performance of advanced scene understanding methods on the annotated dataset and present a synthetic analysis of semantic segmentation results. 
Based on our findings, we establish some critical challenges towards railway-scale point cloud semantic segmentation.

## Demo


https://github.com/NNU-GISA/GISA-RailPC/assets/40690061/5b60a97f-2205-40ea-9d05-afb30e70efcc


## Download
If you would like to apply for this dataset, please complete the information in the following format and email it to 211345003@njnu.edu.cn or 221302177@njnu.edu.cn. We'll get right back to you. <br />
  
	Subject: Request for RailPC dataset 
 
    ******** Basic information ********
    · Name:
    · Email Address:
    · Affiliation/Unit:
    · Contact Phone Number:
    
    ******* Research background *******
    · Research area/direction:
    · How do you plan to use the dataset? (e.g. academic research, business analysis, curriculum projects, etc.):
    · Would you be willing to cite or refer to this dataset and its sources in your research results:
    · Your suggestions for this dataset(Optional):
    
## Dataset

### Overview

The proposed benchmark called the RailPC dataset, it comprises over 2 billion 3D points collected from two different environments (i.e., urban and mountain railway scenes). 
The urban railway was captured a section of Nanjing, China, covering length of around 10 km. As for data of mountain railway environments, 
the data were collected in the rural railway yard area of Chengdu. The mountain railway point cloud covers road length of approximately 15 km, which is located in the relative high altitude regions.

## Updates
* 2024/04/23: The dataset is available for download!
* 2024/04/18: Initial release!
* 2024/03/13: The RailPC has been accepted by CAAI!

## To do
- [x] Mountain railway scene semantic segmentation dataset！
- [x] Urban railway scene semantic segmentation dataset！
- [ ] Railway scene instance segmentation dataset！
- [ ] Railway scene panoptic segmentation dataset！

## Related Repos
1. [SPGraph:Large-scale Point Cloud Semantic Segmentation with Superpoint Graphs](https://github.com/loicland/superpoint_graph)![GitHub stars](https://img.shields.io/github/stars/loicland/superpoint_graph.svg?style=flat&label=Star)
2. [KPConv: Flexible and deformable convolution for point clouds](https://github.com/HuguesTHOMAS/KPConv)![GitHub stars](https://img.shields.io/github/stars/HuguesTHOMAS/KPConv.svg?style=flat&label=Star)
3. [RandLA-Net: Efficient Semantic Segmentation of Large-Scale Point Clouds](https://github.com/QingyongHu/RandLA-Net) ![GitHub stars](https://img.shields.io/github/stars/QingyongHu/RandLA-Net.svg?style=flat&label=Star)
4. [SQN: Weakly-Supervised Semantic Segmentation of Large-Scale 3D Point Clouds](https://github.com/QingyongHu/SQN) ![GitHub stars](https://img.shields.io/github/stars/QingyongHu/SQN.svg?style=flat&label=Star)
 
