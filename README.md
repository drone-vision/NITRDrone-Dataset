# NITRDrone-Dataset
This is an aerial image dataset for semantic scene understanding.

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


## LICENSE:

This dataset is licenensed to Visual Surveillance Laboratory, Department of Computer Science and Engineering, National Institute of Technology, Rourkela, India. If you are using the dataset for your research, kindly cite the dataset.
