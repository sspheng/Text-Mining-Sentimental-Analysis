A. WHAT IS TEXT MINING ?

Text Mining is the process of deriving meaningful information from natural language text.

B. WHAT IS TEXT CLEANING ?

Text cleaning is task-specific and one needs to have a strong idea about what they want their end result to be and even review the data to see what exactly they can achieve. Use of Text Cleaning Because :- Having too many typos or spelling mistakes in the text Having too many numbers and punctuations (E.g. Love!!!!)
Text is full of emojis and emoticons and username and links too. (If the text is from Twitter or Facebook) Some of the text parts are not in the English language. Data is having a mixture of more than one language. Some of the words are combined with the hyphen or data having contractions words. (E.g. text-processing)
Repetitions of words (E.g. Data)

HOW TO CLEAN THE TEXT?

We will see how to code and clean the textual data for the following methods.
1. Lowecasing the data

2. Removing Punctuations

3. Removing Numbers

4. Removing extra space

5.Replacing the repetitions of punctations

6. Removing Emojis

7. Removing emoticons

8.Removing Contractions

C. WHAT IS REGEX ?

Regular expressions or RegEx is defined as a sequence of characters that are mainly used to find or replace patterns present in the text. In simple words, we can say that a regular expression is a set of characters or a pattern that is used to find substrings in a given string. A regular expression (RE) is a language for specifying text search strings. It helps us to match or extract other strings or sets of strings, with the help of a specialized syntax present in a pattern.
For Example, extracting all hashtags from a tweet, getting email iD or phone numbers, etc from large unstructured text content!

To work with Regular Expressions, Python has a built-in module known as “re”. Some common functions from this module are as follows: re.search(); re.match(); re.sub(); re.compile(); re.findall()

D. WHAT IS STEMMING ?

Stemming is a technique used to extract the base form of the words by removing affixes from them. It is just like cutting down the branches of a tree to its stems. For example, the stem of the words eating, eats, eaten is eat. Stemming is the process of producing morphological variants of a root/base word. 
Stemming programs are commonly referred to as stemming algorithms or stemmers. A stemming algorithm reduces the words “chocolates”, “chocolatey”, “choco” to the root word, “chocolate” and “retrieval”, “retrieved”, “retrieves” reduce to the stem “retrieve”. Stemming is an important part of the pipelining process in Natural language processing. 
Tokenization involves breaking down the document into different words.

1. Porter Stemmer – PorterStemmer()

2. Snowball Stemmer – SnowballStemmer()

3. Lancaster Stemmer – LancasterStemmer()

E. WHAT IS LEMMATIZATION?

Lemmatization is the process of grouping together the different inflected forms of a word so they can be analyzed as a single item. Lemmatization is similar to stemming but it brings context to the words. So it links words with similar meanings to one word. Text preprocessing includes both Stemming as well as Lemmatization. 
Many times people find these two terms confusing. Some treat these two as the same. Actually, lemmatization is preferred over Stemming because lemmatization does morphological analysis of the words. Examples of lemmatization: 
-> rocks : rock
-> corpora : corpus 
-> better : good!

![image](https://github.com/sspheng/Text-Mining-Sentimental-Analysis/assets/78303183/b77d71ac-200c-4a3c-9fb2-b9b66860ff59)

F. WHAT IS WORD CLOUD ?

Word Cloud or Tag Clouds is a visualization technique for texts that are natively used for visualizing the tags or keywords from the websites. These keywords typically are single words that depict the context of the webpage the word cloud is being made from. 
These words are clustered together to form a Word Cloud. Each word in this cloud has a variable font size and color tone. Thus, this representation helps to determine words of prominence. A bigger font size of a word portrays its prominence more relative to other words in the cluster. Word Cloud can be built in varying shapes and sizes based on the creators’ vision.
The number of words plays an important role while creating a Word Cloud. More number of words does not always mean a better Word Cloud as it becomes cluttery and difficult to read. A Word Cloud must always be semantically meaningful and must represent what it is meant for. Although, there are different ways by which Word Clouds can be created but the most widely used type is by using the Frequency of Words in our corpus. And thus, we will be creating our Word Cloud by using the Frequency type.

![image](https://github.com/sspheng/Text-Mining-Sentimental-Analysis/assets/78303183/aeca2bdc-5602-4edc-b62e-43533a9966ba)

G. WHAT IS PRINCIPAL COMPONENT ANALYSIS ?

Principal Component Analysis is an unsupervised learning algorithm that is used for the dimensionality reduction in machine learning. It is a statistical process that converts the observations of correlated features into a set of linearly uncorrelated features with the help of orthogonal transformation. 
These new transformed features are called the Principal Components.  It is one of the popular tools that is used for exploratory data analysis and predictive modeling. It is a technique to draw strong patterns from the given dataset by reducing the variances.PCA generally tries to find the lower-dimensional surface to project the high-dimensional data.PCA works by considering the variance of each attribute because the high attribute shows the good split between the classes, and hence it reduces the dimensionality.Some real-world applications of PCA are image processing, movie recommendation system, optimizing the power allocation in various communication channels. It is a feature extraction technique, so it contains the important variables and drops the least important variable.

H. TF-IDF

TF-IDF in NLP stands for Term Frequency – Inverse document frequency. It is a very popular topic in Natural Language Processing which generally deals with human languages. During any text processing, cleaning the text (preprocessing) is vital. Further, the cleaned data needs to be converted into a numerical format where each word is represented by a matrix (word vectors). This is also known as word embedding.
Term Frequency (TF) = (Frequency of a term in the document)/(Total number of terms in documents)Inverse Document Frequency(IDF) = log( (total number of documents)/(number of documents with term t))TF.IDF = (TF).(IDF)

I. BIGRAMS & TRIGRAMS

Bigrams: Bigram is 2 consecutive words in a sentence. E.g. “The boy is playing football”. The bigrams here are:

The boy 

Boy is 

Is playing 

Playing football 

Trigrams: Trigram is 3 consecutive words in a sentence. For the above example trigrams will be:

The boy is 

Boy is playing Is

playing football

J. WHAT IS WEB SCRAPPING ?

Web scraping is an automatic method to obtain large amounts of data from websites.  Most of this data is unstructured data in an HTML format which is then converted into structured data in a spreadsheet or a database so that it can be used in various applications. There are many different ways to perform web scraping to obtain data from websites. These include using online services, particular API’s or even creating your code for web scraping from scratch. 
Many large websites, like Google, Twitter, Facebook, StackOverflow, etc. have API’s that allow you to access their data in a structured format. This is the best option, but there are other sites that don’t allow users to access large amounts of data in a structured form or they are simply not that technologically advanced. In that situation, it’s best to use Web Scraping to scrape the website for data.
Web scraping requires two parts, namely the crawler and the scraper. The crawler is an artificial intelligence algorithm that browses the web to search for the particular data required by following the links across the internet. The scraper, on the other hand, is a specific tool created to extract data from the website. The design of the scraper can vary greatly according to the complexity and scope of the project so that it can quickly and accurately extract the data.

K. WHAT IS TEXT SUMMARIZATION ?

In this approach we build algorithms or programs which will reduce the text size and create a summary of our text data. This is called automatic text summarization in machine learning. Text summarization is the process of creating shorter text without removing the semantic structure of text.

![image](https://github.com/sspheng/Text-Mining-Sentimental-Analysis/assets/78303183/d3c4f20a-9869-49ea-a946-4a0e6549d5dc)

L. TYPES OF TEXT SUMMARIZATION:

Extractive Approaches: Using an extractive approach we summarize our text on the basis of simple and traditional algorithms. For example, when we want to summarize our text on the basis of the frequency method, we store all the important words and frequency of all those words in the dictionary. 
On the basis of high frequency words, we store the sentences containing that word in our final summary. This means the words which are in our summary confirm that they are part of the given text!

Abstractive Approaches: An abstractive approach is more advanced. On the basis of time requirements we exchange some sentences for smaller sentences with the same semantic approaches of our text data.The approach is to identify the important sections, interpret the context and reproduce in a new way. This ensures that the core information is conveyed through shortest text possible. 
Note that here, the sentences in summary are generated, not just extracted from original text.

M. WHAT IS WORD2VEC ARCHITECTURE (SKIP GRAMS VS CBOW) ?

Word2Vec is a shallow, two-layer neural networks which is trained to reconstruct linguistic contexts of words. It takes as its input a large corpus of words and produces a vector space, typically of several hundred dimensions, with each unique word in the corpus being assigned a corresponding vector in the space. Word vectors are positioned in the vector space such that words that share common contexts in the corpus are located in close proximity to one another in the space.Word2Vec is a particularly computationally-efficient predictive model for learning word embeddings from raw text.It comes in two flavors, the Continuous Bag-of-Words (CBOW) model and the Skip-Gram model.Algorithmically, these models are similar.

![image](https://github.com/sspheng/Text-Mining-Sentimental-Analysis/assets/78303183/f8ec4385-0c28-4ef9-b392-5313eca154d9)

N. WORD2VEC ARCHITECTURE

![image](https://github.com/sspheng/Text-Mining-Sentimental-Analysis/assets/78303183/95a6b2fd-18db-426c-bd45-95791c675529)


The hidden layer operates as a lookup table. The output of the hidden layer is just the “word vector” for the input word.More concretely, if you multiply a 1 x 10,000 one-hot vector by a 10,000 x 300 matrix, it will effectively just select the matrix row corresponding to the ‘1’.

![image](https://github.com/sspheng/Text-Mining-Sentimental-Analysis/assets/78303183/ffafc4ab-fed2-47e9-b0d4-fca84a8b430b)

L. TEXT CLASSIFICATION

Text claification is the process of categorizing the text into a group of words. By using NLP, text classification can automatically analyze text and then assign a set of predefined tags or categories based on its context. NLP is used for sentiment analysis, topic detection, and language detection.There is mainly three text classification approach-Rule-based System, Machine System; Hybrid System.






