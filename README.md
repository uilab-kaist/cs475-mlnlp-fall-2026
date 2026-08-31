# ML for NLP / CS475 / Fall 2026 KAIST

**All contents in this document are tentative.**

## Teaching Staff

<a href="https://uilab.kr/">Alice Oh</a> (Professor), Jieun Han (TA), Yen Shin (TA)

<details>
<summary><strong>When you send emails, please email to all TAs and prof. Oh. [Click me to see our emails.]</strong></summary>

<p><code>alice.oh@kaist.edu, jieun_han@kaist.ac.kr, yeeun@kaist.ac.kr</code></p>

<p><i>And put "CS475" to the title. (e.g., [CS475] Do we have a class on thanksgiving day?)</i></p>

</details>

## Useful Links
- [Slack Channel Invite](https://join.slack.com/t/mlnlp-26-f/shared_invite/zt-488ssz93m-nDI7Lv2DZW3exTQy7qnvNA)
- [Zoom](https://kaist.zoom.us/my/aliceatkaist)
- [Google Drive](https://drive.google.com/drive/folders/187-1yaXVp6-UJxJHU5IiTaM3l7mglLQ5?usp=sharing)

## Course Description

This course will cover advanced and state-of-the-art machine learning for text data. ML methods covered will include graphical models, Bayesian inference, nonparametric models, and deep learning. By the end of the course, students will be able to

- Understand important concepts in NLP
- Read current research papers in NLP
- Implement some of the basic ML models for NLP
- Conduct replication studies based on a recent NLP+ML paper
- Communicate in written and spoken English about NLP+ML research

## Time and Classroom
- E3-1 1101 (some classes may be held virtually)
- Tue/Thurs 10:30 - 11:45 

## Prerequisites  

- You need to have good programming skills in Python for replication/modification of recent NLP research.
- You need to have a basic understanding of ML concepts. You do not need to have taken CS376 or any other undergraduate ML course, but you need to know concepts such as supervised vs unsupervised learning, train vs test data, clustering vs classification, accuracy/precision/recall, overfitting, and basic classification models such as SVM, random forest, etc. You can learn these concepts as we go along, but you may find some lectures and papers difficult to understand if you do not put in extra time to learn these concepts.

## Materials

- Recent NLP papers (especially from ACL, EMNLP, NAACL, COLM)
- Recent ML papers (AAAI, ICML, IJCAI, NeurIPS, etc)
- [Dan Jurafsky & James H. Martin, Speech and Language Processing (3rd ed. draft)](https://web.stanford.edu/~jurafsky/slp3/)

## Schedule (Subject to Change)

All deadlines are 23:59:59 unless specified.

| Week | Date       | Topic                                      | Notes         | Project             |
|------|------------|--------------------------------------------|---------------|---------------------|
|    1 | 2026.09.01 | Introduction to CS475                      |               |                     |
|    1 | 2026.09.03 | Introduction to NLP                        |               |                     |
|    2 | 2026.09.08 | Words and Tokens                           |               |                     |
|    2 | 2026.09.10 | N-gram Language Models                     |               |                     |
|    3 | 2026.09.15 | Logistic Regression and Text Classification |             | Team Signup Due     |
|    3 | 2026.09.17 | Embeddings                                 |               |                     |
|    4 | 2026.09.22 | Neural Networks                            |               |                     |
|    4 | 2026.09.24 | Holiday                                    | No Class      |                     |
|    5 | 2026.09.29 | Transformers and Pretraining (1)           |               |                     |
|    5 | 2026.10.01 | Transformers and Pretraining (2)           |               | Paper Selection     |
|    6 | 2026.10.06 | Project Proposal                           | Zoom (Online) | Proposal Presentation| 
|    6 | 2026.10.08 | Project Proposal                           | Zoom (Online) | Proposal Presentation| 
|    7 | 2026.10.13 | No Class                                   | No Class      |                     |
|    7 | 2026.10.15 | Post-traning                               |               |                     |
|    8 | 2026.10.20 | Midterm                                    | No Class      |                     |
|    8 | 2026.10.22 | Midterm                                    | No Class      |                     |
|    9 | 2026.10.27 | Masked Language Models                     |               |                     |
|    9 | 2026.10.29 | Interpretability                           | Zoom (Online) |                     |
|   10 | 2026.11.03 | Information Retrieval and RAG              |               |                     |
|   10 | 2026.11.05 | Machine Translation                        |               |                     |
|   11 | 2026.11.10 | RNNs and LSTMs                             |               |                     |
|   11 | 2026.11.12 | Project Progress                           |               | Upload Progress Video|
|   12 | 2026.11.17 | Phonetics and Speech Feature Extraction    |               |                     |
|   12 | 2026.11.19 | Automatic Speech Recognition               |               |                     |
|   13 | 2026.11.24 | Guest Lecture / Tutorial                   |               |                     |
|   13 | 2026.11.26 | Undergraduate Admissions                   | No Class      |                     |
|   14 | 2026.12.01 | Wrap-up                                    |               |                     |
|   14 | 2026.12.03 | Wrap-up                                    |               |                     |
|   15 | 2026.12.08 | Final Presentation                         | Zoom (Online) | Final Presentation  |
|   15 | 2026.12.10 | Final Presentation                         | Zoom (Online) | Final Presentation  |
|   16 | 2026.12.15 | Final Exam                                 | No Class      |                     |
|   16 | 2026.12.17 | Final Exam                                 | No Class      |                     |
|   16 | 2026.12.20 | Project Final Report                       |               |                     |



## Homework & Quiz (Subject to Change)
- Homework assignments will primarily consist of exercises from the textbook.
- You may use LLMs when working on homework, but you are responsible for fully understanding all answers and solutions you submit.
- Quiz questions may assess concepts or problems related to previous homework assignments. If your quiz performance indicates that you do not understand material that you correctly submitted in your homework, the teaching staff may re-evaluate and reduce the score of the corresponding homework assignment.

## Attendance and Participation
- Attendance will not be checked separately. However, unannounced in-class quizzes will be given approximately 6 times during the semester. If you are absent on a quiz day, you will not receive credit for that quiz.
Because the quizzes are unannounced, there will generally be no make-up quizzes for absences. Exceptions may be considered only in special circumstances, such as prolonged illness, in which case you should contact the teaching staff.

## Team Projects
- You will form teams of *four*, and as a team, pick one paper from the given paper list and replicate it. You will be required to change at least one thing -- dataset, model, or research question. More details will be given out during the first week of class.
- Please refer to [this link](https://uilab-kaist.github.io/cs475-mlnlp-fall-2026/project) for the details.

## Evaluation
Your grade will be a combination of the following:

- **Homework: 20%**
  - 2 homework assignments (10% each)

- **Quiz: 30%**
  - 6 unannounced written in-class quizzes (5% each)
  - Each quiz covers material from the previous classes and homework
  - 5 written questions per quiz, consisting of short-answer and multiple-choice questions

- **Team Project: 50%**
  - Proposal: 5%
  - Progress Presentation: 10%
  - Final Presentation: 10%
  - Final Report: 10%
  - Teamwork: 5%
    - Note: A team may receive a penalty of up to 25% of the total course grade in cases of serious teamwork issues.
  - Peer Review Participation: 10%
  
## Policy on Large Language Models
Recent progress in large-scale language models (LLM), such as ChatGPT, motivates explicit policies.
- The entire course policy is **LLM-agnostic**: no grader will evaluate your submission differently simply because an LLM was used.
- You are free to use LLMs for homework and team projects as long as you **acknowledge their use**.
- You are ultimately responsible for everything you submit, regardless of whether an LLM or another external tool was used.
- You must **understand and be able to explain any part of your homework or project that was produced or assisted by an LLM**.
- We may ask you questions about your submitted work to verify your understanding. If you are unable to adequately explain or answer questions about work you submitted, the corresponding homework or project score may be **re-evaluated and penalized**.
- You will be asked at the end of the semester to report how you used LLMs in the course to help us improve future course policies.

## Late Policy
- Unless otherwise specified, we will not accept late homework assignments, quizzes, peer evaluations, or project submissions. For exceptional individual circumstances, please contact the teaching staff.
