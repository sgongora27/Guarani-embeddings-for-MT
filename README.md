# Can We Use Word Embeddings for Enhancing Guarani-Spanish Machine Translation?

This repository contains some of the resources used in "Can We Use Word Embeddings for Enhancing Guarani-Spanish Machine Translation?" (ComputEL-5, co-located with ACL 2022). 

## Contents:
- ``Corpus/`` contains the tweets set used for training some of the 24 embeddings models.
- ``Word embeddings/`` contains 2 of the 24 trained word embeddings models:
    - ``s150w9none``: size 150 and window 9.
    - ``s300w6none``: size 300 and window 6.
- ``Analogy and Similarity tests/`` contains the tests used for intrinsically evaluating the trained word embeddings.
    - ``Family`` (Analogy)
    - ``capital-common-countries`` (Analogy)
    - ``MC-30`` (Similarity)

## Citation

If you use some part of this work in your research, please cite:

```@inproceedings{gongora-etal-2022-use,
    title = "Can We Use Word Embeddings for Enhancing {G}uarani-{S}panish Machine Translation?",
    author = "G{\'o}ngora, Santiago  and
      Giossa, Nicol{\'a}s  and
      Chiruzzo, Luis",
    booktitle = "Proceedings of the Fifth Workshop on the Use of Computational Methods in the Study of Endangered Languages",
    month = may,
    year = "2022",
    address = "Dublin, Ireland",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.computel-1.16",
    pages = "127--132",
}```
