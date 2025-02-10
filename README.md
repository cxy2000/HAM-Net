# Enhancing Multimodal 3D Object Detection with Hybrid Attention Fusion
# Astract
With the advancement of computer vision technology, 3D object detection has emerged as a pivotal technique in autonomous driving, robotics, and virtual reality. Multimodal fusion approaches often outperform single-modal methods in 3D object detection, yet they face challenges such as feature redundancy, insufficient fusion, and loss of spatial resolution. To address these issues, we propose HAM-Net, a hybrid attention-based multimodal 3D object detection method. HAM-Net employs an SEFusion module to adaptively weight and fuse features from LiDAR and camera data, enhancing the model's ability to focus on critical features. A hybrid attention module, integrating channel, spatial, and BAM attentions, further optimizes feature selection. Additionally, we improve the FPN module to restore feature map resolution, mitigating information loss. Experiments on the KITTI dataset demonstrate that HAM-Net significantly outperforms baseline models, achieving 87.84% and 78.48% mAP in aerial view and 3D detection, respectively. Our contributions lie in the novel SEFusion strategy, hybrid attention mechanism, and optimized FPN, collectively enhancing the performance, generalization, and adaptability of multimodal 3D object detection.
# Installation
Please refer to INSTALL.md for installation instructions.
# Datasets
Datasets can be downloaded https://mmdetection3d.readthedocs.io/zh-cn/latest/advanced_guides/datasets/kitti.html.
# Citations
If these codes are helpful for your study, please cite:
```
@article{MVX-NET,
  title={Enhancing Multimodal 3D Object Detection with Hybrid Attention Fusion},
  author={WANG Huijuan,CHEN Xinyue, LIU Peng,Yin Guocai,Wang Jianhua,Jin Shilong},
  journal={The Visual Computer},
}
``` 
