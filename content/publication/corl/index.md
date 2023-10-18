---
title: 'SA6D: Self-Adaptive Few-Shot 6D Pose Estimator for Novel and Occluded Objects'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Ngo Anh Vien
  - Hanna Ziesche
  - Gerhard Neumann

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-10-17T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-17T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Conference on Robot Learning (CoRL) 2023*
publication_short: In *CoRL23'*

abstract: To enable meaningful robotic manipulation of objects in the real world, 6D pose estimation is one of the critical aspects. Most existing approaches have difficulty extending predictions to scenarios where novel object instances are continuously introduced, especially with heavy occlusions. In this work, we propose a few-shot pose estimation (FSPE) approach called SA6D, which uses a self-adaptive segmentation module to identify the novel target object and construct a point cloud model of the target object using only a small number of cluttered reference images. Unlike existing methods, SA6D does not require object-centric reference images or any additional object information, making it a more generalizable and scalable solution across categories. We evaluate SA6D on real-world tabletop object datasets and demonstrate that SA6D outperforms existing FSPE methods, particularly in cluttered scenes with occlusions, while requiring fewer reference images. 

# Summary. An optional shortened abstract.
summary: In this work, we propose a few-shot pose estimation (FSPE) approach called SA6D, which uses a self-adaptive segmentation module to identify the novel target object and construct a point cloud model of the target object using only a small number of cluttered reference images.

tags: [6D pose, self-supervised learning, few-shot learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=gdkKi_F55h'
# url_code: ''
# url_dataset: ''
url_poster: './content/publication/corl/poster.pdf'
url_project: 'https://sites.google.com/view/sa6d'
# url_slides: ''
# url_source: ''
url_video: 'https://www.youtube.com/watch?v=Rdk1Iv-SX1c&feature=youtu.be'

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
