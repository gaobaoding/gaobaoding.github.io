---
title: 'What Matters For Meta-Learning Vision Regression Tasks?'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Hanna Ziesche
  - Ngo Anh Vien
  - Michael Volpp
  - Gerhard Neumann

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-06-17T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-06-17T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2022*
publication_short: In *CVPR22'*

abstract: Meta-learning is widely used in few-shot classification and function regression due to its ability to quickly adapt to unseen tasks. However, it has not yet been well explored on regression tasks with high dimensional inputs such as images. This paper makes two main contributions that help understand this barely explored area. \emph{First}, we design two new types of cross-category level vision regression tasks, namely object discovery and pose estimation of unprecedented complexity in the meta-learning domain for computer vision. To this end, we (i) exhaustively evaluate common meta-learning techniques on these tasks, and (ii) quantitatively analyze the effect of various deep learning techniques commonly used in recent meta-learning algorithms in order to strengthen the generalization capability, namely data augmentation, domain randomization, task augmentation and meta-regularization. Finally, we (iii) provide some insights and practical recommendations for training meta-learning algorithms on vision regression tasks. \emph{Second}, we propose the addition of functional contrastive learning (FCL) over the task representations in Conditional Neural Processes (CNPs) and train in an end-to-end fashion. The experimental results show that the results of prior work are misleading as a consequence of a poor choice of the loss function as well as too small meta-training sets. Specifically, we find that CNPs outperform MAML on most tasks without fine-tuning. Furthermore, we observe that naive task augmentation without a tailored design results in underfitting.  

# Summary. An optional shortened abstract.
summary: This work investigates meta-learning algorithms on vision regression tasks and demonstrates their ability to tackle structured problems with a new proposed functional contrastive learning on the task representation of CNPs to improve its expressivity. Furthermore, it quantitatively analyzes various deep learning techniques to alleviate meta overfitting. 

tags: [pose estimation, contrastive learning, few-shot learning, meta-learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openaccess.thecvf.com/content/CVPR2022/papers/Gao_What_Matters_for_Meta-Learning_Vision_Regression_Tasks_CVPR_2022_paper.pdf'
url_code: 'https://github.com/boschresearch/what-matters-for-meta-learning'
url_dataset: 'https://github.com/boschresearch/what-matters-for-meta-learning/tree/main/data'
# url_poster: ''
# url_project: 'https://sites.google.com/view/sa6d'
# url_slides: ''
# url_source: ''
# url_video: 'https://www.youtube.com/watch?v=Rdk1Iv-SX1c&feature=youtu.be'

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
