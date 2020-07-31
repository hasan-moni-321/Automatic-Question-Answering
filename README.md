## Automatic Question Answering

I used Questin-Answering-Dataset from Kaggle that's link is https://www.kaggle.com/rtatman/questionanswer-dataset 

Automatic-Question-Answering is a very popular technique that is used almost for every mid and high level business nowadays. And It's popularity increasing day by day. 

### What I did :-
1. All the file was in txt format. I read those file as csv format.
2. I took only three columns those are necessary for my project and that are Title, Question and Answer. 
3. I added Title and Question Column Together, to get the persons's name.
4. Dropped the duplicate question.
5. To get word I used built-in word_tokenize.
6. To know type of word, for example Noun, Verb, Adjective I used built-in pos_tag function 
7. Cleaned word like removing punctuation.
8. I removed stopwords.
9. I also used built-in WordNetLemmatizer to remove duplicate words like dog and dogs, those meaning are same but with different character. WordNetLemmatizer will 
convert those two words into one word as dog.
10. All the character into lower case.
11. I used CountVectorizer and TfidfVectorizer for creating vector.
12. For similarity checking I used cosine_similarity and linear_kernel.
