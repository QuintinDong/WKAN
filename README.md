# WKAN
# Dataset
* The ACDC dataset with mask annotations can be downloaded from: [ACDC](https://www.creatis.insa-lyon.fr/Challenge/acdc/databases.html).
* The Scribble annotations of ACDC can be downloaded from: [Scribble](https://gvalvano.github.io/wss-multiscale-adversarial-attention-gates/data).
* The data processing code in [Here](https://github.com/Luoxd1996/WSL4MIS/blob/main/code/dataloaders/acdc_data_processing.py)  the pre-processed ACDC data in [Here](https://github.com/HiLab-git/WSL4MIS/tree/main/data/ACDC).
* The ISBI-MR-Prostate-2013 dataset with mask annotation can be downloaded from [TCIA](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=21267207), the scribble annotation of this dataset (annotated by Mr. X. Luo and M.D. W. Liao) can be downloaded [GoogleDrive](https://drive.google.com/file/d/1VFKP1-bychADhGw5rbRtd_JKLallccGz/view?usp=sharing) and [BaiduPan](https://pan.baidu.com/s/1jLz5tDAUBw4deKxHntv0gg?pwd=jqr1).
* **To simulate the scribble annotation for other datasets, we further provide the simulation code at [Here](https://github.com/HiLab-git/WSL4MIS/blob/main/code/scribbles_generator.py)**.
# Requirements
Some important required packages include:
* [Pytorch][torch_link] version >=0.4.1.
* TensorBoardX
* Python >= 3.6 
* Efficientnet-Pytorch `pip install efficientnet_pytorch`
* Some basic python packages such as Numpy, Scikit-image, SimpleITK, Scipy ......
