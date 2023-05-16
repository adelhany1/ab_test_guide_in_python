# A/B testing: A step-by-step guide in Python
1. Problem Statement – What is the goal of the experiment ? What are the metrics?
2. Hypothesis Testing -  What result do you hypothesize from the experiment? 
3. Design the Experiments – How to select target (users)?
4. Run the Experiments 
5. Validity Checks 
6. Interpret Results  and Launch Decision 

This is a walkthrough of how to design and analyse an A/B test using Python.

https://goldinlocks.github.io/Introduction-to-A-B-testing-in-python/#Introduction-to-A/B-testing

https://github.com/tvasil/ab-testing-intro/blob/master/ironhack_presentation_20200213.ipynb

https://www.optimizely.com/optimization-glossary/ab-testing/

A/B testing is an experiment design and hypothesis testing is a statistical technique for making inferences from data.

The distinction is between how you are collecting data, and how you analyze the results.

In A/B testing you are creating two groups of users. One group will serve as a control the other is the treatment group. We randomly assign the users to one of two groups. This is also called a single blind research design.

Now hypothesis testing is what happens when we want to compare some outcome variable between these two groups from this experiment. We have a null of no difference between the two groups, and we want to see if there is an actual difference.
