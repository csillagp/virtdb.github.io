---
layout: post
subtitle: "What’s new in VirtDB Data Unfolder?"
date: "2016-05-02"
published: false
title: "What’s new in VirtDB Data Unfolder?"
---
## Why it is here and what happens with the previous VirtDB versions?

Now that the new VirtDB version, Data Unfolder for SAP is publicly available, some of you (who already have tried / used / read about previous VirtDB versions) may ask how it is different, and what will happen with the original product line.

The previous VirtDB versions are standalone products, in a sense: they are running on separate machines, not on source systems and are more specific to the target databases, like our last version of VirtDB was integrated to PostgreSQL server. (see the high level architecture below). This architecture has its benefits (e.g. data federation capabilities, real-time queries, mutual SQL syntax on relational and nonrelational data -  just to name a few), and has drawbacks as well, like it isn’t able to utilize all the resources of the different source systems, and sometimes it is too complex for a regular analyst / business user. 

img

After collecting tons of feedbacks and feature requests from clients and demo participants from the last year, we have decided to start the Data Unfolder product line, specific to SAP data access only. It comes with reduced complexity, we have removed everything which were not strongly justified by SAP data unfolding purposes and embedded its user interface into SAP’s own client UI.  

The result is VirtDB Data Unfolder for SAP, it opens up data management self-service for SAP end-users, by enabling to send your own choice of SAP data (e.g. your favourite SAP ERP tables, reports, queries, custom and standard stuff, etc) to non-SAP systems  (like 3rd party business intelligence, data mining tools, MS Excel, cloud or local storage, SaaS offerings, etc.) without leaving your SAP Client or writing a line of ABAP code. 

img
caption:VirtDB Data Unfolder for SAP architecture

VirtDB Data Unfolder runs as an ABAP add-on on SAP application server, no external users/technologies should log-in to SAP at all. All data movements and transformations are managed by the regular SAP users only.

Those who are interested in our original data virtualization product line, should not worry either. We’re doing a major redesign of the legacy VirtDB product and will come up with new, more scalable and more usable versions shortly. 
Stay tuned!
