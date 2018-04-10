# 2018_Interspeech
Data used in experiments described in the paper *Glottal Closure Instant Detection from Speech Signal Using Voting Classifier and Recursive Feature Elimination*.

The data is stored utterance-by-utterance in CSV format and gzipped.

The training dataset UWB is stored [here](data/train/uwb_train.tar.gz).

The testing data is stored in the folder ``data/test`` and includes:
* UWB testing [dataset](data/test/uwb_test.tar.gz)
* CMU ARCTIC BDL [dataset](data/test/bdl.tar.gz) ([speech waveforms](http://festvox.org/cmu_arctic/dbs_bdl.html))
* CMU ARCTIC SLT [dataset](data/test/slt.tar.gz) ([speech waveforms](http://festvox.org/cmu_arctic/dbs_slt.html))
* CSTR KED TIMIT [dataset](data/test/ked.tar.gz) ([speech waveforms](http://festvox.org/dbs/dbs_kdt.html))
