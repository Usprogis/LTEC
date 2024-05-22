# Latvian Twitter Eater Corpus - Image-text Relation Classification Test Set

The data set contains images attached to the tweets, tweet IDs, text, and a manually annotated relation class between the image and tweet text. 
The relation classes are similar to the ones in the paper "[Categorizing and Inferring the Relationship between the Text and Image of Twitter Posts](https://aclanthology.org/P19-1272/)"

Relations:
---------

    0 - The image ADDS to tweet meaning and tweet text IS represented in the image
    1 - The image ADDS to tweet meaning but tweet text is NOT represented in the image
    2 - The image does NOT ADD to tweet meaning but tweet text IS represented in the image
    3 - The image does NOT ADD to tweet meaning and tweet text is NOT represented in the image


Publications
---------

If you use this corpus or scripts, please cite the following paper:

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