# Fake-News-Stance-Detection
# **About the Dataset**

**Context**
The rise of "fake news" has become a significant challenge in maintaining quality journalism and ensuring the public has access to reliable information. In response, the Fake News Challenge, launched in early 2017, aimed to promote the development of machine learning-based classification systems for "stance detection." The goal of stance detection is to determine whether a specific news headline "agrees," "disagrees," "discusses," or is "unrelated" to a particular news article. This would help journalists and others more efficiently identify and investigate potential instances of fake news.

**Distribution of the Data**

The stance classes in `train_stances.csv` are distributed as follows:

| Rows  | Unrelated | Discuss | Agree  | Disagree |
| ----- | --------- | ------- | ------ | -------- |
| 49972 | 0.73131   | 0.17828 | 0.0736 | 0.01681  |

There are four possible classifications:

1. **Agree**: The article text agrees with the headline.
2. **Disagree**: The article text disagrees with the headline.
3. **Discuss**: The article text discusses the headline without taking a position.
4. **Unrelated**: The article text is unrelated to the headline (i.e., it doesn't address the same topic).

**Acknowledgements**

For more information about the task, visit [FakeNewsChallenge.org](https://www.fakenewschallenge.org/).


