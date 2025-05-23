The official implementation of LQVG.

<div align="center">
<h1>
<b>
Language Query based Transformer with Multi-Scale Cross-Modal Alignment for Visual Grounding on Remote Sensing Images
<!-- Language as Queries for Referring <br> Video Object Segmentation -->
</b>
</h1>



</div>


<p align="center"><img src="docs/framework.png" width="800"/></p>

<!-- > **Bidirectional Correlation-Driven Inter-Frame Interaction Transformer for Referring Video Object Segmentation**
>
> Meng Lan, Fu Rong, Zuchao Li, Wei Yu, Lefei Zhang -->

### Abstract

Visual grounding for remote sensing images (RSVG) aims to localize the referred objects in the remote sensing (RS) images according to a language expression. Existing methods tend to align visual and text features followed by concatenation and then employ a fusion Transformer to learn a token representation for final target localization. However, simple fusion Transformer structure fails to sufficiently learn the location representation of referred object from the multi-modal features. Inspired by the detection Transformer, in this paper, we propose a novel language query based Transformer framework for RSVG termed LQVG. Specifically, we adopt the extracted sentence-level text features as the queries, called language queries, to retrieve and aggregate representation information of the referred object from the multi-scale visual features in the Transformer decoder. The language queries are then converted into object embeddings for final coordinate prediction of referred object. Besides, a multi-scale cross-modal alignment module is devised before the multimodal Transformer to enhance the semantic correlation between the visual and text features, thus facilitating the cross-modal decoding process to generate more precise object representation. Moreover, a new RSVG dataset named RSVG-HR is built to evaluate the performance of the RSVG approaches on very high-resolution remote sensing images with inconspicuous objects. Experimental results on two benchmark datasets demonstrate that our proposed method significantly surpasses the comparison methods and achieves state-of-the-art performance.



## Installation

Please refer to [install.md](docs/install.md) for installation.

## Data Preparation

We build the RSVG-HR dataset based on the RSVG dataset, please download the images from [Here](https://sunyuxi.github.io/publication/GeoVG), and our annotations are provided in 'RSVG-HR/Annotations' folder. The DIOR-RSVG dataset could be download from [Here](https://github.com/ZhanYang-nwpu/RSVG-pytorch?tab=readme-ov-file).

## Model Weights

The model weights of LQVG on both DIOR-RSVG and RSVG-HR could be download from [Here](https://drive.google.com/drive/folders/1uC9TAPOwiIbHcee6hSO_3b2Mwr-zDGtg?usp=drive_link).


## Get Started

Please see the detail in tran.sh and test.sh









