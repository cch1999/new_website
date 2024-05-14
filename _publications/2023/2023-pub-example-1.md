---
title:          "PoseCheck: Generative Models for 3D Structure-based Drug Design Produce Unrealistic Poses"
date:           2023-01-05 00:01:00 +0800
selected:       true
pub_last:       ' <span class="badge badge-pill badge-custom badge-success">Spotlight</span>'
pub:            "MLSB Workshop @ NeurIPS 2023"
pub_date:       "2023"
abstract: >-
  Deep generative models for structure-based drug design (SBDD), where molecule generation is conditioned on a 3D protein pocket, have received considerable interest in recent years. These methods offer the promise of higher-quality molecule generation by explicitly modelling the 3D interaction between a potential drug and a protein receptor. However, previous work has primarily focused on the quality of the generated molecules themselves, with limited evaluation of the 3D \emph{poses} that these methods produce, with most work simply discarding the generated pose and only reporting a ``corrected” pose after redocking with traditional methods. Little is known about whether generated molecules satisfy known physical constraints for binding and the extent to which redocking alters the generated interactions. We introduce \posecheck{}, an extensive analysis of multiple state-of-the-art methods and find that generated molecules have significantly more physical violations and fewer key interactions compared to baselines, calling into question the implicit assumption that providing rich 3D structure information improves molecule complementarity. We make recommendations for future research tackling identified failure modes and hope our benchmark will serve as a springboard for future SBDD generative modelling work to have a real-world impact.
cover:          assets/images/covers/cover1.jpg
authors:
- Charles Harris
- Kieran Didi
- Arian Jamasb
- Chaitanya Joshi
- Simon Mathis
- Pietro Lio
- Tom Blundell
links:
  Paper: https://www.cell.com
---