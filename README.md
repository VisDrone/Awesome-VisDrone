# Awesome-VisDrone
You can find the latest data,algorithms, paper in the area of drone based computer vision. 

## Dataset

### VisDrone
The VisDrone2019 dataset is collected by the AISKYEYE team at Lab of Machine Learning and Data Mining , Tianjin University, China. The benchmark dataset consists of 288 video clips formed by 261,908 frames and 10,209 static images, captured by various drone-mounted cameras, covering a wide range of aspects including location (taken from 14 different cities separated by thousands of kilometers in China), environment (urban and country), objects (pedestrian, vehicles, bicycles, etc.), and density (sparse and crowded scenes). Note that, the dataset was collected using various drone platforms (i.e., drones with different models), in different scenarios, and under various weather and lighting conditions. These frames are manually annotated with more than 2.6 million bounding boxes of targets of frequent interests, such as pedestrians, cars, bicycles, and tricycles. Some important attributes including scene visibility, object class and occlusion, are also provided for better data utilization.

http://aiskyeye.com/

### UAV123
Video captured from low-altitude UAVs is inherently different from video in popular tracking datasets like OTB50, OTB100, VOT2014, VOT2015, TC128, and ALOV300++. Therefore, we propose a new dataset (UAV123) with sequences from an aerial viewpoint, a subset of which is meant for long-term aerial tracking (UAV20L). Our new UAV123 dataset contains a total of 123 video sequences and more than 110K frames making it the second largest object tracking dataset after ALOV300++. All sequences are fully annotated with upright bounding boxes. 

https://ivul.kaust.edu.sa/Pages/Dataset-UAV123.aspx

### DOTA
DOTA-v1.5 contains 0.4 million annotated object instances within 16 categories, which is an updated version of DOTA-v1.0. Both of them use the same aerial images but DOTA-v1.5 has revised and updated the annotation of objects, where many small object instances about or below 10 pixels that were missed in DOTA-v1.0 have been additionally annotated. The categories of DOTA-v1.5 is also extended. Concretely, the category of container crane is added.

https://captain-whu.github.io/DOAI2019/dataset.html


### UAVDT
Selected from 10 hours raw videos, about 80; 000 represen-tative frames are fully annotated with bounding boxes as well as up to 14 kinds of attributes (e.g., weather condition, fying altitude, camera view, vehicle category, and occlusion) for three fundamental computer vision tasks: object detection, single object tracking, and multiple object tracking. 

https://sites.google.com/site/daviddo0323/projects/uavdt

### Inria Aerial Image Labeling Dataset
The Inria Aerial Image Labeling addresses a core topic in remote sensing: the automatic pixelwise labeling of aerial imagery .
Dataset features:
Coverage of 810 km² (405 km² for training and 405 km² for testing).
Aerial orthorectified color imagery with a spatial resolution of 0.3 m.
Ground truth data for two semantic classes: building and not building (publicly disclosed only for the training subset).
The images cover dissimilar urban settlements, ranging from densely populated areas (e.g., San Francisco’s financial district) to alpine towns (e.g,. Lienz in Austrian Tyrol).

https://project.inria.fr/aerialimagelabeling/

### iSAID

iSAID is a benchmark dataset for instance segmentation in aerial images. This large-scale and densely annotated dataset contains 655,451 object instances for 15 categories across 2,806 high-resolution images. The distinctive characteristics of iSAID are the following: (a) large number of images with high spatial resolution, (b) fifteen important and commonly occurring categories, (c) large number of instances per category, (d) large count of labelled instances per image, which might help in learning contextual information, (e) huge object scale variation, containing small, medium and large objects, often within the same image, (f) Imbalanced and uneven distribution of objects with varying orientation within images, depicting real-life aerial conditions, (g) several small size objects, with ambiguous appearance, can only be resolved with contextual reasoning, (h) precise instance-level annotations carried out by professional annotators, cross-checked and validated by expert annotators complying with well-defined guidelines.

https://captain-whu.github.io/iSAID/index.html


## Paper 


### Object Detection

Pengfei Zhu, Longyin Wen, Xiao Bian, Haibin Ling, Qinghua Hu: Vision Meets Drones: A Challenge. CoRR abs/1804.07437 (2018)

Gui-Song Xia, Xiang Bai, Jian Ding, Zhen Zhu, Serge J. Belongie, Jiebo Luo, Mihai Datcu, Marcello Pelillo, Liangpei Zhang:
DOTA: A Large-Scale Dataset for Object Detection in Aerial Images. CVPR 2018: 3974-3983

Dawei Du, Yuankai Qi, Hongyang Yu, Yifan Yang, Kaiwen Duan, Guorong Li, Weigang Zhang, Qingming Huang, Qi Tian, " The Unmanned Aerial Vehicle Benchmark: Object Detection and Tracking", European Conference on Computer Vision (ECCV), 2018. 

### Object Tracking 

Pengfei Zhu, Longyin Wen, Xiao Bian, Haibin Ling, Qinghua Hu: Vision Meets Drones: A Challenge. CoRR abs/1804.07437 (2018)

Dawei Du, Yuankai Qi, Hongyang Yu, Yifan Yang, Kaiwen Duan, Guorong Li, Weigang Zhang, Qingming Huang, Qi Tian, " The Unmanned Aerial Vehicle Benchmark: Object Detection and Tracking", European Conference on Computer Vision (ECCV), 2018. 


###  Segmentation 

Syed Waqas Zamir, Aditya Arora, Akshita Gupta, Salman Khan, Guolei Sun, Fahad Shahbaz Khan, Fan Zhu, Ling Shao, Gui-Song Xia, Xiang Bai:iSAID: A Large-scale Dataset for Instance Segmentation in Aerial Images. CoRR abs/1905.12886 (2019)

Emmanuel Maggiori, Yuliya Tarabalka, Guillaume Charpiat and Pierre Alliez. “Can Semantic Labeling Methods Generalize to Any City? The Inria Aerial Image Labeling Benchmark”. IEEE International Geoscience and Remote Sensing Symposium (IGARSS). 2017.


### Crowd Analysis 


### Challenge Results 
Pengfei Zhu, Longyin Wen, Dawei Du, VisDrone-DET2018: The Vision Meets Drone Object Detection in Image Challenge Results. ECCV Workshops (5) 2018: 437-468.

Longyin Wen, Pengfei Zhu, Dawei Du, VisDrone-SOT2018: The Vision Meets Drone Single-Object Tracking Challenge Results. ECCV Workshops (5) 2018: 469-495. 

Pengfei Zhu, Longyin Wen, Dawei Du, VisDrone-VDT2018: The Vision Meets Drone Video Detection and Tracking Challenge Results. ECCV Workshops (5) 2018: 496-518. 


### Others 



## Code


