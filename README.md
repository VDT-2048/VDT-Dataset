# VDT-2048-Dataset
## Image acquisition system
![Fig4](https://user-images.githubusercontent.com/101792089/159106101-8c472bfb-e4e1-4a47-84ed-826e1dc3970a.png)

## VDT-2048 Dataset Analysis
This dataset contains 2048 image groups, and each group contains triple-modal images (i.e., visible image, depth image, and thermal image). All of the images have the same resolution of **640×480**. This dataset collected 34 household items in the seven most common household scenes. The proportion of each scene and item category is shown in the following figure.
![summary](https://user-images.githubusercontent.com/101792089/159106121-19712142-e24e-41e0-9215-a6330a9833cf.png)
## V challenging scenes
V information mainly has seven challenging scenes. V-SA (similar appearance): the salient object has a similar color or shape to the background. V-BSO (big salient object): the ratio of the sum of salient pixels to the total pixel sum of the entire image is greater than 0.08. V-SSO (small salient object): the ratio of the sum of salient pixels to the total pixel sum of the entire image is less than 0.007. V-MSO (multiple salient objects): the number of salient objects is more than one. V-LI (low illumination): images are collected under low illumination, and objects are not easier to identify visually. V-SI (side illumination): illumination is given from the side of salient objects, and the brightness of salient objects is uneven. V-NI (no illumination): the image is collected under no illumination, and objects are visually difficult to identify.
![Fig8](https://user-images.githubusercontent.com/101792089/159106130-819735e9-15d0-44a7-8dd0-8690fc02812d.jpg)
## D challenging scenes
D information mainly has four challenging scenes. D-BM (background messy): background messy when there is no wallpaper. D-II (information incomplete): partial lack of D information leads to incomplete information of salient objects. D-SSO (small salient objects): the ratio of the sum of salient pixels to the total pixel sum of the entire image is less than 0.007. D-BI (background interference): using wallpaper as a background to interfere with D information.
![Fig9](https://user-images.githubusercontent.com/101792089/159106135-d475106c-641b-4e20-80e5-3645f7b6cc5c.jpg)
## T challenging scenes
T information mainly has three challenging scenes. T-Cr (crossover): the salient object has a similar temperature to the surrounding or other objects. T-RD (radiation dispersion): part of a salient object is more salient than the whole object. T-HR (heat reflection): the heat radiation of the salient object is reflected.
![Fig10](https://user-images.githubusercontent.com/101792089/159106138-e635e485-3cba-4233-be27-407839ffa7da.jpg)
## Proposed HWSI method 
The overall architecture of the proposed HWSI method and two main modules are shown in the following figure.
![Fig7](https://user-images.githubusercontent.com/101792089/159121921-db6db448-08ad-4019-b849-b0c73bad24a4.png)

## Visual comparison results
Comparison of the salient map visualization results of the proposed model and the latest methods in dealing with different challenging scenes.
![可视化1_看图王](https://user-images.githubusercontent.com/101792089/159106227-29d1b59a-2235-42b1-b53b-7a90ed4e35a7.jpg)
Visual comparison results of two modalities are disturbed.
![可视化2](https://user-images.githubusercontent.com/101792089/159106001-be104f6b-f0d6-4cc8-b928-83b9e9b1adb7.png)

## Download the dataset
The dataset is provided for non-commercial use only. By downloading the dataset, you accept the license agreement. Please send the signed license agreement to vdt2048@163.com for a download link.
