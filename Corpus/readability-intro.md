# 🌱 Readability measures

Readability refers to the ease with which a reader can understand written text. In a scientific context, readability is quantitatively assessed using various metrics that evaluate the text's complexity based on factors such as sentence length, word length, syllable count, and vocabulary difficulty. These metrics estimate the educational level required to comprehend the text, often reported as a grade level or age group.

The purpose of readability assessments is to ensure that written materials match the cognitive and reading skills of their intended audience, thus improving comprehension and accessibility. Readability tests are utilized across diverse fields including education, healthcare, legal, and commercial sectors to tailor content appropriately for specific audiences. This facilitates effective communication, enhances learning outcomes, and ensures that information is accessible to all readers, regardless of their background or reading proficiency.

## Example) The Gunning Fog Index

+ The Gunning Fog formula generates a grade level between 0 and 20. It estimates the education level required to understand the text.
+ A Gunning Fog score of 6 is easily readable for sixth-graders. Text aimed at the public should aim for a grade level of around 8. Text above a 17 has a graduate level.

+ [Calculating GF index online](http://gunning-fog-index.com/)

+ The **Gunning Fog Index** is calculated using the following formula:

$$
\text{Gunning Fog Index} = 0.4 \left( \left(\frac{\text{words}}{\text{sentences}}\right) + 100 \left(\frac{\text{complex words}}{\text{words}}\right) \right)
$$

> Where:  
> - **words** is the total number of words in the text.  
> - **sentences** is the total number of sentences in the text.  
> - **complex words** are words with three or more syllables, excluding proper nouns, familiar jargon, and compound words.

+ Grade levels:

  + Level 0 – Kindergarten – ages 4 – 6
  + Level 1 – Grade 1 – ages 6 – 8
  + Level 2 – Grade 2 – ages 7 – 9
  + Level 3 – Grade 3 – ages 8 – 10
  + Level 4 – Grade 4 – ages 9 – 11
  + Level 5 – Grade 5 – ages 10 – 12
  + Level 6 – Grade 6 – ages 11 – 13
  + Level 7 – Grade 7 – ages 12 – 14
  + Level 8 – Grade 8 – ages 12 – 15
  + Level 9 – Grade 9 – ages 14 – 16
  + Level 10 – Grade 10 – ages 15 – 17
  + Level 11 – Grade 11 – ages 16 – 18
  + Level 12 – Grade 12 – ages 16 – 18
  + Level 13-16 – College 
  + Level 17-20 – Graduate and beyond

# 🔍 Readabiliity Consensus-based upon multiple measures
+ Using {teststat} library

Multiple Readability Formulas: textstat.text_standard applies several readability formulas such as the Flesch Reading Ease, Flesch-Kincaid Grade Level, Gunning Fog Index, SMOG Index, Automated Readability Index (ARI), and others.
Grade Level Estimation: The function then compiles the results from these tests and often returns the result as a US school grade level. It typically picks the median or most middle result to avoid extreme values from any single formula.
General Usage: This function is quite useful when you need a general estimation rather than a specific reading level from a particular formula. It's helpful for ensuring that texts are appropriate for their intended audience in terms of complexity and readability.

### Here is a list of the readability measures commonly included in the results provided by the textstat.text_standard function:

+ Flesch Reading Ease: Evaluates text based on sentence length and word length. Higher scores indicate easier readability.

$$
\text{Flesch Reading Ease} = 206.835 - 1.015 \left(\frac{\text{total words}}{\text{total sentences}}\right) - 84.6 \left(\frac{\text{total syllables}}{\text{total words}}\right)
$$

+ Flesch-Kincaid Grade Level: Provides a U.S. school grade level; the calculation is based on word length and sentence length.

$$
\text{Flesch-Kincaid Grade Level} = 0.39 \left(\frac{\text{total words}}{\text{total sentences}}\right) + 11.8 \left(\frac{\text{total syllables}}{\text{total words}}\right) - 15.59
$$

+ Gunning Fog Index: Estimates the years of formal education a person needs to understand the text on the first reading. It considers word complexity and sentence complexity.

$$
\text{Gunning Fog Index} = 0.4 \left( \left(\frac{\text{total words}}{\text{total sentences}}\right) + 100 \left(\frac{\text{complex words}}{\text{total words}}\right) \right)
$$

+ SMOG Index (Simple Measure of Gobbledygook): Calculates the number of years of education needed to understand a text, focusing on the number of polysyllabic words.

$$
\text{SMOG Index} = 1.043 \sqrt{\text{number of polysyllabic words} \times \frac{30}{\text{total sentences}}} + 3.1291
$$

+ Automated Readability Index (ARI): Uses character counts to predict the grade level required to comprehend the text.

$$
\text{ARI} = 4.71 \left(\frac{\text{total characters}}{\text{total words}}\right) + 0.5 \left(\frac{\text{total words}}{\text{total sentences}}\right) - 21.43
$$

+ Coleman-Liau Index: Relies on character counts instead of syllables per word, providing an estimation of the U.S. grade level needed to understand the text.

$$
\text{Coleman-Liau Index} = 0.0588 \left(\frac{\text{total letters}}{\text{total words}} \times 100\right) - 0.296 \left(\frac{\text{total sentences}}{\text{total words}} \times 100\right) - 15.8
$$

+ Linsear Write Formula: A formula that is simple and was originally designed for U.S. Air Force texts. It provides an estimate based on sentence and word length, focusing particularly on how many words have three or more syllables.

$$
\text{Linsear Write} = \left(\frac{\text{easy words} + (\text{difficult words} \times 3)}{\text{sentences}}\right) / 2
$$

+ Dale-Chall Readability Score: Uses a list of familiar words and calculates a score based on sentence length and the percentage of difficult words not on the familiar words list.

$$
\text{Dale-Chall Score} = 0.1579 \left(\frac{\text{difficult words}}{\text{total words}} \times 100\right) + 0.0496 \left(\frac{\text{total words}}{\text{total sentences}}\right)
$$

> Where difficult words are those not found on a predefined list of commonly understood words.


