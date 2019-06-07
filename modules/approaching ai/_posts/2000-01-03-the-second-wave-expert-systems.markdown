---
title: The Second Wave꞉ Expert Systems
---

# The Second Wave꞉ Expert Systems

<br>
Though AI research suffered drastic cuts in the AI winter of the 1970s, research progress did continue, albeit at a slower rate. One particularly promising area of research was the development of <b>expert systems</b>, computer programs that emulated the decision-making ability of human experts.

<br>
To answer questions or solve problems within a specific domain, expert systems stored “if-then” rules derived from the knowledge of experts. For example, a simple medical diagnosis system might include the following rules:
<ol>
  <li>If the patient has a fever and a rash of small red bumps, then the patient has chickenpox or measles.</li>
  <li>If Rule 1 is satisfied and the patient has small white spots inside of their mouth, then the patient has measles.</li>
</ol>

The system could then ask the user questions to narrow down which rules apply to the patient and thus narrow down a diagnosis. For example, using the above rules:

```
>>> Does the patient have a fever?
Yes
>>> Does the patient have a rash of small red bumps?
Yes
>>> Does the patieht have small white spots on the inside of their mouth?
No
>>> The patient has chickenpox.
```

<br>
Unlike the AI of earlier decades, expert systems demonstrated high potential to be <i>useful.</i> A system called <i>Dendral</i> identified compounds from spectrometer readings, and another system called <i>MYCIN</i> diagnosed infectious blood diseases.

<br>
<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/bro6fkDxCUE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
  <small>A sample MYCIN session.</small>
</center>

<br>
Finally, in 1980, an expert system called <i>XCON</i> saved a company 40 million dollars annually, thereby redeeming the reputation of AI to funders. This time, it was not just AI research that received funding -- the commercialization of AI had become a reality.

<br>
However, the profitability of expert systems was brief. The bubble burst suddenly in 1987, when Apple and IBM’s general-purpose desktop computers became more powerful than the expensive specialized software upon which many expert systems were built. Earlier successful expert systems like XCON proved too expensive to maintain, in addition to being difficult to improve, and funding again disappeared from the AI community.
