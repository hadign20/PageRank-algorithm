# PageRank-algorithm
PageRank (PR) is an algorithm used by Google Search to rank web pages in their search engine results. It is named after both the term "web page" and co-founder Larry Page. PageRank is a way of measuring the importance of website pages.


### sample input and output
We present the two cases synchronous and asynchronous for initial conditions `1/n` as used in the algorithm.
```
(a) Synchronous all 1/3
Base : 0 :P[ 0]=0.33333 P[ 1]=0.33333 P[ 2]=0.33333
Iter : 1 :P[ 0]=0.05000 P[ 1]=0.19167 P[ 2]=0.47500
Iter : 2 :P[ 0]=0.05000 P[ 1]=0.07125 P[ 2]=0.23417
Iter : 3 :P[ 0]=0.05000 P[ 1]=0.07125 P[ 2]=0.13181
Iter : 4 :P[ 0]=0.05000 P[ 1]=0.07125 P[ 2]=0.13181
(b) Asynchronous all 1/3
Base : 0 :P[ 0]=0.33333 P[ 1]=0.33333 P[ 2]=0.33333
Iterat : 1 :P[ 0]=0.05000 P[ 1]=0.07125 P[ 2]=0.13181
Iterat : 2 :P[ 0]=0.05000 P[ 1]=0.07125 P[ 2]=0.13181
```

# How to run:
```
hits0206.java
	
java Pgrk0206 15 -1 samplegraph.txt
```
