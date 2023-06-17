---
title: "t-METASET: Tailoring Property Bias of Large-Scale Metamaterial Datasets through Active Learning"
collection: publications
permalink: /publications/2022-09-11-tmetaset_idetc
date: 2022-09-11
venue: 'Proceedings of the ASME 2021 International Design Engineering Technical Conferences and Computers and Information in Engineering Conference'
paperurl: '/files/pdf/publications/2202.10565.pdf'
link: 'https://arxiv.org/pdf/2202.10565.pdf'
github: 
authors: 'Doksoo Lee, Yu-Chin Chan, <b>Wei Chen</b>, Liwei Wang, Anton van Beek, Wei Chen'
abstract: "Inspired by the recent achievements of machine learning in diverse domains, data-driven metamaterials design has emerged as a compelling paradigm that can unlock the potential of multiscale architectures. The model-centric research trend, however, lacks principled frameworks dedicated to data acquisition, whose quality propagates into the downstream tasks. Often built by naive space-filling design in shape descriptor space, metamaterial datasets suffer from property distributions that are either highly imbalanced or at odds with design tasks of interest. To this end, we present t-METASET: an active-learning-based data acquisition framework aiming to guide both diverse and task-aware data generation. Distinctly, we seek a solution to a commonplace yet frequently overlooked scenario at early stages of data-driven design of metamaterials: when a massive (~O(10^4 )) shape-only library has been prepared with no properties evaluated. The key idea is to harness a data-driven shape descriptor learned from generative models, fit a sparse regressor as a start-up agent, and leverage metrics related to diversity to drive data acquisition to areas that help designers fulfill design goals. We validate the proposed framework in three deployment cases, which encompass general use, task-specific use, and tailorable use. Two large-scale mechanical metamaterial datasets are used to demonstrate the efficacy. Applicable to general image-based design representations, t-METASET could boost future advancements in data-driven design."
category: 'conference'
topic: 
  design_representation: False
  inverse_design: False
  generative_modeling: False
  adaptive_sampling: True
  metamaterials_design: True
---
