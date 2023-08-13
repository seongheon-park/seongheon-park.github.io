---
title: 'Hierarchical Visual Primitive Experts for Compositional Zero-Shot Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hanjae Kim
  - Jiyoung Lee
  - admin
  - Kwanghoon Sohn

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2023-10-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2023-10-02T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CVF International Conference on Computer Vision*
publication_short: In *ICCV 2023*

abstract: Compositional zero-shot learning (CZSL) aims to recognize unseen compositions with prior knowledge of known primitives (attribute and object). Previous works for CZSL often suffer from grasping the contextuality between attribute and object, as well as the discriminability of visual features, and the long-tailed distribution of real-world compositional data. We propose a simple and scalable framework called Composition Transformer (CoT) to address these issues. CoT employs object and attribute experts in distinctive manners to generate representative embeddings, using the visual network hierarchically. The object expert extracts representative object embeddings from the final layer in a bottom-up manner, while the attribute expert makes attribute embeddings in a top-down manner with a proposed object-guided attention module that models contextuality explicitly. To remedy biased prediction caused by imbalanced data distribution, we develop a simple minority attribute augmentation (MAA) that synthesizes virtual samples by mixing two images and oversampling minority attribute classes. Our method achieves SoTA performance on several benchmarks, including MIT-States, C-GQA, and VAW-CZSL. We also demonstrate the effectiveness of CoT in improving visual discrimination and addressing the model bias from the imbalanced data distribution. 


# Summary. An optional shortened abstract.
summary: IEEE/CVF International Conference on Computer Vision (ICCV) 2023

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2308.04016.pdf'
url_code: 'https://github.com/HanjaeKim98/CoT'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
