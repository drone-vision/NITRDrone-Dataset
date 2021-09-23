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



## DIRECTORY STRUCTURE:


NITRDrone Dataset-----|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--------Images <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--------RGB_GT  <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;                       |<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;                      |--------GT     <br />
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;                      |<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;                       |--------utils   <br />

DESCRIPTION:<br />
|Folder Name| Description |
|---|---|
| Images  | Contains the aerial images captured by DJI Phantom 4 drone  |
| RGB_GT  | Contains the RGB masks which are generated after annotations  |
|  GT      | Contains the one-hot code images      |
| utils  | Contains the important files related to dataset preparation  |

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
[GDrive](https://drive.google.com/drive/folders/1-w4hGLcrx6pfWVX4NR80nf7fKSE7_Gj0?usp=sharing)


## LICENSE:

This dataset is licenensed to Visual Surveillance Laboratory, Department of Computer Science and Engineering, National Institute of Technology, Rourkela, India. 

## Citation & Acknowledgements
This dataset is available publicly for only for non-commercial use. If you use this dataset in your research or wish to refer to the baseline results published in the README, please use the following BibTeX entry.

\cite{key}
