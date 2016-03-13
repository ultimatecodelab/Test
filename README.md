
#Table of contents

###1: Introduction
###2: Background
###3: Words List
###4: Files and Scripts 
###4: Algorithms (Two versions)
    -CountdownV1Recursive.py
    
    -CountdownV2Perm.py
###5: Compare and Contrast of both algorithms
###6: References
 
##1: Introduction
 The idea of this project was to demonstrate the understand of different data structures and algorithms. This is a college project
 and it is about solving the countdown letters game as efficient as we could along with the detailed analysis of the chosen  approach/algorithm
 to solve this particular problem.

## Background
The first task I completed as part of this project was to Google "countdown letters game solver".
Google gave me two relevant results on the first page, these are [Cool Project name][2] and [Cool Solver][3].

## Words list
My words list is in the file [wordslist.txt](wordslist.txt) in this repoistory/gist.
I got my words list from the [Oxford Learner's Dictionaries][1] website.

## Python script
My script is in the files [solver.py](solver.py) in this repository and it works as follows.
The most important section is:

```python
import random
print(random.shuffle("My code is cool."))
```

Previously it looks like this:
```python
# Note that the following snippet of code was adapted from
# the Stack Overflow post available here: http://www.so.com/post/123
import nothing
```
That didn't work too well, so I changed it.

## Preprocessing
My script does a lot of preprocessing, which only needs to be run once.
Once the preprocessing is done we can run the game solver again and again without that overhead.

## Efficiency
Here's some stuff about how efficient my code is, including an analysis of how many calculations my algorithm requires.

## Results
My script runs very quickly, and certainly within the 30 seconds allowed in the Coutdown letters game.


## References
