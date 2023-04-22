# Summarize-Text


Text Summarization involves condensing a piece of text into a shorter version, reducing the size of the original text while preserving key information and the meaning of the content. Since manual text synthesis is a long and generally laborious task, task automation is gaining in popularity and therefore a strong motivation for academic research.

In Machine Learning, there are important applications for text summarization in various Natural Language Processing related tasks such as text classification, answering questions, legal text synthesis, news synthesis, and headline generation which can be achieved with Machine Learning. The intention to summarize a text is to create an accurate and fluid summary containing only the main points described in the document.

## Types of Approaches to Summarize Text
Generally, Text Summarization is classified into two main types: Extraction Approach and Abstraction Approach. Now let’s go through both these approaches before we dive into the coding part.

### The Extractive Approach
The Extractive approach takes sentences directly from the document according to a scoring function to form a cohesive summary. This method works by identifying the important sections of the text cropping and assembling parts of the content to produce a condensed version.

### The Abstractive Approach
The Abstraction approach aims to produce a summary by interpreting the text using advanced natural language techniques to generate a new, shorter text – parts of which may not appear in the original document, which conveys the most information.

I have used the extractive approach to summarize text using Machine Learning and Python. I have used the TextRank algorithm which is an extractive and unsupervised machine learning algorithm for text summarization.
