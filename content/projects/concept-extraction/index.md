---
title: "Concept Extraction in Electronic Health Records"
date: "2019-09-13:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"
# external_link: https://arxiv.org/abs/1910.00752

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
# publication: In *Source Themes Conference*
# publication_short: In *STC*

# abstract: 
# Summary. An optional shortened abstract.

summary: Employing Bootstrap Learning Algorithms to Interpret Concept Extraction in EHR. 

# tags:
# - Source Themes
featured: true

links:
# - name: paper
#   url: 
# url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Health Catalyst**](https://www.healthcatalyst.com/ehr-vs-data-warehouse-7-points-to-ponder/)'
  focal_point: ""
  preview_only: false
---
Deep learning algorithms have been sucessful in addressing problems in the healthcare industry. One of the most studied tasks in this industry are electronic health records, where machines search and classify relevant tokens in text records. For this task, the deep learning models are represented by vectors that embeds the words and their contexts within the medical records. Although this dense and vectorized representation allows high precision and recall for the concept extraction task, it is not easy to determine which are the elements within the documents that guided the machine in the classification of the tokens.

An alternative to deep learing algorithms for the concept extraction task are the bootstrap learning algorithms. They can represent the semantics of the electronic health records by grouping similar words and their contexts, organized in a knowledge base. The bootstrap learning algorithms rely on shallow features of the semantics of the text, that is, it only considers words and close dependency contexts to learn. Although these algorithms can not understand long term dependencies like the deep learning algorithms, their knowledge base are built in natural language and are easy to understand.

With the recent success of deep learning models to address real world problems in the healthcare industry, there is a tendency that these complex models will be more present in the future. To allow more transparency and make these solutions more available to the general people, we propose the novel idea of employing the natural language knowledge base built by bootstrap learning algorithms to interpret complex, deep learning models for the task of concept extraction in electronic health records.
