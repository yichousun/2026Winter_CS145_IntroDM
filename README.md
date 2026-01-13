# CS 145: Introduction to data mining
### Instructor: Yizhou Sun
- Lecture Time: Mondays & Wednesdays, 2:00 – 4:00 PM
- Classroom: BH 2760
- Office hours: Mondays 4-5:15pm; Tuesdays 1:30-2:00 @Boelter Hall 3531F


### TAs:
-	Jade Xu
-	Kaiqiao Han

## Course Description
This course introduces basic concepts, algorithms, and techniques of data mining on different types of datasets, including (1) tabular data, (2) set data, (3) sequence data, (4) time series data, (5) text data, and (6) graph data. The class project involves hands-on practice of mining useful knowledge from large data sets. The course is an undergraduate-level computer science course. Also, the course may attract students from other disciplines who need to understand, develop, and use data mining techniques to analyze large amounts of data.

## Prerequisites
- You are expected to have background knowledge in data structures, algorithms, basic linear algebra, and basic statistics.
-	You will also need to be familiar with at least one programming language, and have programming experiences.

## Learning Objectives
- Know what data mining is and learn the basic algorithms
- Develop skills to apply data mining algorithms to solve real-world applications
- Gain initial experience in conducting research on data mining

## Grading
-	Homework: 40%
-	Midterm exam: 25%
-	Final exam: 30%
-	Participation: 5%

*All the deadlines are 11:59PM (midnight) of the due dates.

*Late submission policy: you will get original score * <a href="https://www.codecogs.com/eqnedit.php?latex=\mathbf{1}(t<=24)e^{-(ln(2)/12)*t}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathbf{1}(t<=24)e^{-(ln(2)/12)*t}" title="\mathbf{1}(t<=24)e^{-(ln(2)/12)*t}" /></a>, if you are t hours late.

*No copying or sharing of homework!

- You can discuss general challenges and ideas with others.
- Suspicious cases will be reported to The Office of the Dean of Students.


## Q & A
-	We will be using [Piazza](piazza.com/ucla/winter2026/cs145) for class discussion. The system is highly catered to getting you help fast and efficiently from classmates, the TAs, and myself. Rather than emailing questions to the teaching staff, I encourage you to post your questions on Piazza.
-	Sign up Piazza here: [piazza.com/ucla/winter2026/cs145](piazza.com/ucla/winter2026/cs145)
-	Tips: Answering other students' questions will increase your participation score.

## Academic Integrity Policy
"With its status as a world-class research institution, it is critical that the University uphold the highest standards of integrity both inside and outside the classroom. As a student and member of the UCLA community, you are expected to demonstrate integrity in all of your academic endeavors. Accordingly, when accusations of academic dishonesty occur, The Office of the Dean of Students is charged with investigating and adjudicating suspected violations. Academic dishonesty, includes, but is not limited to, cheating, fabrication, plagiarism, multiple submissions or facilitating academic misconduct."
For more information, please refer to the <a href="https://www.deanofstudents.ucla.edu/portals/16/documents/studentguide.pdf">guidance</a>.

## Tentative Schedule
*Book refers to: Jiawei Han, Micheline Kamber, and Jian Pei, Data Mining: Concepts and Techniques, 3rd edition.

| Week    | Date   | Topic                                                          | Further Reading                                                                 | Homework |
|---------|--------|----------------------------------------------------------------|---------------------------------------------------------------------------------|----------|
| Week 1  | 5-Jan  | Introduction [[slides]](https://drive.google.com/file/d/19Jxn9aWNsHwjIqtND3UeVSSVtMyqsrxQ/view?usp=drive_link) and Know Your Data [[slides]](https://drive.google.com/file/d/1qkmkaXHYD5J3RkDRxWYpJTxQ8MPKMkK2/view?usp=drive_link)                               | <ul><li>Book Chapter 1, 2, 3</li><li>[Review of probability from a course by David Blei](http://www.cs.princeton.edu/courses/archive/spring07/cos424/scribe_notes/0208.pdf) from Princeton U.</li><li>[Machine Learning Math Essentials](http://courses.washington.edu/css490/2012.Winter/lecture_slides/02_math_essentials.pdf) by Jeff Howbert from Washington U.</li><li>[http://cs229.stanford.edu/section/cs229-prob.pdf](http://cs229.stanford.edu/section/cs229-prob.pdf)</li><li>[Optimization](http://web.cs.ucla.edu/~yzsun/classes/2018Fall_CS145/Slides/optimization.pdf)</li></ul>                                                                 |          |
| Week 1  | 7-Jan  | Linear Regression [[slides]](https://drive.google.com/file/d/1ryTdZXhYQqhmeD3VkLWKqcBbI7qFm31U/view?usp=drive_link)                                              | <ul><li>https://cs229.stanford.edu/notes2021fall/cs229-notes1.pdf </li><ul>                     |          |
| Week 2  | 12-Jan | Logistic Regression [[slides]](https://drive.google.com/file/d/14hzRzfGBeR49KyqGeLewz_fXY01k_8rI/view?usp=sharing); KNN [[slides]](https://drive.google.com/file/d/1Cr0OoCeWiaKvzSlWGTnxMTbDTJfGV2rb/view?usp=sharing); Practical Issues of Classification   | <ul><li>https://cs229.stanford.edu/notes2021fall/cs229-notes1.pdf  </li><li>Book Chapter 8.5  </li></ul>                     | HW1 Out  |
| Week 2  | 14-Jan | Tree-based Models                                              | Decision Tree: Book Chapter 8.1, 8.2                                            |          |
|         |        |                                                                | Regression Tree: http://www.stat.cmu.edu/~cshalizi/350-2006/lecture-10.pdf      |          |
|         |        |                                                                | Random Forest: https://www.stat.berkeley.edu/~breiman/RandomForests/cc_home.htm |          |
| Week 3  | 19-Jan | Martin Luther King, Jr. holiday (No Class)                     |                                                                                 |          |
| Week 3  | 21-Jan | Neural Networks (1)                                            | http://neuralnetworksanddeeplearning.com/                                       | HW1 Due  |
|         |        |                                                                | http://www.deeplearningbook.org/                                                | HW2 Out  |
| Week 4  | 26-Jan | Neural Networks (2)                                            |                                                                                 |          |
| Week 4  | 28-Jan | Clustering and K-Means; Practical Issues of Clustering         | Book Chapter 10.1-10.4                                                          | HW2 Due  |
|         |        |                                                                |                                                                                 | HW3 Out  |
| Week 5  | 2-Feb  | Mixture Models                                                 | http://www.stat.cmu.edu/~cshalizi/350/lectures/29/lecture-29.pdf                |          |
|         |        |                                                                | http://www.cs.ubc.ca/~murphyk/Teaching/CS340-Fall06/reading/mixtureModels.pdf   |          |
| Week 5  | 4-Feb  | Set Data: Frequent Pattern Mining and Association Rules        | Book Chapter 6                                                                  | HW3 Due  |
| Week 6  | 9-Feb  | In-class Midterm                                               |                                                                                 |          |
| Week 6  | 11-Feb | Image Data: Convolutional Neural Network                       |                                                                                 | HW4 out  |
| Week 7  | 16-Feb | Presidents’ Day holiday (No Class)                             |                                                                                 |          |
| Week 7  | 18-Feb | Sequence Data: Sequential Pattern Mining and Similarity Search |                                                                                 | HW4 Due  |
|         |        |                                                                |                                                                                 | HW5 out  |
| Week 8  | 23-Feb | Time Series Data: AR model and Recurrent Neural Network        |                                                                                 |          |
| Week 8  | 25-Feb | Text Data: Naive Bayes                                         | http://www.ccs.neu.edu/home/yzsun/classes/2014Fall_CS6220/Slides/NB.pdf         | HW5 Due  |
| Week 9  | 2-Mar  | Text Data: Topic Models                                        |                                                                                 |          |
| Week 9  | 4-Mar  | Text Data: Transformers and LLMs                               |                                                                                 | HW6  Out |
| Week 10 | 9-Mar  | Graph Data: Random Walk, Classification and Clustering         |                                                                                 |          |
| Week 10 | 11-Mar | Graph Data: Graph Neural Networks                              |                                                                                 | HW6 due  |
| Week 11 | 17-Mar | Final Exam (11:30am-2:30pm)                                    |                                                                                 |          |

