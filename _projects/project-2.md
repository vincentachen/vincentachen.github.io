---
layout: project
title: "CDF Fat Tail Distribution of Healthcare Index Returns"
category:
  - "Pharma & Biotech"
  - "Finance"
image: "/assets/images/project2.png"
images:
  - /assets/images/XLV_TimeSeries.png
  - /assets/images/XLV_Return.png
  - /assets/images/XLV_CDF.png
  - /assets/images/XLV_powerlaw.png
summary: "I visualized and analyzed CDF graphs using Python and Excel to analyze 26 years of returns for the XLV (SPDR Health Care Select Sector ETF). This analysis supports my objective of assessing tail risk by identifying whether extreme events, like crashes, are anomalies or align with a fat-tailed distribution characteristic of the healthcare sector's financial markets."
capabilities:
  - "Python: numpy, pandas, scipy, matplotlib"
  - "Microsoft Excel: VLOOKUP(), NORM.DIST()"
tags:
  - featured
  - finished
permalink: /projects/healthcare-cdf-function
objectives:
  - "In my analysis of the XLV (SPDR Health Care Select Sector ETF), I utilized Jupyter Notebook to access and import financial datasets directly from Yahoo Finance. By creating the analysis in Microsoft Excel and recreating it in Python, I was able to manipulate the data efficiently and create visualizations of the index's performance. My primary objective was to gain a deeper understanding of the risk and return profiles associated with the XLV by comparing its observed cumulative density function (CDF) to that of a theoretical normal Gaussian distribution."
outcomes:
  - "The analysis revealed that the tails of the XLV's CDF were significantly heavier than those of the Gaussian curve, indicating a higher probability of extreme returns—both positive and negative—than would be expected in a normal distribution. To quantify and better understand this tail-end risk, I employed Gabaix's power law estimation. This method is particularly effective in modeling fat-tailed distributions, which are common in financial markets due to the occurrence of rare but impactful events.

The presence of heavy tails suggests that traditional risk management models, which often assume normality, may underestimate the likelihood of extreme market movements. Incorporating power law estimations can improve the accuracy of risk assessments for the XLV.

Next, I aim to extend the analysis to compare the tail behaviors of different sector ETFs to identify the healthcare sector's unique risk characteristics.
"
---
---
