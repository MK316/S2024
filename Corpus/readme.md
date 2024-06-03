# 🌿 Corpus Linguistics (Spring 2024)
### Course Overview

This graduate-level course, designed for in-service English teachers at the secondary education level, offers an insightful exploration into corpus linguistics, combined with a practical introduction to Natural Language Processing (NLP) using basic Python coding. By integrating these computational techniques, the course aims to enhance the study of large electronic text collections (corpora) and their application in understanding language use and patterns. Participants will gain a deeper comprehension of language variation and how it can inform and improve teaching practices, leading to more effective development of teaching materials and activities. The course provides a balanced mix of theoretical instruction and practical application, focusing on the analysis and interpretation of corpus data in English language usage and introducing essential NLP techniques through Python programming.

## Course board & links
| 💾 [Syllabus](https://github.com/MK316/Spring2024/blob/main/Corpus/data/S24_Syllabus_Corpus_Linguistics.pdf) | 👭 [Padlet: inclass activity](https://padlet.com/mirankim316/S24Corpus) | 📗[Python basics manual](https://github.com/MK316/Coding4ET/blob/main/README.md) | 🌳 [Class log](https://github.com/MK316/Spring2024/blob/main/log-corpus.md) |

## Weekly Schedule

|Week|Date|Key topic(s)|Description|Code page|Assignments|
|--|--|--|--|--|--|
|W01|Mar6|Introduction|Course overview, syllabus; What is corpus linguistics?||[survey](https://forms.gle/xcNdf7gxZFCsxEH9A)|
|W02|Mar13|Python basics #1| Online Corpora: COCA, BNC, Types of corpora; NLTK|[CL01](https://github.com/MK316/Spring2024/blob/main/Corpus/lecture/Ch01_What%20is%20corpus%20linguistics_0313.pdf),[CL02](https://github.com/MK316/Spring2024/blob/main/Corpus/CL02.md),🔸[nltk](https://www.nltk.org/book/ch01.html),[📗](https://github.com/MK316/Coding4ET/blob/main/README.md)||
|W03|Mar20|Python basics #2|Data types, NLTK (section 1)|🔸[nltk](https://www.nltk.org/book/ch01.html), [NLTK01](https://github.com/MK316/Spring2024/blob/main/Corpus/NLTK01.ipynb)||
|W04|Mar27|Project #1| NLTK, 🔸[Word cloud](https://github.com/MK316/Spring2024/blob/main/Corpus/wordcloud.md), 🔸[Word Frequency list](https://github.com/MK316/Spring2024/blob/main/Corpus/NLP01.ipynb)|🔸[nltk](https://www.nltk.org/book/ch01.html)||
|W05|Apr3|Lexical analysis|Type vs. token, lemmatization |[Code](https://github.com/MK316/Spring2024/blob/main/Corpus/TTR-and-lemmatization.ipynb), 🔸[nltk](https://www.nltk.org/book/ch01.html)|[Assign01 (Apr17)](https://github.com/MK316/Spring2024/blob/main/Corpus/assignment/assign01.md)|
|W06|(Apr10)|Keywords|Text analysis, Words in context, concordance, collocations|[NgramCode](https://github.com/MK316/Spring2024/blob/main/Corpus/Words_in_context.ipynb)||
|W07|Apr17|Lexical diversity|Type-Token-Ratio (TTR) and other lexical diversity measures|Reading[^1][^2][^3],<br>[wordlist-stopwords](https://github.com/MK316/Spring2024/blob/main/Corpus/NLTK_FreqList.ipynb),<br>[code](https://github.com/MK316/Spring2024/blob/main/Corpus/Lexical-Diversity.ipynb)|Assign1 Presentation (15mins)|
|W08|Apr24|lexical diversity measures|Midterm discussion|[LD-practice](https://github.com/MK316/Spring2024/blob/main/Corpus/LD_practice.ipynb),<br>[N-gramCode](https://github.com/MK316/Spring2024/blob/main/Corpus/Words_in_context.ipynb)||
|W09|(May1)|Midterm |(take-home)|||
|W10|May8|Readability, Topic-modeling| Readability measures, NLP preprocessing, topic-modeling|[Intro](https://github.com/MK316/Spring2024/blob/main/Corpus/readability-intro.md), [Readability](https://github.com/MK316/Spring2024/blob/main/Corpus/Readability01.ipynb), [App](https://github.com/MK316/Spring2024/blob/main/Corpus/Readability_textstat_app.ipynb)|[sampletext](https://www.corpusdata.org/formats.asp), [RE](https://github.com/MK316/Spring2024/blob/main/Corpus/RE01.ipynb), [ArticleUse](https://github.com/MK316/Spring2024/blob/main/Corpus/Articles.ipynb)|
|W11|(May15)|Sentiment Analysis|Data collection, | Individual project submission|
|W12|May22|Clustering Analysis|Data collection, (Clustering Analysis), Sentiment Analysis|[Code](https://github.com/MK316/Spring2024/blob/main/Corpus/SentimentalAnalysis.ipynb)|||
|W13|May29|Project #2|Idea brainstorming, individual project discussions, samples||[TEDdata](https://docs.google.com/spreadsheets/d/1HCmWn9U0kpJFxpVVr0SticO9mwhsqetcyULJpDW8pfw/edit?usp=sharing)|
|W14|June5|Project #3|individual project discussions, samples|Removing timestamps, parenthetical notes|[Text preprocess 01](https://github.com/MK316/Spring2024/blob/main/Corpus/TEDdata/TED_preprocess.ipynb)|
|W15|June12|Final project|Presentations|||

## 📙 How to handle frequency data

### 1. **Data Types and Variables:** ➡️[details](https://github.com/MK316/Spring2024/blob/main/Corpus/L01.md)
+ Understanding different types of data (quantitative vs. qualitative) and variables (discrete vs. continuous).
### 2. **Frequency Data Basics::**
+ Definition of frequency data.
+ Differentiating between absolute frequency, relative frequency, and cumulative frequency.

### 3. **Data Collection and Organization:****

+ Techniques for collecting frequency data
+ Organizing data into tables and charts.

### 4. **Descriptive Statistics:**

+ Measures of central tendency (mean, median, mode) specifically for frequency data.
+ Measures of variability (range, variance, standard deviation).

### 5. **Graphical Representation of Data:**
+ Histograms, bar charts, and pie charts for frequency data.
+ Understanding and interpreting these graphical representations.

### 6. **Probability Fundamentals:**
+ Basic probability concepts and rules.
+ Probability distributions relevant to frequency data (e.g., binomial, Poisson).

### 7. **Sampling and Sampling Distributions:**
+ Concepts of population vs. sample.
+ Understanding sampling distributions and the central limit theorem.

### 8. Hypothesis Testing and Inferential Statistics:
+ Concepts of null and alternative hypotheses.
+ Tests of significance (e.g., Chi-square test) for frequency data.

### 9. **Correlation and Regression Analysis:**
+ Understanding the relationship between variables.
+ Linear regression analysis pertinent to frequency data.

### 10. **Data Interpretation and Reporting:**
+ Analyzing and interpreting statistical results.
+ Effective communication of findings.

### 11. **Ethical Considerations in Data Analysis:**
+ Ethical issues in data collection, analysis, and reporting.
+ Data privacy and confidentiality.

### 12. **Advanced Topics (Optional):**

+ Multivariate analysis.
+ Time-series analysis and its relevance to frequency data.

---
[^1]: Reference reading for lexical diversity of KSAT reading passages [link](https://www.kci.go.kr/kciportal/landing/article.kci?arti_id=ART002898744#none)
[^2]: 'Back to basics: how measures of lexical diversity can help discriminate between CEFR levels'[link](https://core.ac.uk/download/pdf/42153994.pdf)
[^3]: 'MTLD, vocd-D, and HD-D: A validation study of sophisticated approaches to lexical diversity assessment' [link](https://www.researchgate.net/publication/44608173_MTLD_vocd-D_and_HD-D_A_validation_study_of_sophisticated_approaches_to_lexical_diversity_assessment)
