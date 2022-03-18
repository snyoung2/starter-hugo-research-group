---
title: Robust plant segmentation of color images based on image contrast optimization
publication_types:
  - "2"
authors:
  - Y. Lu
  - "**S.N. Young**"
  - H. Wang
  - N. Wijewardane
publication: "*Computers and Electronics in Agriculture*, 193, 106711.
  [doi.org/10.1016/j.compag.2022.106711](doi.org/10.1016/j.compag.2022.106711)"
abstract: Plant segmentation is a crucial task in computer vision applications
  for identification/classification and quantification of plant phenotypic
  features. Robust segmentation of plants is challenged by a variety of factors
  such as unstructured background, variable illumination, biological variations,
  and weak plant-background contrast. Existing color indices that are
  empirically developed in specific applications may not adapt robustly to
  varying imaging conditions. This study proposes a new method for robust,
  automatic segmentation of plants from background in color (red-green-blue,
  RGB) images. This method consists of unconstrained optimization of a linear
  combination of RGB component images to enhance the contrast between plant and
  background regions, followed by automatic thresholding of the
  contrast-enhanced images (CEIs). The validity of this method was demonstrated
  using five plant image datasets acquired under different field or indoor
  conditions, with a total of 329 color images as well as ground-truth plant
  masks. The CEIs along with 10 common index images were evaluated in terms of
  image contrast and plant segmentation accuracy. The CEIs, based on the
  maximized foreground-background separability, achieved consistent, substantial
  improvements in image contrast over the index images, with an average
  segmentation accuracy of F1 = 95%, which is 4% better than the best accuracy
  obtained by the indices. The index images were found sensitive to imaging
  conditions and none of them performed robustly across the datasets. The
  proposed method is straightforward, easy to implement and can be potentially
  extended to nonlinear forms of color component combinations or other color
  spaces and generally useful in plant image analysis for precision agriculture
  and plant phenotyping.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2022-03-18T21:35:57.045Z
---
