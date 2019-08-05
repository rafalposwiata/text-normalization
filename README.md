# text-normalization
Data set prepared for publication ["Numbers Normalisation in the Inflected Languages: a Case Study of Polish"](https://www.aclweb.org/anthology/papers/W/W19/W19-3703/).

Zip contains two files:

- data_set.txt (file with our whole data set),
- tts_answers.txt (file with written answers from TTS systems: Google Cloud Text-to-Speech and Amazon Polly).

In TTS answers there are &lt;dav&gt; tags which means "different accepted version" and indicates situations where TTS system normalize phrase in different way than we in our data set but this normalization is accepted. We treat this cases as correct normalization.
