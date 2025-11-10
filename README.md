# TwinsTNet -- TIP 2025
The code is coming soon！
- Please cite our paper if you find it useful for your research.
```
@article{lyu2025twinstnet,
  title={TwinsTNet: Broad-View Twins Transformer Network for Bi-Modal Salient Object Detection},
  author={Lyu, Pengfei and Yu, Xiaosheng and Chi, Jianning and Wu, Hao and Wu, Chengdong and Rajapakse, Jagath C},
  journal={IEEE Transactions on Image Processing},
  year={2025},
  publisher={IEEE}
}
```
## Requirement
- Python (3.7.10+), Pytorch (1.7.0+), Cuda, Torchvision, Tensorboard, TensorboardX, Numpy.
## Datasets
- RGB-T Datasets: [VT821, VT1000, VT5000,](https://github.com/lz118/RGBT-Salient-Object-Detection), [VI-RGBT1500](https://github.com/huanglm-me/VI-RGBT1500)
- RGB-D Datasets: [NLPR, NJUD, DUT-RGBD, STERE, SIP, ReDWeb-S](https://github.com/jiwei0921/RGBD-SOD-datasets).
## Pre-trained models
- RGB-T:
- Baidu cloud disk [link](https://pan.baidu.com/s/1TM7sSkTttBr-rYMrUmBvXw), fetch code (u9dh)
- RGB-D:
- Training on NLPR and NJUD, Baidu cloud disk [link](https://pan.baidu.com/s/1jDlSbE7qp3M6RWGFb1JZnA), fetch code (putl)
- Training on NLPR, NJUD and DUT-RGBD, Baidu cloud disk [link](https://pan.baidu.com/s/1PI9CEDvqGbmOjhDUFmgEng), fetch code (rlex)
## Results
- RGB-T: The RGB-T results can be downloaded [here](https://pan.baidu.com/s/1UC1rRC3zHTAy6jakr-hUIw?pwd=7dpd).
- 
|  | *Em* | *Sm* | *wF* | *Fm* | *MAE* |
| :------: | :------: | :------: | :------: | :------: | :------: |
| VT821 | 0.940 | 0.911 | 0.865 | 0.869 | 0.023 |
| VT1000 | 0.954 | 0.943 | 0.922 | 0.913 | 0.015 |
| VT5000 | 0.950 | 0.912 | 0.874 | 0.880 | 0.023 |
| VI-RGBT1500 | 0.956 | 0.909 | 0.880 | 0.895 | 0.028 |
- RGB-D: The RGB-D results will be available soon.
- 
|  | *Em* | *Sm* | *wF* | *Fm* | *MAE* |
| :------: | :------: | :------: | :------: | :------: | :------: |
| NLPR | 0.976 | 0.941 | 0.922 | 0.922 | 0.016 |
| NJUD | 0.940 | 0.934 | 0.925 | 0.935 | 0.026 |
| DUT-RGBD | 0.973 | 0.948 | 0.946 | 0.956 | 0.018 |
| SIP | 0.949 | 0.915 | 0.907 | 0.926 | 0.034 |
| STERE | 0.945 | 0.925 | 0.905 | 0.913 | 0.029 |
| ReDWeb | 0.780 | 0.756 | 0.696 | 0.728 | 0.109 |
## Evaluation Metrics Toolbox
- The Evaluation Metrics Toolbox is available [here](https://github.com/jiwei0921/Saliency-Evaluation-Toolbox).
## Acknowledgements
- Thanks to all the seniors who put in the effort.
## Contact Us
If you have any questions, please contact us (lvpengfei1995@163.com).
