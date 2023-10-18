---
title: 'Category-Agnostic 6D Pose Estimation with Conditional Neural Processes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yumeng Li
  - admin
  - Hanna Ziesche
  - Gerhard Neumann

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-05-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-18T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Women in Computer Vision (WiCV) workshop in CVPR2022*
publication_short: In *CVPR2022 WiCV workshop*

abstract: We present a novel meta-learning approach for 6D pose estimation on unknown objects. In contrast to "instance-level" and "category-level" pose estimation methods, our algorithm learns object representation in a category-agnostic way, which endows it with strong generalization capabilities across object categories. Specifically, we employ a neural process-based meta-learning approach to train an encoder to capture texture and geometry of an object in a latent representation, based on very few RGB-D images and ground-truth keypoints. The latent representation is then used by a simultaneously meta-trained decoder to predict the 6D pose of the object in new images. Furthermore, we propose a novel geometry-aware decoder for the keypoint prediction using a Graph Neural Network (GNN), which explicitly takes geometric constraints specific to each object into consideration. 
To evaluate our algorithm, extensive experiments are conducted on the LineMOD dataset, and on our new fully-annotated synthetic datasets generated from Multiple Categories in Multiple Scenes (MCMS). Experimental results demonstrate that our model performs well on unseen objects with very different shapes and appearances. Remarkably, our model also shows robust performance on occluded scenes though trained fully on data without occlusion. To our knowledge, this is the first work exploring **cross-category level** 6D pose estimation. 

# Summary. An optional shortened abstract.
summary: We introduce a novel meta-learning framework for 6D pose estimation with strong generalization ability on unseen objects within and across object categories, with a proposed GNN-based keypoint prediction module that leverages geometric information from canonical keypoint coordinates and captures local spatial constraints among keypoints via message passing.

tags: [few-shot learning, meta-learning, 6D pose estimation, sim2real]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2206.07162.pdf'
# url_code: ''
# url_dataset: ''
url_poster: './content/publication/cvpr22-workshop/poster.pdf'
# url_project: 'https://sites.google.com/view/sa6d'
# url_slides: ''
# url_source: ''
# url_video: 'https://youtu.be/VyQe44mgfe8'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
