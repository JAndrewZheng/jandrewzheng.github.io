---
layout: homepage
---

## About Me

I am a Masters at University of Maryland, College Park, majoring in Computer Science. I am interested in the intersection of quantum computing and machine learning, hoping to develop quantum algorithms to make current algorithms in machine learning faster through quantum. Aside from school, I really enjoying teaching and playing chess, basketball and ice hockey.

## Research Interests

- **Quantum Computing:** Simulation, Algorithms
- **LLMs:** Theory, Database vectorization, Signal Denoising, Computer Vision

## Projects 

**Quantum Simulation Project (Ongoing)**

For matrices, the <a href="ttps://en.wikipedia.org/wiki/Lie_product_formula">lie-product formula</a> isn't separable via product formulas for numbers. This has severe implications on the simulation of time-independent <a href="https://en.wikipedia.org/wiki/Hamiltonian_(quantum_mechanics)">hamiltonians</a>, where the solution to the <a href="ttps://en.wikipedia.org/wiki/Lie_product_formula">Schrödinger equation</a> produces exponentials, and more specifically, matrix exponentials. In addition, the full hamiltonian of system is often separable into many individual terms. Lie-product formula can give an arbitarily good estimation of the product formula exponentiation for small enough time intervals, however, these hamiltonian matrices can get exponentially large as the system size gets larger, thus, methods to achieve good estimates in relatively low computation time. One such method is presented in <a href="https://journals.aps.org/prx/abstract/10.1103/PhysRevX.11.011020">A Theory of Trotter Error</a> which uses <a href="https://en.wikipedia.org/wiki/Commutator">commutator</a> scaling between individual terms of the hamiltonian to give a good upperbound on product formula estimation where the upperbound is computable using machines, despite these expressions still being computationally expensive. Taking advantage of system properties such as <a href="https://en.wikipedia.org/wiki/Translational_symmetry">translation invariance</a> and <a href="https://en.wikipedia.org/wiki/Principle_of_locality">locality</a>, clever algorithms can be implemented to compute these commutators efficiently. 

This project is still ongoing, but close to wrapping up. Code is granted upon request. 

**ClearCOMM**

Noise cancellation has always been an area without good solutions until recent advancements in deep learning models. Traditional noise cancellation takes advantage of the fourier basis, where frequencies that cannot represent human speech are removed. However, such techniques are not good for removing background noise produced by other people. Thus, deep learning models are more appropriate to solve such problems by training the model to learn what is background noise and what isn't background noise given a bunch of data. These methods allow us to avoid the usage of the fourier basis which is not applicable in general for noise cancellation. This <a href="https://github.com/Brandonio-c/ClearComm-NN">project</a> dives deep into what model we deemed most appropriate for this task along with dataset choices for the best, practical results. 

**NLP Information Storage and Retrieval**

Information retrieval from a database is being used daily by search engines made by Google and Bing. The most obvious way to find the most relevant document in a database is to turn all documents into a vector, turn the query into a vector, and find which document would have the largest dot product with query. How do we do this vectorization? This <a href="https://github.com/rifaaQ/cmsc674">project</a> seeks to compare differen benchmarks of methods that use different methods to perform this query-document vectorization. 

**Fantasy Basketball Project**

Data science techniques are always useful for analyzing any type of data, including NBA data. Zayn and I created a <a href="https://andrewzayn.github.io/">tutorial</a> which teaches how to calculate Fantasy Points from NBA player stats from the 2021-2022 season and conduct data analysis on those calculated fantasy point values. 

**(NASA Goddard Internship) Binning Techniques for Solar Wind and Geomagnetic Data**

I spent two-years of my high school working on a research project seeking to categorize the intensity of solar wind data continuously gathered every since 1990. Throughout my research project, I created <a href="https://drive.google.com/drive/u/0/folders/1kQjVQ5YEQRJgyfJcXdeBf3LZXl0UATRK">3 posters</a> representing my work throughout this two-year research project. In addition, I presented a poster during the AGU conference held on December 12th, 2018 in Washington, D.C. titled
<a href="https://agu.confex.com/agu/fm18/meetingapp.cgi/Paper/396419">"SM31D-3525 Effects of Data Binning Techniques on Results of Analyzing Solar Wind and Geomagnetic Indices Data”</a>

## Experiences 

**REU Intern at UMD**

I had the chance to continue the quantum simulation research I started in the Spring of 2024 during the summer of 2024 as part of UMD's REU CARR program. This program allowed me to collaborate with other REU students working on various research projects, and I had the opportunity to present my own work as well. Over the summer, I focused on extending my simulation of k-local Hamiltonians to include fermionic operators, building on the previous work with Pauli operators. I found this experience particularly rewarding because it gave me the chance to work on a project full-time, free from the usual pressures of coursework. It also gave me a clearer insight into what life as a graduate student is really like, and helped me reassure myself that a PhD is something I really wanted to do after I obtained my masters degree. 

**ITS Intern at AARP**

At AARP, I worked on implemented chat bots in industry to be deployed for automation. During my internship, I implemented a couple chat bots to be used for customer help, including a model finetuned to AARP data starting from a pre-existing checkpoint. This experience gave me a glimpse into how experience in research can lead to advancement in industry. 

**Teaching Assistant (Discrete Mathematics)**

Expanding on my past teaching experience, being a TA for an actual university class taught me how to teach class in a fast but understandable manner to students. As a TA, I led a discussion section, graded student work, and held office hours. Not only did I give personalized help in a 1-1 manner to students in office hours, but I also had the chance to lead my own discussion section. I was grateful that I was able to lead my own discussion section because it gave me more freedom to teach in a matter that would help the students understand the material in a conceptual manner and help answer the question "Why?" to course material instead of just looking at the "How?". In addition, I also had the opportunity to grade work that reflected the things that I taught in a setting where my teaching mattered more. This grading gave me feedback to areas in the coursework where students had more confusion in. These areas of confusion allowed me to figure out what to emphasize during my discussion sections and office hours.

I really enjoyed my TA experience and I wish to do more in the form to teaching later on. Teaching college courses suits me as well since in college, courses get to a point where they are actually interesting and the importance of actually understanding the "Why?" becomes more important instead of just learning the "How?". I would definitely be interested in teaching more college-level courses in the area of computer science or mathematics. 

**Kumon Math and Reading Center of Clarksville**

At this job, I taught a lot of students of differing ages, from toddlers to students in high school. Predominantly, I taught high-level math, which included topics from Algebra II, Precalculus, Calculus I and Calculus II. I really enjoyed this job because it allowed me to interact with the same students and watch each student grow. 

**(Internship) NASA Goddard Space Flight Center**

At this internship, I worked with a large dataset containing solar wind and magnetosphere data. Throughout this internship, I learned a lot about the physics behind the relationship between the Earth's Magnetosphere and solar wind and how to conduct data analysis on large data. However, I felt like I gained the most on the thought process behind doing research. In the end, I really enjoyed this experience because I was given autonomy to do research on areas that related to the project and accept or reject ideas based on the unique circumstances of my project. 

## Courses Taken at University

- **Completed:** Complex Analysis (MATH463), Advanced Linear Algebra (MATH405), Abstract Algebra (MATH403), Number Theory (MATH406), Differential Equations (MATH246), Calculus III (MATH241), Introduction to Linear Algebra (MATH240), Special Topics in Computer Science; Quantum Boot Camp (CMSC488A),  Advanced Data Structures (CMSC420), Introduction to Quantum Computing (CMSC457), Algorithms (CMSC351), Programming Languages (CMSC330), Introduction to Data Science (CMSC320), Introduction to Computer Systems (CMSC216), Object-Oriented Programming II (CMSC132), Applied Probability and Statistics I (STAT400)
- **In Progress:** Advanced Calculus (MATH410), Partial Differential Equations (MATH462), Introduction to Machine Learning (CMSC422), Computer Vision (CMSC426), Capstone in Machine Learning (CMSC673)

## Other Experiences

**Chess:** Ever since I was around 5.5 years old, I've been playing chess competitively. Over time, I became really good at board game, winning state championships and playing at invitational events. Here are some of my achievements: 

- Scholastic Maryland State Champion for years 2014 – 2017, 2020
- Maryland Sweet 16 Champion in the 5th Grade, achieving full scholarship to University of Maryland, Baltimore County
- Achieved National Master Title at age 12

My Chess.com Account: <a href="https://www.chess.com/member/bravehorse">bravehorse</a>

**Ice Hockey:** I started playing ice hockey when I was around 7 years old. In my ice hockey career, I played in both high school leagues and club ice hockey leagues playing with other future D1 players. Here are some of my achievements in ice hockey: 

- Howard County All-Star 2016-2020
- 2x Maryland Student Hockey League Second Team All-State
- Last Ice Hockey Team: Washington Little Caps AAA U18

**Basketball:** I'm a bit too short to play basketball well competitively but it has always been a fun sport for me to play. Whenever I have free time, I usually spend it playing pickup basketball. Recently, basketball has become one of my favorite hobbies because it's a way to connect with friends and engage in an activity that is beneficial for everybody.
