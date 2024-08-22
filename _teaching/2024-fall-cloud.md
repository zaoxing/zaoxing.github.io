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
| 8/27 Tue | Course Overview | [How to Read](/files/course/CCR07_HowToRead.pdf), [You and Your Research](/files/course/Bell86_YouAndYourResearch.pdf) | [Project Template](https://github.com/zaoxing/cloudcourse22/blob/main/Project_Description_Template.md), [Project Management Guidelines](), [Example Projects]() |
| 8/29 Thu | Overview of Cloud Computing | [The Datacenter as a Computer](https://www.morganclaypool.com/doi/abs/10.2200/S00874ED3V01Y201809CAC046) |  |
| 9/3 Tue | Distributed Systems | [Google File System](/files/course/SOSP03_GFS.pdf), [MapReduce](/files/course/CACM_MapReduce.pdf) | Lecture | 
| 9/5 Thu | Big Data Frameworks | [Spark](/files/course/NSDI12_Spark.pdf), [Hive](/files/course/VLDB09_Hive.pdf) |  |
| 9/10 Tue | A Glimpse into Cloud Computing and Scale | Guest lecture: Nick Gramsky, Microsoft |  |
| 9/12 Thu | In-class lab: Intro to Cloud + Monitoring |  | Project descriptions Due |
| 9/17 Tue | Overview of Virtualization | [Xen](/files/course/SOSP03_Xen.pdf)|  |
| 9/19 Thu | In-class lab: Docker | [Container-based OS virtualization](/files/course/EuroSys07_Container.pdf)|  |
| 9/24 Tue | Cloud Development and Agile Methods | Guest Lecture |[Agile-1](https://youtu.be/RJaF4owQDgg), [Agile-1.1](https://billmoyers.com/content/how-to-tell-your-story-of-self/) [Agile-2](http://www.deltamatrix.com/horizontal-and-vertical-user-stories-slicing-the-cake/) |
| 9/26 Thu | In-class lab: Kubernetes |   |  |
| 10/1 Tue | Datacenter Architectures | [VL2](/files/course/SIGCOMM09_VL2.pdf), [Aquila](/files/course/NSDI22_Aquila.pdf) |  |
| 10/3 Thu | Sprint Demos 1 |  | Presentations from student groups | 
| 10/8 Tue | Storage Systems | [Ceph](/files/course/OSDI06_Ceph.pdf), [Flat Datacenter Storage](/files/course/OSDI12_FDS.pdf)| |
| 10/10 Thu | Storage Systems and Networking | [Ceph](/files/course/OSDI06_Ceph.pdf), [Flat Datacenter Storage](/files/course/OSDI12_FDS.pdf)| |
| 10/15 Tue | Resource Management | [Borg](/files/course/EuroSys15_Borg.pdf), [Mesos](/files/course/NSDI11_Mesos.pdf), [Kubernetes](https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/pivotal/vmware-demystifying-kubernetes-overcoming-misconceptions-whitepaper.pdf) |  |
| 10/17 Thu | Sprint Demos 2 |  | Presentations from student groups |
| 10/22 Tue | Advacned Datacenter Networking | [DCTCP](/files/course/SIGCOMM10_DCTCP.pdf), [P4](/files/course/CCR14_P4.pdf) |  |
| 10/24 Thu | Invited Talk |  |  |
| 10/29 Tue | Resource Disaggregation | [InfiniSwap](/files/course/NSDI17_Infiniswap.pdf)([slides](/files/course/nsdi17_slides_gu.pdf)), [LegoOS](/files/course/OSDI18_LegoOS.pdf) |  |
| 10/31 Thu | Milestone Demos 3 Part I | | |
| 11/5 Tue | Milestone Demos 3 Part II | | |
| 11/7 Thu | Midterm Exam |  |  |
| 11/12 Tue | Distributed Systems II | [Dynamo](/files/course/SOSP07_Dynamo.pdf), [Kafka](/files/course/NetDB11_Kafka.pdf) | |
| 11/14 Thu | Geo-distributed Services | [Spanner](https://research.google/pubs/spanner-googles-globally-distributed-database-2/) | |
| 11/19 Tue | Serverless Computing | [Serverless](/files/course/Berkeley_Serverless.pdf) | |
| 11/21 Thu | Sprint Demo 4 | | |
| 11/26 Tue | Cloud Research Talk | Guest lecture: Chang Lou, UVA| |
| 11/28 Thu | Thanksgiving Recess |  | |
| 12/3 Tue | Final Presentations I | | |
| 12/5 Thu | Final Presentations II | | |
| TBD | Poster Session in Iribe Lobby | Invite Industry Partners | |


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

- **Capstone Project**: The project is a teamwork. Projects may use the public clouds via our industry partners (e.g., Microsoft Azure, Amazon AWS.) The project presentations will be given in the form of a final poster and a demo. There will also be demos scheduled throughout the course to demonstrate regular progress.

- **How to Review Papers**: Write a review in four sections, including summary, paper strengths paper weaknesses, and detailed comments.
  - Summary (points in sentence or bullet form): What program? Core novel ideas or technical contributions? Summarize approach, mechnisms, or main findings.
  - Strengths/Weaknesses: 2-4 points each.
  - Detailed comments: Be constructive. Imagine conversation w/ authors. For example,
    - Problem: What is it? Is it new? Is it real? Is it important?
    - Solution: What is the technique(s)? Is it novel? How is it compared to past solutions? What is the intuition(s)?
    - Implementation/evaluation: Does it have a real system prototype? Is the evaluation dataset(s) representative? Does the evaluation cover all aspects?
    - Looking forward: Can you come up with a new/different/better solution? Can you find a new/related problem to solve?