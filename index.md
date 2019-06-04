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
      <li><a href='https://aihigh.github.io/intro-to-ai/modules/approaching ai/the-third-wave-computation-power-connectionism/'>The Third Wave: Computation Power and Connectionism</a></li>
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
<li><b>Reasoning as Search</b></li>
<li><b>Expert Systems</b></li>
<li><b>Connectionism</b></li>
</ol>
</div>
