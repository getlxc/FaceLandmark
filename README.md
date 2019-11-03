# FacialFeaturePoints• [![License](http://dftech.oss-cn-hangzhou.aliyuncs.com/opendface/img/apache_2.svg)](https://opensource.org/licenses/Apache-2.0)


| **`Ubuntu 18.04CPU`** | **`Ubuntu 18.04GPU`** | **`Windows 10 GPU`** | **`Windows 10 CPU`** |
|-----------------|---------------------|------------------|-------------------|
| [![Build Status](http://dftech.oss-cn-hangzhou.aliyuncs.com/opendface/img/build_pass.svg)](http://dftech.oss-cn-hangzhou.aliyuncs.com/opendface/img/build_pass.svg) | [![Build Status](http://dftech.oss-cn-hangzhou.aliyuncs.com/opendface/img/build_pass.svg)](http://dftech.oss-cn-hangzhou.aliyuncs.com/opendface/img/build_pass.svg) | [![Build Status](http://dftech.oss-cn-hangzhou.aliyuncs.com/opendface/img/build_pass.svg)](http://dftech.oss-cn-hangzhou.aliyuncs.com/opendface/img/build_pass.svg) | [![Build Status](http://dftech.oss-cn-hangzhou.aliyuncs.com/opendface/img/build_pass.svg)](http://dftech.oss-cn-hangzhou.aliyuncs.com/opendface/img/build_pass.svg) |


## Introduction
- 本项目实现了基本图片的人脸关键点定位，主要运用了300W_LP数据集进行网络的训练。现在基本的人脸的关键点定位已经实现（环境参数正常的情况下）。主要运用了SENet进行的网络训练，运用跳连相加的思想。

## Installation

本项目运行在Python3.6.8的环境参属性，具体依赖库下面所述。环境参数推荐使用Ubuntu 18.04、TensorFlow 1.12的GPU版本。CUDA推荐9.0、cudnn推荐7.0。

## Requirements
* numpy
* tensorflow
* opencv3.42.16
* glob
* dlib



## Demo （此处借用一张女神照片）

![输入](https://s2.ax1x.com/2019/11/03/KORsN6.jpg)  

![输出](https://s2.ax1x.com/2019/11/03/KORRjH.jpg)  


## License

[Apache License 2.0](LICENSE)

