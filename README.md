<p align="center">
 <img src="https://github.com/drone-vision/NITRDrone-Dataset/blob/main/readme_images/frame271-ok.jpg" width=150 height=150 alt="centered logo" />
 </p>
<h1 align="center">NITRDrone Dataset (NITRDD)</h1>



This is an aerial image dataset for semantic scene understanding and is under development.

## LOG
|Date   | Log  |
|---|---|
| 2019.09.01  | Initialization  |
| 2021.09.23  |  NITRDD(4) released |

## Dataset Overview:
-NITRDD
| class  | GT  | (R, G, B)  |
|---|---|---|
| _background_ | 0   | (0, 0, 0)  |
| road |  1 |  (128, 0, 0) |
| occluded_road |  2 | (0, 128, 0)  |
| vegetation |  3 | (128, 128, 0)  |
## DIrectory Structure:
```
NITRDrone Dataset
│
└─── readme_images
│          |
│          └─── images
|          |      
|          └─── seg_class
|          |        
|          |   .gitignore
|          | 
|          |    frame271.jpg
|          ...
└───utils
│   │  label_generator.py
│   │  labels.txt 
│   │  requirements.txt
│   
│   
|   .gitignore
|    CITATION.cff
|    LICENSE
|    README.md
```




DESCRIPTION:<br />
|Folder Name| Description |
|---|---|
| Images  | Sample aerial images captured by DJI Phantom 4 drone  |
| RGB_GT  | RGB masks of the corresponding images generated after annotations  |
|  GT      | Gray scale masks of the corresponding images     |
| utils  | Important files related to dataset preparation  |

## Sample Images
<table>
     
  <tr>
    <td>image</td>
     <td>mask</td>
  </tr>
  <tr>
    <td><img src="https://github.com/drone-vision/NITRDrone-Dataset/blob/main/readme_images/imgs/NITR_AC_JAN26_30.jpg" width=480 height=270></td>
    <td><img src="https://github.com/drone-vision/NITRDrone-Dataset/blob/main/readme_images/seg_class/NITR_AC_JAN26_30.png" width=480 height=270></td>
  </tr>
  <tr>
    <td><img src="https://github.com/drone-vision/NITRDrone-Dataset/blob/main/readme_images/imgs/NITR_FR_1.jpg" width=480 height=270></td>
    <td><img src="https://github.com/drone-vision/NITRDrone-Dataset/blob/main/readme_images/seg_class/NITR_FR_1.png" width=480 height=270></td>
  </tr>
  <tr>
    <td><img src="https://github.com/drone-vision/NITRDrone-Dataset/blob/main/readme_images/imgs/NITR_FR_6.jpg" width=480 height=270></td>
    <td><img src="https://github.com/drone-vision/NITRDrone-Dataset/blob/main/readme_images/seg_class/NITR_FR_6.png" width=480 height=270></td>
  </tr>
 </table>

## Download Link:
- NITRDrone(4): (train+val) <br />
[GDrive](https://drive.google.com/drive/folders/1IQUadXFpEFEsB_9I5JVUuGJBjqIL5MFG?usp=sharing)


## LICENSE:

This dataset is licenensed to Visual Surveillance Laboratory, Department of Computer Science and Engineering, National Institute of Technology, Rourkela, India. 

## Citation & Acknowledgements
This dataset is available publicly for only for non-commercial use. If you use this dataset in your research or wish to refer to the baseline results published in the README, please cite the work from Cite this repository as:


<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
  <meta name="generator" content="pandoc" /> 
</head>
<body>
<!-- <h1 id="bibliography" class="unnumbered">Bibliography</h1> -->
<div id="refs" class="references">
<div id="ref-behera2021nitrdd">
<p>Tanmay Kumar Behera, Sambit Bakshi, Pankaj Kumar Sa, and Michael Nappi. 2021. “NITRDrone Dataset: A Dataset for Aerial Scene Understanding for Road Extraction”, <em>GitHub. 2021-09-23,</em> https://github.com/drone-vision/NITRDrone-Dataset.</p>
</div>


</body>
