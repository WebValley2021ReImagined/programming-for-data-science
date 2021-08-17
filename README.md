# Programming for Data Science @ WebValley Re-Imagined 2021

This is a concise programming tutorial, aimed at researchers and practitioners with no prior programming experience, as well as people with previous programming skills. 

We will walk through several concepts to give you an introduction to some of the principal programming concepts like _conditionals_, _functions_, _iterations_, as well as more specialised topics like _classes_, _objects_ and what's sometimes called _defensive programming_.

_If all these terms sounds like [gibberish](https://en.wikipedia.org/wiki/Gibberish) to you, don't you worry!_ 

 I'll try to show everything with simple code examples: no long and complicated explanations with fancy words. At the end of this tutorial, I am sure you will master all these concepts like a _pro_ 🙌

### Why Programming for _Data Science_ ?

In this tutorial we will be using **Python 3**. Python is nowadays considered as **"the"** language of choice for Data Science. 
There are indeed many reasons for that, and many articles have been written on the subject. 
This [article](https://analyticsindiamag.com/heres-why-python-continues-to-be-the-language-of-choice-for-data-scientists/) looks like a good and clear example on the topic.

#### A Few notes before we start

* `Q:` _Yes, ok.. but.. is this a tutorial on Data Science?_
* `A:` **No**. This is a **tutorial** on programming with Python. The _perspective_ though is of a _wanna-be_ data scientists.

* `Q:` _Cool... but.. is this a tutorial on the Python Language ?_
* `A:` **Ehm, No again. Sorry**. 
We will focus on programming concepts _using_ Python as a language. Most of the concepts you will learn are shared in most of other languages (_just the syntax will be different, ed. _) _Although_ there is a section in the Lecture materials named `Python Extras` that is **specifically** focusing on features of the Python language. You could read it, if interested :)

#### Here is what I had in mind for this course (HTH)

![lecture sketch](./images/lectures_sketch.png)

_I do hope that this (very simple) mind-map look-alike clarifies a bit the perspective I chose when I thought about this course._

`tl,dr;` We will dive into programming focusing on two main aspects: the _Algorithmic_ perspective, that is "what are the steps we need to implement to solve a specific problem", and the _Data Structure_ perspective, that is "what is the data structure that would simplify as much as possible our algorithm implementation". These two perspectives led in the past decades to two completely different approaches to programming: **Procedural** vs **Object-Oriented**, respectively.

Python allows for _a lot_ of flexibility, and this flexibility will be our [swiss-knife](https://www.ctotech.io/blog/python/why-python3-insights-in-the-swiss-army-knife-of-coding/). In fact, Python supports _multiple programming paradigms_ at once (i.e _imperative_, _OOP_, _functional_ [1]), and we will be (seemingly) shifting our focus on those as we go along with the lecture materials.

---

`1`: functional programming only for the intrepid programmers of you :) See this [video](https://www.youtube.com/watch?v=ThS4juptJjQ)



# Lecture Materials

Course materials consists of three main parts:

### Introductory Readings (`intro` folder)

This part will introduce to the concept of computer programming, and to the 
very basics of the Python programming language:

1. [The Way of the Program](intro/1-the-way-of-the-program.html)
2. [Variables, Statements and Expressions](intro/2-variables-statements-expressions.html)
3. [Introduction to Functions](intro/3-intro-functions.html)
4. [Setting up an editor](intro/4-setup-editor.html)
5. [Conditional Statements](basics/5-conditionals.html)

Regardless you have already programmed before, using Python or not,  I would suggest to take a look at this introductory section anyway. There is always time to **skip**, based on your learning pace.

**Alternatively**, a good starting point would be this online course: [Intro to Python by Microsoft](https://docs.microsoft.com/en-us/learn/modules/intro-to-python/)

### Programming with Python (`programming_with_python` folder)
This section contains the materials for the main topics that will be covered during our two-hours lecture. These are (in no specific order):

1. [Pythonic Functions](programmin_with_python/functions.ipynb)
2. [Collections and Sequences](programmin_with_python/collections.ipynb)
3. [Dictionaries](programmin_with_python/dictionaries.ipynb)
4. [Iterators, Generators, Comprehensions](programmin_with_python/iterators.ipynb)
5. [Classes and OOP](programmin_with_python/classes.ipynb)
6. [Errors and Exceptions](programming_with_python/exceptions.ipynb)

###  Python Extras (`pyhton_extras` folder)
This section contains some extra notebooks you could go through to read more about some specific aspects of the Python programming language. 

**Note:** This is the only part of the course spefically focused on _how Python_ does things

1. [Modules](python_extras/modules.ipynb)
2. [Python Data Model](python_extras/data-model.ipynb)
3. [Function as Objects](python_extras/functions-objects.ipynb)
4. [Magic Methods](python_extras/magic.ipynb)
5. [ Pythonic Coding Style](python_extras/pep8.ipynb)