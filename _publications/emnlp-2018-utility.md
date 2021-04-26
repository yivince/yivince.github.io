---
title: "Evaluating the Utility of Hand-crafted Features in Sequence Labelling"
collection: publications
permalink: /publication/emnlp-2018-utility
date: 2018-11-02
venue: 'Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing'
paperurl: 'http://aclweb.org/anthology/D18-1310'
paperurltext: 'Link to ACL anthology'
citation: 'Minghao Wu, <b>Fei Liu</b> and Trevor Cohn (2018) <a href="http://liufly.github.io/files/papers/emnlp-2018-utility.pdf"><u>Evaluating the Utility of Hand-crafted Features in Sequence Labelling</u></a>. In <i>Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing</i>, Brussels, Belgium, pp. 2850-2856.'
---

```
@InProceedings{Wu+:2018,
  author    = {Wu, Minghao and Liu, Fei  and  Cohn, Trevor},
  title     = {Evaluating the Utility of Hand-crafted Features in Sequence Labelling},
  booktitle = {Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing},
  year      = {2018},
  address   = {Brussels, Belgium},
  pages     = {2850--2856}
}
```

## Abstract
Deep learning model is believed to be capable of extract representation features automatically with large amount of annotated data. In this work, we demonstrate handcrafted features are still meaningful in deep learning models, especially when the volume of training data is insufficient. We take name entity recognition (NER) as a case study to demonstrate this idea. We propose a novel hybrid approach by incorporating auto-encoders (AE) with Bi-directional LSTM, character-level CNNs and CRF.  Our neural architecture learns features from word and character representations along with basic Part-of-Speech tags, word shapes and gazetteer information. The hybrid model is responsible for NER task and the auto-encoders are used to enhance the parameter optimization during training. We evaluate our system on CoNLL-2003 shared task (English) and obtain the new state of the art performance with F1 score of 91.89, which significantly outperforms all the previous models.