# SARSeg-Net
## Description
Training by LIDAR point cloud for SAR 3D reconstruction point cloud segmentation based on the proposed UDA framework
## Dataset
- Trainning Set on Source Domain:
  
    The LiDAR point cloud data used for training is the Vaihingen3D dataset released at ISPRS, which can be downloaded from the official website:
  
    https://www.isprs.org/education/benchmarks/UrbanSemLab/3d-semantic-labeling.aspx
  
- SAR Dataset on Target Domain

    The SAR 3D point cloud used to implement SAR 3D point cloud segmentation on the target domain is obtained from an elevation-directed inverse reconstruction based on a sequence of SAR 2D images from the SARMV3D dataset.

    - SARMV3D Dataset:

      https://radars.ac.cn/web/data/getData?dataType=SARMV3D

    - The specific SAR 3D point cloud elevation inversion reconstruction method is described in detail in the article.

  - SAR 3D Point Cloud Data with Reference Labeling:
 
    We have annotated the SAR 3D point cloud obtained from the reconstruction of the Yuncheng scene in the SARMV3D dataset against the corresponding optical image, and the reference annotation can be obtained as follows:

    BaiduNetdisk: https://pan.baidu.com/s/1ECscy4CgD0LK4YsWh9mPYQ   Password: ACPT
  
## Code
The manuscript is currently under review and the full code will be made public after publication.
## 
