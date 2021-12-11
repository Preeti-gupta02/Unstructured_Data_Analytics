# Unstructured_Data_Analytics
Assignment 1 
Perform a competitive analysis of the entry level luxury car market in the USA. Give advice/insights based on the analysis of social media conversations. Proof Zipf's Law usig word frequencies.

Assignent 2
Building a Crowdsourced Recommendation System. The objective of this group assignment is to create the building blocks of a crowdsourced recommendation system. This recommendation system accepts user inputs about desired attributes of a product and comes up with 3 recommendations (I have used both bag of words and word embeddings to conclude that word embeddings give better results). 

Assignment 3
Topic Modeling using instagram data of Zara page. Use the image Urls to run google vision api and labels for images. Then run LDA topic modeling to assign topics to different posts.

Final Assignment 
The goal of this project is to create a model to measure the box office success of movies that have been revealed but not yet released to the public. I hope to design and deploy an analytic solution to consume unstructured data such as comments from a social media post to create a measurement of box-office success based on previous data.

Libraries used :<br/>
1. BeautifulSoup : For pulling data out of html file.
2. nltk : To work with linguistic data, used for tokenization, stemming, classification.
3. tqdm : A library in Python which is used for creating Progress Meters or Progress Bars. 
4. spaCy : for linguistic data (better than nltk for industrial purpose). Used to computer word embeddings similarity between two sentences. I have used spaCy's Statistical Models : en_core_web_md: English multi-task CNN trained on OntoNotes, with GloVe vectors trained on Common Crawl. Size – 91 MB
    ![image](https://user-images.githubusercontent.com/19946278/145664117-a9622deb-d5c3-4848-ada1-0acadac8ba63.png)
    
Sentiment Analysis : <br/>
Textblob sentiment analyzer returns two properties for a given input sentence:

Polarity is a float that lies between [-1,1], -1 indicates negative sentiment and +1 indicates positive sentiments.
Subjectivity is also a float that lies in the range of [0,1]. Subjective sentences generally refer to opinion, emotion, or judgment.
 I instead used VADER Sentiment Analyser
VADER Sentiment Analysis :
VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media. VADER uses a combination of A sentiment lexicon is a list of lexical features (e.g., words) which are generally labeled according to their semantic orientation as either positive or negative. VADER not only tells about the Positivi
