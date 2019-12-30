[![HitCount](http://hits.dwyl.io/Santosh-Gupta/NaturalLanguageRecommendations.svg)](http://hits.dwyl.io/Santosh-Gupta/NaturalLanguageRecommendations)

## NaturalLanguageRecommendations

### Paper Data
The papers used for this project were cleaned from Semantic Scholar's Open Corpus. 
Link to the cleaned data used: https://drive.google.com/open?id=1PcdLDJUXoVXorlCTcGlM98GllArk5Z9s


### Notebooks
#### [a relative link](build_index_and_search.ipynb)
Description: 

#### create_abstract_vectors.ipynb
Description: 

#### inference_model.ipynb
Description: 

#### medical_preprocessing.ipynb
Description: This notebook was used to clean the original Open Corpus dataset to retain all papers that either had a PubMed id or were part of MedLine and had at least 1 citation. Cleaned medical data in folder linked above.

#### model.ipynb
Description: 

#### pruning_first_pass.ipynb
Description: This notebook pruned our filtered data meaning that it only kept papers in the cleaned dataset that either had a citation to or were cited by another paper in the cleaned data. Pruned data in folder linked above.

#### text2cite_preprocessing.ipynb
Description: This notebook was used to clean the original Open Corpus data in order to only keep papers related to fields such as engineering, math, physics, and CS. Medical/humanities papers were filtered out. Cleaned CS data in folder linked above.

#### tfrecords_debug.ipynb
Description: 

#### tpu_index.ipynb
Description: 

### Scripts
#### tfrecordwriter.py
Description: 

#### model.py
Description: 
