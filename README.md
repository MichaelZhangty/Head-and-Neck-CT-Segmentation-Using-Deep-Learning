# Head-and-Neck-CT-Segmentation-Using-Deep-Learning
This project aims to automate OARs segmentation using deep learning and transfer learning techniques.
The model performance on MICCAI Dataset is around 77.1 % in mean Dice Score and 2.66 mm in mean 95% hausdorff distance. 

## Data

### [MICCAI 2015 Head and Neck Auto Segmentation Challenge](http://www.imagenglab.com/wiki/mediawiki/index.php?title=2015_MICCAI_Challenge)

Executing the following code will download, extract, and split the dataset.

```bash
    cd data
    python download.py miccai
```

## Requirements

1. Python (3.7)
2. [pynrrd](https://github.com/mhe/pynrrd) (0.4) - For loading MICCAI data in `.nrrd` format
3. Tqdm - For displaying progress bars
4. PyTorch (1.10.0)
5. Torchvision (0.8)
6. [MONAI](https://github.com/Project-MONAI/MONAI) (0.7) - For domain specific models, losses, metrics, etc
7. [PyTorch-Lightning](https://github.com/PyTorchLightning/pytorch-lightning) (1.5.3)


### [Reference Projects](https://github.com/MrinalJain17/CT-image-segmentation)

This project is the continutation of the following project.
https://github.com/MrinalJain17/CT-image-segmentation