# Naive Bayes Implementation from Scratch for Text Classification

This is an implementation of the Naive Bayes Algorithm for Text Classification.

The dataset used here is "Twenty Newsgroups Data Set". 
The dataset consists of News articles which are divided into 20 groups, where each group consists of 1000 articles.

The groups are:
1. alt.atheism
2. comp.graphics
3. comp.os.ms-windows.misc
4. comp.sys.ibm.pc.hardware
5. comp.sys.mac.hardware
6. comp.windows.x
7. misc.forsale
8. rec.autos
9. rec.motorcycles
10. rec.sport.baseball
11. rec.sport.hockey
12. sci.crypt
13. sci.electronics
14. sci.med
15. sci.space
16. soc.religion.christian
17. talk.politics.guns
18. talk.politics.mideast
19. talk.politics.misc
20. talk.religion.misc

The dataset is easily available [here](http://archive.ics.uci.edu/ml/datasets/Twenty+Newsgroups)

 
# Result

I Performed Test Classification using Multinomial Naive Bayes(already implemented in sklearn) and got a presion of 0.79

Whereas, my own Implementation of Naive Bayes gives a precision of 0.80
