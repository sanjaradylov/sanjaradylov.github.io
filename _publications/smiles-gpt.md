---
title: "Generative Pre-Training from Molecules"
collection: publications
permalink: /publication/smiles-gpt
excerpt: 'Pre-training a multi-task GPT-2 transformer for drug design. Transfer learning with adapter modules for molecular-property prediction and focused molecule generation.'
date: 2021-09-16
venue: 'ChemRxiv'
paperurl: 'http://doi.org/10.33774/chemrxiv-2021-5fwjd'
citation: 'Adilov, Sanjar (2021): Generative Pre-Training from Molecules. ChemRxiv. Preprint. doi:10.33774/chemrxiv-2021-5fwjd'
---
Pre-training a multi-task GPT-2 transformer for drug design. Transfer learning with adapter modules for molecular-property prediction and focused molecule generation.
[[ChemRxiv]](http://doi.org/10.33774/chemrxiv-2021-5fwjd)

## Abstract
SMILES is a line notation for entering and representing molecules. Being inherently a language construct, it allows estimating molecular data in a self-supervised
fashion by employing machine learning methods for natural language processing (NLP). The recent success of attention-based neural networks in NLP has made large-corpora
transformer pretraining a de facto standard for learning representations and transferring knowledge to downstream tasks. In this work, we attempt to adapt transformer
capabilities to a large SMILES corpus by constructing a GPT-2-like language model. We experimentally show that a pretrained causal transformer captures general knowledge
that can be successfully transferred to such downstream tasks as focused molecule generation and single-/multi-output molecular-property prediction. For each task, we
freeze model parameters and attach trainable lightweight networks between attention blocks—adapters—as alternative to fine-tuning. With a relatively modest setup, our
transformer outperforms the recently proposed ChemBERTa transformer and approaches state-of-the-art MoleculeNet and Chemprop results. Overall, transformers pretrained on
SMILES corpora are promising alternatives that do not require handcrafted feature engineering, make few assumptions about structure of data, and scale well with the
pretraining data size.
