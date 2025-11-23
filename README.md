# ReRF Dataset
The dataset of the paper "Neural Residual Radiance Fields for Streamably Free-Viewpoint Videos".

> Neural Residual Radiance Fields for Streamably Free-Viewpoint Videos   
> [Liao Wang](https://aoliao12138.github.io/), [Qiang Hu](https://qianghu-huber.github.io/qianghuhomepage/), 
>[Qihan He](https://www.linkedin.com/in/qihan-he-a378a61b7/), Ziyu Wang, [Jingyi Yu](http://www.yu-jingyi.com/),
>[Tinne Tuytelaars](https://homes.esat.kuleuven.be/~tuytelaa/), [Lan Xu](https://www.xu-lan.com/index.html), [Minye Wu](https://wuminye.com/)  
> CVPR 2023
> 

#### [project page](https://aoliao12138.github.io/ReRF/) | [paper](https://arxiv.org/abs/2304.04452) | [data & model](https://github.com/aoliao12138/ReRF_Dataset)

### Description

We have uploaded 3 sample cases of data with different scenes (kpop, box and sing) and our compressed files of the scene kpop. The file structure is as follows:

- kpop.zip (contains 4000 frames)
  - image (Captured videos with white background)
    - 000.mp4 ([Camera index].mp4)
    - ...
    - 075.mp4
  - mask (Mask)
    - 000.mp4 ([Camera index].mp4)
    - ...
    - 075.mp4
  - bbox.json (the bounding box of the scene)
  - CamPose.inf (camera poses in the [NHR](https://github.com/wuminye/NHR) format)
  - Intrinsic.inf (camera intrinsics in the [NHR](https://github.com/wuminye/NHR) format)
- box.zip (contains 1000 frames)
- sing.zip (contains 800 frames)
- compressed_kpop.zip (compressed 4000 frames of the scene kpop)


### Download our dataset

The dataset is available on [GoogleDrive](https://drive.google.com/drive/folders/1nIl3wmbp10eN0X6z5W04GIZa1MNLv7i8?usp=sharing) and requires permission to access it. Please carefully read, fill in the [license form](./license.pdf), and send it to Lan Xu (xulan1@shanghaitech.edu.cn) and cc Liao Wang (czzx_2012_231@126.com), Neudim (hello@neudim.com) to request access.

By requesting access to the content, you acknowledge that you have read this agreement, understand it, and agree to be bound by its terms and conditions. This agreement constitutes a legal and binding agreement between you and the provider of the protected system or content. The Neudim is the only owner of all intellectual property rights, including copyright, of ReRF DATASET, and Neudim reserves the right to terminate your access to the dataset at any time.

Notes:

(1) Students are **NOT** eligible to be a recipient.  If you are a student, please ask your supervisor to make a request.

(2) Once the license agreement is signed, we will give access to the data.

### Citation

If you use this dataset for your research, please cite our paper:

```
@InProceedings{Wang_2023_CVPR,
    author    = {Wang, Liao and Hu, Qiang and He, Qihan and Wang, Ziyu and Yu, Jingyi and Tuytelaars, Tinne and Xu, Lan and Wu, Minye},
    title     = {Neural Residual Radiance Fields for Streamably Free-Viewpoint Videos},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2023},
    pages     = {76-87}
}
```



