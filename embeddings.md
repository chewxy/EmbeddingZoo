# Pretrained Word Embedding Vectors #

Model | Dimensions | By | Paper (If Any) | Link To Download | File Size | Licence | Method | Notes
------|------------|----|----------------|------------------|-----------|---------|--------|-------
Collobert & Weston | 50 | Ronan Collobert & Jason Weston | [NLP (Almost) From Scratch (2011)](http://ronan.collobert.com/pub/matos/2011_nlp_jmlr.pdf) | [SENNA](http://ronan.collobert.com/senna/download.html) | 185MB  | [NonCommercial Only](http://ronan.collobert.com/senna/license.html) | | The embeddings are in the Senna gzip file
Turian, Ratinov and Bengio | 50 | Joseph Turian, Andriy Mnih, et at | [A simple and general method for semi-supervised learning](http://www.aclweb.org/anthology/P10-1040) | [Here](http://metaoptimize.s3.amazonaws.com/hlbl-embeddings-ACL2010/hlbl-embeddings-scaled.EMBEDDING_SIZE=50.txt.gz) | 84.3 MB | ??? | 100 epochs; context window of 5 words; learn rate: 0.0003 | 
Turian, Ratinov and Bengio | 50 (Unscaled) | Joseph Turian, Andriy Mnih, et at | As Above | [Here](http://metaoptimize.s3.amazonaws.com/hlbl-embeddings-ACL2010/hlbl-embeddings-original.EMBEDDING_SIZE=50.txt.gz) | 66.9 MB |??? | As Above | 
Turian, Ratinov and Bengio | 100 | Joseph Turian, Andriy Mnih, et at | As Above | [Here](http://metaoptimize.s3.amazonaws.com/hlbl-embeddings-ACL2010/hlbl-embeddings-scaled.EMBEDDING_SIZE=100.txt.gz) |  167 MB | ??? | As Above | 
Turian, Ratinov and Bengio | 100 (Unscaled) | Joseph Turian, Andriy Mnih, et at | As Above | [Here](http://metaoptimize.s3.amazonaws.com/hlbl-embeddings-ACL2010/hlbl-embeddings-original.EMBEDDING_SIZE=100.txt.gz) | 132 MB |??? | As Above |
GloVe Wikipedia 2014| 50, 100, 200, 300 | Jeffrey Pennington, Richard Socher, Christopher Manning | [Global Vectors for Word Representation](http://nlp.stanford.edu/pubs/glove.pdf) | [Here](http://nlp.stanford.edu/data/glove.6B.zip) | 822 MB |Public Domain (?) | See Paper | |
GloVe Common Crawl 42B | 300 | As Above | As Above | [Here](http://nlp.stanford.edu/data/glove.42B.300d.zip) | 1.75 GB |Public Domain(?) | See Paper | |
GloVe Common Crawl 840B | 300 | As Above | As Above | [Here](http://nlp.stanford.edu/data/glove.840B.300d.zip) | 2.03 GB |Public Domain(?) | See Paper | |
GloVe Twitter 27B | 25, 50, 100, 200 | As Above | As Above | [Here](http://nlp.stanford.edu/data/glove.twitter.27B.zip) | 1.42 GB | Public Domain(?) | See Paper | |
Word2Vec Google News | 300 | Tomas Mikolov, Kai Chen, Greg Corrado and Jeffrey Dean | [Efficient Estimation of Word Representation in Vector Spaces](http://arxiv.org/pdf/1301.3781.pdf) | [Here](https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?usp=sharing) | 1.5 GB | ???? | Skipgram + negative sampling | Common stop words have been removed. Your model may act weirdly
Word2Vec FreeBase | 1000 | Tomas Mikolov, Kai Chen, Greg Corrado and Jeffrey Dean | [Efficient Estimation of Word Representation in Vector Spaces](http://arxiv.org/pdf/1301.3781.pdf) | [Here](https://docs.google.com/file/d/0B7XkCwpI5KDYaDBDQm1tZGNDRHc/edit?usp=sharing) | 2.3 GB | ???? | Skipgram + negative sampling | This is the embeddings for entities, not words.
Dependency Based Word Embeddings | 300 | Omer Levy and Yoav Goldberg |[Dependency Bsaed Word Embeddings](http://levyomer.files.wordpress.com/2014/04/dependency-based-word-embeddings-acl-2014.pdf) | [Here](http://u.cs.biu.ac.il/~yogo/data/syntemb/deps.words.bz2) | 306 MB | ???????? | Dependency Tree as context | |


# TODO: #

Dhillon's Eigen words