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
    * Class Time: Tue/Thu 2:00-3:15PM
    * Office Hours: Thu 4-5 or by appointment

Prerequisites
------
Experiences with computer networking and software systems, including one or more of CMSC330, CMSC412, CMSC414, CMSC417, etc., or permission of the instructor. The assignments and projects assume students have familiarity with programming (e.g., Python and C/C++).


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
    a.	Topic: Reproduce a paper discussed in class, or novel research with a system-building component.  
    b.	Can work alone, or in groups of two students. Must involve writing some code.  
    c.	Can overlap with other research projects, with permission.


Academic Conduct Statement
------
 Academic Conduct Statement including expectations for academic honesty, reference to consequences for cheating or plagiarism, course-specific guidelines for, e.g., extent of allowable collaboration on assignments, and URL for [Academic Conduct Code](https://academiccatalog.umd.edu/undergraduate/registration-academic-requirements-regulations/academic-integrity-student-conduct-codes/).

Grading
------
- Class participation: 10% 
- Paper reviews: 20% 
- Programming/measurement assignments: 20% 
- Paper and project presentations: 50%

Late Policy: Programming/measurement assignments receive 10% off grades for each 24 hours late, rounded up.


Tentative Course Schedule
------

| Date    | Topics  | Readings |
| :------: | :------: | :------  |
| Week 1  | Administrative delay | No Class |
| Week 2  | Administrative delay | No Class |
| Week 3  | Course Overview | *[How to Read](/files/course/CCR07_HowToRead.pdf), *[The New Frontier of Machine Learning Systems](https://arxiv.org/pdf/1904.03257.pdf) |
| Week 4  | New Architecture | *[A Datacenter Infrastructure Perspective for ML](), *[Optimized Network Architectures for Large Language Model Training with Billions of Parameters](https://arxiv.org/pdf/2307.12169.pdf) |
| Week 5  | Data Parallelism | *[PyTorch FSDP: Experiences on Scaling Fully Sharded Data Parallel](https://arxiv.org/pdf/2304.11277.pdf),  *[A Berkeley View of Systems Challenges for AI](https://arxiv.org/pdf/1712.05855.pdf) |
| Week 6  | Model Parallelism | *[PipeDream: Generalized Pipeline Parallelism for DNN Training](), *[GPipe: Efficient Training of Giant Neural Networks using Pipeline Parallelism]() |
| Week 7  | Tensor and Automated Parallelism | *[Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism](), *[Alpa: Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning]() |
| Week 8  | Communicaton Library | *[A Unified Architecture for Accelerating Distributed DNN Training in Heterogeneous GPU/CPU Clusters](), *[NCCL Communication Primitives](https://docs.nvidia.com/deeplearning/nccl/user-guide/docs/overview.html) |
| Week 9  | Congestion Control | *[Congestion Control in Machine Learning Clusters](), *[Efficient Flow Scheduling in Distributed Deep Learning Training with Echelon Formation]() |
| Week 10  | ML Workflow: Data| *[Understanding data storage and ingestion for large-scale deep recommendation model training](), *[Check-N-Run: a Checkpointing System for Training Deep Learning Recommendation Models]() |
| Week 11  | ML Workflow: Preproessing | *[Where Is My Training Bottleneck? Hidden Trade-Offs in Deep Learning Preprocessing Pipelines](), *[FastFlow: Accelerating Deep Learning Model Training with Smart Offloading of Input Data Pipeline]() |
| Week 12  | ML Workflow: Job Scheduling and Energy | *[Where Is My Training Bottleneck? Hidden Trade-Offs in Deep Learning Preprocessing Pipelines](), *[Looking Beyond GPUs for DNN Scheduling on Multi-Tenant Clusters]() |
| Week 13  | ML Workflow: Model Serving | TBD |
| Week 14  | New Hardware |  |
| Week 15  | Final Presentations |