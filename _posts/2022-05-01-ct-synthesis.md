---
title:  "Accurate estimation of total intracranial volume in MRI using a multi-tasked image-to-image translation network"
layout: post
---

Total intracranial volume (TIV) is the volume enclosed inside the cranium, inclusive of the meninges and the brain.
TIV is extensively used to correct variations in inter-subject head size for the evaluation of neurodegen- erative diseases. 
In this work, we present an automatic method to generate a TIV mask from MR images while synthesizing a CT image to be used in subsequent analysis. 
In addition, we propose an alternative way to obtain ground truth TIV masks using a semi-manual approach, which results in significant time savings. 
We train a conditional generative adversarial network (cGAN) using 2D MR slices to realize our tasks. 
The quantitative evaluation showed that the model was able to synthesize CT and generate TIV masks that closely approximate the reference images. 
This study also provides a comparison of the described method against skull stripping tools that output a mask enclosing the cranial volume, using MRI scan. 
In particular, highlighting the deficiencies in using such tools to approximate the volume using MRI scan.
