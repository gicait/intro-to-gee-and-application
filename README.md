# Introduction of Google Earth Engine (GEE) and Applications using Python

## Introduction

Google Earth Engine (GEE) is a platform for scientific analysis and visualization of geospatial datasets for academic, non-profit, business, and government users. There are lots of satellite data, and geospatial data gathered every day. Many people do not use those data due to satellite data's large size and complicated nature. GEE provides an online platform that can be used to access, visualize, and analyze those data within google cloud, making life easier for remote-sensing data analysts.

For example, assume we want to map the paddy area in Thailand in 2010 with MODIS Data. First, we have to download 100s of images, perform preprocessing for each image and do the analysis to extract the paddy area. With GEE, this entire pipeline of work can be done in Cloud, and only the resulting map can be exported, eliminating a big part of the pipeline.

This tutorial includes an introduction to Google Earth Engine (GEE) with a wide range of GEE applications (case studies). We can use either JavaScript or Python programming languages to access GEE. And we are using Python Programing language for this tutorial. But at the end, some short notes are also included for JavaScript users. 

We have tested these tutorials using Google Colab (https://colab.research.google.com/). So it’s recommended to use Google Colab for this tutorial as well.

## Content

The content of this tutorial is as follows,
* __Chapter 1 - Basics of Google Earth Engine (GEE) - Python__
  * (1) Google Earth Engine Initial Set-up
  * (2) Getting Started with GEE Images
  * (3) Mathematical Operations on Images
  * (4) Exporting GEE Images
  * (5) Working with Image Collections is GEE
  * (6) Vector Data and Charts in GEE
* __Chapter 2 - Case Studies (Applications) of GEE__
  * (1) Mapping Surface Water Dynamics
  * (2) Mapping Agricultural Area
  * (3) Mapping Drought Area
  * (4) *Assessing Ground Water Dynamics with GRACE Satellite Data (To be Completed)*
  * (5) *Assessing the Impact of COVID19 on Air Pollution using Sentinel-5P Satellite Data (To be Completed)*
* __Chapter 3 - Image Supervised and Unsupervised Classification with GEE__
  * (1) Supervised Classification
  * (2) Accuracy Assessment
  * (3) Unsupervised Classification (Clustering)
 * __zAppendix 1 - Short Notes for Using Google Earth Engine (GEE) with JavaScript (Optional)__

## Acknowledgements

Created by [N. Lakmal Deshapriya](https://github.com/lakmalnd) for activities of the Geoinformatics Center of the Asian Institute of Technology, Thailand.

## References 
* Gorelick, N., Hancher, M., Dixon, M., Ilyushchenko, S., Thau, D., & Moore, R. (2017). Google Earth Engine: Planetary-scale geospatial analysis for everyone. Remote Sensing of Environment.
* Hijmans, R.J., Guarino, L., Jarvis, A., O’Brien, R., Mathur, P., Bussink, C., Cruz, M., Barrantes, I. & Rojas, E. DIVA-GIS. Available at: www.diva-gis.org
