# Internship

This repository highlights the projects I undertook during my internship at Axle Informatics.

## Methodology:

### Nucleus Segmentation:
In the first stage of the proposed method, a U-Net model, which is a convolutional neural network (CNN) is used for nucleus instance segmentation. 

The U-Net model extracts each instance of a cell, which is then fed to the multi-scale function which is an image cropping function used to generate a multi-scale representation. 

The objective of the multi-scale function is to capture the shape variation and reduce the effect of object scale on the cytoplasm segmentation network. 

### Cytoplasm Segmentation

In the second stage of the proposed method, Deeplabv3+ models is used for cytoplasm instance segmentation. 

The generated scales from the multi-scale function are fed into the cytoplasm networks to learn the segmentation map in various scales. 

On top of the cytoplasm segmentation network, a scale aggregation function is included to refine and generate a final prediction. 

This mechanism is used to enhance the feature representation of the model by selectively attending to the most informative regions of the input image.


### Conclusion:


#### Automated Precision 

The proposed method combines deep learning and image processing techniques for automated plasma cell detection and segmentation, enhancing precision in multiple myeloma diagnosis.

#### Efficiency Boost

By replacing time-consuming manual methods, the proposed approach significantly accelerates the diagnostic process, reducing the burden on pathologists and facilitating quicker medical interventions.

#### Enhanced Visualization

Automated detection, coupled with advanced visualization techniques, improves interpretability of microscopic images in multiple myeloma diagnosis.
