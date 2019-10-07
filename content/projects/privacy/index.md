---
title: "Protecting patient privacy"
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

summary: Protecting patient privacy with Generative Adversarial Networks (GAN).

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
  caption: 'Image credit: [**Bajibabu Bollepalli**](https://www.researchgate.net/publication/317388182_Generative_Adversarial_Network-Based_Glottal_Waveform_Model_for_Statistical_Parametric_Speech_Synthesis)'
  focal_point: ""
  preview_only: false
---

Data access is an important component of advancing any scientific field. The Artificial Intelligence community has often enjoyed significant performance improvements in Machine Learning tasks due to the availability of datasets such as MNIST, ImageNet, and CIFAR-10.

Improvements are due to two reasons: a common reference for comparing algorithms and reuse on tasks different from those originally proposed by the author and data provider. Healthcare is no different, but suffers from the concern of institutions to protect the confidentiality and privacy of patient information. 

Recently, _Generative Models_ have seen significant advances in the task of synthesizing information with privacy guarantees. From a dataset with sensitive information (e.g. patient test result) it is possible to generate a second set with the same statistical characteristics as the original, but without the records representing any real patient data. In addition, experiments show that a synthetic dataset-trained algorithm has performance comparable to the original with a precisely controlled margin of error.

This anonymization can be viewed as the insertion of noise into the original data. The more noise inserted, the greater the degradation of the statistical signal (i.e. utility) available in the dataset. With Differential Privacy theory, it is possible to precisely calculate the amount of noise needed to ensure the privacy of the people whose information is present in the dataset while controlling the degradation of the statistical signal so that a learning algorithm can still be trained.

This enables us to generate synthetic hospital data and share it without worrying about violating patient privacy. Entities such as the U.S. Census Bureau are already adapting to adopt Differential Privacy technologies (https://digitalcommons.ilr.cornell.edu/ldi/49/).

**We have recently released a pre-print of our work entitled [Ward2ICU: A Vital Signs Dataset of Inpatients from the General Ward](https://arxiv.org/abs/1910.00752) where we train a GAN to synthesize a time-series dataset.**
