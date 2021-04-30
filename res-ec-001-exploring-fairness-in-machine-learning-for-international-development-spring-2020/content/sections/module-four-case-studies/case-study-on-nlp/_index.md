---
course_id: res-ec-001-exploring-fairness-in-machine-learning-for-international-development-spring-2020
layout: course_section
menu:
  leftnav:
    identifier: a5c725d2f88055c12a5dbcda24b3db0b
    name: Demographic Bias in NLP
    parent: cce773cc98d045b1b18183c340d2d168
    weight: 120
parent_title: 'Module 4: Case Studies with Data '
title: 'Case Study on Natural Language Processing: Identifying and Mitigating Unintended
  Demographic Bias in Machine Learning for NLP'
type: course
uid: a5c725d2f88055c12a5dbcda24b3db0b

---

{{< youtube 3f98wYIWsN0 >}}

[Case Study on Natural Language Processing: Identifying and Mitigating Unintended Demographic Bias in Machine Learning for NLP slides (PDF - 1.3MB)]({{< baseurl >}}/sections/module-four-case-studies/case-study-on-nlp/mitres_ec001s19_video9)

Learning Objectives
-------------------

*   Explore a case study on bias in NLP.
*   Demonstrate techniques to mitigate word embedding bias.

Content
-------

Natural language processing is used across multiple domains, including education, employment, social media, and marketing. There are many sources of unintended demographic bias in the NLP pipeline. The NLP pipeline is the collection of steps from collecting data to making decisions based on the model results.

### Unintended demographic bias

Key definitions for this course:

*   Unintended: bias has an adverse side effect, but it is not deliberately learned.
*   Demographic: the bias is some form of inequality between demographic groups.
*   Bias: artifact of the NLP pipeline that causes unfairness.

There are two types of unintended demographic bias, sentiment bias and toxicity bias. Sentiment bias refers to an artifact of the ML pipeline that causes unfairness in sentiment analysis algorithms. Toxicity bias refers to an artifact of the ML pipeline that causes unfairness in toxicity prediction algorithms.

Whether a phrase is toxic or non-toxic can be determined by a single word, and specific nationalities or groups are often marginalized. For example, "I am American" may be classified as non-toxic where as "I am Mexican" may be classified as toxic.

### Bias introduction

Bias introduction can occur at many phases in the NLP pipeline, including the word corpus, word embedding, dataset, ML algorithm, and decision steps. Possible unfairness can occur from the applying these results to society.

### Measuring word embedding bias

Word embeddings encode text into vector spaces where the distance between words describes important semantic meaning. This allows for analogies such as man is to woman as to king is to queen. However, research shows that biases from word embeddings trained from Google News articles will complete the analogy man is to woman as to computer scientist is to homemaker.

A method to quantify word embedding bias is demonstrated in the slides. Biased word embeddings are used to initialize a set of unbiased labeled word sentiments. A logistic regression classifier is trained using this dataset and predicts negative sentiment for a set of identities, for example "American" or "Canadian."

The probabilities for negative sentiment can be compared to a uniform distribution to generate a relative negative sentiment bias (RNSB) score.

### Mitigating word embedding bias

Adversarial learning can be used to debias word embeddings. Different identity terms can be more or less correlated with negative or postitive sentiment. In datasets, "American," "Mexican," or "German" can have more correlations with negative sentiment subspaces, which can cause downstream unfairness. We would ideally have balanced correlations between positive and negative sentiment subspaces for each group to prevent any effects of bias. Adversarial learning algorithms can be used to mitigate these biases.

Key Takeaways
-------------

*   No silver bullet for NLP applications.
*   Bias can come from all stages of the ML pipeline and implementing mitigation strategies at each stage is essential to addressing bias.

 Contributions
--------------

Content presented by Audace Nakeshimana (MIT).

The research for this project was conducted in collaboration with Christopher Sweeney and Maryam Najafian (MIT). The content for this presentation was created by Audace Nakeshimana, Christopher Sweeney, and Maryam Najafian (MIT).