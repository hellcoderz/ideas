## CLA

* Read the whitepaper: http://numenta.org/resources/HTM_CorticalLearningAlgorithms.pdf

## HTM

* get accuanted with HTM code: https://github.com/numenta/nupic

## CEPT word SDR

* word SDR is a sparse bitmap representation for a word based on its meaning
* each SDR has 128 x 128 features 
* "cat" bitmap and "dog" bitmap is different but "cat" and "dog"
    has some similarirty and that's why they have similar regions which
    depicts simarirty and some dissimilar regions which depicts their 
    unique features

## Use SDR representation for VREX NLU

* create SDR representation for all patterns and entities
* get representations for all words in the query
* and based on SDR representations get all valid entities
* disambigute
* add all the SDR representations to get desired set of actions
