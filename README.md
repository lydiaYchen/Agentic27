
:warning: **We are making significant changes to the evaluation of the course, compared to the previous year. The content will only be finalized by the end of the first week of the semester.**

<!-- vscode-markdown-toc -->
* 1. [Important links](#1-important-links)
* 2. [Course description](#2-course-description)
* 3. [Course team](#3-course-team)
* 4. [Learning objectives](#4--learning-objectives)
* 5. [Workload and expectation](#5-️--workload-and-expectations) 
* 6. [:dart: Grading policy](#6-dart-grading-policy)
    * 6.1. [Quizzes]()
    * 6.2. [Group projects]()
* 7. [Detailed schedule](#7--detailed-schedule)
* 8. [Relevant references](#8-relevant-references)

    
<!-- vscode-markdown-toc-config
    numbering=true
    autoSave=true
    /vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc --><!-- vscode-markdown-toc -->


# [Agentic27] Agentic Systems <!-- omit in toc -->

This repository contains the materials of the **MSc Agentic Systems** course running in fall 2027 at UNINE. This is part of BeNeFri Master's program.




##  1. <a name='Importantlinks'></a>Important links

- [Project description](project.md)
- [Labs and assignments](labs/README.md)


##  2. <a name='Coursedescription'></a>Course description

Today's artificial intelligence landscape is rapidly shifting from static generative models to autonomous, multi-step agentic systems. Agentic AI systems are capable of reasoning, planning, executing tools, and adapting dynamically to solve complex real-world tasks. However, building and deploying agentic systems that meet high performance, reliability, and safety standards while efficiently managing computational constraints remains a significant technical challenge. To build production-grade agentic applications, it is essential to master both full-stack agent orchestration and the underlying systems engineering—from low-level key-value (KV) cache management to distributed optimization.

A real-world implementation of this paradigm is Klarna’s OpenAI-powered AI Assistant. Moving far beyond traditional rule-based chatbots, this agentic system executes dynamic multi-step tasks by integrating directly with live backend payment systems, verifying account histories, and autonomously resolving refunds or payment disputes. In production, the assistant managed 2.3 million customer conversations in its first month alone—performing the workload equivalent of 700 full-time agents while slashing average resolution times from 11 minutes down to under two minutes.

The goal of this course is to provide students with the core foundations, systems-level optimizations, and practical skills required to design, improve, and secure agentic AI systems. Through hands-on architecture design and experimental evaluation, students will learn how to build effective agent harnesses, engineer context dynamically, implement self-correction and self-improving loops, scale training via distributed SGD, and protect systems using modern guardrails, activation steering, and privacy-preserving techniques.

Course topics include

* **Part I: Building Agentic Systems**
  * Introduction to Agentic Systems
  * Agentic Benchmark: tool use and function calling
  * Harness of Agentic Systems
  * System and KV Cache

* **Part II: Improving Agentic Systems**
  * Context Engineering
  * Self-Correction
  * Self-Improving
  * Distributed SGD

* **Part III: Robustness of Agentic Systems**
  * Self-Evolving
  * Attacks/Defenses for LLMs
  * Safety: Guardrails & Activation Steering
  * Privacy for LLMs



##  3.👩‍🏫👨‍🏫 <a name='Courseteam'></a>Course team

This course will be primarily taught by [Prof. Lydia Y Chen](https://lydiaychen.github.io/)  The course team is composed of a number of PhDs  who support the course through guest lectures and project supervision and a TA who focuses on the grading of homework. 


-  [Giulio ](mailto:) (Unine PhD student) 
-  [Abel](mailto:) (Unine PhD student)


Lydia is the responsible instructor of this course and can be reached at **lydiaychen@ieee.org**.



##  4. 🏆 <a name='Learningobjectives'></a>Learning objectives

LO1. Understand the core architectures, harnesses, and memory systems of agentic AI, including tool use and KV caching.

LO2. Improve agent performance through context engineering, self-correction, self-improving loops, and distributed SGD.

LO3. Design resilient, self-evolving agents hardened against adversarial attacks, prompt injections, and privacy risks.

LO4. Implement runtime safety mechanisms and operational controls using guardrails, activation steering, and trajectory benchmarks.


## 5. ⏱️ <a name='Expectation'></a> Workload and Expectations

This course covers many exciting and rapidly evolving topics in AI. As these topics build on a range of existing concepts in machine learning and deep learning, the course can be demanding. Students should expect to spend an average of **4–6 hours per week** on this course, including lectures, labs, and independent study. Students without a solid background in machine learning can still take this course, but should be prepared to put in **significant additional effort to catch up with the required background**. In our experience, students who lack the necessary background may find it challenging to keep up with the course and its hands-on exercises.

At the same time, the effort can be highly rewarding. A well-executed project can develop into a successful conference publication, provide a strong foundation for a master's thesis, or serve as a strong basis for an internship. We have close collaborations with industry, and successful projects may provide opportunities to connect with our industry partners. We have several examples of students who have taken their course projects further into publications, theses, and internships, and we are happy to share these examples with the class.


## 6. <a name='dart:Gradingpolicy'></a>:dart: Grading policy

This course has no final exam; instead, the grade is largely determined through continuous evaluation. You need to **receive more than 55% on each quiz** to be eligible for the final project.

1. **Labs (0%):** Each lab provides hands-on exercises that connect the concepts covered in the course with practical coding implementations. The first part of each lab is dedicated to students working on the exercises, while the second part is led by the TA, who will address students' questions and discuss common challenges. We strongly encourage students to attend the labs and work through the exercises together, as this will help them learn the course materials more effectively and prepare for the project. **Additional content and concepts covered in the labs will also be included in the quizzes.** We expect students to spend an average 4-6 hours per week for this course. 
   
2. **Quizzes (30%):** There are 2 quizzes in weeks 4, 9, and 12. Each quiz accounts for 12% of the grade and covers 3–5 weeks of material, depending on the subject. The exact format of each quiz will be announced during the corresponding lab. The key purpose of the quizzes is to ensure that students have a sufficient understanding of **the materials covered in the course and labs.**

3. **Group project (70%):** The group project consists of a project report and a presentation. Students will develop a GAI application and optimize its performance. There will be an initial proposal in week 6, followed by an in-class interim discussion with each team in week 10. The final report will be due in week 14, with a 20-minute presentation in week 14 as well. The grading criteria of the project is described below. 




**All assessment items (project reports) have to be submitted via ILIAS.**




###  6.1. <a name='Groupprojects'></a>Group projects
<!-- 7 predefined project topics: evaluating the systems of 
-->


- Group size: 2-3 students
- Schedule: 
  - Initial proposal: week 6
  - Interim meeting: week 10
  - Report due: week 14
  -  Presentation/interview: week 14



At the end of each project phase we will conduct a short interview (20 minutes per group) about the group project and its connection to the course content. Based on the project report and the interview, each member of the group receives a grade. 





##  7. 📅 <a name='Detailedschedule'></a>Detailed schedule

| **Week** | **Lecture Topic** | **Lab Topic** |
| :--- | :--- | :--- |
| Week 1 (Feb 23) | 1. Introduction to Agentic Systems | No-Lab |
| Week 2 (Mar 2) | 2. Agentic Benchmark: Tool Use and Function Calling | Tool Use & Function Calling Benchmarking |
| Week 3 (Mar 9) | 3. Harness of Agentic Systems | Agentic Harness Engineering |
| Week 4 (Mar 16) | 4. System and KV Cache | KV Cche |
| Week 5 (Mar 23) | 5. Context Engineering | Context Engineering |
| Week 6 (Mar 30) | Easter Holiday - No class | Easter Holiday - No Lab |
| Week 7 (Apr 6) | 6. Self-Correction | Self-Correction Loops |
| Week 8 (Apr 13) | 7. Distributed SGD | **Quiz 1** |
| Week 9 (Apr 20) | 8. Self-improve  | Self-Improving |
| Week 10 (Apr 27) | 9. Self-Evolving | Self-Evolving Architectures | Project Midterm |
| Week 11 (May 4) | 10. Attacks/Defenses for LLMs | Adversarial Attacks & Defenses |
| Week 12 (May 11) | 11. Safety: Guardrails & Activation Steering | Guardrails & Activation Steering |
| Week 13 (May 18) | 12. Privacy for LLMs | **Quiz 2** |
| Week 14 (May 25) |  Project Presentation |  |

## 8. <a name='Relevantreferences'></a>Relevant references

### Top-Tier University Online Course Materials

* **UC Berkeley CS294/194-196 (Agentic AI):** [UC Berkeley RDI Agentic AI Course Portal](https://rdi.berkeley.edu/agentic-ai/f25)
* **Stanford University CS224N (NLP with Deep Learning & Agents):** [Stanford CS224N Course Website](https://www.stanford.edu/class/cs224n/)
* **MIT AI Studio (AI Agents and Agentic Web):** [MIT AI Studio Agentic Web Course](https://aiforimpact.github.io/fall25.html)
* **National Taiwan University, Hung-yi Lee (Machine Learning 2026):** [AI Agents and Harness Engineering](https://speech.ee.ntu.edu.tw/~hylee/ml/2026-spring.php)






