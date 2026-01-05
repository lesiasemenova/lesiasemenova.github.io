---
layout: page
permalink: /teaching/
title: teaching
#description: Materials for courses you taught. Replace this text with your description.
nav: true
nav_order: 4
---


<div style="text-align:center; margin: 2rem 0 1.5rem 0;">
  <h1 style="margin-bottom:0.25rem;">Interpretable and Explainable AI</h1>
  <div style="font-size:1.05rem; opacity:0.85;">Course for Graduate students, Spring 2026</div>
</div>

<section>
  <p>
    Machine learning models increasingly shape decisions that affect real people: medical diagnoses, hiring and lending decisions,
    content moderation, legal risk assessment, and scientific discovery. At the same time, the models we rely on, including deep neural networks,
    foundation models, and large language models, are becoming more complex, less transparent, and harder to reason about.
    This tension raises a fundamental question: how can we understand, trust, and responsibly deploy models whose internal logic is
    opaque, fragile, or underspecified?
  </p>

  <p>
    Interpretability and explainability aim to address this question. Many widely used explanation
    methods are heuristic, poorly evaluated, or misleading when used outside their intended scope. Explanations can be manipulated,
    disagreed upon, or give a false sense of understanding. Meanwhile, regulatory pressure (e.g., accountability and transparency requirements),
    safety concerns, and the rise of LLMs have made these issues impossible to ignore.
  </p>

  <p><strong>This course is motivated by three observations:</strong></p>

  <ol>
    <li>
      <strong>Accuracy alone is no longer sufficient.</strong><br/>
      In many applications, we need to debug models, detect spurious correlations, ensure robustness, justify decisions, and reason about
      failures—not just optimize performance metrics.
    </li>
    <li>
      <strong>Not all explanations are created equal.</strong><br/>
      Different stakeholders (developers, domain experts, decision subjects, regulators) require different kinds of understanding. A method
      that is useful for model debugging may be harmful or meaningless for user-facing explanations.
    </li>
    <li>
      <strong>Multiplicity and underspecification are fundamental, not edge cases.</strong><br/>
      Many distinct models can fit the same data equally well yet behave very differently. Understanding this Rashomon effect is essential
      for interpretability, fairness, and trustworthiness, especially in modern overparameterized models.
    </li>
  </ol>

  <p><strong>The goal of this course is therefore not to catalog intepretability or explanability methods, but to develop judgment:</strong></p>

  <ul>
    <li>When should we prefer inherently interpretable models over post-hoc explanations?</li>
    <li>What do popular methods like SHAP or LIME actually guarantee and what do they not?</li>
    <li>How do explanations interact with robustness, fairness, or privacy?</li>
    <li>What does “understanding” mean for large language models and other generative systems?</li>
    <li>How should understadability be evaluated, and for whom?</li>
  </ul>

  <p>
    By the end of the course, students should be able to critically assess interpretability claims, choose appropriate methods for a given
    context, and reason clearly about the limits of explanation in modern AI systems.
  </p>
</section>

<strong>Office hours.</strong> After class. I’m usually happy to stay for ~20 minutes after class for quick questions or to discuss project ideas, paper selection, or course logistics. For longer discussions, please follow up by email.

<strong>Prerequisites.</strong> This is a graduate-level course. Students should be comfortable with basic linear algebra, probability, and core machine learning concepts. You should also be able to implement and debug ML experiments in Python (e.g., NumPy, scikit-learn, and PyTorch), including working with real datasets and writing reasonably organized, reproducible code.





<!--I have formal pedagogical training in college teaching from Duke Graduate School.
I served as a Teaching Assistant for the following classes:

<ul>
  <li>CS474, Data Science Competition, SP23, Duke University</li>
  <li>Terng Lecture Course on Interpretable Machine Learning, May 2022, Institute of Advanced Study</li>
  <li>CS474, Data Science Competition, SP22, Duke University</li>
  <li>CS474, Data Science Competition, SP21, Duke University</li>
  <li>CS571, Probabilistic Machine Learning, SP18, Duke University</li>
  <li>CS101, Introduction to Computer Science, SP17, Duke University</li>
</ul>-->
