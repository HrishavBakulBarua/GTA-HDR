# GTA-HDR: A Dataset for High Dynamic Range Content Creation and Qualtiy Assessment 
Dataset and code for our newly proposed LDR-HDR dataset: GTA-HDR

## About the project

This project is a collaboration between [Monash University, Malaysia campus](https://www.monash.edu.my/) and [Monash University, Melbourne, Australia](https://www.monash.edu/)

Project Members - [Hrishav Bakul Barua](https://www.researchgate.net/profile/Hrishav-Barua)  [(Monash University and TCS Research, Kolkata)](https://www.tcs.com/research-and-innovation), [Ganesh Krishnasami](https://research.monash.edu/en/persons/ganesh-krishnasamy) [(Monash University, Malaysia)](https://www.monash.edu.my/), [KokSheik Wong](https://scholar.google.com/citations?user=oMjrLWcAAAAJ&hl=en) [(Monash University, Malaysia)](https://www.monash.edu.my/), [Abhinav Dhall](https://sites.google.com/site/dhallabhinav/) [(IIT Ropar, India)](https://www.iitrpr.ac.in/) , and [Kalin Stefanov](https://research.monash.edu/en/persons/kalin-stefanov) [(Monash University, Melbourne, Australia)](https://www.monash.edu/)

### Funding details

This work is supported by the prestigious [`Global Excellence and Mobility Scholarship (GEMS)`](https://www.monash.edu.my/research/support-and-scholarships/gems-scholarship), Monash University. This research is also supported, in part, by the E-Science fund under the project: *Innovative High Dynamic Range Imaging - From Information Hiding to Its Applications* **(Grant No. 01-02-10-SF0327)**.

## Overview

> **_NOTE:_** The official implementation of our GTA-HDR Benchmark Dataset is comming soon!!  
 
![My Image](assets/GTA-HDR-Teaser.png)

## Data collection pipeline

![My Image](assets/data_pipeline.png)


## Our work utilizes the following:

### State-of-the-art models

`HDRCNN` - HDR image reconstruction from a single exposure using deep CNNs (*ACM TOG 2017*) | [Code](https://github.com/gabrieleilertsen/hdrcnn)

`DrTMO` - Deep Reverse Tone Mapping (*ACM TOG 2017*) | [Code](https://github.com/shleecs/DrTMO_unofficial_pytorch)

`FHDR` - HDR Image Reconstruction from a Single LDR Image using Feedback Network (*GlobalSIP 2019*) | [Code](https://github.com/mukulkhanna/FHDR)

`SingleHDR` - Single-Image HDR Reconstruction by Learning to Reverse the Camera Pipeline (*CVPR 2020*) | [Code](https://github.com/alex04072000/SingleHDR) 

`HDR-GAN` - HDR Image Reconstruction from Multi-Exposed LDR Images with Large Motions (*IEEE TIP 2021*) | [Code](https://github.com/nonu116/HDR-GAN)

`SingleHDR` - Single-Image HDR Reconstruction by Multi-Exposure Generation (*WACV 2023*) | [Code](https://github.com/VinAIResearch/single_image_hdr)

`ArtHDR-Net` - Perceptually Realistic and Accurate HDR Content Creation (*APSIPA 2023*) | [Code](https://arxiv.org/abs/2309.03827#:~:text=ArtHDR%2DNet%3A%20Perceptually%20Realistic%20and%20Accurate%20HDR%20Content%20Creation,-Hrishav%20Bakul%20Barua&text=High%20Dynamic%20Range%20(HDR)%20content,and%20Augmented%2FVirtual%20Reality%20industries.)

### LDR-HDR datasets

`HDR-Eye` - Visual attention in LDR and HDR images (*VPQM 2015*) | [Link](https://www.epfl.ch/labs/mmspg/downloads/hdr-eye/)

`City Scene`, site1 - Learning high dynamic range from outdoor panoramas (*ICCV 2017*) | [Link](https://github.com/jacenfox/ldr2hdr-public) 
           
`City Scene`, site2- The Laval HDR sky database | [Link](http://hdrdb.com/)

`Kalantari` *et al.* - Deep high dynamic range imaging of dynamic scenes (*ACM TOG 2017*) | [Link](https://cseweb.ucsd.edu/~viscomp/projects/SIG17HDR/)

`Endo` *et al.* - Deep reverse tone mapping (*ACM TOG 2017*) | [Link](https://www.npal.cs.tsukuba.ac.jp/~endo/projects/DrTMO/)

`Eilertsen` *et al.* - HDR image reconstruction from a single exposure using deep CNNs (*ACM TOG 2017*) | [Link](https://computergraphics.on.liu.se/hdrcnn/)

`Lee` *et al.* - Deep chain hdri: Reconstructing a high dynamic range image from a single low dynamic range image (*IEEE Access 2018*) | [Link](https://siyeong-lee.github.io/hdr_vds_dataset/)
