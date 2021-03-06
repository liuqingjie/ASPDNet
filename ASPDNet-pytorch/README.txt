ASPDNet-pytorch
This is the PyTorch version for ASPDNet: "Dense Object Counting in Remote Sensing Images" in ICASSP 2020, which delivered a state-of-the-art, straightforward and end-to-end architecture for object counting tasks.

***************************************************
Prerequisites
We strongly recommend Anaconda as the environment.

Python: 3.6

PyTorch: 1.0.1

CUDA: 10.0

***************************************************
Ground Truth
Please follow the make_dataset.py to generate the ground truth. It shall take some time to generate the dynamic ground truth. Note you need to generate your own json file.


***************************************************
Training Process
Try python train.py train.json val.json 0 0 to start training process.

***************************************************
Validation
Follow the val.py to try the validation.

***************************************************
References

If you find the ASPDNet useful, please cite our paper. Thank you!

@inproceedings{gao2020dense,
  title={Dense Object Counting in Remote Sensing Images},
  author={Gao, Guangshuai and Liu, Qingjie and Wang, Yunhong},
  booktitle={ICASSP},
  year={2020}
}

