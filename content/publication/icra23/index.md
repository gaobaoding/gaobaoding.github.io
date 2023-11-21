---
title: "Meta-Learning Regrasping Strategies for Physical-Agnostic Objects"
authors:
- admin
- Jingyu Zhang
- Ruijie Chen
- Ngo Anh Vien
- Hanna Ziesche
- Gerhard Neumann
date: "2023-10-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Under review"
publication_short: "Under review"

abstract: Grasping heterogeneous objects in real-world applications remains a challenging task due to the unknown physical properties such as mass distribution and coefficient of friction. In this study, we propose a meta-learning algorithm called ConDex to autonomously discern the underlying physical properties of objects using depth images. ConDex efficiently acquires physical embeddings from limited trials, enabling precise grasping point estimation. Furthermore, ConDex is capable of updating the predicted grasping quality iteratively from new trials in an online fashion. To the best of our knowledge, we are the first who generate two object datasets focusing on heterogeneous physical properties with varying mass distributions and friction coefficients. Extensive evaluations in simulation demonstrate ConDex's superior performance over DexNet-2.0 and existing meta-learning-based grasping pipelines. Furthermore, ConDex shows robust generalization to previously unseen real-world objects despite training solely in the simulation. The synthetic and real-world datasets will be published as well.

# Summary. An optional shortened abstract.
summary: We introduce a novel meta-learning grasp framework aimed at addressing the relatively unexplored challenge of grasping objects characterized by diverse physical properties, relying solely on visual input. Two innovative synthetic datasets that explicitly incorporate physical properties are introduced, making them compatible with a wide range of simulation frameworks. Our approach demonstrates substantial advantages in real-world object manipulation, despite being trained exclusively in a simulated environment.

tags: [meta-learning, few-shot learning, grasping, sim2real]

featured: true

links:
- name: ICRA workshop on Scaling Robot Learning
  url: https://sites.google.com/view/icra22-srl#:~:text=Adaptation%20%5Bpaper%5D-,Meta%2DLearning%20Regrasping%20Strategies%20for%20Physical%2DAgnostic%20Objects,-%5Bpaper%5D
url_pdf: https://arxiv.org/pdf/2205.11110.pdf
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: '#'
url_poster: 'publication/icra23/poster.pdf'
# url_project: ''
# url_slides: ''
# url_source: '#'
url_video: 'https://youtu.be/kV093OtcpwI'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
