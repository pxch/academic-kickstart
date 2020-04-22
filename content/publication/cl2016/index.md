---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Representing Meaning with a Combination of Logical and Distributional Models"
authors: ["I. Beltagy", "Stephen Roller", "admin", "Katrin Erk", "Raymond J. Mooney"]
date: 2016-12-01

doi: "10.1162/COLI_a_00266"
arxiv: "1505.06816"

bibkey: beltagy-etal-cl2016

# Schedule page publish date (NOT publication's date).
publishDate: 2020-04-01T00:00:00-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Computational Linguistics, 42(4)"
publication_short: "Computational Linguistics"

abstract: "NLP tasks differ in the semantic information they require, and at this time no single semantic representation fulfills all requirements. Logic-based representations characterize sentence structure, but do not capture the graded aspect of meaning. Distributional models give graded similarity ratings for words and phrases, but do not capture sentence structure in the same detail as logic-based approaches. It has therefore been argued that the two are complementary.<br/>We adopt a hybrid approach that combines logical and distributional semantics using probabilistic logic, specifically Markov Logic Networks. In this article, we focus on the three components of a practical system: 1) Logical representation focuses on representing the input problems in probabilistic logic; 2) knowledge base construction creates weighted inference rules by integrating distributional information with other sources; and 3) probabilistic inference involves solving the resulting MLN inference problems efficiently. To evaluate our approach, we use the task of textual entailment, which can utilize the strengths of both logic-based and distributional representations. In particular we focus on the SICK data set, where we achieve state-of-the-art results. We also release a lexical entailment data set of 10,213 rules extracted from the SICK data set, which is a valuable resource for evaluating lexical entailment systems."

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
links:
- name: ACL Proceedings
  url: http://aclweb.org/anthology/J16-4007

url_pdf: http://aclweb.org/anthology/J16-4007.pdf
url_code:
url_dataset:
url_poster:
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
