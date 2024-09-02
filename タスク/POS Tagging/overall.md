
# POS Tagging

## Algorithms
### Embedding Module
- **Hand-crafted Features**
  - Spelling features
    - 2011_Word_suffix,_gazetteer,_capitalization,_tags
  - Context features
    - 2015_unigram,_bi-gram,_tri-gram
  - 2011_Senna
- **Pretrained Word Embeddings**
  - Word2Vec
  - GloVe
  - ELMo
  - BERT
- **Character-level Representations**
  - CNN
    - 2014_Max_pooling
    - 2018_ItNet
  - RNN
    - 2015_BiLSTM_on_word+Final_States
    - 2017_+Attention
    - 2018_+Self-supervised_Task
- **Sentence-level Representations**
  - 2019_Assign_every_word_with_a_global_representation

### Context Encoder Module
- **RNN**
  - 2015_Bi-LSTM
  - 2017_Bi-GRU
  - 2017_LM_as_auxiliary-task
  - 2017_Multi-Order_BiLSTM
  - 2017_Classification_as_auxiliary-task
  - 2018_Parallel_BiLSTM
  - 2017_Implicitly-defined_neural_networks
  - 2018_Lattice-LSTM
  - 2019_Deep-transition_RNN
  - 2020_+Attention
- **CNN**
  - 2017_GCNN
  - 2017_ID-CNN
  - 2019_LR-CNN
- **GNN**
  - 2019_GRN
  - 2019_CGN
  - 2019_TENER
- **Transformer**
  - 2019_Star-Transformer
  - 2020_FLAT

### Inference Module
- **Softmax**
  - 2015_SRNN
- **CRF**
  - 2005_Semi-CRF
  - 2016_grSemi-CRFs
  - 2018_HSCRF
  - 2012_Skip-chain_CRF
  - 2018_Embedded-State_Latent_CRF
  - 2019_NCRF_transducers
  - 2016_parallel_with_context_encoder
  - 2018_before_Softmax
  - 2018_joint_labeling
  - 2017_Encoder-Decoder-Pointer_Framework
- **RNN**
  - 2016_parallel_with_context_encoder
  - 2018_before_Softmax
  - 2018_joint_labeling

## Explanation
