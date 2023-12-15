# TDRNet-PyTorch (ICME-2022)

IEEE ICME 2022 Oral: [TDRNet: Transformer-Based Dual-Branch Restoration Network for Geometry Based Point Cloud Compression Artifacts](https://ieeexplore.ieee.org/abstract/document/9859853)



## Abstract
With the development of 3D point cloud applications, compression plays an important role in lightweight transmission. However, there are barely related works for recovering the compressed point clouds. In this paper, we investigate the geometry-based point cloud compression (G-PCC) artifact removal problem, which is reflected in position offsets and quantity reductions. To address these issues, we propose a novel Transformer-based Dual-branch Restoration Network (TDRNet). First, we design a Transformer Feature Extractor (TFE), which aims to accurately model structural features for position correction and handle inputs of different sizes. Second, a Dual-Branch Restoration (DBR) module is proposed to deeply exploit global shape and local geometry information to restore the quantity reduction distortion. In this way, the proposed TFE and DBR can work cooperatively for the overall compression artifact removal to reconstruct dense point cloud with better completeness and fine-grained details. Experiments show that our proposed TDRNet achieves state-of-the-art results, and our model is expected to provide a baseline for future point cloud compression distortion restoration studies.



## <a name="Citing TDRNet"></a>Citing  TDRNet

If you use TDRNet in your research, please use the following BibTeX entry.

```BibTeX
@inproceedings{TDRNet_ICME22,
  title={TDRNet: Transformer-Based Dual-Branch Restoration Network for Geometry Based Point Cloud Compression Artifacts},
  author={Zhang, Xiaoyu and Liao, Guibiao and Gao, Wei and Li, Ge},
  booktitle={2022 IEEE International Conference on Multimedia and Expo (ICME)},
  pages={1--6},
  year={2022},
  organization={IEEE}
}
```
