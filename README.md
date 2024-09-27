
# FAWO-MVSNet: Multi-View 3D Reconstruction Based on Feature Enhancement and Weight Optimization

## 介绍 
本文在TransMVSNet网络基础上进行针对性改进，提出一种基于特征增强和权重优化（AS-MVSNet）的三维重建算法。首先，设计一种自适应特征增强策略来提取图像中的多尺度信息，获得准确且丰富的局部和全局特征。接着，引入注意力机制和空间特征捕捉模块，对困难特征信息进行高敏度识别，并通过权重优化来高效获取均匀分布的特征。

## 实验数据
本次实验主要运用数据集[DTU](https://roboimagedata.compute.dtu.dk/), [BlendedMVS](https://github.com/YoYo000/BlendedMVS/) 和 [Tanks and Temples](https://www.tanksandtemples.org/) 去训练和评估模型. 

### 1.DTU
训练：
训练集中包括[DTU training data](https://drive.google.com/file/d/1eDjh-_bxKKnEuz5h-HXS7EDJn59clx6V/view)和[Depths_raw](https://virutalbuy-public.oss-cn-hangzhou.aliyuncs.com/share/cascade-stereo/CasMVSNet/dtu_data/dtu_train_hr/Depths_raw.zip)数据来源(https://github.com/YoYo000/MVSNet))
评估：

### 2.BlendedMVS和Tanks and Temples
训练：
我们使用BlendedMVS的低分辨率集进行训练[low-res set](https://1drv.ms/u/s!Ag8Dbz2Aqc81gVDgxb8MDGgoV74S?e=hJKlvV).
评估：
我们使用Tanks and Temples[Tanks and Temples dataset](https://drive.google.com/file/d/1IHG5GCJK1pDVhDtTHFS3sY-ePaK75Qzg/view?usp=sharing)对训练好的模型进行评估
