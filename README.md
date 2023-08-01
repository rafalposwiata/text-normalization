# text-normalization
Dataset prepared for publication ["Numbers Normalisation in the Inflected Languages: a Case Study of Polish"](https://www.aclweb.org/anthology/W19-3703).

Zip contains two files:

- data_set.txt (file with our whole dataset),
- tts_answers.txt (file with written answers from TTS systems: Google Cloud Text-to-Speech and Amazon Polly).

In TTS answers there are &lt;dav&gt; tags which means "different accepted version" and indicates situations where TTS system normalize phrase in different way than we in our data set but this normalization is accepted. We treat these cases as correct normalization.

If you use the dataset from this repository, please cite:

```bib
@inproceedings{poswiata-perelkiewicz-2019-numbers,
    title = "Numbers Normalisation in the Inflected Languages: a Case Study of {P}olish",
    author = "Po{\'s}wiata, Rafa{\l} and Pere{\l}kiewicz, Micha{\l}",
    booktitle = "Proceedings of the 7th Workshop on Balto-Slavic Natural Language Processing",
    month = aug,
    year = "2019",
    address = "Florence, Italy",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/W19-3703",
    doi = "10.18653/v1/W19-3703",
    pages = "23--28"
}
```
