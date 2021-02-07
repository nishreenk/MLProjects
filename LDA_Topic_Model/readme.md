
Data Source:
Initiative 20x20 
AFR100 
Cities4forests 
Combined data of all the three websites and their partner organizations in /data folder. Lightly scraped data.

Models:
WhyTopic Modeling ? 
	To assess the websites and their respective organizations’ websites, to  uncover if and how these platforms are approaching or mentioning climate adaptation, and understand the key climate risks and adaptation measures that are present in and across these platforms.
	The data gathered from various websites is large and going over it manually to understand what NbS approaches would prove to be a herculean task. Using NLP and specifically topic modeling algorithms will help understand what topics are discussed and are of interest in the domain of Climate Change.
	Topic modelling provides us with methods to organize, understand and summarize large collections of textual information. It helps in:
- Discovering hidden topical patterns that are present across the collection
- Annotating documents according to these topics
- Using these annotations to organize, search and summarize texts
Topic modelling can be described as a method for finding a group of words known as  topics from a collection of documents that best represents the information in the collection. It can also be thought of as a form of text mining – a way to obtain recurring patterns of words in textual material.
There are many techniques that can be used to obtain topic models, The algorithms/techniques  used here is: LDA with Gensim and Spacy

![alt text](https://raw.githubusercontent.com/nishreenk/MLProjects/images/Topic_Modeling.jpg?raw=true)

Latent Dirichlet Allocation(LDA) is a popular algorithm for topic modeling with excellent implementations in the Python’s Gensim package.
What does LDA do?
LDA’s approach to topic modeling is it considers each document as a collection of topics in a certain proportion. And each topic as a collection of keywords, again, in a certain proportion.
Once you provide the algorithm with the number of topics, all it does is rearrange the topics distribution within the documents and keywords distribution within the topics to obtain a good composition of topic-keywords distribution.
Topic Coherence measures score a single topic by measuring the degree of semantic similarity between high scoring words in the topic.
Perplexity is a statistical measure of how well a probability model predicts a sample; the statistic makes more sense when comparing it across different models with varying the number of topics. The model with the lowest perplexity is generally considered the “best”
 
Limitations:
	A few limitations are:
Topic modeling requires a lot of relevant data and consistent structure to be able to form clusters.
It also needs domain expertise to interpret the results

References
https://github.com/ddangelov/Top2Vec
https://ryanjgallagher.github.io/code/corex/overview
