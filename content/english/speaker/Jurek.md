---
title: "Dominik Jurek"
date: 2019-09-10T13:51:25+06:00
draft: false
talk: "Patent texts for identification in economic and innovation research"
abstract: "Does patent eligibility impact job creation? To answer this question, I use a 2014 Supreme Court decision that limited what innovations can receive patents and NLP methods to identify invalid patents. I find that treated firms reduce job creation and create fewer new establishments in response, providing insight into how patents accelerate economic growth. 

To allow for a consistent measure of treated patents before and after the court decision, I develop and train a NLP model to identify claim language that is invalid and classify existing patents. I use application data from the US patent office to find rejected claim texts mentioning the relevant court decision to build a corpus of texts that are not patent eligible anymore. I select issued patents from the same filing years and patent classes as the rejected applications as control texts with eligible language. I extract from the corpora rejected and valid claim texts, tokenize, and vectorize the texts in a TF-IDF matrix. I then train a support-vector machine to predict for a given claim text whether it would be rejected after the court decision. I use this NLP model to classify all relevant patents since 1990, a total of 1,062,897 patents. Thus, I can predict for each patent in related patent classes if it is valid or not following the court decision. 

My NLP classification method identifies treated patents better than patent classes alone: for example, the affected patent classes saw a decline in patent issuance from 2014 to 2015 of 7.1%, while treated patents identified with my NLP method declined by more than 16.3%. Patent classes are broad and cover more technologies than are treated, thus, patent classes are not precise enough for identification strategies in economic settings. My method provides a valuable new tool to reliably identify invalid patents beyond broad patent classes and the few cases in which patents are litigated. 

Future works in economic and innovation research on the impact of patents will benefit from this new method. My main analysis is one example for how my method can establish causality in empirical research: I identify treated firms by measuring the share of treated patents in patent portfolios. I estimate a difference-in-differences model and find that firms receive fewer patents after the court decision and create fewer new establishments and jobs, which is direct evidence for the positive link between patents, job creation, and economic growth."
description: "I am a PhD candidate in Finance at Haas Business School on the job market in 2022/23.  My research interests are at the intersection between Finance, Computer Science, and Innovation Research.  In my current work, I combine machine learning, natural language processing, and causal inference to classify patent texts based on whether they are at risk of invalidation and estimate the causal effect of limited patentability on innovation direction and the economic performance of firms.  I am always looking for opportunities to leverage my knowledge of empirical methods, causal inference, and corporate finance to gain new data-driven insight into economic questions about firms, innovation, and digitization."
bg_image : "images/speakers/Jurek.jpg"
image : "images/speakers/Jurek.jpg"
designation : UC-Berkeley Haas School of Business
email : 
type : "speaker"

---

