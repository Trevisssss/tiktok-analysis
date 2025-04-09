# TikTok Project

## Overview

Statistics can drive actions and inspire meaningful decisions. This project demonstrates how data empowers us to make better choices by leveraging the power of both descriptive and inferential statistics.

## Objective

The primary goal of this project is to showcase how statistical analysis can be applied to real-world scenarios, enabling informed decision-making. By combining descriptive statistics to summarize data and inferential statistics to draw conclusions, this project highlights the synergy between these two approaches.

## Key Features

- **Descriptive Statistics**: Summarizing and visualizing data to uncover patterns and trends.
- **Inferential Statistics**: Making predictions and testing hypotheses based on data samples.
- **Actionable Insights**: Translating statistical findings into meaningful actions.

## Why It Matters

Understanding and applying statistical methods can lead to smarter, data-driven decisions. This project serves as a practical example of how statistics can be a powerful tool for driving impactful outcomes.

## The TikTok Dataset

This TikTok dataset was used to answer the following initial question:

- Is there a statistical difference in view count between verified and unverified accounts?  
This answer will lead to the next steps in this project, which aims to investigate why this happens.

## Insights💡

After analyzing the data, it was found that the mean view count of non-verified accounts was much higher than that of verified accounts.  
However, this was not enough evidence since the difference could have been caused by chance. For that reason, a two-sample t-test was conducted.

**The Null Hypothesis:** The difference in the mean view counts between non-verified and verified accounts is due to chance.  
**The Alternative Hypothesis:** The difference in the mean view counts is statistically significant and represents the entire population.

**Result:**  
There is statistical significance in the difference between non-verified and verified accounts regarding view counts.  
With this result, we can proceed to a more in-depth analysis using regression, a more complex method that allows us to consider additional variables.