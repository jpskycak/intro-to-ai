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
      <li>Strings, Ints, Floats, and Booleans</li>
      <li>Lists, Dictionaries, and Arrays</li>
      <li>For, While, If, and Try</li>
      <li>Functions</li>
      <li>DataFrames and Storage</li>
      <li>Runtime Estimation and Speed Optimization</li>
    </ol>
  </li>
<li><b>Reasoning as Search</b>
    <ol>
        <li>Monkey and Banana Problem</li>
        <li>Stanford Research Institute Problem Solver</li>
        <li>Natural Language Processing</li>
        <li>ELIZA</li>
        <li>STUDENT</li><!--https://dspace.mit.edu/bitstream/handle/1721.1/6903/AITR-219.pdf?sequence=2&isAllowed=y-->
    </ol>
</li>
<li><b>Expert Systems</b>
    <ol>
        <li>Knowledge Base</li>
        <li>Inference Engine</li>
    </ol>
</li>
<li><b>Decision Trees and Random Forests</b>
    <ol>
        <li>Splits</li>
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
        <li>Single-Layer Perceptrons</li>
        <li>Data Preparation</li>
        <li>Backpropagation</li>
        <li>Hyperparameters</li>
        <li>Limits of Single-Layer Perceptrons</li>
        <li>Multi-Layer Perceptrons</li>
        <li>Multi-Class Perceptrons</li>
        <li>States and Actions in Games</li>
        <li>Genetic Algorithms</li><!-- https://theailearner.com/2018/11/09/snake-game-with-genetic-algorithm/ | https://www.youtube.com/watch?v=R9OHn5ZF4Uo -->
    </ol>
  </li>
</ol>
</div>
