# Thesis Title
BL-NERC: An Introduction to Bengali Literature Named Entity Recognition Corpus
# Thesis Abstract
Named Entity Recognition (NER) iden-
tifies specific nouns in text, such as people, places,
and organizations. While it’s challenging to perform
NER on the Bangla language due to its complexity
and lack of resources, this study aims to address this
gap. We introduce a new Bangla NER dataset sourced
from Bengali literature, consisting of 650K sentences
where we annotated 30K sentences with a kappa score
of 83%. The data is categorized into four entity types:
persons, locations, organizations, and times, and uses
the BIO tagging method to mark entity boundaries.
This dataset, curated from 16 famous Bengali authors,
is one of the largest of its kind and has been carefully
annotated by experts. Our research provides detailed
annotation guidelines and highlights the key aspects
of this BanglaLit-NEC dataset. For initial testing, we
used sequence-to-sequence and transformer models
for finetune where pretrained BERT model named
”sagarsarkar/bangla-bert-base” performed the best
with a Micro-F1 score of 85%. This study presents
a significant dataset for Bangla literature NER, along
with a clear methodology and evaluation. Our work
can pave the way for future advancements in the
Bangla NER field.
