---
title: Fourier PlenOctrees for Dynamic Radiance Field Rendering in Real-time
publication_types:
  - "1"
authors:
  - Liao Wang
  - Jiakai Zhang
  - Xinhang Liu
  - Fuqiang Zhao
  - Yanshun Zhang
  - Yingliang Zhang
  - Minye Wu
  - Jingyi Yu
  - Lan Xu
publication: Proceedings of the IEEE/CVF Conference on Computer Vision and
  Pattern Recognition
publication_short: CVPR 2022
abstract: Implicit neural representations such as Neural Radiance Field (NeRF)
  have focused mainly on modeling static objects captured under multi-view
  settings where real-time rendering can be achieved with smart data structures,
  eg, PlenOctree. In this paper, we present a novel Fourier PlenOctree (FPO)
  technique to tackle efficient neural modeling and real-time rendering of
  dynamic scenes captured under the free-view video (FVV) setting. The key idea
  in our FPO is a novel combination of generalized NeRF, PlenOctree
  representation, volumetric fusion and Fourier transform. To accelerate FPO
  construction, we present a novel coarse-to-fine fusion scheme that leverages
  the generalizable NeRF technique to generate the tree via spatial blending. To
  tackle dynamic scenes, we tailor the implicit network to model the Fourier
  coefficients of time-varying density and color attributes. Finally, we
  construct the FPO and train the Fourier coefficients directly on the leaves of
  a union PlenOctree structure of the dynamic sequence. We show that the
  resulting FPO enables compact memory overload to handle dynamic objects and
  supports efficient fine-tuning. Extensive experiments show that the proposed
  method is 3000 times faster than the original NeRF and achieves over an order
  of magnitude acceleration over SOTA while preserving high visual quality for
  the free-viewpoint rendering of unseen dynamic scenes.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2022-06-29T23:18:59.328Z
---
[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Fourier_PlenOctrees_for_Dynamic_Radiance_Field_Rendering_in_Real-Time_CVPR_2022_paper.pdf)