---
abstract: Policy Mirror Descent (PMD) is a popular framework in reinforcement learning, serving as a unifying perspective that encompasses numerous algorithms. These algorithms are derived through the selection of a mirror map and enjoy finite-time convergence guarantees. Despite its popularity, the exploration of PMD's full potential is limited, with the majority of research focusing on a particular mirror map---namely, the negative entropy---which gives rise to the renowned Natural Policy Gradient (NPG) method. It remains uncertain from existing theoretical studies whether the choice of mirror map significantly influences PMD's efficacy. In our work, we conduct empirical investigations to show that the conventional mirror map choice (NPG) often yields less-than-optimal outcomes across several standard benchmark environments. Using evolutionary strategies, we identify more efficient mirror maps that enhance the performance of PMD. We first focus on a tabular environment, i.e. Grid-World, where we relate existing theoretical bounds with the performance of PMD for a few standard mirror maps and the learned one. We then show that it is possible to learn a mirror map that outperforms the negative entropy in more complex environments, such as the MinAtar suite. Additionally, we demonstrate that the learned mirror maps generalize effectively to different tasks by testing each map across various other environments.
authors:
- admin
- Silvia Sapora
- Jakob Nicolaus Foerster
- Patrick Rebeschini
- Yee Whye Teh
date: "2024-09-23T00:00:00Z"
doi: ""
featured: false
projects:
- internal-project
publication: "arXiv preprint arXiv:2411.06568"
publication_short: ""
#publication_types:
#- "3"
publishDate: "2024-09-23"
slides:
summary:
#tags:
#- Source Themes
title: Learning Loss Landscapes in Preference Optimization
#url_code: https://github.com/wowchemy/wowchemy-hugo-themes
#url_dataset: '#'
url_pdf: https://arxiv.org/pdf/2411.06568
#url_poster: '#'
#url_project: ""
#url_slides: ""
#url_source: '#'
#url_video: '#'
---

