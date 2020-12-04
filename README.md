# TripR-2020 dataset

We present **Trip**advisor **R**estaurant **2020** (TripR-2020) dataset, a new set of reviews from Tripadvisor referred to restaurants located in the city of London.

Trip-2020 dataset provides the reviews of 1,428 experts evaluating 78 restaurants. Not all experts evaluate all the restaurants. The dataset collects 8,306 reviews. In particular, each review is given by attributes:

- Concerning the restaurant: name, identifier code, location name, and location identifier code.
- Concerning the expert: name, identifier code, and location name.
- Concerning the review: title, body, date, general rating, food rating, service rating, and value rating.


## Reduced dataset
For the evaluation of the **S**entiment **A**nalysis based **M**ulti-**p**erson **M**ulti-**c**riteria **D**ecision **M**aking (**SA-MpMcDM**) methodology, a reduction of the TripR-2020 dataset has been analyzed. Specifically, 4 restaurants are evaluated by 6 experts. The six experts evaluate the four restaurants providing a total of 24 reviews and avoiding the loss of information.

The dataset is annotated following the official SemEval-2016 annotation manual. We show the main features of the annotation:

| Features      | Value |
| ----------- | ----------- |
| Num. Sentences      | 168       |
| Num. Opinions   | 185        |
| Num. Pos. Opinions | 149 |
| Num. Neg. Opinions | 26 |
| Aspect categories | Restaurant, Food, Service, Drinks, Ambience and Location|
| Polarities value | positive, negative and neutral|

The 24 reviews from the dataset are split into 168 sentences. We labelled 185 opinions of which 149 are positive, 26 are negative and the rest are neutral opinions. Each sentence can have at least an aspect category annotated (Restaurant, Food, Service, Drinks, Ambience and Location).

## Example
We show an example of annotation of a review from the TripR-2020 dataset:

| Sentence  | Aspect | Category | Polarity |
| ----------- | ----------- | ----------- | ----------- |
| Consistently good.	| *implicit* 	| Restaurant	| positive |
| I have been coming for years.	| *implicit* 	| Restaurant	| positive |
| Always good atmosphere and fun people watching.	| atmosphere 	| Ambience	| positive |
| The food is always good and quick.	| food 	| Food	| positive |

The review is split into sentences. First column presents the text of the sentence. Second column is referred to the aspect terms discussed in the sentence. The aspect is *implicit* when the aspect term is not explicitly mentioned in the sentence. Third column is the aspect category to which the aspect term is categorized. Fourth column is the sentiment polarity about each aspect category.






## Citation
Please use the following citation:

[Zuheros, C., Martínez-Cámara, E., Herrera-Viedma, E., & Herrera, F. Sentiment Analysis based Multi-Person Multi-criteria Decision Making methodology using natural language processing and deep learning for smarter decision aid. Case study of restaurant choice using TripAdvisor reviews. Information Fusion 68 (2021) 22-36](https://doi.org/10.1016/j.inffus.2020.10.019)
```
@article{zuheros2021SAMpMcDM,
   author = "Cristina Zuheros and Eugenio Martínez-Cámara and Enrique Herrera-Viedma and Francisco Herrera",
   title = "Sentiment Analysis based Multi-Person Multi-criteria Decision Making methodology using natural language processing and deep learning for smarter decision aid.   Case study of restaurant choice using TripAdvisor reviews",
   journal = "Information Fusion",
   volume = "68",
   pages = "22 - 36",
   year = "2021",
}
```


## Contact
María Cristina Zuheros Montes - czuheros@ugr.es
