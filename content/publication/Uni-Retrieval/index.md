---
title: 'Uni-Retrieval: A Universal Framework for Multi-style Retrieval'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Hao Li
  - Peng Jin
  - Qihao Duan
  - Jialu Sui
  - Li Yuan

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-09-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: Image Retrieval has vital applications in various fields including the recommendation system and the search engine. Recent retrieval models provide limited query style options, restricting the expression of user intentions. We present the Uni-Retrieval, a prompt-based retrieval framework to fit multi-style queries, e.g.text, image, sketch, art, mosaic. Specifically, we use prompt learning to leverage the vision-language contrastive models. We extract the query style feature as the prototype and employ it as the guiding element for generating query-specific prompt tokens. We also establish a continuously updated prompt bank to contain the prototype and prompt tokens for different queries. Our Uni-Retrieval framework exhibits both scalability and robustness. We can continuously update the prompt bank for different retrieval scenarios. Facing unknown queries, Uni-Retrieval retrieves corresponding prompt tokens based on prototype similarity for learning purposes. Experiments show that our Uni-Retrieval model outperforms CLIP, BLIP, and prompt-based models on multi-style data from the Imagenet dataset. 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: '[**Uni-Retrieval**](https://arxiv.org/abs/2307.07697)'
  focal_point: ''
  preview_only: false

links:
  - name: Paper
    url: 
  - name: Code
    url: 
# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
