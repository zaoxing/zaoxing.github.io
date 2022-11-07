---
title: "Cloud Computing"
collection: teaching
type: "Undergraduate and Graduate"
permalink: /teaching/2022-fall-cloud
venue: "Boston University, ECE, CS"
date: 2022-09-01
location: "Boston, MA"
---

The course aims to explore several fundamental topics of cloud computing, including IaaS (e.g., Open Stack), key big data platforms, and datacenter networking. The course combines group reading and discussion of influential publications in the field, lectures by the instructor, talks by invited speakers, and a large project. In particular, the students will be a part of an agile team, with extensive experience with GitHub, agile tools, and various technologies. The project will be done by teams of 3 to 5 students working with a mentor, depending on the project, an industry leader and/or engineer with a relevant project, or a senior graduate student or a postdoc working on a relevant research project. Projects may use the Mass Open Cloud or industry clouds (Amazon AWS, Microsoft Azure, Rackspace, etc.)


Annoucements
------
- [Sprint demo video deck](https://drive.google.com/drive/folders/1Plfp6h0JkQBHOiaFeS6T8afcJ9gAaDgF?usp=sharing) is alive!
- The first demo video will be due on Mon (10/10). Project demos will be presented on Mon/Wed lectures.
- Please fill out the [account and user skill survey](https://docs.google.com/forms/d/e/1FAIpQLSe-6rylhna2YiovEiNMmm1BrmjkacraWC3sxALCcL2XNKV0uQ/viewform?usp=sf_link) to help us assign you with a project. Note that, project descriptions require BU email logins.
- Please join our Piazza discussion channel via [piazza.com/bu/fall2022/eccs528](https://piazza.com/bu/fall2022/eccs528). The access code is `cloudcomputing`.
- We have an active waitlist for this class. If you have a strong interest in joining this class, email the instructor, and we will try to enroll you with a higher priority.

Instructors
------
- Instructor: [Prof. Alan (Zaoxing) Liu](https://www.bu.edu/eng/profile/alan-liu/)
  - Office Hours: Tuesday 4-5PM.
- TA: Zeying Zhu, PhD Student
  - Office Hours: Thursday 7-8PM.
- Many thanks to [Prof. Orran Krieger](https://www.bu.edu/eng/profile/orran-krieger/) for his materials from previous years.

Tentative Syllabus
------

| Date    | Topics  | Readings | Notes|
| :------: | :------: | :------:  | :----: |
| Week 1  | Course Overview ([slide](/files/slides/lecture1.pdf)) | [How to Read](/files/course/CCR07_HowToRead.pdf), [You and Your Research](/files/course/Bell86_YouAndYourResearch.pdf) | [Project Template](https://github.com/zaoxing/cloudcourse22/blob/main/Project_Description_Template.md), [Project Management Guidelines](), [Example Projects]() |
| Week 2  | Overview of Cloud Computing ([Mon](/files/slides/lecture2.pdf),[Wed](/files/slides/week2_2.pdf)) | [The Datacenter as a Computer](https://www.morganclaypool.com/doi/abs/10.2200/S00874ED3V01Y201809CAC046) | Sign up for projects |
| Week 3  | Overview of Virtualization ([Mon](/files/slides/week3_1.pdf),[Wed](/files/slides/week3_2.pdf)) | [Xen](/files/course/SOSP03_Xen.pdf), [Container-based OS virtualization](/files/course/EuroSys07_Container.pdf)| Project descriptions Due |
| Week 4 | Agile Methods | [Agile-1](https://youtu.be/RJaF4owQDgg), [Agile-1.1](https://billmoyers.com/content/how-to-tell-your-story-of-self/) [Agile-2](http://www.deltamatrix.com/horizontal-and-vertical-user-stories-slicing-the-cake/)  | Invited lectures (Michael Daitzman) |
| Week 5 | Distributed Systems ([Mon](/files/slides/week5_1.pdf)) | [Google File System](/files/course/SOSP03_GFS.pdf), [MapReduce](/files/course/CACM_MapReduce.pdf) | Lecture (Ata Turk) | 
| Week 6 | Datacenter Architectures | [VL2](/files/course/SIGCOMM09_VL2.pdf), [Aquila](/files/course/NSDI22_Aquila.pdf) | Invited talk (Wei Bai) |
| Week 7 | Storage Systems | [Ceph](/files/course/OSDI06_Ceph.pdf), [Flat Datacenter Storage](/files/course/OSDI12_FDS.pdf)| Lecture (Orran Krieger) |
| Week 8 | Resource Management ([Mon](/files/slides/week8_1.pdf)) | [Borg](/files/course/EuroSys15_Borg.pdf), [Mesos](/files/course/NSDI11_Mesos.pdf), [Kubernetes](https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/pivotal/vmware-demystifying-kubernetes-overcoming-misconceptions-whitepaper.pdf) | Invited talk |
| Week 9 | Big Data Frameworks ([Mon](/files/slides/week9_1.pdf.pdf)) | [Spark](/files/course/NSDI12_Spark.pdf), [Hive](/files/course/VLDB09_Hive.pdf) | Sprint project demos |
| Week 10 | Datacenter Networking | [DCTCP](/files/course/SIGCOMM10_DCTCP.pdf), [P4](/files/course/CCR14_P4.pdf) | Invited talk |
| Week 11 | Resource Disaggregation | [InfiniSwap](/files/course/NSDI17_InfiniSwap.pdf), [LegoOS](/files/course/OSDI18_LegoOS.pdf) |  Sprint project demos |
| Week 12 | Distributed Systems II (Thanksgiving) | [Dynamo](/files/course/SOSP07_Dynamo.pdf), [Kafka](/files/course/NetDB11_Kafka.pdf) | Sprint project demos |
| Week 13 | Beyond the Cloud | [Serverless](/files/course/Berkeley_Serverless.pdf), [Sky Computing](/files/course/HotOS21_Sky.pdf) | Sprint project demos |
| Week 14 | Final Presentations | 
| Week 15 | Final Project Review |


Prerequisites
------
This course assumes students have a strong programming background. You will have difficulty completing the projects if you don't have signficant programming experience. Come talk to the instructors if you have any concerns.

For BU ECE students/grads: Undergrads must have taken EC327 or equivalent and preferably another software course, EC330 or EC440, before taking this course. Graduate students must have taken a rigorous programming class recently, such as EC504 or equivalent (or have major software design experience in industry).

For BU CS students/grads: This course assumes students have a strong programming background. Undergrads must have taken CS350 Operating Systems (preferably CS552 as well), CS 460 Database Systems (preferably CS562 as well), and CS 455 Computer Networks (preferably but not must) courses. Graduate students must have taken a rigorous programming class recently, (or have major software design experience).

Projects
------
In addition to paper readings, there will be a major project, starting from the course beginning, with a mentor, from industry, senior graduate student, or one of the instructors.

The project is due by the end of the exam week. The project presentations will be given in the form of a final poster and a demo. There will also be demos scheduled throughout the course to demonstrate regular progress.

Some example final demos:
- [Visualizing MBTA Performance](https://www.youtube.com/watch?v=7MUcfHN1Mzs&feature=youtu.be)
- [Adding Trusted Platform Module support to OpenStack](https://www.youtube.com/watch?v=F1FcnJCmZpg)

Grading
------
- 70%: Project
Team members typically receive the same project grades, but individual grades may be scaled based on feedback we solicit from your mentor and teammates.
   - 10%: project description
   - 30%: bi-weekly project demo and status (5 x 6%)
   - 25%: final project result and report
   - 5%: project quizzes (checking if you listened to your classmates' presentations)

- 30%: Paper quizzes and Piazza discussion
  Brief quizzes on reading assignments will be open during first 5 minutes of class.
   - PhD students: must complete all
   - MS students: must complete 80%
   - Undergrad: must complete 50%

There is no mid-term or final exam.

Evaluation of the project will involve evaluation of your demo, poster, bi-weekly status reports, code reviews, and mentor and project partner reviews.