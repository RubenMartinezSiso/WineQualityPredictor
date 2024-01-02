# Wine Quality Predictor 🍷

## Introduction ✨
This activity consists of putting into practice the ideas and implementations learned during the development of the Advanced Programming in Artificial Intelligence subject's final project. The idea is to solve a data prediction problem on a real dataset, so that the necessary measures must be taken and the appropriate processes carried out to obtain an optimal and correct result.

The project consists of several parts. First, the problem is described as we have decided to approach it. Then we do a data understanding, where we visualize and analyze the data in a general way and go through each of the columns to obtain new conclusions about the data. Finally, some iterations are performed where in each iteration the data is treated differently and a different model is used to train and validate the prediction obtained. The objective is that, for each iteration, the way in which the data are processed is improved and the results are optimized.

## Problem Definition 🔎
Dataset chosen: Wine Quality

Wine is the beverage obtained from the total or partial alcoholic fermentation of the juice of ripe grapes. Alcoholic fermentation is a chemical process by which organisms called yeasts (leaven) transform sugars into ethanol (alcohol) and carbon dioxide gas. As alcoholic fermentation proceeds, the sugar present in the medium decreases because it is consumed by the yeasts, and the alcohol content increases.

The dataset is related to the red and white variants of the Portuguese wine "Vinho Verde". It is a unique product from the Minho region (northwest) of Portugal. Of medium alcohol content, it is particularly appreciated for its freshness (especially in summer). This dataset is publicly available for research purposes only; for more information, read Cortez et al., 2009. . For privacy and logistical reasons, only physicochemical (input) and sensory (output) variables are available (e.g., no data on grape types, wine brand, wine sales price, etc.).

This dataset includes the following attributes per row:
1 - type
2 - fixed acidity
3 - volatile acidity
4 - citric acid
5 - residual sugar
6 - chlorides
7 - free sulfur dioxide
8 - total sulfur dioxide
9 - density
10 - pH
11 - sulphates
12 - alcohol
13 - quality (score between 0 and 10)

## Objective 🎯
Based on the attributes recorded for each wine, the aim is to classify them as `low`, `medium` or `high` quality (0, 1 or 2). It can certainly be revealing to analyze the physicochemical attributes of the wine and understand their relationship and significance to wine quality. The original dataset classifies the quality of the wines with a value between 0 and 10. To simplify the problem and obtain better results, in the following section the quality column will be modified to group the different values into only three possible types of wine quality.
