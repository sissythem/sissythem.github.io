---
title: "A study of text representations for Hate Speech Detection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- sthemeli
- George Giannakopoulos
- Nikiforos Pittaras

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
# - "Equal contribution"

date: "2019-04-13T00:00:00Z"
doi: "2102.04521"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *CICLing2019 Conference*
publication_short: In *CICLing*

abstract: "The pervasiveness of the Internet and social media have enabled the rapid and anonymous spread of Hate Speech 
content on microblogging platforms such as Twitter. Current EU and US legislation against hateful language, in 
conjunction with the large amount of data produced in these platforms has led to automatic tools being a necessary 
component of the Hate Speech detection task and pipeline. In this study, we examine the performance of several, 
diverse text representation techniques paired with multiple classification algorithms, on the automatic Hate Speech 
detection and abusive language discrimination task. We perform an experimental evaluation on binary and multiclass 
datasets, paired with significance testing. Our results show that simple hate-keyword frequency features (BoW) work best, 
followed by pre-trained word embeddings (GLoVe) as well as N-gram graphs (NGGs): a graph-based representation which 
proved to produce efficient, very low-dimensional but rich features for this task. A combination of these representations 
paired with Logistic Regression or 3-layer neural network classifiers achieved the best detection performance, in terms 
of micro and macro F-measure. "

# Summary. An optional shortened abstract.
summary: 

tags: [hatespeech, nlp, ngramgraphs, neuralnets]

# Display this page in the Featured widget?
featured: true

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
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
