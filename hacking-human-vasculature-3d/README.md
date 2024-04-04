# SenNet + HOA - Hacking the Human Vasculature in 3D
#### Segment vasculature in 3D scans of human kidney


## Link

### Overview
The goal of this competition is to segment blood vessels. You will create a model trained on 3D Hierarchical Phase-Contrast Tomography (HiP-CT) data from human kidneys to help complete a picture of vasculature throughout a body.

Your work will better researchers' understanding of the size, shape, branching angles, and patterning of blood vessels in human tissue.

### Description
Your body's organs and tissues depend on the interaction, spatial organization, and specialization of your cells—all 37 trillion of them. Researchers make sense of cellular functions and relationships with the Vasculature Common Coordinate Framework (VCCF). The VCCF maps cells using the blood vasculature in the human body as the primary navigation system. The framework crosses all scale levels and provides a unique way to identify cellular locations using capillary structures as an address. However, the gaps in what researchers know about the vasculature lead to gaps in the VCCF. If data science could help automatically segment vasculature arrangements, researchers could use the real-world tissue data to fill in those gaps and complete their picture of the vasculature throughout the body.

Currently, human expert annotators manually trace the vascular structures—a slow process. Even with expert annotators, each new dataset takes 6+ months to complete. Machine learning approaches using this manual data do not generalize well to new datasets because of the variability of both human anatomy and to changes in the image quality as HiP-CT technology continues to improve and change.

Competition host the Common Fund’s Cellular Senescence Network (SenNet) Program was established to comprehensively identify and characterize the differences in senescent cells across the body, across various states of human health, and across the lifespan. SenNet provides publicly accessible atlases of senescent cells and develops innovative tools and technologies that build upon previous advances in single-cell analysis.

SenNet is joined by the Human Organ Atlas (HOA) for this competition. HOA is a digital atlas containing 3D multi-resolution imaging datasets, created at the world’s brightest synchrotron (European Synchrotron Radiation Facility), using an imaging technique called Hierarchical Phase-Contrast Tomography (HiP-CT). HiP-CT spans a previously poorly explored scale in researchers’ understanding of human anatomy, from microns to entire intact organs.

Your efforts could ​​​​improve our understanding of the effect of vasculature on different cells in the human body. With better data, researchers could simulate the flow of blood, oxygen, or even drugs through the vessel network. They could also use the available organ images to augment their understanding of how blood vasculature changes as sex, age, and BMI change. Ultimately, you could help pave the way towards a more complete Vascular Common Coordinate Framework (VCCF) and Human Reference Atlas (HRA), which could identify how the relationships between cells affect our health.

### Evaluation
We evaluate submissions using the surface dice metric with a tolerance of 0.0.
