---
title: The Third Wave꞉ Computation Power and Neural Networks
---

# The Third Wave꞉ Computation Power and Neural Networks

<br>
Though AI suffered another round of funding cuts in the late 1980s and early 90s, increases in computation power would soon bring AI back into the public eye. The number of transistors on an integrated circuit chip, a generally accepted proxy for computation power, had been roughly doubling every two years since the early 1970s in a trend known as <b>Moore’s law</b>. From the early 70s to the early 90s, the number of transistors per chip rose from a thousand to a million, meaning that 90s computers were roughly a thousand times more powerful than those of the 70s.

<br>
<center>
  <iframe width="80%" height="315" src="https://www.youtube.com/embed/aWLBmapcJRU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>

<br>
The tremendous increase in computation power led to tremendous increases in the performance of AI. In 1997, <i>Deep Blue</i>, a chess-playing system 10 million times faster than those of the 1950s, succeeded in beating the world chess champion.

<br>
<center>
  <iframe width="80%" height="315" src="https://www.youtube.com/embed/KF6sLCeBj0s" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>

<br>
In 2011, IBM’s question answering system, <i>Watson</i>, defeated two <i>Jeopardy!</i> champions by a significant margin.

<br>
<center>
  <iframe width="80%" height="315" src="https://www.youtube.com/embed/P18EdAKuC1U" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>

<br>
Advancements in computer hardware also made it feasible to create useful <b>neural networks</b>, a type of model loosely based on the brain which exhibits many layers of neurons connected by synapses. Neural networks consisted of many simple processing units or <b>neurons</b> connected together at various strengths or <b>weights</b>, in a way that enabled them to accomplish complicated tasks.

<br>
The appeal of neural networks was that they “learned” to perform tasks without any prior knowledge. For example, to detect whether an image contains a cat, a neural network would start with random weights. Then, using a dataset of example images that have been manually labeled as "cat" or "no cat," the network would be <b>trained</b> through many repetitions or <b>batches</b>. 

<br>
Each training batch would consist of two phases, a prediction phase and a weight update phase. In the prediction phase, an image would be supplied as input to the neural network, the neurons would perform computations while interacting according to their connection weights, and an output neuron would predict whether the image had a cat based on the results of those prior computations. After several rounds of this prediction process, the update phase would begin. In the weight update phase, the neural network's predictions would be compared to the true labels on the images, and each connection’s contribution to the predictions would be computed using an algorithm called <b>backpropagation</b>. Then connection weights would be adjusted so as to strengthen connections contributing to a correct prediction or weaken connections contributing to an incorrect prediction.

<br>
After many training batches, the neural network's connectivity would adjust to respond more favorably to images containing cat-identifying characteristics such as fur, tails, whiskers, and cat-like faces. In a sense, then, the model would have “learned” how to recognize a cat.

<br>
<center>
  <iframe width="80%" height="315" src="https://www.youtube.com/embed/aircAruvnKk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>

<br>
Unfortunately, the training process for neural networks was rather computationally intensive: many neurons and connections were needed, many computations had to be done for each weight update phase, and many training batches were required in order for the neural network to begin to converge on a suitable connectivity configuration for a task. As a result, neural networks were unable to undergo sufficient training on the relatively slow computers of the 1970s.

<br>
As computation power increased, though, neural networks began to take center stage in AI. A key turning point occurred in 2009, when <b><i>deep</i> neural networks</b> (i.e. neural networks consisting of many layers of units) were trained using <b>graphics processing units</b> or <b>GPUs</b>, a type of computer hardware specialized for running many computations in parallel.
