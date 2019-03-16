# text-normalization
Data set prepared for publication "Component System Specialized in Numbers Normalization for Polish".

Zip contains two files:

- data_set.txt (file with our whole data set)
- tts_answers.txt (file with written answers from Text-to-Speech systems: Google Translate and Amazon Polly)

In TTS answers there are <dav> tags which means "different accepted version" and indicates situations where TTS system normalize phrase in different way than we in our data set but this normalization is accepted. We treat this cases as correct normalization.