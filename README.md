# EgoCentric-Human-Pose(ECHP) Dataset
This is the official version of ECHP dataset in the paper **"EgoFish3D: Egocentric 3D Pose Estimation from a Fisheye Camera via Self-Supervised Learning"**--[paper](https://www.techrxiv.org/articles/preprint/EgoFish3D_Egocentric_3D_Pose_Estimation_from_a_Fisheye_Camera_via_Self-Supervised_Learning/18516119/1).
![overview](https://user-images.githubusercontent.com/86871168/147398404-7ee8fcad-24a8-4a7a-89ad-5288c7bfccdd.png)

Information:
- [x] Images from the third-person view and the egocentric view for a self-supervised learning.
- [x] Diverse real-world scenarios.
- [x] Different subjects performing many daily actions in different body textures.

## Introduction
To address the challenges in egocentric 3D pose estimation, we propose a real-world egocentric human pose dataset, named ECHP, using a head-mounted GoPro camera with a fisheye lens. The training and validation sets of the ECHP dataset consist of **30** video sequences(**fps=30Hz**) recorded in **8** diverse real-world indoor/outdoor scenes with **10** different daily actions performed by **9** subjects in **20** different body textures. The ten daily actions include: squatting, walking, dancing, stretching, waving, boxing, kicking, touching, clamping, knocking. The test set of the ECHP dataset consists of **7** video sequences by 4 subjects with new body textures captured by a multi-camera motion capture system with ground truth annotations.

![data_collection](https://user-images.githubusercontent.com/86871168/147669662-4c266356-ef4d-46a2-ad81-90e3c43b21cc.png)
![actions](https://user-images.githubusercontent.com/86871168/147398391-418eebfc-05eb-4a70-a78c-444ddfe7f2a5.png)

## Download
We will public the egocentric images soon.

## Results
Below shows some qualitative results on our ECHP dataset, you can refer to our paper for more results.
![vis_3d](https://user-images.githubusercontent.com/86871168/147670746-03d20b38-f9f7-4b75-8b07-eb6cb215ceac.png)


## Citation
Please cite our work if you find this dataset or paper useful for your research.
```latex
@misc{liu_2022, title={EgoFish3D: Egocentric 3D Pose Estimation from a Fisheye Camera via Self-Supervised Learning}, url={https://www.techrxiv.org/articles/preprint/EgoFish3D_Egocentric_3D_Pose_Estimation_from_a_Fisheye_Camera_via_Self-Supervised_Learning/18516119/1}, DOI={10.36227/techrxiv.18516119.v1}, publisher={TechRxiv}, author={Liu, Yuxuan}, year={2022}, month={Jan} } 
  
```
