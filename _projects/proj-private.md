---
title: "Privacy-Preserving, Automated Open Tracing and Telemetry Framework"
collection: projects
permalink: /projects/proj-private
---
Our conversations with leading cloud and AI vendors across market verticals (e.g., security,
telemetry, finance) tell us that at every step along the way, lack of access to realistic and diverse data from multiple deployments hampers innovation. For instance, data-driven products trained on data not representative of real customer environment, there is no way to quantitatively assess products; machine learning workflows experiences data drift, and product feedback is not quantitative. The result today is poor products, lack of transparency, lots of effort in debugging/reproduction/resolution, and impossibility to share insights across diverse customers. 

The core problems behind lacking of access to realistic and trustworthy data in the cloud are three-fold:

* Operational data (e.g., continuous network packet traces) are usually proprietary, restricting the data sharing under non-disclosure agreements and privacy policies such as GDPR. This is why we do not see these kinds of data coming from public clouds.

* If the data are shareable, the datasets are usually incomplete, scattered, and missing ground truth (labels). The reason is that collecting datasets is usually assigned as manual tasks by a few engineers on a team. It is really difficult for an engineer or a team to collect and maintain complete data over a longer period of time. Moreover, labels and cross-layer metadata are also difficult to obtain, as different infrastructures and applications are often controlled by different teams in an organization. For instance, a packet trace collected by the networking team may not have the corresponding knowledge about the upper-layer workloads.

* Even if the data are collected cross-layer and sharable, the anonymization process to meet user requirements is nontrivial, time-consuming, and somewhat untrustable. For instance, a simple tool for anonymizing network packets is just to cut the payloads, while packet header fields can leak private user information.
