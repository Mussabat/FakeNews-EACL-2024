# [EACL-2024](https://2024.eacl.org/)

<img title="" src="Figures\EACL.jpeg" alt="">

Code and dataset of the tasks are released here. In order to use the dataset interested ones have to follow policy of workshop organizers.

# Shared Task#1 (FakeDetect-Malayalam)

## Fake News Detection in Dravidian Languages

**Author:** Nafisa Tabassum∗, Sumaiya Rahman Aodhora∗, Rowshon Akter, Jawad Hossain, Shawly Ahsan and Mohammed Moshiul Hoque

**Venue:** Shared task description paper of DravidianLangTech workshop collocated with EACL-2024. [DravidianLangTech@EACL2024](https://sites.google.com/view/dravidianlangtech-2024/home)

**Paper Link:** [https://aclanthology.org/2024.dravidianlangtech-1.30/](https://aclanthology.org/2024.dravidianlangtech-1.30/)

## Abstract

The alarming rise of fake news on social media poses a significant threat to public discourse and decision-making. While automatic detection of fake news offers a promising solution, research in low-resource languages like Malayalam often falls behind due to limited data and tools. This paper presents the participation of team Punny\_Punctuators in the Fake News Detection in Dravidian Languages shared task at DravidianLangTech@EACL 2024, addressing this gap. The shared task focuses on two sub-tasks: 1. classifying social media texts as original or fake, and 2. categorizing fake news into 5 categories. We experimented with various machine learning (ML), deep learning (DL) and transformer-based models as well as processing techniques such as transliteration. Malayalam-BERT achieved the best performance on both sub-tasks, which obtained us $2^{nd}$ place with a macro $f_1$-score of 0.87 for the subtask-1 and $11^{th}$ place with a macro $f_1$-score of 0.17 for the subtask-2. Our results highlight the potential of transformer models for low-resource languages in fake news detection and pave the way for further research in this crucial area.
## Contribution

 - Developed several machine learning (ML), deep learning (DL), and transformer-based models to identify fake news in the Malayalam language.
- Investigated and assessed the performance of the models using a variety of metrics to determine the best approach for the classification of fake news..

## Dataset Analysis

The number of instances used to train, validate and test the models summarized in Table 1.

<img title="" src="Figures\Table.PNG" alt="">

## System Overview

Figure 1 presents the schematic diagram of our system, which has three major phases: preprocessing, feature extraction and classification.

<p align = "center">
<img title="" src="Figures\Methodology.PNG" alt="">
</p>

## Results

Table 3 presents the evaluation results of the tasks on the test set.

<img title="" src="Figures\Result.PNG" alt="">

Figure 2 presents the confusion matrices of the best model for each language.

<img title="" src="Figures\confusion_matrix.png" alt="">

## Conclusion

This work aimed to detect and classify fake news from Malayalam social media text. We have thoroughly investigated several machine learning (ML), deep learning (DL) and transformer-based models for Malayalam fake news identification and classification. The Malayalam-BERT model has proven to be more effective than the others, as evidenced by its highest macro F1-Score of 0.87 for subtask-1 and 0.17 for subtask-2.
In subtask-1, the model excels, securing the 2\textsuperscript{nd} position with a noteworthy macro $f_1$-score of 0.87. In contrast, in subtask-2, it ranks \nth{11} with a macro $f_1$-score of 0.17.
To improve model performance in the future, we want to look at different architectures and use ensemble techniques. We'll explore different ways to tackle problems that come from imbalanced datasets.


## Ackonwlegement

All the works are supported and funded by [CUET NLP Lab](https://cuetnlp.com/). Besides, we are thanking to [Prof. Dr. Mohammed Moshiul Hoque](https://www.researchgate.net/profile/Moshiul_Hoque) for his valuable guidance.

## Citation

If you use our work please consider citing our paper:

```
@inproceedings{tabassum2024punny_punctuators,
  title={Punny\_punctuators@ dravidianlangtech-eacl2024: Transformer-based approach for detection and classification of fake news in malayalam social media text},
  author={Tabassum, Nafisa and Aodhora, Sumaiya and Akter, Rowshon and Hossain, Jawad and Ahsan, Shawly and Hoque, Mohammed Moshiul},
  booktitle={Proceedings of the Fourth Workshop on Speech, Vision, and Language Technologies for Dravidian Languages},
  pages={180--186},
  year={2024}
}
```
