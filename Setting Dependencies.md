#Setting Up Dependencies

We will be using several Python libraries and frameworks specific to text analytics, NLP, and
Machine Learning. Before starting the Internship Project you need to make sure you have
pandas, numpy, scipy, and scikit-learn installed.
NLP libraries which will be used; include spacy, nltk, and gensim. Do remember to check that
your installed nltk version is at least >= 3.2.4, otherwise, the ToktokTokenizer class may not be
present.
For nltk you need to type the following code from a Python or ipython shell after installing nltk
using either pip or conda.

**import nltk
nltk.download('all', halt_on_error=False)
**

For spacy, you need to type the following code in a Unix shell/windows command prompt, to
install the library (use pip install spacy if you don’t want to use conda) and also get the English
model dependency
