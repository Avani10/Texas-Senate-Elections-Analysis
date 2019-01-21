# Texas-Senate-Elections-Analysis
Analysis of Beto O'Rourke vs. Ted Cruz tweets scrapped from Twitter

This one is one of my most favorite codes, do go through it to enjoy the simplistic & elaborated structure.

Results were as follows:

1.	We could see a general trend of major support to Beto (Democrat) nationwide but not so much in Texas.
2.	The topics extracted using topic modelling indicated general trend of Beto discussing Ted’s views & counterarguing.
3.	A major support for Ted from rural areas could be observed while the same was observed for Beto from urban areas.
4.	The topics we got revolved around immigration, gun policies and democratic & republican viewpoints from respective sides.
5.	We predicted a win by Ted from the numbers from analysis of just Texas data & premise that majority rural population would not be active on Twitter. (It turned out to be true)

The following code is a completely reproducible code with exhaustive comments, with couple of new additions to my class project:

1.	Editted twitter scrapper which is now in Python 3.6 with a sample comment scrapped for Bandersnatch [I am a Black Mirror Fan :)]
2.	The graphs generated to compare scores of Beto & Ted have been aligned better for comparison.
3.	Topic modelling at the end has been done in two ways with LDA:<br />
  A.	Bag of words with word-count using gensim & spacy libraries <br />
  B.	TF-IDF using gensim

