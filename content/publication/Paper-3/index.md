---
abstract: Modern policy optimization methods in reinforcement learning, such as Trust Region Policy Optimization and Proximal Policy Optimization, owe their success to the use of parameterized policies. However, while theoretical guarantees have been established for this class of algorithms, especially in the tabular setting, the use of general parameterization schemes remains mostly unjustified. In this work, we introduce a novel framework for policy optimization based on mirror descent that naturally accommodates general parameterizations. The policy class induced by our scheme recovers known classes, e.g., softmax, and generates new ones depending on the choice of mirror map. Using our framework, we obtain the first result that guarantees linear convergence for a policy-gradient-based method involving general parameterization. To demonstrate the ability of our framework to accommodate general parameterization schemes, we provide its sample complexity when using shallow neural networks and show that it represents an improvement upon the previous best results.
authors:
- admin
- Rui Yuan
- Patrick Rebeschini
date: "2023-01-31T00:00:00Z"
doi: ""
featured: false
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false
#links:
#- name: Custom Link
#  url: http://example.org
projects:
- internal-project
publication: "To appear in Advances in Neural Information Systems"
publication_short: ""
#publication_types:
#- "3"
publishDate: "2023-01-31"
slides:
summary:
#tags:
#- Source Themes
title: A Novel Framework for Policy Mirror Descent with General Parametrization and Linear Convergence
#url_code: https://github.com/wowchemy/wowchemy-hugo-themes
#url_dataset: '#'
url_pdf: https://arxiv.org/pdf/2301.13139.pdf
#url_poster: '#'
#url_project: ""
#url_slides: ""
#url_source: '#'
#url_video: '#'
---

