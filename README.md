# What is event prediction:
During the execution of process models, it can become interesting to predict future behavior of the currently running process instance.

we are focusing on task prediction, i.e., which task will probably happen next? We have built a prediction system. The general input for
this predictor is a currently running process instance (i.e., an incomplete trace).

How to use the predictor:
1. Put the data file in csv format in the same directory where the predictor is. You can find the data file in .xes format but you will have to convert it into .csv format before you put that in here.
2. Change the json file accordingly. 
3. Open a command line in the directory.

Run below command in the command line.
`python spa_predictor_v1.py`

You will be asked for an instance for which, you want to find the next event for.
Write your instance in the alphabet format.

You will see matrix and visualization plot of the possible events.
