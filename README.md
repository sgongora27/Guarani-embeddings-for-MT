# Can We Use Word Embeddings for Enhancing Guarani-Spanish Machine Translation?

This repository contains some of the resources used in "Can We Use Word Embeddings for Enhancing Guarani-Spanish Machine Translation?" (ComputEL-5, co-located with ACL 2022). 

## Contents:
- ``Corpus/`` contains the tweets set used for training some of the 24 embeddings models.
- ``Word embeddings/`` contains 2 out of the 24 trained word embeddings models.
    - ``s150w9none``: size 150, window 9, no tweets
    - ``s300w6none``: size 300, window 6, no tweets
- ``Analogy and Similarity tests/`` contains the tests used for intrinsically evaluating the trained word embeddings.
    - ``Family`` (Analogy)
    - ``capital-common-countries`` (Analogy)
    - ``MC-30`` (Similarity)