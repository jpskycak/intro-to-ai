---
layout: index
published: true
---

<!-- css taken from https://stackoverflow.com/questions/4098195/can-ordered-list-produce-result-that-looks-like-1-1-1-2-1-3-instead-of-just-1 -->
<head>
    <style type="text/css">
      ol { counter-reset: item }
      li{ display: block }
      li:before { content: counters(item, ".") " "; counter-increment: item }
    </style>
</head>

<div style="width:100%; max-width:400px; margin:auto">
<ol>
  <li>Approaching AI
    <ul>
      <li>What is AI?</li>
      <li>Seasons of AI</li>
      <li>Cutting Through the Hype</li>
      <li>Machine Learning in General</li>
      <li>Deep Learning in Particular</li>
    </ul>
  </li>
  <li>Coding Bootcamp
    <ul>
      <li>Getting Started in Colab</li>
      <li>Strings, Ints, Floats, and Booleans</li>
      <li>Lists, Dictionaries, and Arrays</li>
      <li>For, While, If, and Try</li>
      <li>Functions</li>
      <li>Pandas</li>
      <li>Storing Data</li>
      <li>Runtime Estimation and Speed Optimization</li>
    </ul>
  </li>
</ol>
</div>
