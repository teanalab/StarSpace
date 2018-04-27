# StarSpace for multitask learning of TransE + word2vec + alignment

run with `-trainMode 6 -fileFormat fastText -trainWord 1 -label 'e:' -relation 'r:'`

Input data.txt:
```
e:headEntityURI <tab> r:relationURI <tab> e:tailEntityURI
word_1 word_2 ... word_k <tab> e:entityURI
```