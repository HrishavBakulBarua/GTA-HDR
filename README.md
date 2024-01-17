# GTA-HDR: High Dynamic Range Content Creation and Qualtiy Assessment using Deep Learning   

This page contains all the Datasets and Code bases involved in experimenting and establishing our newly proposed LDR-HDR dataset (GTA-HDR) for Deep Learning models.

## About the project

This project is a collaboration between [Monash University, Malaysia campus](https://www.monash.edu.my/) and [Monash University, Melbourne, Australia](https://www.monash.edu/)

Project Members - [Hrishav Bakul Barua](https://www.researchgate.net/profile/Hrishav-Barua)  [(Monash University and TCS Research, Kolkata)](https://www.tcs.com/research-and-innovation), [Ganesh Krishnasami](https://research.monash.edu/en/persons/ganesh-krishnasamy) [(Monash University, Malaysia)](https://www.monash.edu.my/), [KokSheik Wong](https://scholar.google.com/citations?user=oMjrLWcAAAAJ&hl=en) [(Monash University, Malaysia)](https://www.monash.edu.my/), [Abhinav Dhall](https://sites.google.com/site/dhallabhinav/) [(IIT Ropar, India)](https://www.iitrpr.ac.in/) , and [Kalin Stefanov](https://research.monash.edu/en/persons/kalin-stefanov) [(Monash University, Melbourne, Australia)](https://www.monash.edu/)

### Funding details

This work is supported by the prestigious [`Global Excellence and Mobility Scholarship (GEMS)`](https://www.monash.edu.my/research/support-and-scholarships/gems-scholarship), Monash University. This research is also supported, in part, by the E-Science fund under the project: *Innovative High Dynamic Range Imaging - From Information Hiding to Its Applications* `(Grant No. 01-02-10-SF0327)`.

## Overview

![My Image](assets/GTA-HDR-Teaser.png)

> **_NOTE:_** **The official GTA-HDR Benchmark Dataset is releasing soon!!**  

## Data collection pipeline

![My Image](assets/data_pipeline.png)


## Our work utilizes the following:

### State-of-the-art learning models


`ACM TOG 2017` | `HDRCNN` - HDR image reconstruction from a single exposure using deep CNNs | [Code](https://github.com/gabrieleilertsen/hdrcnn)

`ACM TOG 2017` | `DrTMO` - Deep Reverse Tone Mapping | [Code](https://github.com/shleecs/DrTMO_unofficial_pytorch)

`GlobalSIP 2019` | `FHDR` - HDR Image Reconstruction from a Single LDR Image using Feedback Network | [Code](https://github.com/mukulkhanna/FHDR)

`CVPR 2020` | `SingleHDR` - Single-Image HDR Reconstruction by Learning to Reverse the Camera Pipeline (*CVPR 2020*) | [Code](https://github.com/alex04072000/SingleHDR) 

`IEEE TIP 2021` | `HDR-GAN` - HDR Image Reconstruction from Multi-Exposed LDR Images with Large Motions | [Code](https://github.com/nonu116/HDR-GAN)

`WACV 2023` | `SingleHDR` - Single-Image HDR Reconstruction by Multi-Exposure Generation | [Code](https://github.com/VinAIResearch/single_image_hdr)

`APSIPA 2023` | `ArtHDR-Net` - Perceptually Realistic and Accurate HDR Content Creation | [Code](https://arxiv.org/abs/2309.03827#:~:text=ArtHDR%2DNet%3A%20Perceptually%20Realistic%20and%20Accurate%20HDR%20Content%20Creation,-Hrishav%20Bakul%20Barua&text=High%20Dynamic%20Range%20(HDR)%20content,and%20Augmented%2FVirtual%20Reality%20industries.)


### LDR-HDR datasets

`VPQM 2015` | `HDR-Eye` - Visual attention in LDR and HDR images | [Link](https://www.epfl.ch/labs/mmspg/downloads/hdr-eye/)

`ICCV 2017` | `City Scene`, site1 - Learning high dynamic range from outdoor panoramas | [Link](https://github.com/jacenfox/ldr2hdr-public) 
           
`City Scene`, site2- The Laval HDR sky database | [Link](http://hdrdb.com/)

`ACM TOG 2017` | `Kalantari` *et al.* - Deep high dynamic range imaging of dynamic scenes | [Link](https://cseweb.ucsd.edu/~viscomp/projects/SIG17HDR/)

`ACM TOG 2017` | `Endo` *et al.* - Deep reverse tone mapping | [Link](https://www.npal.cs.tsukuba.ac.jp/~endo/projects/DrTMO/)

`ACM TOG 2017` | `Eilertsen` *et al.* - HDR image reconstruction from a single exposure using deep CNNs | [Link](https://computergraphics.on.liu.se/hdrcnn/)

`IEEE Access 2018` | `Lee` *et al.* - Deep chain hdri: Reconstructing a high dynamic range image from a single low dynamic range image | [Link](https://siyeong-lee.github.io/hdr_vds_dataset/)

`IEEE TIP 2018` | `Cai` *et al.* - Learning a deep single image contrast enhancer from multi-exposure images | [Link](https://github.com/csjcai/SICE)

`IEEE ICCP 2019` | `Prabhakar` *et al.* - A fast, scalable, and reliable deghosting method for extreme exposure fusion | [Link](https://github.com/rajat95/Deep-Deghosting-HDR)

`IEEE Access 2020` | `LDR-HDR Pair` - Dynamic range expansion using cumulative histogram learning for high dynamic range image generation | [Link](https://github.com/HanbyolJang/LDR-HDR-pair_Dataset/tree/master)

`CVPR 2020` | `HDR-Synth & HDR-Real` - Single-image HDR reconstruction by learning to reverse the camera pipeline | [Link](https://github.com/alex04072000/SingleHDR)


| Dataset       |    Type     | #HDR<sub>GT<sub> | Resolution | In-the-wild | HDR<sub>Dist<sub> | Scene diversity | Image diversity |
| ------------- | ------------- | -------------| -------------| -------------| -------------| -------------| -------------| 
| HDR-Eye (2015)  | Synthetic | 46 | 512&cross;512  | :x: | :x: | :x: | :x: |
| City Scene (2017)  | Mixed | 41222 | 128&cross;64|  :x: | :x: | :white_check_mark: | :x: |
|Kalantari *et al.* (2017) | Real | 89 | 1500&cross;1000|:x: | :x: | :x: | :x: |
| Endo *et al.* (2017) | Synthetic| 1043 |512&cross;512 | :x: | :x: | :x: | :x: |


## Experiments






