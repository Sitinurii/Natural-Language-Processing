---
license: apache-2.0
datasets:
- universal-dependencies/universal_dependencies
language:
- id
pipeline_tag: token-classification
library_name: spacy
tags:
- part-of-speech
- nlp
- spacy
- tagger
---

https://github.com/jdoerfler/ar-fa-id-tl-SpaCy-Training

SpaCy morphologizer (universal POS tagger) and dependency labeler. Trained on ~5k samples from Universal Dependencies' id_csui-ud-train.conllu and id_gsd-ud-train.conllu, tested on ~.8k samples Universal Dependencies' id_csui-ud-test.conllu and id_gsd-ud-test.conllu.

  - uPOS accuracy: 0.9293
  - Dep head accuracy: 0.7875
  - Dep label accuracy: 0.6817