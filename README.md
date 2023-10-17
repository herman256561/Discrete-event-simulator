Discrete Event Simulator for a buffer
=============
> It's a coursework that aims to simulate a buffer and its performance related to the packets in the queue and the packets that are dropped when the buffer is full.

----------
### How to run the simulator
The simulator contains two main files, "**discrete event simulator_constant_rate.ipynb**" and "**Discrete event simulator_variable_input_rate.ipynb**".
These two files should be executed in Jupyter Notebook.

TXT files will be generated after executing the two simulators. Users need to execute the "**plot_results.py**" file in the terminal to translate the txt files into graphs.

----------
### Introduction of the implementation of my simulator
My simulator can be divided into two main files, the one that simulates constant rate and the other one that simulates the variable input rates. 

In each simulation, a variable y was set to generate a random number between 0 and 1. With variable y, I can simulate individual events by evaluating whether y is larger or smaller than the probability of a packet arriving at the buffer.

By simulating the event 1,000,000 times, the result will be close to a real-world case of a buffer. 

Completed the 1,000,000 times of simulations, the results will be recorded into a text file and will be translated into graphs which will make it easier for us to observe the patterns of experiments.

By observing the results from the experiments, the relationship between the arrival rate, departure rate of a packet, and the buffer size follows a certain pattern. 

The results of experiments such as text files and graphs are stored in the “logs” file. The explanations of the results can be found in **[this report](https://drive.google.com/file/d/1x5jnUg3pf4zwbvlNmS39Cj2HsDAb607d/view?usp=sharing)**. 
The context of this project can be found **[here](https://drive.google.com/file/d/1QWXSbpenz0Xe0Qau0QvVnE13LAc6Sj6m/view?usp=share_link)**.




