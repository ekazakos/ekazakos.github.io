---
title: "EPIC-Fusion: Audio-Visual Temporal Binding for Egocentric Action Recognition"
collection: publications
permalink: /publications/TBN
date: 2019-10-27
venue: 'IEEE International Conference on Computer Vision (ICCV 2019)'
citation: '<b>Evangelos Kazakos</b>, Arsha Nagrani, Andrew Zisserman, Dima Damen. <i>Proceedings of the IEEE International Conference on Computer Vision</i>. <b>ICCV 2019</b>.'
---
[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Kazakos_EPIC-Fusion_Audio-Visual_Temporal_Binding_for_Egocentric_Action_Recognition_ICCV_2019_paper.pdf) [Project](http://ekazakos.github.io/TBN/) [Code](https://github.com/ekazakos/temporal-binding-network) [bibtex](http://ekazakos.github.io/files/tbn.bib)

## Abstract
We focus on multi-modal fusion for egocentric action recognition, and propose a 
novel architecture for multimodal temporal-binding, i.e. the combination of 
modalities within a range of temporal offsets. We train the architecture with 
three modalities – RGB, Flow and Audio – and combine them with mid-level 
fusion alongside sparse temporal sampling of fused representations. In contrast 
with previous works, modalities are fused before temporal aggregation, with 
shared modality and fusion weights over time. Our proposed architecture is 
trained end-to-end, outperforming individual modalities as well as late-fusion 
of modalities.

We demonstrate the importance of audio in egocentric vision, on per-class basis, 
for identifying actions as well as interacting objects. Our method achieves 
state of the art results on both the seen and unseen test sets of the largest 
egocentric dataset: EPIC-Kitchens, on all metrics using the public leaderboard.
