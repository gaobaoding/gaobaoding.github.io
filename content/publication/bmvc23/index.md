---
title: 'Enhancing Interpretable Object Abstraction via Clustering-based Slot Initialization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Bernard Hohmann
  - Gerhard Neumann

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-10-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-18T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In * 34th British Machine Vision Conference (BMVC) 2023*
publication_short: In *BMVC23'*

abstract: Object-centric representations using slots have shown advances towards efficient, flexible and interpretable abstraction from low-level perceptual features in a compositional scene. Current approaches randomize the initial state of slots followed by an iterative refinement. As we show in this paper, the random slot initialization significantly affects the accuracy of the final slot prediction. Moreover, current approaches require a predetermined number of slots from prior knowledge of the data, which limits the applicability in the real world. In our work, we initialize the slot representations with clustering algorithms conditioned on the perceptual input features. This requires an additional layer in the architecture to initialize the slots given the identified clusters. We design permutation invariant and permutation equivariant versions of this layer to enable the exchangeable slot representations after clustering. Additionally, we employ mean-shift clustering to automatically identify the number of slots for a given scene. We evaluate our method on object discovery and novel view synthesis tasks with various datasets. The results show that our method outperforms prior works consistently, especially for complex scenes.

# Summary. An optional shortened abstract.
summary: This work proposes the conditional slot initialization using clustering algorithms instead of random initialization and allows to generate flexible number of slots. Furthermore, it analyzes the effect of permutation symmetry including invariance and equivariance on the object-centric slot representations indicating the permutation equivariant mean-shift model presents notable advances especially for complex scenes.

tags: [slot attention, self-supervised learning, few-shot learning, scene understanding, novel view synthesis]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2308.11369.pdf'
# url_code: ''
# url_dataset: ''
url_poster: 'content/publication/bmvc23/poster.pdf'
# url_project: 'https://sites.google.com/view/sa6d'
# url_slides: ''
# url_source: ''
url_video: 'https://youtu.be/VyQe44mgfe8'

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
