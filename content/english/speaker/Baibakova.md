---
title: "Viktoriia Baibakova"
date: 2019-09-10T13:51:25+06:00
draft: false
talk: "Dataset of BiFeO3 thin film sol-gel synthesis recipes extracted manually and with GPT-3"
abstract: "Thin film sol-gel synthesis is a complicated multi-step process with many degrees of freedom. While general steps are usually typical (precursor gel preparation, deposition, drying), the choice of parameters (precursor materials, experimental setup) is often inspired by authors' scientific intuition or peer experience. As the number of reports grows, synthesis recipe databases become helpful in linking the synthesis parameters with the outcome. Here we present a manually extracted dataset of BiFeO3 thin film sol-gel synthesis recipes and propose a pipeline for automated parameters extraction using GPT-3. To compile a corpus of relevant articles, we queried the 5-million full-text and Web of Science DBs with text-mining tools (Apache Solr search engine, Chemical Named Entity Recognition, synthesis paragraph classifier). We manually located and parsed synthesis recipes. After that, we built a workflow for automated recipe extraction with GPT-3. Among 5 million full-text papers, we found 121 papers reporting the sol-gel synthesis of BiFeO3 thin films and discussing phase purity. With additional 57 articles from the Web of Science, we compiled a corpus of 178 relevant papers. We manually extracted parameters for 341 recipes and shaped them into a synthesis recipe dataset with numerical and categorical values. For the automated extraction, we avoided fine-tuning GPT-3. Instead, we built a set of consecutive GPT-3 prompts, gradually fining the graining of information. The compiled dataset is educative for understanding the BiFeO3 thin film sol-gel synthesis process. It shows that hidden variables never reported in publications influence the result. Automating the extraction process is crucial for generating big datasets and observing a more comprehensive picture. GPT-3 is a flexible yet powerful tool for this task, and an accurate compilation of prompts allows specific information extraction without annotation and training."
description: "I am 4th year Ph.D. student at University of California at Berkeley in the Materials Science and Engineering department. Also, I work as Graduate Student Research Assistant at Lawrence Berkeley National Laboratory in the group Hacking Materials under the supervision of Anubhav Jain. Our group uses an interdisciplinary approach focusing on machine learning and deep learning. I train and fine-tune models for the theoretical prediction of material properties."
bg_image : "images/speakers/Baibakova.jpg"
image : "images/speakers/Baibakova.jpg"
designation : UC-Berkeley / Lawrence Berkeley National Laboratory
email : 
type : "speaker"

---

