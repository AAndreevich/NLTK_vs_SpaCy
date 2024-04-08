# NLTK_vs_SpaCy

* Используя библиотеку Spacy, вывести ТОП-20 популярных NER в combine_df датасете. Какой тип NER (ORG, GPE, PERSON и тд) оказался самым популярным? (Учтите, что max_word_limit_spacy для Spacy = 1000000)
С помощью Spacy выяснить: какие персоны и организации самые обсуждаемые в train и test датасетах? вывести ТОП-20 самых популярных. Действительно ли в топ вошли только персоны и организации или есть мусор?

Повторим шаги из заданий 1 и 2, используя библиотеку nltk.

* Используя библиотеку nltk, вывести ТОП-20 популярных NER в combine_df датасете. Какой тип NER (ORG, GPE, PERSON и тд) оказался самым популярным? Для данного задания используем ограничение на количество символов во входном датасете (max_word_limit_spacy = 1000000), чтобы иметь возможность сравнить результаты работы Spacy и nltk. Обратите внимание, что nltk чувствителен к регистру.
С помощью nltk выяснить: какие персоны и организации самые обсуждаемые в train и test датасетах? вывести ТОП-20 самых популярных. Действительно ли в топ вошли только персоны и организации или есть мусор?

In my opinion the "SpaCy" were better then nltk because it took less time for get the results and code. And nltk finded only two criterion while "SpaCy" more 10 criterion in the same text.

Maybe I did something wrong while use nltk.

Code on collab
https://colab.research.google.com/drive/1d34HKGxKXAqdnWmBolJSz4whCvkoRFLW?usp=sharing
