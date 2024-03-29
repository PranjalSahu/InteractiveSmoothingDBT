# InteractiveSmoothingDBT

<h3>The aim of the work is to provide control over image quality for volumes reconstructed with PWLS algorithm.
It introduces modifications in U-Net which allows it to filter the input for a given beta value.
</h3>

![UNet](https://github.com/PranjalSahu/InteractiveSmoothingDBT/blob/main/unet2.png "UNet Modification")
![ScreenShot](https://github.com/PranjalSahu/InteractiveSmoothingDBT/blob/main/intro1.png "Result on Walnut CT sample")


Jupyter Notebook for the MICCAI 2021 paper: [Interactive Smoothing Parameter Optimizationin DBT Reconstruction using Deep learning](https://www.researchgate.net/publication/352998652_Interactive_Smoothing_Parameter_Optimization_in_DBT_Reconstruction_using_Deep_learning)

Sample images and beta values are uploaded as ground_sample.zip and value_sample.zip.

## References
<b>Public Walnut CT dataset<b>
[Henri Der Sarkissian, Felix Lucka, Maureen van Eijnatten, Giulia Colacicco, Sophia Bethany Coban, Kees Joost Batenburg, "A Cone-Beam X-Ray CT Data Collection Designed for Machine Learning", Sci Data 6, 215 (2019)](https://doi.org/10.1038/s41597-019-0235-y) or [arXiv:1905.04787](https://arxiv.org/abs/1905.04787) (2019)

## Contributors
Pranjal Sahu (psahu@cs.stonybrook.edu)


## Citation
  <br>
  
  ```
  @inproceedings{sahu2021interactive,
    title={Interactive Smoothing Parameter Optimization in DBT Reconstruction Using Deep Learning},
    author={Sahu, Pranjal and Huang, Hailiang and Zhao, Wei and Qin, Hong},
    booktitle={International Conference on Medical Image Computing and Computer-Assisted Intervention},
    pages={57--67},
    year={2021},
    organization={Springer}
  }
  ```
