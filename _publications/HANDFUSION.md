---
title: "On the Fusion of RGB and Depth Information for Hand Pose Estimation"
collection: publications
permalink: /publications/HANDFUSION
date: 2018-10-7
venue: 'IEEE International Conference on Image Processing'
---

[PDF](https://ekazakos.github.io/files/rgbd_fusion_handpose_Kazakos_ICIP_2018.pdf)

## Abstract
Recent advances in deep learning have spurred 3D hand pose
estimation, as convolutional network (ConvNet) based methods
outperformed random forests. However, in the state of
the art, ConvNet based methods employ only depth images
of the hand without leveraging color and texture information
from the RGB domain. In this paper, we investigate
whether ConvNets can learn more rich and discriminative embeddings,
by combining RGB and depth information. To answer
this question, we propose the fusion of RGB and depth
information in a double-stream architecture. More specifically,
RGB and depth images are fed into two separate networks
by extracting features, which are subsequently fused
at an intermediate layer of the ConvNet, implementing inputlevel
fusion, feature-level fusion and score-level fusion. The
double-stream scheme is coupled with a deep ConvNet, contrary
to the shallow networks that are mostly proposed in the
literature. Experimental results show that while the depth of
the network is crucial for hand pose estimation, the doublestream
nets perform very similarly with the net trained only
with depth images. This may suggest that training double-stream
architectures purely with supervision may be insufficient
for hand pose estimation with RGB-D fusion.
