---
title: Neural Residual Radiance Fields for Streamably Free-Viewpoint Videos
publication_types:
  - "1"
authors:
  - Liao Wang
  - Qiang Hu
  - Qihan He
  - Ziyu Wang
  - Jingyi Yu
  - Tinne Tuytelaars Lan Xu
  - Minye Wu
author_notes: []
publication: The IEEE/CVF Conference on Computer Vision and Pattern Recognition 2023
publication_short: CVPR2023
abstract: The success of the Neural Radiance Fields (NeRFs) for modeling and
  free-view rendering static objects has inspired numerous attempts on dynamic
  scenes. Current techniques that utilize neural rendering for facilitating
  free-view videos (FVVs) are restricted to either offline rendering or are
  capable of processing only brief sequences with minimal motion. In this paper,
  we present a novel technique, Residual Radiance Field or ReRF, as a highly
  compact neural representation to achieve real-time FVV rendering on
  long-duration dynamic scenes. ReRF explicitly models the residual information
  between adjacent timestamps in the spatial-temporal feature space, with a
  global coordinate-based tiny MLP as the feature decoder. Specifically, ReRF
  employs a compact motion grid along with a residual feature grid to exploit
  inter-frame feature similarities. We show such a strategy can handle large
  motions without sacrificing quality. We further present a sequential training
  scheme to maintain the smoothness and the sparsity of the motion/residual
  grids. Based on ReRF, we design a special FVV codec that achieves three orders
  of magnitudes compression rate and provides a companion ReRF player to support
  online streaming of long-duration FVVs of dynamic scenes. Extensive
  experiments demonstrate the effectiveness of ReRF for compactly representing
  dynamic radiance fields, enabling an unprecedented free-viewpoint viewing
  experience in speed and quality.
draft: false
featured: false
image:
  filename: teaser.jpg
  focal_point: Smart
  preview_only: false
  caption: Our proposed ReRF utilizes a residual radiance field and a global MLP
    to enable highly compressible and streamable radiance field modeling. Our
    ReRF-based codec scheme and streaming player gives users a rich interactive
    experience.
summary: ""
date: 2023-04-11T19:22:10.276Z
---
![Our proposed ReRF utilizes a residual radiance field and a global MLP to enable highly compressible and streamable radiance field modeling. Our ReRF-based codec scheme and streaming player gives users a rich interactive experience.](teaser.jpg "Our proposed ReRF utilizes a residual radiance field and a global MLP to enable highly compressible and streamable radiance field modeling. Our ReRF-based codec scheme and streaming player gives users a rich interactive experience.")

Project: [https://aoliao12138.github.io/ReRF/](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbTdiMlRtaTREWDhIMVNnMFI3d1AwV3FiRlFwd3xBQ3Jtc0trSG1xVkxPNEtBNzJnZWxMY2VBdDRrTEpqdHJMZk5XR2tfOVNKNEFLZ0dSLWJzSEZfUTVTY1dYM19QaWtzS2lKcDR6S2FYb1lVXzVUaTVOYk81bGRocjljanh2T2FLUHVlSDdTMWtiNktQT1VBSTRPWQ&q=https%3A%2F%2Faoliao12138.github.io%2FReRF%2F&v=dFvwaI1h-nc) 

Arxiv: [https://arxiv.org/abs/2304.04452](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbU5sTHM4QmdBOE0yT2tRVFZoYVBXWjhVT2RlUXxBQ3Jtc0ttaFExRGFXMWk3Y3UxN3pEMWttdE11SkVxZ3FHVTJocE5BdjZPRm9GTzlpdTdnUW1YbzlsODM1UmoyckVFWHRNcGoyS0FnbEFPaHRnS0U4S3VCNHZHeVFjNk51TEVLVHp2d1BoLUFlQmkyaVR0TDJFbw&q=https%3A%2F%2Farxiv.org%2Fabs%2F2304.04452&v=dFvwaI1h-nc)