---
title: "Advanced Topics in Cloud Networking and Computing"
collection: teaching
type: "Graduate Seminar"
permalink: /teaching/2023-cloud-network
venue: "University of Maryland, CS"
date: 2023-08-29
location: "College Park, MD"
---

The course aims to explore latest advances in cloud networking and computing in light of emerging workloads (e.g., machine learning and large-scale analytics), including communication platforms, compute parallelism, and datacenter networking. The class will discuss the latest developments in the entire networking stack, the interactions between networks and high-level applications, and their connections with other system components such as compute and storage. The course combines group readings and presentations of influential publications in the field, lectures by the instructor, talks by invited speakers, and a project etc.

Instructors
------
* Instructor: Prof. Alan Zaoxing Liu
    * Class Time: Tue/Thu 2:00-3:15PM, IRB 1207
    * Office Hours: IRB 5138, Thu 4-5 or by appointment


Annoucements
------
* The classroom teaching are cancelled in the first two weeks.


Prerequisites
------
All levels are welcome. Recommended experiences with computer networking and software systems, including one or more of CMSC330, CMSC412, CMSC414, CMSC417, etc., or permission of the instructor. The assignments and projects assume students have familiarity with programming (e.g., Python and C/C++).



Textbook
------
There are no mandatory textbooks for this course, but every class will have corresponding readings from research papers. A reading list with links to the papers will be provided.

Course Overview
------
1. **Paper Reviews:** Each student reviews 1 paper/class from top conferences or journals. Submit reviews before the class in four sections, including summary, paper strengths paper weaknesses, and  detailed comments.

2. **Paper Presentations:** Each student will select papers from the paper reading list (the list will be provided, selections are first-come first-serve) and present that paper during a lecture. The presentation will be followed by a technical discussion.

3. **Lectures:** In each topic, the instructor will give one or two introductory lectures, followed by paper presentations by class participants.

4. **Programming Assignments:** There will be (tentatively) two programming assignments during the class. These assignments assume basic computer systems knowledge and some familiarity with network programming.

5. **Project:** This class has a final project:  
    * Topic: Reproduce a paper discussed in class, or novel research with a system-building component.  
    * Can work alone, or in groups of two students. Must involve writing some code or conducting some measurement studies.  
    * Can overlap with other research projects, with permission.


Academic Conduct Statement
------
 Academic Conduct Statement including expectations for academic honesty, reference to consequences for cheating or plagiarism, course-specific guidelines for, e.g., extent of allowable collaboration on assignments, and URL for [Academic Conduct Code](https://academiccatalog.umd.edu/undergraduate/registration-academic-requirements-regulations/academic-integrity-student-conduct-codes/).

Grading
------
- Class participation: 10% 
- Paper reviews: 20% 
- Paper presentation: 10%
- Programming/measurement assignments: 20% 
- Project: 40%

Late Policy: Programming/measurement assignments receive 10% off grades for each 24 hours late, rounded up.


Tentative Course Schedule
------

| Date    | Topics  | Readings |
| :------: | :------: | :------  |
| Week 1  | Administrative delay | *No Class <br/> *(Optional) [How to Read a Paper](/files/course/CCR07_HowToRead.pdf) |
| Week 2  | Administrative delay | *No Class <br/> *(Optional) [MLSys: The New Frontier of Machine Learning Systems](https://arxiv.org/pdf/1904.03257.pdf)|
| Week 3  | Course Overview ([slides](/files/slides/818Q/1-Introduction.pdf)) | *[A Datacenter Infrastructure Perspective for ML](/files/course/HPCA18_FacebookDCInfra.pdf), (HPCA'18) | 
| Week 4  | New Architecture | *[Empowering Azure Storage with RDMA](https://www.usenix.org/system/files/nsdi23-bai.pdf), (NSDI'23) <br/> *[Optimized Network Architectures for Large Language Model Training with Billions of Parameters](https://arxiv.org/pdf/2307.12169) |
| Week 5  | Data Parallelism | *[PyTorch FSDP: Experiences on Scaling Fully Sharded Data Parallel](https://arxiv.org/pdf/2304.11277), (VLDB'23) <br/> *[A Berkeley View of Systems Challenges for AI](https://arxiv.org/pdf/1712.05855) |
| Week 6  | Model Parallelism | *[PipeDream: Generalized Pipeline Parallelism for DNN Training](https://arxiv.org/pdf/1806.03377), (SOSP'19) <br/> *[GPipe: Efficient Training of Giant Neural Networks using Pipeline Parallelism](https://arxiv.org/pdf/1811.06965), (NeurIPS'19) |
| Week 7  | Tensor and Automated Parallelism | *[Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism](https://arxiv.org/pdf/1909.08053) <br/> *[Alpa: Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning](https://arxiv.org/pdf/2201.12023), (OSDI'22) |
| Week 8  | Communicaton Library | *[A Unified Architecture for Accelerating Distributed DNN Training in Heterogeneous GPU/CPU Clusters](https://www.usenix.org/system/files/osdi20-jiang.pdf), (OSDI'20) <br/> *[NCCL Communication Primitives](https://docs.nvidia.com/deeplearning/nccl/user-guide/docs/overview.html) |
| Week 9  | Congestion Control | *[Congestion Control in Machine Learning Clusters](https://conferences.sigcomm.org/hotnets/2022/papers/hotnets22_rajasekaran.pdf), (HotNets'22) <br/> *[Efficient Flow Scheduling in Distributed Deep Learning Training with Echelon Formation](https://conferences.sigcomm.org/hotnets/2022/papers/hotnets22_pan.pdf), (HotNets'22) |
| Week 10  | ML Workflow: Data| *[Understanding Data Storage and Ingestion for Large-scale Deep Recommendation Model Training](https://arxiv.org/pdf/2108.09373), (ISCA'22) <br/> *[Check-N-Run: a Checkpointing System for Training Deep Learning Recommendation Models](https://www.usenix.org/system/files/nsdi22-paper-eisenman.pdf), (NSDI'22) |
| Week 11  | Preproessing | *[Where Is My Training Bottleneck? Hidden Trade-Offs in Deep Learning Preprocessing Pipelines](https://arxiv.org/pdf/2202.08679), (SIGMOD'22) <br/> *[FastFlow: Accelerating Deep Learning Model Training with Smart Offloading of Input Data Pipeline](/files/course/VLDB23_FastFlow.pdf), (VLDB'23) |
| Week 12  | Job Scheduling and Energy | *[Where Is My Training Bottleneck? Hidden Trade-Offs in Deep Learning Preprocessing Pipelines](https://arxiv.org/pdf/2202.08679), (SIGMOD'22) <br/> *[Looking Beyond GPUs for DNN Scheduling on Multi-Tenant Clusters](https://www.usenix.org/system/files/osdi22-mohan.pdf), (OSDI'22) |
| Week 13  | Model Serving | *[Cocktail: A Multidimensional Optimization  for Model Serving in Cloud](https://www.usenix.org/system/files/nsdi22-paper-gunasekaran.pdf), (NSDI'22) <br/> *Thanksgiving Break |
| Week 14  | New Hardware | *[TPUv4](https://arxiv.org/pdf/2304.01433) <br/> *[Jupiter Evolving: Transforming Google's Datacenter Network via Optical Circuit Switches and Software-Defined Networking](https://research.google/pubs/pub51587.pdf), (SIGCOMM'22) <br/> *[FAERY: An FPGA-accelerated Embedding-based Retrieval System](https://www.usenix.org/system/files/osdi22-zeng.pdf), (OSDI'22) |
| Week 15  | Final Presentations |


Paper Reviews
------
The goal of the reviews is to get you comfortable of reading research papers in the software systems and networking space.
* Students are expected to write reviews for the papers in each class. We will give scores based on the top 90% of the reviews. This means it is ok if you miss 10% of the reviews throughout the class.
* Your reviews are due at noon one day before (Monday noon for Tuesday classes; Wednesday noon for Thursday classes). So the presenter of the paper can have time collect all your questions and we can discuss in class. For the lectures we have guest speakers, we will collect the questions and please raise your question in class.


Project Proposal and Project Pitch Presentation
------
The project proposal is not graded but it serves as the good basis for your individual meeting with the instructor and for your pitch presentation. Each student should give a 10-minute talk on your project ideas. The talk should include

* What problem are you solving?
* Why it's an important problem?
* What are the potential challenges you may face in solving the problem?
* What are the first steps (your plan for the next month)?

Midterm Project Report
------
* Describe the problem you plan to solve, why it is novel/unique, what the major challenges.
* Describe the detailed design for your project and what you have implemented/evaluated so far.
* Describe the remaining challenges, how you would address them, and your plan for the remaining time.
* The midterm report should be about 2-4 pages and serve as a starting point for your final project report (see detailed requirements for the final report below)

Final Project Presentations
------
This should be similar to a workshop talk. You might consider covering the following content (not necessarily in the same order):
* What problem are you trying to solve?
* Why is it an important problem?
* What's your basic solution to the problem?
* What are the challenges in the problem?
* How did you solve these challenges? Or how do you plan to solve the challenges?
* Some preliminary results
* Future directions
