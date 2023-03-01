# Web-Scrapping

## Problem statement
The objective of this project is to extract textual data articles from the given URL and perform text analysis to compute variables like:
  1. POSITIVE SCORE
  2. NEGATIVE SCORE
  3. POLARITY SCORE
  4. SUBJECTIVITY SCORE
  5. AVG SENTENCE LENGTH
  6. PERCENTAGE OF COMPLEX WORDS
  7. FOG INDEX
  8. AVG NUMBER OF WORDS PER SENTENCE
  9. COMPLEX WORD COUNT
  10. WORD COUNT
  11. SYLLABLE PER WORD
  12. PERSONAL PRONOUNS
  13. AVG WORD LENGTH
  
  ### Definition
  
   Topic      |  Definition
------------- | -------------
Positive Score| This score is calculated by assigning the value of +1 for each word if found in the Positive Dictionary and then adding up all the values.
Negative Score| This score is calculated by assigning the value of -1 for each word if found in the Negative Dictionary and then adding up all the values. We multiply the score with -1 so that the score is a positive number.
Polarity Score|  This is the score that determines if a given text is positive or negative in
nature. It is calculated by using the formula:
Polarity Score = (Positive Score – Negative Score)/ ((Positive Score + Negative Score) +
0.000001)
Range is from -1 to +1


Subjectivity Score: This is the score that determines if a given text is objective or subjective.
It is calculated by using the formula:
Subjectivity Score = (Positive Score + Negative Score)/ ((Total Words after cleaning) +
0.000001)
Range is from 0 to +1
