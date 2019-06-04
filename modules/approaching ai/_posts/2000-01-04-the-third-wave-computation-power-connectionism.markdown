---
title: The Third Wave꞉ Computation Power and Connectionism
---

# The Third Wave꞉ Computation Power and Connectionism

<br>
Though AI suffered another round of funding cuts in the late 1980s and early 90s, increases in computation power would soon bring AI back into the public eye. The number of transistors on an integrated circuit chip, a generally accepted proxy for computation power, had been roughly doubling every two years since the early 1970s in a trend known as <b>Moore’s law</b>. From the early 70s to the early 90s, the number of transistors per chip rose from a thousand to a million, meaning that 90s computers were roughly a thousand times more powerful than those of the 70s.

<br>
The tremendous increase in computation power led to tremendous increases in the performance of AI. In 1997, <i>Deep Blue</i>, a chess-playing system 10 million times faster than those of the 1950s, succeeded in beating the world chess champion. In 2007, Carnegie Mellon researchers developed a vehicle that autonomously navigated 55 miles in an urban environment while adhering to traffic hazards and all traffic laws. In 2009, IBM’s question answering system, <i>Watson</i>, defeated two <i>Jeopardy!</i> champions by a significant margin.

<br>
Advancements in computer hardware also made it feasible to create useful connectionist models, which had not performed so well in past decades due to a lack of necessary computation power. <b>Connectionist models</b> consisted of many simple processing units connected together in a way that enabled them to accomplish complicated tasks, and extensive computation power was necessary to search for the right connectivity configurations.

<br>
The appeal of connectionist models was that they “learned” to perform tasks without any prior knowledge. For example, to detect whether an image contains a cat, a connectionist model would start with some random connectivity configuration. Then, using a dataset of example images that have been manually labeled as "cat" or "no cat," the network would be <b>trained</b> through many repetitions. 

<br>
Each training repetition would consist of two phases, a prediction phase and an adjustment phase. In the prediction phase, an image would be supplied as input to the model, the model’s units would perform computations according to their connectivity, and an output unit would predict whether the image had a cat based on the results of those prior computations. Then, in the adjustment phase, the model’s prediction would be compared to the true label on the image, each connection’s contribution to the prediction would be computed, and the connections would be adjusted so as to strengthen connections supporting a correct prediction or weaken connections supporting an incorrect prediction.

<br>
After many training repetitions, the model’s connectivity would adjust to respond more favorably to images containing cat-identifying characteristics such as fur, tails, whiskers, and cat-like faces. In a sense, then, the model would have “learned” how to recognize a cat.

<br>
Unfortunately, the training process for connectionist models was rather computationally intensive: many units and connections were needed, many computations had to be done for each training repetition, and many training repetitions were required in order for the model to begin to converge on a suitable connectivity configuration for a task. As a result, the models were unable to undergo sufficient training on the relatively slow computers of the 1970s.

<br>
As computation power increased, though, connectionist models such as <b>artificial neural networks</b> began to take center stage in AI. Artificial neural networks were loosely based on the brain, which exhibits many layers of neurons connected by synapses. A key turning point occurred in 2009, when <b><i>deep</i> neural networks</b> (i.e. artificial neural networks consisting of many layers of units) were trained using <b>graphics processing units</b> or <b>GPUs</b>, a type of computer hardware specialized for running many computations in parallel.
