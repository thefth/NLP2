---
layout: photolist
title: Syllabus
menu: yes
---

*Spring 2017* &#124; [Spring 2016](2016)

In this course you will apply several machine learning techniques to deal with structure predictions problems related to translation.
Our course is composed of 3 blocks of lectures: lexical alignment (3 lectures), statistical machine translation (4 lectures), and neural machine translation (4 lectures).
We will also have lab sessions related to project assignments.

# Lectures

{% assign lectures = (site.data.2017.intro | where: "selected", "y") %}
{% for lecture in lectures %}
{% include lecture.html lecture=lecture %}
{% endfor %}

## Lexical alignment

{% assign lectures = (site.data.2017.alignment | where: "selected", "y") %}
{% for lecture in lectures %}
{% include lecture.html lecture=lecture %}
{% endfor %}

## Statistical machine translation

{% assign lectures = (site.data.2017.smt | where: "selected", "y") %}
{% for lecture in lectures %}
{% include lecture.html lecture=lecture %}
{% endfor %}

## Neural machine translation

{% assign lectures = (site.data.2017.nmt | where: "selected", "y") %}
{% for lecture in lectures %}
{% include lecture.html lecture=lecture %}
{% endfor %}


# Labs

* Recap (1 session)
    * Calculus: log identities and basic derivatives
    * Probability theory: random variables, rules of probability, basic distributions
    * Probabilistic graphical models: factorisation and representation

* Project 1 (2 sessions)
    * EM for categorical distributions 
    * Forward-Backward

* Project 2 (2 sessions)
    * Bitext parsing
    * Inside-Outside

* Project 3 (3 sessions)
    * FFNN 
    * backpropagation

