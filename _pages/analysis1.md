---
layout: page
title: Übungsbuch Analysis I
permalink: /study-books/analysis-i/
description: Exercises with hints, model solutions and practice exams for Analysis I
nav: false
---

<img src="{{ '/assets/img/publication_preview/analysis1.jpg' | relative_url }}" alt="Cover of Übungsbuch Analysis I" style="float: right; width: 220px; max-width: 40%; margin: 0 0 1rem 1.5rem;" class="rounded z-depth-1">

[Übungsbuch Analysis I](https://link.springer.com/book/10.1007/978-3-662-64569-7) offers a comprehensive collection of almost 500 exercises, designed to help students work on their exercise sheets, review the lecture material and prepare for exams. The book is written in German and is divided into four parts: exercises, hints, model solutions and practice exams.

## How the book works

Imagine you are attending an Analysis I lecture on the convergence of series, or you have an exercise sheet on this topic due. To deepen your understanding and practice convergence tests, you choose Exercise 57 (a):

> **Exercise 57.** Determine whether the series $$\sum_{n=0}^{\infty} \left(\frac{1}{7}\right)^n$$ converges.

You look up all the convergence tests from the lecture, but you are not sure which one to use. So you turn to the hint for Exercise 57:

> **Hint for Exercise 57.** The series converges by the [root test](https://en.wikipedia.org/wiki/Root_test) or the [ratio test](https://en.wikipedia.org/wiki/Ratio_test). Set $$x_n = (1/7)^n$$ for $$n \in \mathbb{N}_0$$ and observe that $$\sqrt[n]{|x_n|} = 1/7$$ and $$|x_{n+1} / x_n| = 1/7$$.

With this hint, you can solve the exercise on your own. If you still have doubts, you can compare your work with the model solution in the book:

> **Solution to Exercise 57.** The series converges by the root test or the ratio test. We set $$x_n = (1/7)^n$$ for $$n \in \mathbb{N}_0$$. Clearly $$\sqrt[n]{|x_n|} = 1/7$$, so
>
> $$\limsup_{n \to \infty} \sqrt[n]{|x_n|} = \limsup_{n \to \infty} \frac{1}{7} = \frac{1}{7}.$$
>
> Since this limit superior is less than 1, the series converges by the root test. Alternatively, since $$|x_{n+1} / x_n| = 1/7$$, we directly obtain
>
> $$\limsup_{n \to \infty} \left| \frac{x_{n+1}}{x_n} \right| = \frac{1}{7},$$
>
> so the series also converges by the ratio test.

Comparing your work with the model solution lets you confirm that your answer is correct, or see where it needs adjusting.

## Practice exams

At many universities, past exams are available without solutions. That is why this book also contains five practice exams with full solutions. They vary in topics and length, so you can choose the one that best fits your preparation. One of them, for example, has a time limit of 120 minutes, allows no aids such as programmable calculators, and awards up to 55 points. A typical exam problem might read:

> **Problem 1 (8 points).** Let $$x \in \mathbb{R} \setminus \{1\}$$. Prove by induction that for all $$n \in \mathbb{N}$$
>
> $$\sum_{\nu = 0}^{n} \nu x^{\nu - 1} = \frac{1 - x^{n+1}}{(1-x)^2} - \frac{(n+1)x^n}{1-x}.$$

After working through an exam, you can compare your answers with the model solutions in the book. These also show how points are awarded for the individual steps, so even if you only partially solve a problem, you get a realistic idea of how many points you would have earned in a real exam.

[Back to all study books]({{ '/projects/' | relative_url }})
