---
title: Editable free-viewpoint video using a layered neural representation
publication_types:
  - "2"
authors:
  - Jiakai Zhang
  - Xinhang Liu
  - Xinyi Ye
  - Fuqiang Zhao
  - Yanshun Zhang
  - Minye Wu
  - Yingliang Zhang
  - Lan Xu
  - Jingyi Yu
publication: "ACM Transactions on Graphics "
publication_short: TOG
abstract: Generating free-viewpoint videos is critical for immersive VR/AR
  experience, but recent neural advances still lack the editing ability to
  manipulate the visual perception for large dynamic scenes. To fill this gap,
  in this paper, we propose the first approach for editable free-viewpoint video
  generation for large-scale view-dependent dynamic scenes using only 16
  cameras. The core of our approach is a new layered neural representation,
  where each dynamic entity, including the environment itself, is formulated
  into a spatio-temporal coherent neural layered radiance representation called
  ST-NeRF. Such a layered representation supports manipulations of the dynamic
  scene while still supporting a wide free viewing experience. In our ST-NeRF,
  we represent the dynamic entity/layer as a continuous function, which achieves
  the disentanglement of location, deformation as well as the appearance of the
  dynamic entity in a continuous and self-supervised manner. We propose a scene
  parsing 4D label map tracking to disentangle the spatial information
  explicitly and a continuous deform module to disentangle the temporal motion
  implicitly. An object-aware volume rendering scheme is further introduced for
  the re-assembling of all the neural layers. We adopt a novel layered loss and
  motion-aware ray sampling strategy to enable efficient training for a large
  dynamic scene with multiple performers, Our framework further enables a
  variety of editing functions, i.e., manipulating the scale and location,
  duplicating or retiming individual neural layers to create numerous visual
  effects while preserving high realism. Extensive experiments demonstrate the
  effectiveness of our approach to achieve high-quality, photo-realistic, and
  editable free-viewpoint video generation for dynamic scenes.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-07-09T10:42:49.095Z
---
