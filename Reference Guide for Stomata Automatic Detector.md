## Reference Guide for Stomata Automatic Detector

#### 1. Overview

- The Stomata Automatic Detector is a high-throughput microscope image multi-object detection and intelligent recognition system for plant stomatal phenotypic traits,  and it is developed by *Python3* language based on *TensorFlow*, *Keras*, *PyQt5*, *OpenCV* frameworks.

- The Stomata Automatic Detector mainly consists of five modules: ***File***,  ***Detect***,  ***Settings***,  ***Edit***,  ***View***,  ***Language***,  ***Help***.

### 2. Modules

- ***File*** :  It includes the "***Open***" submenu and the "***Quit System***" option.
  
  - the "***Open***" submenu also contains two options, "***Open Image***" and "***Open Dir***".
  
  - When "***Open Image***" is selected, an image file dialog  will pop up, then select the demand single image, the selected image to be detected will appear in the upper-left area of this system.
  
  - When "***Open Dir***" is selected, the same file dialog will appear, and then select the demand image directory that needs to be detected in batches.'

- ***Detect*** :  It includes two options,  "***Detect Image***" and "***Detect Dir***".
  
  - Refer to the operations of  "***File***" module, These two options could detect the chosen image or dir, respectively.

- ***Settings*** :   It includes two options: "***Unit Conversion***" and "***Model Parameter***".
  
  - "***Unit Conversion***": Calculating the ratio of the scale of the microscope image to its pixel length. The default `100 `represents 100$\mu m$ scale,  i.e. 20x magnification in our given `maize_20x`images is equivalent to the 100 $\mu m$ scale. The default `433` represents the pixel length of the 100 $\mu m$ black line.
  
  - "***Model Parameter***": including "***Stomata Minimum Confidence***" and "***NMS***", both parameter could adjust the accuracy of  detection model  and eliminate overlapped bouding-boxes.

- ***Edit*** : It includes two options: "***Reset System***" and "***Clean Caches***".
  
  - When "***Reset System***" option is selected, the system will be reset to the initial state, and several parameters will go back to the default values.
  
  - When  "***Clean Caches***" option is selected,  the cache data saved in the corresponding directory after the stomata detection of the system, so as to release the resources occupied by the system.

- ***View*** :  It includes the "***Image Preview***" option.
  
  - When click this option, a file dialog will pop up, and then select the demand image folder, and the chosn images will be displayed in two-column alignment.

- ***Language*** :  It includes the "***English***" option.
  
  - This module represents the corresponding language of the current system.

- ***Help*** :  It includes two options: "***Website***" and "***About***".
  
  - When click the "***Website***" option, the system will automatically jump to the corresponding official website.
  
  - The "***About***" option records the sytstem information and copyright details.


