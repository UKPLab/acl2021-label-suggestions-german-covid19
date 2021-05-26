# Investigating label suggestions for opinion mining in German Covid-19 social media
### Tilman Beck, Ji-Ung Lee, Christina Viehmann, Marcus Maurer, Oliver Quiring, Iryna Gurevych
#### [UKP Lab, Technical University of Darmstadt](https://www.informatik.tu-darmstadt.de/ukp/ukp_home/index.en.jsp)
#### [Institut für Publizistik, Johannes Gutenberg-University Mainz](https://www.uni-mainz.de)

Source code and data from our user study of our [ACL 2021 article](). 

```
@inproceedings{beck-etal-2021-label-suggestions,
    title = "Investigating label suggestions for opinion mining in German Covid-19 social media",
    author = "Beck, Tilman and Lee, Ji-Ung and Viehmann, Christina and Maurer, Marcus and Quiring, Oliver and Gurevych, Iryna",
    booktitle = "Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics",
    month = aug,
    year = "2021",
    address = "virtual conference",
    publisher = "Association for Computational Linguistics",
    pages = "(to appear)",
}
```

> **Abstract:** This work investigates the use of interactively updated label suggestions to improve upon the efficiency of gathering annotations on the task of opinion mining in German Covid-19 social media data. We develop guidelines to conduct a controlled annotation study with social science students and find that suggestions from a model trained on a small, expert-annotated dataset already lead to a substantial improvement -- in terms of inter-annotator agreement (+.14 Fleiss’κ) and annotation quality -- compared to students that do not receive any label suggestions. We further find that label suggestions from interactively trained models do not lead to an improvement over suggestions from a static model. Nonetheless, our analysis of suggestion bias shows that annotators remain capable of reflecting upon the suggested label in general. Finally, we confirm the quality of the annotated data in transfer learning experiments between different annotator groups. To facilitate further research in opinion mining on social media data, we release our collected data consisting of 200 expert and 2,785 student annotations.

* **Contact person:** Tilman Beck, beck@ukp.informatik.tu-darmstadt.de
    * UKP Lab: http://www.ukp.tu-darmstadt.de/
    * TU Darmstadt: http://www.tu-darmstadt.de/

Drop me a line or report an issue if something is broken (and shouldn't be) or if you have any questions.

> This repository contains experimental software and is published for the sole purpose of giving additional background details on the respective publication. 

## Project structure

* `code` &mdash; Experimental source codes
* `data` &mdash; Twitter IDs and annotations for both expert and student data collected and used in our work

## Data description

A description of the data can be found in `data/README.md` .

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a>