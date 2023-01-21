# GPT-3 language based functions
Notebooks to analyze accuracy of language based functions

### Notebooks

Each repo analyzes one of three functions:

1. A function that takes an input string, expected to be in the form of a question, and tells you if the question makes sense
e.g.  "How many frogs does the photon have?" will be detected as a nonsense question.

2. A function that takes as input two strings, expected to be two sentences, plus another string expected to be a question.  Then the function will say if the two sentences are equivalent answers with respect to the question.

3. A function that takes as input five strings, expected to be sentences, and one more string expected to be a question.  Then the function will return the "popular" answer, i.e. the most frequent one

The idea is that then we could use these functions as part of a larger toolkit to monitor cognitive processes built on GPT-3 cognitive-based architectures.

In the "comparison" directory, I re run the notebooks to see how the davinci 003 model performs.

### Datasets

There's a few datasets of questions/answers built for the sole purpose of testing these functions.  Unfortunately they are small (20 points), but still good enough to give an idea of performance.

# Conclusion

Functions 1 and 2 worked quite well.  Surprisingly number 3 was not as easy and I could not make it perform better -for now-. Latest davinci model did not show major improvements.

I might come back to this repo in the coming months, but if GPT-4 comes out then I might not (or might use this as baseline to test the new model)

