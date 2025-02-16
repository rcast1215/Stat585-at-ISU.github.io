---
layout: blog
topic: "01"
short-topic: Asking Good Questions
due-date: 2022-01-27
root: ../../
---

## Prompt:

Asking good questions is a valuable skill to have - asking questions in an online setting is both easier and harder than asking questions in person: we can prepare to ask a question but we are also expected to prepare.
The links posted here give some advice on how to ask good questions:

- stackoverflow's [Asking a good question](http://stackoverflow.com/help/how-to-ask)

- R's [Posting guidelines](https://www.r-project.org/posting-guide.html)

- [minimal complete verifiable example](https://stackoverflow.com/help/mcve), [minimal reproducible example](https://www.tidyverse.org/help/)

Follow these links and read through the advice given, then

1. **Pick at least one question from stackoverflow or the R help and answer it.**

Write a blog post answering the following questions: 

2. **Document which question you answered (link to your answer).**
Below is the question I chose to answer on Stackoverflow. 
[https://stackoverflow.com/questions/70846054/using-dplyr-for-filtering/70871432#70871432] (using dplyr for filtering)

3. **Relate your experience of answering the question to your reading. **
My experience answering this question
  - **Title**: In my openion, the individual provided an appropriate title to the question asked. This gave me a foreknowledge of what to expect. 
  - **Body**: The individual provided an explanation of his challenge. Including the Error message and a code was useful. 
  - **Reproducibility**: Even though the individual included a code, I received a different Erro message when I tried to reproduce the code. I was able to answer this question because of the code provided. This would've been impossible in complicated situations. 
 

<!--Go to [https://github.com/Stat585-at-ISU/blog](https://github.com/Stat585-at-ISU/blog) for instructions about how to prepare and submit your blog post.-->
Instructions to follow.


{% assign num_posts = site.blog | size %}
{% if num_posts > 0 %}
## Class posts:

<ul>
{% for post in site.blog %}
  {% if page.topic == post.topic %}
  <li><a href="{{ post.url }}">{{ post.title }} by {{ post.author }}</a></li>
  {% endif %}
{% endfor %}
</ul>
{% endif %}
