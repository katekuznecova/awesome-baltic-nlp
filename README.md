# awesome-baltic-nlp
A collection of resources for Natural Language Programming resources for the Baltic languages (Latvian, Lithuanian and Estonian)
Table of Contents
-----------------

-   [Latvian Language](#Latvian-Language)
-   [Lithuanian Language](#Lithuanian-Language)
-   [Estonian Language](#Estonian-Language)

## General
- [fasttext language identification](https://fasttext.cc/docs/en/language-identification.html), includes EE, LT, LV


## Latvian Language

### Datasets

- [Korpuss.lv - Latviešu valodas korpusu kolekcija](http://www.korpuss.lv/)
- [Universaldependencies.org UD Latvian LVTB](https://universaldependencies.org/treebanks/lv_lvtb/index.html) 

### Tools & models

#### Word-Embeddings
 - **FastText** pre-trained word vectors (1): [bin](https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.lv.300.bin.gz), [text](https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.lv.300.vec.gz) The word vectors where trained on *Common Crawl* and *Wikipedia* using fastText. See documentation at [Fasttext.cc](https://fasttext.cc/docs/en/crawl-vectors.html)
 - **FastText** pre-trained word vectors (2): [bin+text](https://dl.fbaipublicfiles.com/fasttext/vectors-wiki/wiki.lv.zip), [text](https://dl.fbaipublicfiles.com/fasttext/vectors-wiki/wiki.lv.vec) The word vectors where trained on *Wikipedia* using fastText. See documentation at [Fasttext.cc](https://fasttext.cc/docs/en/pretrained-vectors.html)
   - Also available for **Latgalian** language: [bin+text](https://dl.fbaipublicfiles.com/fasttext/vectors-wiki/wiki.ltg.zip), [text](https://dl.fbaipublicfiles.com/fasttext/vectors-wiki/wiki.ltg.vec)


### Relevant organisations working on NLP research, projects and products

- [**AI Lab**](ailab.lv) by Latvian University

#### Notable researchers working in developing Latvian NLP / NLU tools, datasets and more

**Dr. Comp. Sc. Inguna Skadiņa**  -- [Publications](https://dblp.org/pid/36/8155.html) -- [CV](http://ailab.mii.lu.lv/users/inguna/)



**[`^        back to top        ^`](#)**


## Lithuanian Language

### Datasets

- [ALKSNIS dependency treebank](https://github.com/UniversalDependencies/UD_Lithuanian-ALKSNIS) The Lithuanian dependency treebank ALKSNIS v3.0 (Vytautas Magnus University).


### Tools and models

#### Part-of-Speech tagging and dependency parsing
- **spaCy** [Lithuanian multi-task CNN](https://spacy.io/models/lt) trained on UD Lithuanian ALKSNIS and TokenMill.lt news corpus. Assigns context-specific token vectors, POS tags, dependency parses and named entities. 3 different models and label scheme included in the documentation. 

#### Word-Embeddings
 - **FastText** pre-trained word vectors: [bin](https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.lt.300.bin.gz), [text](https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.lt.300.vec.gz) The word vectors where trained on *Common Crawl* and *Wikipedia* using fastText. See documentation at [Fasttext.cc](https://fasttext.cc/docs/en/crawl-vectors.html)
 - **FastText** pre-trained word vectors (2): [bin+text](https://dl.fbaipublicfiles.com/fasttext/vectors-wiki/wiki.lt.zip), [text](https://dl.fbaipublicfiles.com/fasttext/vectors-wiki/wiki.lt.vec) The word vectors where trained on *Wikipedia* using fastText. See documentation at [Fasttext.cc](https://fasttext.cc/docs/en/pretrained-vectors.html)
  - Also available for **Samogitian** language: [bin+text](https://dl.fbaipublicfiles.com/fasttext/vectors-wiki/wiki.bat_smg.zip), [text](https://dl.fbaipublicfiles.com/fasttext/vectors-wiki/wiki.bat_smg.vec)

#### Other
- [Rasa NLU COVID model](https://github.com/Naktibalda/rasa-koronavirusas) An open-source model for building an AI assistant to help disseminate information about the virus, how to stay safe, and where to seek help.

**[`^        back to top        ^`](#)**


## Estonian Language

#### Word-Embeddings
- **FastText** pre-trained word vectors: [bin](https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.et.300.bin.gz), [text](https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.et.300.vec.gz) The word vectors where trained on *Common Crawl* and *Wikipedia* using fastText. See documentation at [Fasttext.cc](https://fasttext.cc/docs/en/crawl-vectors.html)
- **FastText** pre-trained word vectors (2): [bin+text](https://dl.fbaipublicfiles.com/fasttext/vectors-wiki/wiki.et.zip), [text](https://dl.fbaipublicfiles.com/fasttext/vectors-wiki/wiki.et.vec) The word vectors where trained on *Wikipedia* using fastText. See documentation at [Fasttext.cc](https://fasttext.cc/docs/en/pretrained-vectors.html)

**[`^        back to top        ^`](#)**
