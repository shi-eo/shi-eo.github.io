---
title: "Improving Fmask cloud and cloud shadow detection in mountainous area for Landsats 4–8 images"
collection: publications
category: manuscripts
permalink: /publication/2017-mfmask
excerpt: 'This paper introduces the Mountainous Fmask (MFmask) algorithm, a specialized version designed for mountainous areas that integrates DEM data and enhances shadow matching in the original Fmask algorithm. These improvements have been incorporated into the latest versions of Fmask.'
date: 2019-09-15
venue: 'Remote Sensing of Environment'
paperurl: 'http://shi-eo.github.io/files/2017-mfmask.pdf'
githuburl: 'https://github.com/GERSL/Fmask'
citation: 'Qiu, Shi, Binbin He, Zhe Zhu, Zhanmang Liao, and Xingwen Quan (2017). &quot;Improving Fmask cloud and cloud shadow detection in mountainous area for Landsats 4–8 images.&quot; <i>Remote Sensing of Environment</i>. 199: 107-119.'
---

<b>Abstract:</b> We developed a new algorithm called MFmask (Mountainous Fmask) for automated cloud and cloud shadow detection for Landsats 4–8 images acquired in mountainous areas. The MFmask algorithm, built upon the success of the Fmask algorithm (Zhu and Woodcock, 2012; Zhu et al., 2015), is designed for cloud and cloud shadow detection in mountainous areas, where the Fmask algorithm is not performing well. The inputs of the MFmask algorithm include Landsat Top of Atmosphere (TOA) reflectance, Brightness Temperature (BT), and Digital Elevation Models (DEMs). Compared to Fmask, MFmask can separate water and land pixels better in mountainous areas with the aid of DEMs. Moreover, MFmask produces better cloud detection results than Fmask in mountainous areas after BT is linearly normalized by DEMs. To provide more accurate cloud shadow detection in mountainous areas, MFmask uses a double-projection approach to better predict cloud shadow shape on slope side. Additionally, MFmask applies a topographic correction to remove terrain shadows and estimates cloud base height with neighboring clouds. Both will reduce the possibility of cloud and cloud shadow mismatch and increase cloud shadow detection accuracy for places with large topographic gradient. To test the performance of the proposed MFmask algorithm, a total of 67 Landsat images acquired in mountainous areas from different parts of the world were selected for assessing the accuracy of cloud detection, in which 15 of them were used for assessing the accuracy of cloud shadow detection. Compared with Fmask, MFmask can provide substantial improvements in cloud and cloud shadow detection accuracies for places with large topographic gradient and also work well for relatively flat terrain.
