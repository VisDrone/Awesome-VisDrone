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



### PRAI-1581

To facilitate the research of person ReID in aerial imagery, we collect a large scale airborne person ReID dataset named as Person ReID for Aerial Imagery (PRAI-1581), which consists of 39,461 images of 1581 person identities. The images of the dataset are shot by two DJI consumer UAVs flying at an altitude ranging from 20 to 60 meters above the ground, which covers most of the real UAV surveillance scenarios. 

https://github.com/stormyoung/PRAI-1581


### VRAI-Dataset

The VARI dataset is split to the training set and testing set, among which the training set contains 66,113 images with 6,302 IDs, and the test set contains 71,500 images with 6,720 IDs. Besides, we subsample a subset from the testing set as the testing_dev set. The testing_dev set contains 20% images of testing set.

https://github.com/JiaoBL1234/VRAI-Dataset

### WebUAV-3M
WebUAV-3M contains over 3.3 million frames across 4,500 videos and offers 223 highly diverse target categories. Each video is densely annotated with bounding boxes by an efficient and scalable semiautomatic target annotation (SATA) pipeline. Importantly, to take advantage of the complementary superiority of language and audio, we enrich WebUAV-3M by innovatively providing both natural language specifications and audio descriptions. 

https://github.com/983632847/WebUAV-3M

###  DUT-VTUAV
Nearly 1.7 million well-aligned RGB-T image pairs with 500 sequences for unveiling the power of RGB-T tracking(the largest RGB-T tracking benchmark so far).

https://github.com/zhang-pengyu/DUT-VTUAV

###  DroneVehicle：
The DroneVehicle dataset consists of a total of 56,878 images collected by the drone, half of which are RGB images, and the resting are infrared images. We have made rich annotations with oriented bounding boxes for the five categories. Among them, car has 389,779 annotations in RGB images, and 428,086 annotations in infrared images, truck has 22,123 annotations in RGB images, and 25,960 annotations in infrared images, bus has 15,333 annotations in RGB images, and 16,590 annotations in infrared images, van has 11,935 annotations in RGB images, and 12,708 annotations in infrared images, and freight car has 13,400 annotations in RGB images, and 17,173 annotations in infrared image. This dataset is available on the download page.

https://github.com/VisDrone/DroneVehicle

###  DroneCrowd：
DroneCrowd, formed by 112 video clips with 33,600 high resolution frames (i.e., 1920x1080) captured in 70 different scenarios. With intensive amount of effort, our dataset provides 20,800 people trajectories with 4.8 million head annotations and several video-level attributes in sequences. 

https://github.com/VisDrone/DroneCrowd

###  AnimalDrone：
A large-scale video based animal counting dataset collected by drones (AnimalDrone) for agriculture and wildlife protection. The dataset consists of two subsets, i.e., AnimalDrone-PartA that are captured on site by our own drones and AnimalDrone-PartB that are collected from Internet. Totally, there are 53,644 frames with more than 4 million object annotations and several attributes, i.e., density, altitude and view.
 
https://github.com/VisDrone/AnimalDrone 
 
###  DroneRGBT
A drone based RGB-Thermal crowd counting dataset (DroneRGBT) that consists of 3600 pairs of images and covers different attributes, including height, illumination and density. 

https://github.com/VisDrone/DroneRGBT

###  MultiDrone
Multi-Drone single Object Tracking (MDOT) dataset that consists of 92 groups of video clips with 113,918 high resolution frames taken by two drones and 63 groups of video clips with 145,875 high resolution frames taken by three drones.

https://github.com/VisDrone/MultiDrone

###  MDMT 
To address the critical challenges of identity association and target occlusion in multi-drone multi-target tracking tasks, we collect an occlusion-aware multi-drone multi-target tracking dataset named MDMT. It contains 88 video sequences with 39,678 frames, including 11,454 different IDs of persons, bicycles, and cars.

https://github.com/VisDrone/Multi-Drone-Multi-Object-Detection-and-Tracking

## Paper 


### Object Detection

Pengfei Zhu, Longyin Wen, Dawei Du, Xiao Bian, Heng Fan, Qinghua Hu, Haibin Ling. Detection and tracking meet drones challenge. IEEE Transactions on Pattern Analysis and Machine Intelligence 44.11 (2021): 7380-7399. 

Gui-Song Xia, Xiang Bai, Jian Ding, Zhen Zhu, Serge J. Belongie, Jiebo Luo, Mihai Datcu, Marcello Pelillo, Liangpei Zhang:
DOTA: A Large-Scale Dataset for Object Detection in Aerial Images. CVPR 2018: 3974-3983

Dawei Du, Yuankai Qi, Hongyang Yu, Yifan Yang, Kaiwen Duan, Guorong Li, Weigang Zhang, Qingming Huang, Qi Tian, " The Unmanned Aerial Vehicle Benchmark: Object Detection and Tracking", European Conference on Computer Vision (ECCV), 2018. 

### Object Tracking 

Pengfei Zhu, Longyin Wen, Dawei Du, Xiao Bian, Heng Fan, Qinghua Hu, Haibin Ling. Detection and tracking meet drones challenge. IEEE Transactions on Pattern Analysis and Machine Intelligence 44.11 (2021): 7380-7399. 

Dawei Du, Yuankai Qi, Hongyang Yu, Yifan Yang, Kaiwen Duan, Guorong Li, Weigang Zhang, Qingming Huang, Qi Tian, " The Unmanned Aerial Vehicle Benchmark: Object Detection and Tracking", European Conference on Computer Vision (ECCV), 2018. 


###  Segmentation 

Syed Waqas Zamir, Aditya Arora, Akshita Gupta, Salman Khan, Guolei Sun, Fahad Shahbaz Khan, Fan Zhu, Ling Shao, Gui-Song Xia, Xiang Bai:iSAID: A Large-scale Dataset for Instance Segmentation in Aerial Images. CoRR abs/1905.12886 (2019)

Emmanuel Maggiori, Yuliya Tarabalka, Guillaume Charpiat and Pierre Alliez. “Can Semantic Labeling Methods Generalize to Any City? The Inria Aerial Image Labeling Benchmark”. IEEE International Geoscience and Remote Sensing Symposium (IGARSS). 2017.


### Crowd Analysis 


### Challenge Results 
VisDrone-DET2018: The Vision Meets Drone Object Detection in Image Challenge Results. ECCV Workshops (5) 2018: 437-468.

VisDrone-SOT2018: The Vision Meets Drone Single-Object Tracking Challenge Results. ECCV Workshops (5) 2018: 469-495. 

VisDrone-VDT2018: The Vision Meets Drone Video Detection and Tracking Challenge Results. ECCV Workshops (5) 2018: 496-518. 


### Others 



## Code


