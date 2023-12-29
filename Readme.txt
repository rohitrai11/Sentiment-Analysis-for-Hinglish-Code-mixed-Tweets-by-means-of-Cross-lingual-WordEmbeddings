Step-1: Import required packages from requirements.txt
Step-2: Add the training (train_tweet.csv and train.csv) and test (test.csv) datasets in the root folder.
Step-3: For each experiment run the respective filenames as [python filename.py]

->Training and Test files for each experiment--->
For Baseline_English- train_tweet.csv and test.csv
For all other experiments- train.csv and test.csv

->For Baseline_English experiment, pretrained fasttext embeddings are required that can be downloaded from the link : [https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.en.300.vec.gz] and upload in the root folder.

->For Muse experiment run python [muse/muse_baseline.py]
->For vecmap-baseline experiment run [python vecmap-baseline/vecmap_baseline.py]
->For vecmap-seeddict experiment run [python vecmap-seeddict/vecmap_seeddict.py]

