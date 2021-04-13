# Paper List
The list of NLP papers that i read

## Contents
- [Audio Synthesis](#Audio-Synthesis)
- [text processing](#text-processing)
- [Active Speaker detection](#Active-Speaker-Detection)
- [Dataset](#Dataset)

## Audio-Synthesis
Title | Contributions | Code | Review | Recommand |
--- | --- | --- | --- | --- |
WAVENET: A GENERATIVE MODEL FOR RAW AUDIO [[pdf]](https://arxiv.org/pdf/1609.03499.pdf) | <ul><li> Develop new architectures based on dilated causal convolutions, which exhibit very large receptive fields <il><li> Show that when conditioned on a speaker identity, a single model can be used to generate different voices. large receptive fields. | [code](https://github.com/ibab/tensorflow-wavenet) | - | :star::star::star::star::star: |

## text-processing
Title | Contributions | Code | Review | Recommand |
--- | --- | --- | --- | --- |
BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding[[pdf]](https://arxiv.org/abs/1810.04805) | <ul><li> Demonstrate the importance of bidirectionalpre-training for language representations <il><li>  Show that pre-trained representations reducethe  need  for  many  heavily-engineered  task-specific  architectures | [code](https://github.com/google-research/bert) | - | :star::star::star::star::star: |

## Active-Speaker-Detection
Title | Contributions | Code | Review | Recommand |
--- | --- | --- | --- | --- |
Disentangled Speech Embeddings using Cross-modal Self-supervision[[pdf]](https://arxiv.org/abs/2002.08742) | <ul><li> propose a framework for learning speech representationscapturing information at different time scales in the speech signal,including in particular the identity of the speaker <il><li> Show that we can learn these representations from a large, unlabelledcollection of “talking faces” in videos as a source of free supervision <il><li>show that sharing a trunk architecture for two different tasks (content andspeaker identity) and adding an explicit disentanglement objectivebetween the two improves performance | [code](https://github.com/joonson/syncnet_trainer) | - | :star::star::star::star: |
Out of time: automated lip sync in the wild[[pdf]](https://www.robots.ox.ac.uk/~vgg/publications/2016/Chung16a/chung16a.pdf) | <ul><li> Do not make an intermediate classification of sounds and mouth shapes into vowels or phonemes <li><il> Learn the visual features directly <li><il> Propose network Learning visual, audio information | [code](https://github.com/joonson/syncnet_python) | - | :star::star::star::star::star: |


## Dataset 
Title | Contributions | Code | Review | Recommand |
--- | --- | --- | --- | --- |
Voxceleb: Large-scale speaker verification in the wild(Computer Science and Language 2019)[[site]](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/) | <ul><li> Propose a fully automated and scalable pipeline for creating a large-scale‘real-world’speaker identification data-set <il><li> VGGVox, Deep CNN based neural speaker verification system, which is trained to mapvoice spectrograms to a compact embedding space. | [code](https://github.com/a-nagrani/VGGVox) | - | :star::star::star::star::star: |
