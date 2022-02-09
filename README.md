{:refdef: style="text-align: center;"}
![teaser](images/teaser.PNG){:width="65%"}
{: refdef}

## Abstract

*Phishing websites are still a major threat in today’s Internet ecosystem. Despite numerous previous efforts, similarity-based detection methods do not offer sufficient protection for the trusted websites –in particular against unseen phishing pages. This paper contributes VisualPhishNet, a new similarity-based phishing detection framework, based on a triplet Convolutional Neural Network (CNN). VisualPhishNet learns profiles for websites in order to detect phishing websites by a similarity metric that can generalize to pages with new visual appearances. We furthermore present VisualPhish, the largest dataset to date that facilitates visual phishing detection in an ecologically valid manner. We show that our method outperforms previous visual similarity phishing detection approaches by a large margin while being robust against a range of evasion attacks.*

## VisualPhish Dataset
The dataset has the following screenshots:

* A legitimate trusted-list of 155 websites
* Phishing pages targeting the trusted-list
* New crawled phishing pages collected in Mar-April 2020
* Benign websites with different domains than the trusted-list
* Other test subsets (e.g. different browsers)

To access the dataset for research purposes, please write an email to: sahar.abdelnabi@cispa.saarland

## BibTex
If you find our code or dataset helpful, please cite our paper: 
~~~~~~~~~~~~~~~~
@inproceedings{abdelnabi20ccs,
title = {VisualPhishNet: Zero-Day Phishing Website Detection by Visual Similarity},
author = {Sahar Abdelnabi and Katharina Krombholz and Mario Fritz},
year = {2020},
booktitle = {ACM Conference on Computer and Communications Security (CCS) }
}
~~~~~~~~~~~~~~~~
