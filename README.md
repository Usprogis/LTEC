# Latvian Twitter Eater Corpus

This repository contains the Latvian Twitter Eater Corpus.
Repository structure:
- **full-corpus** - the full corpus in several formats
- **sub-corpora** - task-specific sub-corpora derrived from the full corpus
- **scripts** - scripts for data preparation and analyis

Full-corpus
---------
This directory contains the LTEC. All information from the corpus is hidden, and only the tweet ID are available due to Twitter data usage
rights. To gain the full corpus information, please, contact the repos owner.

Sub-corpora
---------
The directory contains sub-corpora of tweets: 1) tweets representing questions and their replies gathered from the Twitter API; 2) sentiment annotated tweets containing tweets where sentiment is automatically marked by usage of positive or negative emoticons while tweets from media and restaurant accounts marked as neutral, and manually annotated tweets which we used to train and test a our sentiment analyser.
They are labeled as:
- **ltec-questions-answers.json** - contains tweets which express questions along with replies to those tweets
- **ltec-answers-questions.json** - contains tweets which express questions and are replies to other tweets along with the tweets that they are replying to
- **ltec-sentiment-annotated.json** - contains tweets with human annotated sentiment
- **ltec-sentiment-automatic.json** - contains tweets with automatically assigned sentiment based on emoticons and media/restaurant users
- **ltec-translation-test.json** - contains tweets manually translated into English with two reference translations
- **ltec-image-text-relation.json** - contains tweets with attached images and manually annotated relations between the text and attached image


Scripts
---------
This directory contains script files writen in Python and shell, used to gather information from the Latvian Twitter Eater Corpus or LTEC for short.
Here's a short summary about each of them:
- **analysis** - scripts, which give analysis of the corpus.
- **data-preparation** - scripts, used to create the corpus from MySQL database data.
- **experiments** - scripts, for data preparation and training for QA model and sentiment analysis



Publications
---------

If you use this corpus or scripts, please cite the following papers:

Uga Sproģis and Matīss Rikters (2020). "[What Can We Learn From Almost a Decade of Food Tweets.](https://arxiv.org/abs/2007.05194)" In Proceedings of the 9th Conference Human Language Technologies - The Baltic Perspective ([Baltic HLT 2020](https://klc.vdu.lt/hlt/programme)) (2020).

```bibtex
@inproceedings{SprogisRikters2020BalticHLT,
	author = {Sproģis, Uga and Rikters, Matīss},
	booktitle={In Proceedings of the 9th Conference Human Language Technologies - The Baltic Perspective (Baltic HLT 2020)},
	title = {{What Can We Learn From Almost a Decade of Food Tweets}},
	address={Kaunas, Lithuania},
	year = {2020}
}
```

Matīss Rikters, Edison Marrese-Taylor, Rinalds Vīksna (2024). "[Annotations for Exploring Food Tweets from Multiple Aspects.](https://aclanthology.org/2024.lrec-main.111/)" In Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation ([LREC-COLING 2024](https://lrec-coling-2024.org/)) (2024).

```bibtex
@inproceedings{rikters-etal-2024-annotations-exploring,
    title = "Annotations for Exploring Food Tweets from Multiple Aspects",
    author = "Rikters, Matiss  and
      V{\=\i}ksna, Rinalds  and
      Marrese-Taylor, Edison",
    editor = "Calzolari, Nicoletta  and
      Kan, Min-Yen  and
      Hoste, Veronique  and
      Lenci, Alessandro  and
      Sakti, Sakriani  and
      Xue, Nianwen",
    booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)",
    month = may,
    year = "2024",
    address = "Torino, Italy",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.lrec-main.111",
    pages = "1233--1238"
}

```