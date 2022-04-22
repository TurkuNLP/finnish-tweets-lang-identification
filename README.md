# Language Identification Data for Finnish Tweets

Manually annotated language identification data for Finnish tweets with binary labels (Finnish/non-Finnish).

## Data

The tweets were downloaded between years 2016-2018 using the Twitter streaming API. While downloading, only tweets labeled as Finnish (`lang:fi` available in the tweet json) by the Twitter language identification were kept. From these downloded tweets, a random sample was taken and all tweets in the sample were manually annotated with binary labels (Finnish/non-Finnish).

The dataset is divided into two files: Finnish tweets are in `finnish-tweets.txt` and non-Finnish tweets in `non-finnish-tweets.txt`. Lines starting with `###C:` are comments including metadata, such as retweet status, username and time of publication. Tweets are separated using an empty line.

## License

The annotations are released with the [CC-BY-SA license](https://creativecommons.org/licenses/by-sa/4.0/).

## Reference

If you use this data, please cite the following paper:

```
@inproceedings{kanerva-2022-ood,
    title = "Out-of-Domain Evaluation of Finnish Dependency Parsing",
    author = {Kanerva, Jenna and Ginter, Filip},
    booktitle = "Proceedings of the 13th International Conference on Language Resources and Evaluation (LREC'22)",
    year = "2022",
}
```
