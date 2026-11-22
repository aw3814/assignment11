## Assignment 11
Random dot motion visualization task, in file DotStim_visualize_assignment11.py

## **The task**

This is a PsychoPy experiment that measures how well a participant can judge the direction of moving dots when the motion is hidden among random noise, and their performance will be visualized by graphs by the end of the experiment. 

On each trial, the participant sees a field of 150 moving dots. Some of the dots (the signal dots) all move in the same direction, either left or right. The rest (the noise dots) each move in their own random direction. The participant presses the left or right arrow key to say which way the overall motion is going.

The proportion of signal dots is called coherence. The task uses five fixed coherence levels, namely 0.05, 0.1, 0.2, 0.4, 0.8. The difficulty of the task decreases as the coherence level increases. 

Each trial starts with a fixation cross shown for a random duration between 0.5 and 1.5 seconds, so the participant can't predict when the dots will appear. The dots stay on screen until the participant responds.

The task measures accuracy at at each coherence level and reaction time of the participant. 

## **How to run it** 
1. Install PsychoPy. 
2. Open DotStim_visualize_assignement11.py in PsychoPy Coder and click Run.
3. In the dialog box, enter the participant number and age, and choose the number of trials (10, 50, 100 or 150).
4. Read the instructions and press Enter to start.
5. Press left or right on each trial. Press Escape to quit early.

The trials are split evenly across the 5 coherence levels and 2 directions, and presented in random order.

## **Output**

At the end of the experiment, the script saves a data file named after the participant number (for example 123_random_dot_motion.xlsx) with one row per trial.

## **Visualizations**

After the task ends, the script shows three graphs of the participant's performance (close each window to see the next):

1. Scatter plot of reaction time by coherence, with points coloured by whether the response was correct.
2. Histogram of reaction times, showing how quickly the participant usually responded.
3. Line graph of accuracy by coherence, which shows the proportion of correct responses at each coherence level, with a dashed line at 50% marking chance performance. Accuracy should rise from near chance at low coherence to near 100% at high coherence. The point where the curve rises shows how sensitive the participant is to motion.
