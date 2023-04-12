# LEARNING-BASED LOSSLESS POINT CLOUD GEOMETRY CODING USING SPARSE TENSORS
* **Authors**:
[Dat T. Nguyen](https://scholar.google.com/citations?hl=en&user=uqqqlGgAAAAJ),
[André Kaup](https://scholar.google.de/citations?user=0En1UwQAAAAJ&hl=de),

* **Affiliation**: Friedrich-Alexander University Erlangen-Nuremberg, 91058 Erlangen, Germany
* **Accepted to**: [[IEEE International Conference on Image Processing]](https://ieeexplore.ieee.org/xpl/conhome/1000349/all-proceedings)
* **Links**: [[Paper]](https://arxiv.org/pdf/2204.05043), [[Slides]](https://github.com/Weafre/SparseVoxelDNN/tree/main/Materials/Paper_2520_Dat_Nguyen.pdf), [[Poster]](https://github.com/Weafre/SparseVoxelDNN/tree/main/Materials/Poster_2520_DatNguyen.pdf)

Description — Most point cloud compression methods operate in the voxel or octree domain which is not the original representation of point clouds. Those representations either remove the geometric information or require high computational power for processing. In this paper, we propose a context-based lossless point cloud geometry compression that directly processes the point representation. Operating on a point representation allows us to preserve geometry correlation between points and thus to obtain an accurate context model while significantly reduce the computational cost. Specifically, our method uses a sparse convolution neural network to estimate the voxel occupancy sequentially from the x, y, z input data. Experimental results show that our method outperforms the state-of-the-art geometry compression standard from MPEG with average rate savings of 52% on a diverse set of point clouds from four different datasets.

## Requirments
- pytorch 1.9.0, py3.9_cuda11.1_cudnn8.0.5_0 
- MinkowskiEngine 0.5
- torchac 0.9.3
## News
- 2022.06.22 The paper is now available on arxiv (https://arxiv.org/abs/2204.05043).
- 2023.04.12 The source code wil be made available soon. The experimental results is now available. 
 
