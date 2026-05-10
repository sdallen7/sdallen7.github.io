---
layout: post
title: The power of cloud in diagnosing brain tumours
subtitle: The future of oncology!
comments: true
mathjax: true
author: Serina Allen
---


While researching the use of cloud computing within oncology, I came across an impressive study - _BrainView: A cloud-based deep learning system for brain image segmentation, tumor detection and visualisation._[^1]
AI is being used to diagnose brain cancer in seconds – not only cutting-edge technology but potentially lifesaving!

According to the latest stats from Cancer Research UK[^2],
> "there are over 12,500 new cases of brain tumours diagnosed in the UK every year."

More concerningly, in 2019, 40% of brain cancer cases were diagnosed via an emergency presentation (often when the disease is already advanced).
But what if the diagnosis timeline was shortened, and high-resolution, expert level brain tumour analysis was more accessible?

This is where the **power of cloud** comes in!

BrainView is a cloud platform that uses two AI models; DeepBrainNet and EffB7-UNet, to diagnose and detect brain tumours. Firstly, the system analyses the MRI data to determine if a tumour is present, and if so, what type it is. If a tumour is detected, the second AI model creates a mask of the tumour to allow doctors to see exactly where the bad tissue ends and the healthy tissue begins. 

The results published have been extremely impressive – the model consistently achieves high accuracies (99.96%) on a dataset of over 7,000 images. 
The AI models are hosted in a cloud server, with a front-end web application. A doctor is now able to upload an MRI to the BrainView cloud and receive a report within seconds.

By highlighting the specific area of the brain that triggers a cancer detection / diagnosis, the AI allows the surgeon to verify the logic before making any important decisions.

Having these capabilities in the cloud provides specialist and expert knowledge to more rural and low-income areas (only requiring an internet connection).

Seriously inspiring work! 

#### References
[^1]: BrainView in PubMed: [BrainView: A cloud-based deep learning system for brain image segmentation](https://pmc.ncbi.nlm.nih.gov/articles/PMC12874125/)
[^2]: Cancer Research UK: [Brain and CNS tumour statistics](https://www.cancerresearchuk.org/health-professional/cancer-statistics/statistics-by-cancer-type/brain-other-cns-and-intracranial-tumours)
