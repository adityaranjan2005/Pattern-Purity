# Pattern-Purity

# Overview

Dark patterns encompass user interface designs strategically implemented on online services to prompt users to act in ways inconsistent with their intended behavior.

In this research, we curated a text-based dataset specifically tailored for the automated detection of dark patterns within the realm of e-commerce websites. Machine learning serves as our baseline for detection.

For the baseline detection, we applied the following two methodologies:

Classical NLP Methods (utilizing Bag-of-Words combined with a Classical Machine Learning Model)
Leveraging transformer-based pre-trained language models (such as BERT)

#Dataset

Dataset is a text-based dataset for dark pattern automatic detection (TSV Format). Dark pattern texts were obtained from Mathur et al.’s study in 2019, which consists of 1,818 dark pattern texts from shopping sites. Then, we collect non-dark pattern texts on e-commerce sites by accessing and segmenting the sites targeted by the Mathur et al.'s study.

Scraping code for non-dark pattern texts is on scraping/. That is implemented using Typscript (Javascript) and Puppeteer.
