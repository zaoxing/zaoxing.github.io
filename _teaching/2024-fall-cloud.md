---
title: "Cloud Computing"
collection: teaching
type: "Undergraduate"
permalink: /teaching/2024-fall-cloud
venue: "University of Maryland, CS"
date: 2024-09-01
location: "College Park, MD"
---

The course explores several fundamental topics of cloud computing, including IaaS (e.g., Open Stack, Kubernetes), key big data platforms, and data center networking. The course combines group reading and discussion of
influential publications in the field, lectures by the instructor, talks by invited speakers, and a large project. Students will be a part of an agile development team, with extensive experience with GitHub, agile tools,
and various technologies. Each course project is solicited from open-source community and will be mentored by an industry leader and/or engineer, or a senior graduate student/postdoc. A project is expected to be done by teams of 3 to 5 students working with a mentor. Projects may use public clouds from our industry partners (e.g., Microsoft Azure).


Annoucements
------
- Thank you Microsoft Azure and Red Hat for agreeing to share their **cloud development experience** with our students!
- Thank you Microsoft for agreeing to **sponsor our course projects with Azure credits**!
- Please enroll **CMSC498B** and email the instructor for any questions.
- An updated **speaker list** and project descriptions will be available before the semester starts.

Instructors
------
- Instructor: [Prof. Alan Zaoxing Liu](https://www.cs.umd.edu/people/zaoxing)
  - Office Hours: TBA
- TA: TBA
  - Office Hours: TBA.

Tentative Syllabus
------

| Date    | Topics  | Readings | Notes|
| :------: | :------: | :------:  | :----: |
| Week 1  | Course Overview | [How to Read](/files/course/CCR07_HowToRead.pdf), [You and Your Research](/files/course/Bell86_YouAndYourResearch.pdf) | [Project Template](https://github.com/zaoxing/cloudcourse22/blob/main/Project_Description_Template.md), [Project Management Guidelines](), [Example Projects]() |
| Week 2  | Overview of Cloud Computing | [The Datacenter as a Computer](https://www.morganclaypool.com/doi/abs/10.2200/S00874ED3V01Y201809CAC046) | Sign up for projects |
| Week 3  | Overview of Virtualization | [Xen](/files/course/SOSP03_Xen.pdf), [Container-based OS virtualization](/files/course/EuroSys07_Container.pdf)| Project descriptions Due |
| Week 4 | Agile Methods | [Agile-1](https://youtu.be/RJaF4owQDgg), [Agile-1.1](https://billmoyers.com/content/how-to-tell-your-story-of-self/) [Agile-2](http://www.deltamatrix.com/horizontal-and-vertical-user-stories-slicing-the-cake/)  | Invited lectures (Michael Daitzman) |
| Week 5 | Distributed Systems | [Google File System](/files/course/SOSP03_GFS.pdf), [MapReduce](/files/course/CACM_MapReduce.pdf) | Lecture (Ata Turk) | 
| Week 6 | Datacenter Architectures | [VL2](/files/course/SIGCOMM09_VL2.pdf), [Aquila](/files/course/NSDI22_Aquila.pdf) | Invited talk (Wei Bai) |
| Week 7 | Storage Systems | [Ceph](/files/course/OSDI06_Ceph.pdf), [Flat Datacenter Storage](/files/course/OSDI12_FDS.pdf)| Lecture (Orran Krieger) |
| Week 8 | Resource Management | [Borg](/files/course/EuroSys15_Borg.pdf), [Mesos](/files/course/NSDI11_Mesos.pdf), [Kubernetes](https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/pivotal/vmware-demystifying-kubernetes-overcoming-misconceptions-whitepaper.pdf) | Invited talk |
| Week 9 | Big Data Frameworks | [Spark](/files/course/NSDI12_Spark.pdf), [Hive](/files/course/VLDB09_Hive.pdf) | Sprint project demos |
| Week 10 | Datacenter Networking | [DCTCP](/files/course/SIGCOMM10_DCTCP.pdf), [P4](/files/course/CCR14_P4.pdf) | Invited talk |
| Week 11 | Resource Disaggregation | [InfiniSwap](/files/course/NSDI17_Infiniswap.pdf)([slides](/files/course/nsdi17_slides_gu.pdf)), [LegoOS](/files/course/OSDI18_LegoOS.pdf) |  Sprint project demos |
| Week 12 | Distributed Systems II (Thanksgiving) | [Dynamo](/files/course/SOSP07_Dynamo.pdf), [Kafka](/files/course/NetDB11_Kafka.pdf) | Sprint project demos |
| Week 13 | Beyond the Cloud | [Serverless](/files/course/Berkeley_Serverless.pdf), [Sky Computing](/files/course/HotOS21_Sky.pdf) | Sprint project demos |
| Week 14 | Final Presentations | 
| Week 15 | Final Project Review |


Prerequisites
------
- CMSC 330: Organization of Programming Languages
- CMSC 351: Algorithms

Projects
------
In addition to paper readings, there will be a major project, starting from the course beginning, with a mentor, from industry, senior graduate student, or one of the instructors.

The project is due by the end of the exam week. The project presentations will be given in the form of a final poster and a demo. There will also be demos scheduled throughout the course to demonstrate regular progress.

Some example final demos:
- [Visualizing MBTA Performance](https://www.youtube.com/watch?v=7MUcfHN1Mzs&feature=youtu.be)
- [Adding Trusted Platform Module support to OpenStack](https://www.youtube.com/watch?v=F1FcnJCmZpg)

Grading
------
- 35%: Project Progress Report
Team members typically receive the same project grades, but individual grades may be scaled based on feedback we solicit from your mentor and teammates.
   - 10%: project description
   - 20%: bi-weekly project demo and status (4 x 5%)
   - 5%: project quizzes (checking if you listened to your classmates' presentations)
- 20%: Midterm Exam
- 25%: Final project result and report
- 20%: Paper quizzes, Piazza discussion, and required project forms      
  Brief quizzes on reading assignments will be open during first 5 minutes of class.

Evaluation of the project will involve evaluation of your demo, poster, bi-weekly status reports, code reviews, and mentor and project partner reviews.


Course Mechanics
------
- **Style**: In each topic, the instructor will give one or two introductory lectures, followed by paper discussions by class participants. In addition, there will be one capstone project. Students will be required to read and review papers before the class.

- **Capstone Project**: The project will be done by teams of 3 to 5 students working with a mentor, depending on the project, an industry leader and/or engineer with a relevant project, or a senior graduate student or a postdoc working on a relevant project. Projects may use the public clouds via our industry partners (e.g., Microsoft Azure, Amazon AWS.) The project is due by the end of the exam week. The project presentations will be given in the form of a final poster and a demo. There will also be demos scheduled throughout the course to demonstrate regular progress.

- **How to Review Papers**: Write a review in four sections, including summary, paper strengths paper weaknesses, and detailed comments.
  - Summary (points in sentence or bullet form): What program? Core novel ideas or technical contributions? Summarize approach, mechnisms, or main findings.
  - Strengths/Weaknesses: 2-4 points each.
  - Detailed comments: Be constructive. Imagine conversation w/ authors. For example,
    - Problem: What is it? Is it new? Is it real? Is it important?
    - Solution: What is the technique(s)? Is it novel? How is it compared to past solutions? What is the intuition(s)?
    - Implementation/evaluation: Does it have a real system prototype? Is the evaluation dataset(s) representative? Does the evaluation cover all aspects?
    - Looking forward: Can you come up with a new/different/better solution? Can you find a new/related problem to solve?