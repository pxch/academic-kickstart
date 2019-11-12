+++
title = "Attending to Entities for Better Text Understanding"
date = 2020-02-09
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Pengxiang Cheng**", "Katrin Erk"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

to_appear = true

# Publication name and optional abbreviated version.
publication = "*AAAI Conference on Artificial Intelligence*"
publication_short = "*AAAI*"

# Abstract and optional shortened version.
abstract = "Recent progress in NLP witnessed the development of large-scale pre-trained language models (GPT, BERT, XLNet, etc.) based on Transformer (Vaswani et al. 2017), and in a range of end tasks, such models have achieved state-of-the-art results, approaching human performance. This demonstrates the power of the stacked self-attention architecture when paired with a sufficient number of layers and a large amount of pre-training data. However, on tasks that require complex and long-distance reasoning where surface-level cues are not enough, there is still a large gap between the pre-trained models and human performance. Strubell et al. (2018) recently showed that it is possible to inject knowledge of syntactic structure into a model through supervised self-attention. We conjecture that a similar injection of semantic knowledge, in particular, coreference information, into an existing model would improve performance on such complex problems. On the LAMBADA (Paperno et al. 2016) task, we show that a model trained from scratch with coreference as auxiliary supervision for self-attention outperforms the largest GPT-2 model, setting the new state-of-the-art, while only containing a tiny fraction of parameters compared to GPT-2. We also conduct a thorough analysis of different variants of model architectures and supervision configurations, suggesting future directions on applying similar techniques to other problems."
abstract_short = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://arxiv.org/pdf/1911.04361.pdf"
url_preprint = "https://arxiv.org/abs/1911.04361"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
