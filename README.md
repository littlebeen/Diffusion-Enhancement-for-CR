# Diffusion-Enhancement-for-CR

The code for [Diffusion Enhancement for Cloud Removal in Ultra-Resolution Remote Sensing Imagery](https://arxiv.org/abs/2401.15105), which is based on [ADM](https://github.com/openai/guided-diffusion). 

Several conventional CR models could refer to [https://github.com/littlebeen/Cloud-removal-model-collection](https://github.com/littlebeen/Cloud-removal-model-collection)!

# Usage

**Train**
1. Pure diffusion. respace.py:gaussian_diffusion; unet.py: UnetModel
2. Locked diffusion + Trained WA :gaussian_diffusion_enhance; unet.py: UnetModel256; locked in train_util.py line74
3. ALL-in change train_util.py line74

# CUHK-CR

A novel multispectral Cloud Removal dataset

Download link: https://pan.baidu.com/s/1z2SgORYz5_t94kya8CeqiQ code:bean

-CUHK-CR1 (The RGB images for thin dataset CUHK-CR1)

-CUHK-CR2 (The RGB images for think dataset CUHK-CR2)

-nir (the near-infrared images for CUHK-CR1 and CUHK-CR2)

If you need image with 4 bands (RGB + nir), you could load the images in the RGB dataset and the nir dataset and combine the 4 channels together. 

# Cite

If this project is useful to you, please cite this paper :)

```
@article{sui2024diffusion,
  title={Diffusion Enhancement for Cloud Removal in Ultra-Resolution Remote Sensing Imagery},
  author={Sui, Jialu and Ma, Yiyang and Yang, Wenhan and Zhang, Xiaokang and Pun, Man-On and Liu, Jiaying},
  journal={arXiv preprint arXiv:2401.15105},
  year={2024}
}
```
If you have any question, be free to contact with me!
