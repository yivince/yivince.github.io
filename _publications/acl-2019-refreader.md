---
title: "The Referential Reader: A RecurrentEntity Network for Anaphora Resolution"
collection: publications
permalink: /publication/acl-2019-refreader
date: 2019-07-28
venue: 'Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics'
paperurl: 'https://www.aclweb.org/anthology/P19-1593'
paperurltext: 'Link to ACL anthology'
citation: '<b>Fei Liu</b>, Luke Zettlemoyer and Jacob Eisenstein <a href="http://liufly.github.io/files/papers/acl-2019.pdf"><u>The Referential Reader: A RecurrentEntity Network for Anaphora Resolution</u></a>. In <i>Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics</i>, Florence, Italy, pp. 5918-5925'
---

```
@InProceedings{Liu+:2019,
  author    = {Liu, Fei  and  Zettlemoyer, Luke and Eisenstein, Jacob},
  title     = {The Referential Reader: A RecurrentEntity Network for Anaphora Resolution},
  booktitle = {Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics},
  year      = {2019},
  address   = {Florence, Italy},
  pages     = {5918--5925}
}
```

## Abstract
We present a new architecture for storing and accessing entity mentions during online text processing. While reading the text, entity references are identified, and may be stored by either updating or overwriting a cell in a fixed-length memory. The update operation implies coreference with the other mentions that are stored in the same cell; the overwrite operation causes these mentions to be forgotten. By encoding the memory operations as differentiable gates, it is possible to train the model end-to-end, using both a supervised anaphora resolution objective as well as a supplementary language modeling objective. Evaluation on a dataset of pronoun-name anaphora demonstrates strong performance with purely incremental text processing.