# Stanford CS224n Winter 2019
###### Natural Language Processing with Deep Learning - Assignment Solutions

Read the handout PDFs in each assignment folder for instructions and details.

### Results Showcase

#### Assignment 1 (Word Vector Visualization & Interpretation)

Please see the [Notebook](a1/exploring_word_vectors.ipynb).

#### Assignment 2 (Word2Vec)
Plot of Word Vector Space.

![Plot](a2/word_vectors.png)

#### Assignment 3 (Dependency Parsing)

* DEBUG = True [Output Log](a3/debug_true_output.txt).
  * Best Avg Train Loss - 0.116
  * Best Dev UAS - 73.76

* DEBUG = False [Output Log](a3/debug_false_output.txt).
  * Best Avg Train Loss - 0.058
  * Best Dev UAS - 88.78
  * Best Test UAS - 88.91

#### Assignment 4 (Neural Machine Translation)

Click [here](a4/outputs/test_outputs.txt) to see the Test Output.

Console Output:
```
(local_nmt) $ sh run.sh test
load test source sentences from [./en_es_data/test.es]
load test target sentences from [./en_es_data/test.en]
load model from /media/storage2/nmt/model.bin
Decoding: 100%|███████████████████████████████████████████████████| 8064/8064 [04:20<00:00, 30.90it/s]
Corpus BLEU: 22.768024049390718
```

#### Assignment 5
Coming Soon!

