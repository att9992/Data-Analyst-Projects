# PISA Project
**Author:** Tran Anh Tong

## Dataset

Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those countries, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy. The survey was sponsored by Organisation for Economic Co-operation and Development (OECD).

I also analyze the data against Freedom House's [_Freedom in the World_ report](https://en.wikipedia.org/wiki/Freedom_in_the_World#cite_note-FITW-2012-11). I obtained data for all years from [here](https://freedomhouse.org/content/freedom-world-data-and-resources) and then extracted the data for 2012, the same year as the PISA study.

**Important Note:** The full dataset (pisa2012.csv) is not included in this repo because it is more than 2.7GB.


## Summary of Findings

I decided to explore three main questions:

* **Does the age when a child begins learning the language using in the test impact their performance?** The students were all 15 years old at the time of the study. The tests were given in a number of languages that reflected the primary language in each region. For many of the students, the test language was not their native language. I was curious if less experience with the test language had any affect on performance, particularly in the reading section. I determined that the less experience a student had with the test language, the lower they scored in the reading section.

* **Do children in freer countries perform differently than those in less free countries?** I introduced the Freedom House ratings to examine test performance against societal freedom, particulary civil liberties. Although China is considered one of the least free countries in the study, it was the top-performing country in overall academic performance. Despite this, students in less free countries performed worse than students in freer countries. Excluding China increased the effect even more. 

* **Does economic, social, and cultural status – advantage vs. disadvantage – relate to academic performance?** PISA introduced a sophisticated index called ESCS (economic, social, and cultural status) that compared a student's opportunity to those of other students. It combined economic, social, and cultural opportunity into one value. I further divided the students into "advantaged" and "disadvantaged" using this index. I considered a student to be advantaged if he or she was +1 standard deviation or higher on the ESCS index and disadvantaged if they were -1 standard deviation. I discovered that opportunity predicts academic success: advantaged students scored higher and disadvantaged students scored lower all other factors being equal.

## Key Insights for Presentation

For my presentation, I focus on the question of opportunity and academic performance. I look at which countries had the most disadvantaged students and how they compared on the overall ESCS index. I then demonstrate that disadvantaged students performed worse and advantaged students performed better compared to the overall mean.
