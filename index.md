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
<div style="width:100%; max-width:500px; margin:auto">
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
      <li><a href='https://aihigh.github.io/intro-to-ai/modules/coding bootcamp/functions/'>Functions</a></li>
      <!--<li><a href='https://aihigh.github.io/intro-to-ai/modules/coding bootcamp/files/'>Files</a></li>-->
      <!--<li><a href='https://aihigh.github.io/intro-to-ai/modules/coding bootcamp/dataframes-storage/'>DataFrames and Storage</a></li>
      <li>Runtime Estimation</li>
      <li>Coding Challenges</li>--><!-- in these tutorials, you've mostly been modifying code to understand how it works. This is good for introduction. Now we'll take what we've learned and take it a step further with coding challenges. Goal is to get to an intermediate level of coding ability. We'll begin with some elementary challenges and they'll get harder. Expect to spend more time on these next 2 sections, and expect to refer back to the previous sections a lot. a notebook of problems such as compute the first 100 primes. Hints in a second notebook. -->
    </ol>
  </li>
<li><b>Early AI</b>
    <ol>
        <li><a href='https://aihigh.github.io/intro-to-ai/modules/early ai/solving-towers-of-hanoi-with-general-problem-solver/'>Solving Towers of Hanoi with General Problem Solver</a></li>
        <li>Solving Monkey and Banana Problem with Stanford Research Institute Problem Solver</li>
        <li>Solving Math Word Problems with STUDENT</li><!--https://dspace.mit.edu/bitstream/handle/1721.1/6903/AITR-219.pdf?sequence=2&isAllowed=y-->
        <li>Attempting the Turing Test with ELIZA + DOCTOR Script</li>
        <li>Expert Systems</li><!-- won't spend as much time on this because expert systems by definition need a bunch of rules from experts. but we'll go through how expert systems are designed (knowledge base, inference engine) and make a smaller expert system for some situation? -->
    </ol>
</li>
<li><b>Decision Trees and Random Forests</b>
    <ol>
        <li>Classification, Splitting, Impurity, and One-Hot Encoding</li>
        <li>Recursively Building a Decision Tree</li>
        <li>Overfitting and Cross-Validation</li>
        <li>Pruning and Random Forests</li>
    </ol>
  </li>
<li><b>Neural Networks</b>
    <ol>
        <li>Preparing a Cat or No Cat Image Database</li>
        <li>Single-Layer Perceptron and Backpropagation</li>
        <li>Detecting Cats with a Single-Layer Perceptron</li>
        <li>Limits of Single-Layer Perceptrons</li>
        <li>Detecting Cats with Multi-Layer Perceptrons</li>
        <li>Detecting Animal Types with Multi-Class Perceptrons</li><!-- put dog images in as well >> cat, dog, or neither? -->
        <li>Solving Snake with Genetic Algorithms</li><!-- https://theailearner.com/2018/11/09/snake-game-with-genetic-algorithm/ | https://www.youtube.com/watch?v=R9OHn5ZF4Uo -->
    </ol>
  </li>
</ol>
</div>
