---
layout: default
---

# DSC 180A Methodology Assignment 4

**Name:** Lillian Tran
**Email:** lnt002@ucsd.edu
**Section:** Domain 5
**Mentor:** Haojian Jin

---

**What is the most interesting topic covered in your domain this quarter?**

The most interesting topic covered in my domain this quarter was zero-shot forecasting from the SarSim0 paper. 
The paper discusses training a model only on simulated time series such as trend, seasonality and noise and then using it on real data that has never seen it.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

A potential investigation I would like to pursue for my quarter 2 project is how to tell an unusual reading from unusual activity using the data set we are currently exploring.
For example, a spike could be a meter fault or a real life event such as scheduled maintenance. An unusual reading doesn't always equate with unusual activity.

**What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

A potential change I'd make to the approach taken this quarter is I would pick the audience and the detector earlier. During this quarter, we spent a lot of time designing indicators with no concrete audience in mind. 
Granted, part of the reason why it was difficult to pick a target audience was due to the lack of access to the dataset we needed to work on.

**What other techniques would you be interested in using in your project?**

- Cross-building comparison: this could be done by clustering buildings or correlating submeters to catch the anomalies that single-series methods miss.
- Time Series Decomposition: good for separating trends, seasonality and residuals. This could help us better understand what parts of the signal look unusual.
