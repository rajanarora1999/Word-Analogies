# Word-Analogies

This Project Finds the word analogous to given word pair(Eg  man : woman:: king:?).

It Uses Word2Vec Model which is a pre trained model by Google. It has a 300 sized vector for each word.

Words in a similar context have similar vectors. 

So the similarity between man and woman is equal to similarity between king and queen.

if a : b::c:d then  d-c=b-a -> d=b-a+c.

Similarity is calculated using cosine similarity.

Link To The Dataset: https://www.kaggle.com/leadbest/googlenewsvectorsnegative300
