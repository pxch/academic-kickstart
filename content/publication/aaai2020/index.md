---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Attending to Entities for Better Text Understanding"
authors: ["admin", "Katrin Erk"]
date: 2020-02-09

doi: ""
arxiv: "1911.04361"

bibkey: cheng-erk-aaai2020

# Schedule page publish date (NOT publication's date).
publishDate: 2020-04-01T00:00:00-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the AAAI Conference on Artificial Intelligence"
publication_short: "AAAI"

abstract: "Recent progress in NLP witnessed the development of large-scale pre-trained language models (GPT, BERT, XLNet, etc.) based on Transformer (Vaswani et al. 2017), and in a range of end tasks, such models have achieved state-of-the-art results, approaching human performance. This demonstrates the power of the stacked self-attention architecture when paired with a sufficient number of layers and a large amount of pre-training data. However, on tasks that require complex and long-distance reasoning where surface-level cues are not enough, there is still a large gap between the pre-trained models and human performance. Strubell et al. (2018) recently showed that it is possible to inject knowledge of syntactic structure into a model through supervised self-attention. We conjecture that a similar injection of semantic knowledge, in particular, coreference information, into an existing model would improve performance on such complex problems. On the LAMBADA (Paperno et al. 2016) task, we show that a model trained from scratch with coreference as auxiliary supervision for self-attention outperforms the largest GPT-2 model, setting the new state-of-the-art, while only containing a tiny fraction of parameters compared to GPT-2. We also conduct a thorough analysis of different variants of model architectures and supervision configurations, suggesting future directions on applying similar techniques to other problems."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/1911.04361.pdf
url_code:
url_dataset:
url_poster: cheng_erk_aaai2020_poster.pdf
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
