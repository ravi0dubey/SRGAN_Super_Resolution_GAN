# SRGAN_Super_Resolution_GAN

## Steps to Train the Model
 !python main.py --LR_path Data/train_LR --GT_path Data/train_HR

## Steps to Test the Model
!python main.py --mode test_only --LR_path test_data --generator_path pretrained_models/SRGAN.pt
