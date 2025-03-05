# liita_derivation
repo for liita derivation segmentation development

data directory contains:

##tsv of liita lemmas
- id_lemma
- infl_cat: inflectional category, only for verbs
- gen: gender
- p: plurality (for only-plural nouns)
- grad: degree of comparation (Pos for simple adjectives - now empty)
- lemma: lemma label
- UPOS: upostag
- timestamp
- src: refers to origin of initial lexical basis

##tsv liita hypolemmas
- id_hypolemma
- label
- type: can be ADV_POS for adverbs and PART_PASS and PART_PRES for adjectives
- timestamp
- src: refers to origin of initial lexical basis
