[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/oqKLEXJJ)
# 🎓 Ethical Admissions Algorithm Simulation

This repository is a classroom exercise exploring **ethics and fairness in algorithmic decision-making** — specifically in college admissions.

You’ll implement and reflect on how feature selection and weighting can impact fairness, transparency, and equity in automated systems.

---

## 🧩 Overview

You are part of the admissions committee for **Anonymous University**, located near Anonymous City.  
Due to a large number of applications, the committee decides to use an algorithm to help **rank and shortlist applicants**.

Your task:
- Decide which factors to include (GPA, test scores, extracurriculars, essays, recommendation letters, legacy status, income, etc.)
- Assign weights to each factor.
- Compare outcomes under two models:
  - **Blind model**: Ignores sensitive factors.
  - **Aware model**: Includes them intentionally to promote fairness (e.g., extra weight for first-gen or low-income applicants).

---

## ⚙️ How to Run

You can run the code on any online Java compiler (e.g. [Replit](https://replit.com/~) or [Programiz Java Compiler](https://www.programiz.com/java-programming/online-compiler))  
or locally via terminal:

```bash
javac Applicant.java Admissions.java Main.java
java Main



NOTES:

     The variables that held the most weight for me in the blind method 
were GPA, test scores, and essay. In the aware method, I gave the 
most weight to low income boost, first gen students, and people 
with disabilities. I removed the weight off of legacy leaving it 
with a weight of 0. I believe that that variable should hold no 
weight in the selection of admitted students. I think the current model 
works fine as I don't think ethnicities, races, or gender should be taken 
into account at a university (unless the point is to serve a certain group 
of people). The model as of now, works impartially against the three 
variables discussed.

     In my model, the people who specifically lost out are the ones who did 
not do great in the blind section of the application. If the student had a 
bad GPA, bad essay, and bad test it was more likely they would be rejected. 
In the aware model, I benefited low income students a lot more as well as 
students with disabilities. I think adding weight to low income and first 
generation students definitely tilts the scale towards a certain side but in 
my opinion, this does not take away opportunities from everybody else. In my 
model, only one person was rejected after the aware model was applied rather 
than the blind one (which definitely counted with much more rejections). 

     I think my blind model is fair academics-wise. I definitely did not 
benefit people with extracurriculars but in terms of basic things required 
to get admitted into a university, I feel like I covered it pretty well. My 
aware model was definitely more biased than I thought as I put personal 
experiences into play when choosing what fields to increment or decrement.

     I definitely built the model in a way that I think I would have wanted 
to be evaluated when being admitted into a university, I feel like I could 
justify why students did not get admitted with my model but, like everything 
else in the ethical world, it might not be received well as everybody has 
different biases and personal models they follow and live by.

     The exercise reveals a deep-rooted truth about algorithms and that is 
that there will always exist a bias when creating models like the one for 
this lab. The human spirit prevails even through technology, all the 
designs, application developments, and algorithm implementations come from 
somebody's mind and the way that certain person or team would have done it. 
There will never be a fully impartial algorithm because there is no fully 
impartial human. Even if we tried to create an algorithm that encapsulated 
the thinking of most of the population, there would still exist somebody 
that is affected negatively. In my opinion, there is no possible way of 
creating a fair software as of now and there is no way we can program 
technology to make fair decisions for us without circling back to a world 
that will still use human decision making ultimately.
