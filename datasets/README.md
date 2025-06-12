# DRFMD Dataset: Parameters and Label Distribution

## Overview

The **DRFMD dataset** is a diverse and robust face mask detection dataset, aggregating a total of **14,727 images** and **29,846 labeled instances** from multiple sources. The dataset is split into training, validation, and test sets for standardized evaluation.

## Dataset Composition

| Dataset             | Train | Valid | Test | Total |
|---------------------|-------|-------|------|-------|
| AIZOO               | 2,686 | 383   | 782  | 3,851 |
| KFMD [18]           | 495   | 64    | 126  | 685   |
| MAFA                | 1,006 | 141   | 289  | 1,436 |
| MOXA3k              | 999   | 144   | 296  | 1,439 |
| PWMFD               | 3,283 | 482   | 938  | 4,703 |
| Zalo AI Challenge   | 1,835 | 260   | 518  | 2,613 |
| **DRFMD (total)**   | 10,304| 1,474 |2,949 |14,727 |

## Label Annotation

All images in DRFMD are manually annotated in **YOLO format** with the following three categories:

- **0:** Without mask &ndash; **14,157 instances**
- **1:** With mask &ndash; **11,590 instances**
- **2:** Wear mask incorrect &ndash; **2,866 instances**

## Instance Distribution

| Parameter                  | Train  | Valid | Test  | Total  |
|----------------------------|--------|-------|-------|--------|
| Images                     | 10,304 | 1,474 | 2,949 | 14,727 |
| Instances                  | 20,603 | 3,052 | 6,191 | 29,846 |
| Without Mask (0)           | 9,683  | 1,392 | 3,082 | 14,157 |
| With Mask (1)              | 8,926  | 1,370 | 2,527 | 11,590 |
| Wear Mask Incorrect (2)    | 1,994  | 290   | 582   | 2,866  |

## Annotation Format

The dataset follows the [YOLO annotation format](https://github.com/AlexeyAB/darknet#how-to-train-to-detect-your-custom-objects):

