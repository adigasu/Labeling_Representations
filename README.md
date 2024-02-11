**Code at new repo:** https://github.com/adigasu/Anatomically-aware_Uncertainty_for_Semi-supervised_Segmentation

### <p align="center"> _Leveraging Labeling Representations in Uncertainty-based Semi-supervised Segmentation_
#### <p align="center"> _MICCAI 2022_  [[paper](https://arxiv.org/pdf/2203.05682.pdf)] [[presentation](https://github.com/adigasu/Labeling_Representations/blob/main/Files/Labeling%20representation.pdf)] [[poster](https://github.com/adigasu/Labeling_Representations/blob/main/Files/MICCAI2022_poster.pdf)]

A prominent way to utilize the unlabeled data in Semi-supervised segmentation is by consistency training which commonly uses a teacher-student network. The predictions of unlabeled data are not reliable, therefore, uncertainty-aware methods have been proposed to gradually learn from reliable predictions. Uncertainty estimation, however, relies on multiple inferences that need to be computed for each training step, which is expensive. We propose a novel method to estimate the uncertainty by leveraging the labeling representation of segmentation masks. A labeling representation is learnt to represent the available segmentation masks. The learnt labeling representation is used to map the prediction of the segmentation into a set of plausible masks. Such a reconstructed segmentation mask aids in estimating the pixel-level uncertainty guiding the segmentation network. The proposed method estimates the uncertainty with a single inference from the labeling representation, thereby reducing the total computation.

**TL;DR:** A novel way to estimate the pixel-wise uncertainty using labeling representation to guide the segmentation model.

<p align="center">  <img src = 'Files/Anatomical_rep_Arch.png' height = '300px'>

**Keywords:** Semi-Supervised learning, Segmentation, Labeling Representation, Anatomical prior and Uncertainty


### Dependencies
This code depends on the following libraries:

- Pytorch (1.8.0+cu111)
- Python >= 3.8
- tensorboardX
- some basic libraries: numpy, glob, skimage, matplotlib, tqdm...

### Datasets
- [LA segmentation data, 2018](https://github.com/yulequan/UA-MT/tree/master/data)

### Training
The model can be trained using below command:  
```
Coming soon...
```

### Testing
```
Coming soon...
```

### Citation
Please cite our paper if you find this code or our work useful for your research.

```
@article{adiga2022leveraging,
  title={Leveraging Labeling Representations in Uncertainty-based Semi-supervised Segmentation},
  author={Adiga V, Sukesh and Dolz, Jose and Lombaert, Herve},
  journal={MICCAI},
  year={2022}
}
```

### Reference
- Uncertainty-aware Self-ensembling Model for Semi-supervised (UAMT) [[paper](https://arxiv.org/abs/1907.07034)][[code](https://github.com/yulequan/UA-MT)]
- Semi-supervised Learning for Medical Image Segmentation (SSL4MIS) [[paper](https://arxiv.org/abs/2012.07042)][[code](https://github.com/HiLab-git/SSL4MIS/tree/master/code)]

#### Any questions?
```
For more informations, please contact Sukesh Adiga (sukesh.adiga@gmail.com).
```

#### License
This project is licensed under the terms of the MIT license. 
