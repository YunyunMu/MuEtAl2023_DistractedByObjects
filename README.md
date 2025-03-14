# Project Name: Distracted By Objects

## Project Objective
Source Code for the data analysis and modeling for our published paper: 
Mu, Y., Tünnermann, J., & Schubö, A. (2024). Distracted by Objects: The Impact of Earlier Semantic Categorization. Advances in Cognitive Psychology, 20(4), 320. https://doi.org/10.5709/acp-0434-y

## Tech Stack
- **Language**: Python
- **Data Cleaning**: Pandas, NumPy
- **Analysis & Modeling**: arviz, acvsfit, pymc
- **Visualization**: Matplotlib, seaborn, aesara.tensor
- **Database**: csv

## Data Source
[LearningCurveAnalysis/data/]

## Key Analysis Steps
1. **Data Cleaning**: Handle missing values and outlier Response Times and accuracies.
2. **Visualization**:
   - The response time of participants in different visual search scenarios/conditions

## Core Findings
According to attentional theories of associative learning, organisms tend to prioritize items with a higher predictive value over those with a lower predictive value. We investigated whether experienc-ing a semantic categorization task with naturalistic object images inuences attentional selection in a subsequent visual search task. Participants rst categorized either between tool and vehicle or be-tween fruit and vegetable. In the subsequent search task, they searched for a new target object and ignored a distractor that was either from the category they had to distinguish in the former learning task or from a nonrelevant category. We assumed that the extent these distractors interfered with se-lecting the target depended on their former response predictiveness. Search times were analyzed by using a hierarchical learning curve model. The results showed that objects from previously response predictive categories impaired performance to a greater degree than objects from nonpredicitive categories, regardless of particular object categories. The ndings suggest that categorization learn-ing from both basic and superordinate level categories can impact attentional control settings simi-larly, with fruit and vegetable more likely being basic level categories and tool and vehicle being superordinate level categories.

## How to Run
Data and analysis scripts are available at: https://osf.io/5hekp/ and https://github.com/YunyunMu/MuEtAl2023_DistractedByObjects
