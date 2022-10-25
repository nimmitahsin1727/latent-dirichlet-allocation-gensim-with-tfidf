# latent-dirichlet-allocation-gensim-with-tfidf

## About
Latent dirichlet allocation model from GENSIM library. 

It's a continuation of [latent-dirichlet-allocation-gensim](https://github.com/nimmitahsin1727/latent-dirichlet-allocation-gensim). Here, I've added ***TF-IDF*** mechanism after bag of words step.

##  Outcome:
Steps in [lda-gensim-with-token-filter.ipynb](/lda-gensim-with-token-filter.ipynb).

`
data_words => dictionary => dictionary.filter_extremes => doc2bow => corpus_tfidf => lda_model => topics
`

**Topics:**
```js
[
(0,
  '0.005*"bike" + 0.004*"bnrca" + 0.004*"infante" + 0.004*"dog" + 0.003*"dod" '
  '+ 0.003*"san" + 0.003*"motorcycle" + 0.003*"mile" + 0.003*"bmw" + '
  '0.003*"computer"'),
 (1,
  '0.004*"gun" + 0.004*"curve" + 0.003*"bike" + 0.003*"lock" + 0.003*"helmet" '
  '+ 0.003*"version" + 0.003*"firearm" + 0.003*"make" + 0.003*"know" + '
  '0.003*"point"'),
 (2,
  '0.005*"bike" + 0.004*"graphic" + 0.004*"tank" + 0.004*"chuck" + 0.003*"gun" '
  '+ 0.003*"like" + 0.003*"look" + 0.003*"buy" + 0.003*"value" + '
  '0.003*"email"'),
 (3,
  '0.004*"gun" + 0.003*"mode" + 0.003*"cdt" + 0.003*"child" + '
  '0.003*"motorcycle" + 0.003*"know" + 0.003*"say" + 0.003*"make" + '
  '0.003*"course" + 0.003*"rider"'),
 (4,
  '0.007*"file" + 0.006*"image" + 0.005*"format" + 0.004*"graphic" + '
  '0.004*"use" + 0.004*"bit" + 0.004*"behanna" + 0.004*"need" + 0.003*"know" + '
  '0.003*"thanks"'),
 (5,
  '0.003*"bike" + 0.003*"dave" + 0.003*"image" + 0.003*"gun" + 0.003*"use" + '
  '0.003*"routine" + 0.003*"dog" + 0.003*"weapon" + 0.003*"say" + '
  '0.003*"email"'),
 (6,
  '0.004*"bike" + 0.004*"image" + 0.004*"ranck" + 0.003*"helmet" + '
  '0.003*"speedy" + 0.003*"use" + 0.003*"bmw" + 0.003*"motorcycle" + '
  '0.003*"tony" + 0.003*"john"'),
 (7,
  '0.004*"law" + 0.004*"right" + 0.003*"graphic" + 0.003*"netcomcom" + '
  '0.003*"atf" + 0.003*"bike" + 0.003*"look" + 0.003*"batf" + 0.003*"need" + '
  '0.003*"good"'),
 (8,
  '0.005*"wave" + 0.004*"split" + 0.004*"roby" + 0.004*"newsgroup" + '
  '0.004*"vesa" + 0.004*"graphic" + 0.004*"program" + 0.003*"scott" + '
  '0.003*"group" + 0.003*"need"'),
 (9,
  '0.006*"gun" + 0.003*"bike" + 0.003*"thing" + 0.003*"use" + 0.003*"right" + '
  '0.003*"just" + 0.003*"way" + 0.003*"time" + 0.003*"state" + '
  '0.003*"criminal"')
]
```

## Packages

- pandas
- nltk
- gensim

## Folder structure
```bash
├── lda-gensim-with-tfidf.ipynb
├── training_df.csv
├── testing_df.csv
├── README.md
└── .gitignore
```
