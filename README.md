# DL_VisDrone
DTSA 5011 - Final
## Problem Statement
I want to explore different **object detection** algorithms on the **VisDrone** dataset, which is primarily for cars, bus, trucks, people, etc captured from various drones between 25-400 ft. AGL.  My goal is to find a training strategy that performs well on this dataset so I can use it with my own personal drone.

## 1 Jupyter Notebook<a class="anchor" id="1"></a>
Links below to visualize the notebooks rendered.

| Notebook | Description |
|--------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [DTSA_5011_Final.ipynb](https://nbviewer.org/github/stevensmiley1989/DL_Visdrone/blob/main/DTSA_5011_Final.ipynb) | Jupyter Notebook|


## 2 Data Inputs <a class="anchor" id="2"></a>
* Data Source:
    * https://github.com/VisDrone/VisDrone-Dataset
    * Train
        * https://drive.google.com/file/d/1a2oHjcEcwXP8oUF95qiwrqzACb2YlUhn/view?usp=sharing
    * Valid
        * https://drive.google.com/file/d/1bxK5zgLn0_L8x276eKkuYA_FzwCIjb59/view?usp=sharing

* Data Details
    * I am using the Task 1 object detection in images challenge data.  The task is to detect objects of certain categories:
        * car
        * bus
        * truck
        * pedestrian
        * awning-tricycle
        * ignored_regions
        * people
        * motor
        * bicycle
        * tricycle
        * van
        * others
    * There are over 7000 images with over 393,666 instances of objects in them.



### 3 License <a class="anchor" id="6"></a>

This repository contains a variety of content; some developed by Steven Smiley, and some from third-parties.  The third-party content is distributed under the license provided by those parties.

The content developed by Steven Smiley is distributed under the following license:

*I am providing code and resources in this repository to you under an open source license.  Because this is my personal repository, the license you receive to my code and resources is from me and not my employer. 

   Copyright 2024 Steven Smiley

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
   
