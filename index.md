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
  <li>Approaching AI
    <ol>
      <li>What is AI?</li>
      <li>The First Wave: Reasoning as Search</li>
      <li>The Second Wave: Expert Systems</li>
      <li>The Third Wave: Computation Power and Connectionism</li>
      <li>Cutting Through the Hype</li>
    </ol>
  </li>
  <li>Coding Bootcamp
    <ol>
      <li>Getting Started in Colab</li>
      <li>Strings, Ints, Floats, and Booleans</li>
      <li>Lists, Dictionaries, and Arrays</li>
      <li>For, While, If, and Try</li>
      <li>Functions</li>
      <li>DataFrames and Storage</li>
      <li>Runtime Estimation and Speed Optimization</li>
    </ol>
  </li>
  <li>Reasoning as Search</li>
  <li>Expert Systems</li>
  <li>Connectionism</li>
</ol>
</div>
