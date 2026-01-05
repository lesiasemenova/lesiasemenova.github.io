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
    content moderation, legal risk assessment, and scientific discovery.
  </p>

  <p>
    At the same time, the models we rely on—including deep neural networks, foundation models, and large language models—are becoming
    more complex, less transparent, and harder to reason about. This tension raises a fundamental question:
    <em>how can we understand, trust, and responsibly deploy models whose internal logic is opaque, fragile, or underspecified?</em>
  </p>

  <p>
    Three distinct paradigms have emerged in response. <strong>Interpretable AI</strong> focuses on designing models that are inherently
    understandable; <strong>Explainable AI (XAI)</strong> seeks to provide post-hoc summaries of complex “black-box” models; and
    <strong>Mechanistic Interpretability</strong> attempts to reverse-engineer the internal circuits of neural networks.
    These approaches offer different guarantees and serve different goals.
  </p>

  <p>
    At the same time, many widely used explanation methods are heuristic, poorly evaluated, or misleading when used outside their
    intended scope. Explanations can be manipulated, disagreed upon, or give a false sense of understanding. Meanwhile, regulatory
    pressure (e.g., accountability and transparency requirements), safety concerns, and the rapid adoption of LLMs have made these
    issues impossible to ignore.
  </p>

  <p>
    This course is motivated by three observations: (i) accuracy alone is no longer sufficient; (ii) not all explanations are created
    equal; and (iii) many distinct models can fit the same data equally well yet behave very differently. Understanding these effects
    (often referred to as the <em>Rashomon effect</em>) is essential for building trustworthy machine learning systems, especially in
    modern overparameterized models.
  </p>

  <p>
    <strong>The goal of this course is therefore not merely to introduce a collection of interpretability and explainability methods,
    but to develop judgment:</strong>
  </p>

  <ul>
    <li>When should we prefer inherently interpretable models over post-hoc explanations?</li>
    <li>What do popular methods like SHAP or LIME actually guarantee, and what do they not?</li>
    <li>How do explanations interact with robustness, fairness, or privacy?</li>
    <li>How do we move from treating models as black boxes toward mechanistic interpretability and circuit-level understanding?</li>
    <li>What does “understanding” mean for large language models and other generative systems?</li>
    <li>How should understandability be evaluated, and for whom?</li>
  </ul>

  <p>
    By the end of the course, students should be able to critically assess interpretability claims, choose appropriate methods for a
    given context, and reason clearly about the limits of explanation in modern AI systems.
  </p>
</section>

<p><strong>Time and room.</strong> Mondays 12:10–3:10 pm, Busch Campus.</p>

<p>
  <strong>Prerequisites.</strong> This is a graduate-level course. Students should be comfortable with basic linear algebra,
  probability, and core machine learning concepts. You should also be able to implement and debug ML experiments in Python
  (e.g., NumPy, scikit-learn, and PyTorch), including working with real datasets and writing reasonably organized, reproducible code.
</p>


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
