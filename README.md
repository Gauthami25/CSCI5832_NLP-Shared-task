# CSCI5832_NLP-Shared-task
Repository for NLP Shared task

**Task 6: LegalEval: Understanding Legal Texts**


**Problem:**

Named Entities Recognition is a frequently researched issue in Natural Language Processing, and there are numerous publicly available pre-trained models. However, when it comes to domain specific entities, in this the legal domain, entities like names of petitioner, respondent, court, statute, provision, precedents, etc. are hard to detect using the regular, off the shelf named entity recognizers. Moreover, standard Named Entity Recognizers like spacy do not recognize these entity types. Therefore, it is necessary to create a Legal NER model fine-tuned on legal documents and entities. Up until now, there weren’t any publicly accessible annotated datasets. But now that we have it, it is crucial to create a separate legal NER for texts of Indian court judgments and the fact that these documents are filled with peculiarities of Indian legal processes and terminology makes it a challenging problem to solve.


**How does the data look like and what kind of entities are we trying to extract?**

Some entities are extracted from Preamble of the judgements and some from judgement text. Preamble of judgment contains formatted metadata like names of parties, judges, lawyers, date, court etc. The text following preamble till the end of the judgment is called as the "judgment"

![](images/img.png)
