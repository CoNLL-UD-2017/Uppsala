# Uppsala
CoNLL 2017 Shared Task Team Uppsala

The Uppsala submission to the CoNLL 2017 shared task has two components:
* a joint sentence segmenter and tokenizer
* a transition-based parser

The parsing code is [here](http://github.com/UppsalaNLP/uuparser). The version we used for the shared task was released as [version 1.0](https://github.com/UppsalaNLP/uuparser/tree/1.0).  
The segmentation code is [here](http://github.com/UppsalaNLP/segmenter). The version we used for the shared task was released as [version 1.0](https://github.com/UppsalaNLP/segmenter/tree/1.0).

We added the scripts that we used for the shared task in scripts/. Our system was run with:

```
./bash_script.sh $inputDataset $outputDir
```

Note that our scripts point to our local models and installation on tira. If there is any interest, we can modify this to be more easily customisable.

You can read more about our system in this paper:

Miryam de Lhoneux, Yan Shao, Ali Basirat, Eliyahu Kiperwasser, Sara Stymne, Yoav Goldberg, and Joakim Nivre. 2017. From raw text to Universal Dependencies - look, no tags! In Proceedings of the CoNLL 2017 Shared Task: Multilingual Parsing from Raw Text to Universal Dependencies. Association for Computational Linguistics.

