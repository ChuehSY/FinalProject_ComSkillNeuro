# FinalProject_ComSkillNeuro
Final project files for computational skills neuroscience.
I plan to convert it into python version.

**Input data**
The input data is the behavioral event recorded during brain computer interface (BCI) task. 
The original MATLAB file will compute the basic trial information in that session.
e.g. Successful trial number, Failed trial number Success rate, Reward/minute, average trial time.

**Multiple behavioral data process**
Combine the CSV file of multiple sessions and output the summarization which contains TotalDuration	TotalTrials, Successful Trial Number,	Success Rate,	Reward Frequency PerMin, Average Trial Time

**Plot the neural trajectory in 3 types in single session**
There are 3 type of figure can generate the neural trajectory and calculate the path length in successful trial and failed trial.

----------------------------------
**After the process above, I will label the neuron ensemble in each session**
Within the same field of view, I selected 1-4 neurons as an ensemble. Thus, the BCI task was performing by different ensembles. 
And then I plot the bar chart of every ensemble regarding success rate, reward frequency, averge trial time.
For the bar chart, I also add the n numebr and STD error bar. 
