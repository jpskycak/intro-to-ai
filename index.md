---
layout: index
published: true
---
<!-- css taken from https://stackoverflow.com/questions/4098195/can-ordered-list-produce-result-that-looks-like-1-1-1-2-1-3-instead-of-just-1 -->
<head>
    <style type="text/css">
    ol {
    counter-reset: item;
    }
    ol li {
        display: block;
        position: relative;
    }
    ol li:before {
        content: counters(item, ".")".";
        counter-increment: item;
        position: absolute;
        margin-right: 100%;
        right: 10px; /* space between number and text */
    }
    </style>
</head>
<div style="width:100%; max-width:400px; margin:auto">
<ol>
 <li><b>Approaching AI</b>
    <ol>
      <li><a href='https://aihigh.github.io/intro-to-ai/modules/approaching ai/what-is-ai/'>What is AI?</a></li>
      <li><a href='https://aihigh.github.io/intro-to-ai/modules/approaching ai/the-first-wave-reasoning-as-search/'>The First Wave: Reasoning as Search</a></li>
      <li><a href='https://aihigh.github.io/intro-to-ai/modules/approaching ai/the-second-wave-expert-systems/'>The Second Wave: Expert Systems</a></li>
      <li><a href='https://aihigh.github.io/intro-to-ai/modules/approaching ai/the-third-wave-computation-power-neural-networks/'>The Third Wave: Computation Power and Neural Networks</a></li>
      <li><a href='https://aihigh.github.io/intro-to-ai/modules/approaching ai/cutting-through-the-hype/'>Cutting Through the Hype</a></li>
    </ol>
  </li>
<li><b>Coding Bootcamp</b>
    <ol>
      <li><a href='https://aihigh.github.io/intro-to-ai/modules/coding bootcamp/getting-started-in-colab/'>Getting Started in Colab</a></li>
      <li><a href='https://aihigh.github.io/intro-to-ai/modules/coding bootcamp/strings-ints-floats-booleans/'>Strings, Ints, Floats, and Booleans</a></li>
      <li><a href='https://aihigh.github.io/intro-to-ai/modules/coding bootcamp/lists-dictionaries-arrays/'>Lists, Dictionaries, and Arrays</a></li>
      <li><a href='https://aihigh.github.io/intro-to-ai/modules/coding bootcamp/if-while-for/'>If, While, and For</a></li>
      <li>Functions</li>
      <li>DataFrames and Storage</li>
      <li>Runtime Estimation and Speed Optimization</li>
      <li>Additional Practice</li><!-- part of succeeding in tech is taking it upon yourself to find additional practice when there are topics you're fuzzy on. link to khan academy, codecademy, etc -->
    </ol>
  </li>
<li><b>Early AI</b>
    <ol>
        <li>Towers of Hanoi</li>
        <li>General Problem Solver</li>
        <li>Monkey and Banana Problem</li>
        <li>Stanford Research Institute Problem Solver</li>
        <li>Parsing Natural Language</li>
        <li>STUDENT</li><!--https://dspace.mit.edu/bitstream/handle/1721.1/6903/AITR-219.pdf?sequence=2&isAllowed=y-->
        <li>ELIZA + DOCTOR script</li>
        <li>Expert Systems</li><!-- won't spend as much time on this because expert systems by definition need a bunch of rules from experts. but we'll go through how expert systems are designed (knowledge base, inference engine) and make a smaller expert system for some situation? -->
    </ol>
</li>
<li><b>Decision Trees and Random Forests</b>
    <ol>
        <li>Classification by Splitting</li>
        <li>One-Hot Encoding and Binary Splitting</li>
        <li>Information Gain and Gini Impurity</li>
        <li>Tree Recursion</li>
        <li>Building a Tree</li>
        <li>Making Predictions</li>
        <li>Overfitting and Cross-Validation</li>
        <li>Pruning</li>
        <li>Random Forests</li>
    </ol>
  </li>
<li><b>Neural Networks</b>
    <ol>
        <li>Single-Layer Perceptron Architecture</li>
        <li>Preparing a Cat or No Cat Image Database</li>
        <li>Backpropagation</li>
        <li>Hyperparameters</li>
        <li>Limits of Single-Layer Perceptrons</li>
        <li>Multi-Layer Perceptron Architecture</li>
        <li>Multi-Class Perceptrons</li><!-- put dog images in as well >> cat, dog, or neither? -->
        <li>States and Actions in Snake</li>
        <li>Solving Snake with Genetic Algorithms</li><!-- https://theailearner.com/2018/11/09/snake-game-with-genetic-algorithm/ | https://www.youtube.com/watch?v=R9OHn5ZF4Uo -->
    </ol>
  </li>
</ol>
</div>
