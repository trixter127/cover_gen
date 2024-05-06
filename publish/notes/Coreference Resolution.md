---
title: Coreference Resolution
---

- Coreference resolution is the task of finding all expressions that refer to the same entity in a text. 
- These expressions are called mentions.
- CR is an important step for many higher level NLP tasks, such as: Document summarization, Question answering, Information extraction.
- CR works by: 
	1. Finding all linguistic expressions in a given text that refer to the same real-world entity
	2. Grouping these mentions
	3. Resolving them by replacing pronouns with noun phrases

### Coreference vs. anaphora resolution
The one case most distinguished from coreference resolution (CR) is anaphora resolution (AR). The relation of anaphora occurs in a text when one term refers to another determining the second’s one interpretation. In the example below, we see that (1) and (2) directly refer to different real-world entities however they are used in the same context and our interpretation of (2) relies on (1). These mentions do not co-refer but are in the relation of anaphora.

![[Anaphora_resolution.png|720]]

### Different types of references
#### Anaphora and cataphora
These are the bread and butter of our topic. The main difference is that anaphora occurs in the sentence after the word it refers to and cataphora is found before it. The word occurring before an anaphora is called an antecedent and the one following a cataphora is a postcedent.
![[Anaphora_Cataphora.png|720]]


### Implementation 
- [[Spacy]]
- [[Stanford NLP]] 
