

# FEWO-MVSNet:Multi-View 3D Reconstruction Based on FEWO-MVSNet


##  Introduce
Inspired by TransMVSNet, this paper proposes a 3D reconstruction algorithm based on feature enhancement and weight optimization MVSNet (FEWO-MVSNet). Our method first extracts global and local feature information from multi-view images using an adaptive feature enhancement module, and then introduces an adaptive optimization mechanism for weight assignment to estimate fine depth maps of scenes with weak/repeated textures, and finally completes the reconstruction of high-density 3D point clouds. 
![image](https://github.com/HuanHuanWZH/img-folder/blob/main/1/1.png)


##  Experimental Data
We mainly use these data to train and evaluate our models.

(1)Train：[DTU training data](https://drive.google.com/file/d/1eDjh-_bxKKnEuz5h-HXS7EDJn59clx6V/view)
and [Depths_raw](https://virutalbuy-public.oss-cn-hangzhou.aliyuncs.com/share/cascade-stereo/CasMVSNet/dtu_data/dtu_train_hr/Depths_raw.zip)(both from [Original MVSNet](https://github.com/YoYo000/MVSNet))

Test:[DTU testing data](https://drive.google.com/open?id=135oKPefcPTsdtLRzoDAQtPpHuoIrpRI_) (from [Original MVSNet](https://github.com/YoYo000/MVSNet))

(2)Train:[Blended low-res set](https://1drv.ms/u/s!Ag8Dbz2Aqc81gVDgxb8MDGgoV74S?e=hJKlvV)from [orignal BlendedMVS](https://github.com/YoYo000/BlendedMVS)

Test:[Tanks and Temples dataset](https://drive.google.com/file/d/1IHG5GCJK1pDVhDtTHFS3sY-ePaK75Qzg/view?usp=sharing)


