---
title: Data Wrangling
---


Data wrangling or data munging is the process of gathering, sorting, and transforming data from an original “raw” format, in order to prepare it for analysis and other downstream processes.

Data wrangling is generally applied to individual “data types” within a data set: rows, columns, values, fields, etc. 

Data munging and wrangling examples include:
- Removing data that is irrelevant to the analysis. In text analysis this could be stop words (the, and, a, etc.), URLs, symbols and emojis, etc.
- Removing gaps in data, like empty cells in a spreadsheet or blank spaces between words in a document.
- Combining data from multiple sources and multiple sets into a single data set.
- Data parsing: for example, turning HTML into a more standardized/easily analyzable format.
- Data augmentation to create more robust machine learning models: for example, [synonym replacement and random word deletion](https://towardsdatascience.com/eda-easy-data-augmentation-techniques-for-boosting-performance-on-text-classification-tasks-3e61a56d1332).
- Filtering data according to locations, demographics, periods of time, etc.

These are processes that will wrangle the outputs to be prepared for downstream needs.

References:
https://monkeylearn.com/blog/data-wrangling/