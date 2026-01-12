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
    At the same time, the models we rely on, including deep neural networks, foundation models, and large language models, are becoming
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

<p>
 <strong>Workload.</strong> The class workload will consist of two main components: (1) in-class paper discussions with student-led presentations, and (2) a semester-long course project completed individually or in a small team. The primary deliverable for the course project is a sequence of in-class presentations: a project proposal, a mid-project review, and a final presentation. These presentations (slides + discussion) serve as the main “report” of the project. Teams may optionally submit a longer written report (PDF) with additional technical details, experiments, or analysis.
</p>

 <strong>Schedule.</strong> The schedule below is tentative. Topics, readings, and ordering may be adjusted during the semester based on class interests, guest lectures, and pacing.

 <table style="width:100%; border-collapse:collapse;">
  <thead>
    <tr>
      <th style="border-bottom:1px solid #ccc; padding:0.6rem; text-align:left;">Week</th>
      <th style="border-bottom:1px solid #ccc; padding:0.6rem; text-align:left;">Date</th>
      <th style="border-bottom:1px solid #ccc; padding:0.6rem; text-align:left;">Topic</th>
      <th style="border-bottom:1px solid #ccc; padding:0.6rem; text-align:left;">Details</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding:0.6rem;">1</td>
      <td style="padding:0.6rem;">January 26</td>
      <td style="padding:0.6rem;">Introduction (remote)</td>
      <td style="padding:0.6rem;">Syllabus overview, introduction to interpretability and explainability. <strong> Guest lecture: Alina Jade Barnett fron university of Rhode Island with talk on Inherently Interpretable Neural Networks for Scientific Discovery and High-Stakes Decision Support </strong></td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">2</td>
      <td style="padding:0.6rem;">February 2</td>
      <td style="padding:0.6rem;">Global understanding and the human in the loop</td>
      <td style="padding:0.6rem;">Data visualization, feature importance, exploratory analysis; stakeholders, use cases, and failure modes</td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">3</td>
      <td style="padding:0.6rem;">February 9</td>
      <td style="padding:0.6rem;">Interpretability and explainability landscape &amp; project directions</td>
      <td style="padding:0.6rem;">Overview of project spaces: interpretable models, post-hoc explanations, counterfactuals and recourse, mechanistic interpretability, large language models, and model multiplicity (Rashomon effect)</td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">4</td>
      <td style="padding:0.6rem;">February 16</td>
      <td style="padding:0.6rem;">Inherently interpretable models</td>
      <td style="padding:0.6rem;">Linear models, sparsity, generalized additive models, scoring systems, decision trees, and rule-based models. <strong> Guest lecture: Hayden McTavish and Varun Babbar from Duke University with talk on modern algorithms of decision trees </strong></td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">5</td>
      <td style="padding:0.6rem;">February 23</td>
      <td style="padding:0.6rem;">Inherently interpretable models &amp; project proposals</td>
      <td style="padding:0.6rem;">Prototype-based and concept-based approaches; project proposal presentations</td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">6</td>
      <td style="padding:0.6rem;">March 2</td>
      <td style="padding:0.6rem;">Post-hoc explanations I: feature and data attributions</td>
      <td style="padding:0.6rem;">What feature attributions approximate; local vs. global explanations; LIME, SHAP, gradient-based methods; assumptions and common misuse</td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">7</td>
      <td style="padding:0.6rem;">March 9</td>
      <td style="padding:0.6rem;">Post-hoc explanations II: evaluation and pitfalls</td>
      <td style="padding:0.6rem;">Explanation disagreement, sensitivity to baselines and perturbations, sanity checks, manipulation and robustness</td>
    </tr>

    <tr>
      <td style="padding:0.6rem;"></td>
      <td style="padding:0.6rem;">March 16</td>
      <td style="padding:0.6rem;">Spring break</td>
      <td style="padding:0.6rem;">No class</td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">8</td>
      <td style="padding:0.6rem;">March 23</td>
      <td style="padding:0.6rem;">Counterfactual explanations and algorithmic recourse</td>
      <td style="padding:0.6rem;">Counterfactual definitions; actionability and feasibility; robustness and human constraints</td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">9</td>
      <td style="padding:0.6rem;">March 30</td>
      <td style="padding:0.6rem;">Mechanistic interpretability &amp; mid-project updates</td>
      <td style="padding:0.6rem;">Representations, features, and circuits; how mechanistic interpretability differs from post-hoc explanations; mid-project updates</td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">10</td>
      <td style="padding:0.6rem;">April 6</td>
      <td style="padding:0.6rem;">Mechanistic interpretability and large language models</td>
      <td style="padding:0.6rem;">LLM internals; probing vs. circuits; steering vs. understanding; limits of current approaches</td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">11</td>
      <td style="padding:0.6rem;">April 13</td>
      <td style="padding:0.6rem;">Understanding and reasoning in large language models</td>
      <td style="padding:0.6rem;">Chain-of-thought and explanation-based prompting; faithfulness vs. usefulness of explanations; reasoning, abstraction, and failure modes</td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">12</td>
      <td style="padding:0.6rem;">April 20</td>
      <td style="padding:0.6rem;">Multiplicity, underspecification, and the Rashomon effect</td>
      <td style="padding:0.6rem;">Model sets rather than single models; why explanations do not resolve ambiguity; implications for fairness and trust</td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">13</td>
      <td style="padding:0.6rem;">April 27</td>
      <td style="padding:0.6rem;">Interpretability, trustworthiness, and deployment</td>
      <td style="padding:0.6rem;">Fairness, robustness, privacy, unlearning; regulation, accountability, and open problems</td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">14</td>
      <td style="padding:0.6rem;">May 4</td>
      <td style="padding:0.6rem;">Final project presentations</td>
      <td style="padding:0.6rem;">In-class final presentations</td>
    </tr>
  </tbody>
</table>


  <!--<p>
    At the same time, many widely used explanation methods are heuristic, poorly evaluated, or misleading when used outside their
    intended scope. Explanations can be manipulated, disagreed upon, or give a false sense of understanding. Meanwhile, regulatory
    pressure (e.g., accountability and transparency requirements), safety concerns, and the rapid adoption of LLMs have made these
    issues impossible to ignore.
  </p>-->

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
