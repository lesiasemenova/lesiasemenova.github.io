---
layout: page
permalink: /ixai_spring2026/
inline: true
title: ixai_spring2026
related_posts: false
nav: false
---

<div style="text-align:center; margin: 2rem 0 1.5rem 0;">
  <h1 style="margin-bottom:0.25rem;">Interpretable and Explainable AI</h1>
  <div style="font-size:1.05rem; opacity:0.85;">Course for Graduate students, Spring 2026</div>
</div>

<section>
  <p>
    Machine learning models increasingly shape decisions that affect real people: medical diagnoses, hiring, legal and lending decisions,  scientific discovery to name a few.
    At the same time, the models we rely on due to their black-box nature are becoming
    more complex, less transparent, and harder to interpret. This tension raises a fundamental question:
    <em>how can we understand, trust, and responsibly deploy models whose internal logic is opaque, easy to trick,  and might be right for the wrong reasons?</em>
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
     is essential for building trustworthy machine learning systems.
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

<p><strong>Time and room.</strong> Mondays 12:10–3:10 pm, Busch Campus, SEC-210 (T. Alexander Pond SERC Science & Engineering Resource Center)</p>

<p>
  <strong>Prerequisites.</strong> This is a graduate-level course. Students should be comfortable with basic linear algebra,
  probability, and core machine learning concepts. You should also be able to implement and debug ML experiments in Python
  (e.g., NumPy, scikit-learn, and PyTorch), including working with real datasets and writing reasonably organized, reproducible code.
</p>

<p>
 <strong>Workload.</strong> The class workload will consist of two main components: (1) in-class paper discussions with student-led presentations, and (2) a semester-long course project completed individually or in a small team. The rubric is: paper presentation 30%, engagement during the class 20%, project 50%. Paper presentations by students will start from week 4. <strong>Syllabus:
  <a href="/assets/pdf/ixai_spring2026_syllabus.pdf" target="_blank">
    CS 671 Interpretable and Explainable AI – Spring 2026 (PDF)
  </a> </strong>.

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
      <td style="padding:0.6rem;">Introduction. Remote: <a href = 'https://rutgers.zoom.us/j/97741773620?pwd=k0vmc1mk8sbilfX6R6UXapFCKPib61.1&from=addon'>Zoom Meeting URL</a>, Meeting ID: 977 4177 3620, Passcode: 891706</td>
      <td style="padding:0.6rem;">Syllabus overview, introduction to interpretability and explainability. Reading: Doshi-Velez and Kim, 2017, <a href="https://arxiv.org/abs/1702.08608">Towards a Rigorous Science of Interpretable Machine Learning</a> <strong> Guest lecture: Alina Jade Barnett from University of Rhode Island with talk on Inherently Interpretable Neural Networks for Scientific Discovery and High-Stakes Decision Support </strong> </td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">2</td>
      <td style="padding:0.6rem;">February 2</td>
      <td style="padding:0.6rem;">Global understanding and the human in the loop</td>
      <td style="padding:0.6rem;">Data visualization, feature importance, exploratory analysis; stakeholders, use cases, and failure modes. Reading: Hong et. al., 2020, <a href="https://arxiv.org/abs/2004.11440">Human Factors in Model Interpretability: Industry Practices, Challenges</a>, 
Kaur et. al., 2020, <a href="https://dl.acm.org/doi/epdf/10.1145/3313831.3376219">Interpreting Interpretability: Understanding Data Scientists’ Use of Interpretability Tools for Machine Learning</a></td>
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
      <td style="padding:0.6rem;">Linear models, sparsity, generalized additive models, scoring systems, decision trees, and rule-based models. <strong>Seminar papers:</strong> Caruana et. al., 2015, <a href="https://people.dbmi.columbia.edu/noemie/papers/15kdd.pdf">Intelligible Models for HealthCare: Predicting Pneumonia Risk and Hospital 30-day Readmission</a>, Liu et. al., 2022, <a href="https://arxiv.org/pdf/2210.05846">FasterRisk: Fast and Accurate Interpretable Risk
Scores</a>. <strong> Guest lecture: Hayden McTavish and Varun Babbar from Duke University with talk on modern algorithms of decision trees </strong></td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">5</td>
      <td style="padding:0.6rem;">February 23</td>
      <td style="padding:0.6rem;">Inherently interpretable models &amp; project proposals</td>
      <td style="padding:0.6rem;">Prototype-based and concept-based approaches; project proposal presentations. <strong>Seminar papers:</strong> Chen at. al., 2019 <a href="https://proceedings.neurips.cc/paper_files/paper/2019/file/adf7ee2dcf142b0e11888e72b43fcb75-Paper.pdf">This Looks Like That: Deep Learning for Interpretable Image Recognition</a>, Koh et. al., 2020, <a href="https://arxiv.org/pdf/2007.04612">Concept Bottleneck Models</a>.</td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">6</td>
      <td style="padding:0.6rem;">March 2</td>
      <td style="padding:0.6rem;">Post-hoc explanations I: feature and data attributions</td>
      <td style="padding:0.6rem;">What feature attributions approximate; local vs. global explanations; LIME, SHAP, gradient-based methods. <strong>Seminar papers:</strong> Ribeiro et. al., 2016, <a href="https://arxiv.org/pdf/1602.04938">“Why Should I Trust You?”
Explaining the Predictions of Any Classifier</a>, Lundberg and Lee, 2017, <a href="https://proceedings.neurips.cc/paper_files/paper/2017/file/8a20a8621978632d76c43dfd28b67767-Paper.pdf">A Unified Approach to Interpreting Model Predictions Scores</a>, Smilkov et. al., 2017, <a href="https://arxiv.org/pdf/1706.03825">Smoothgrad: Removing noise by adding noise</a>, Sundararajan et. al., 2017, <a href="https://arxiv.org/pdf/1703.01365">Axiomatic Attribution for Deep Networks</a>. </td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">7</td>
      <td style="padding:0.6rem;">March 9</td>
      <td style="padding:0.6rem;">Post-hoc explanations II: evaluation and pitfalls</td>
      <td style="padding:0.6rem;">Explanation disagreement, sensitivity to baselines and perturbations, sanity checks, manipulation and robustness. <strong>Seminar papers:</strong> Slack and Hilgard et. al., 2020, <a href="https://arxiv.org/pdf/1911.02508">Fooling LIME and SHAP</a>,
      Dombrowski et. al., 2019, <a href="https://arxiv.org/pdf/1906.07983">Explanations can be manipulated and geometry is to blame</a>.
      <strong> Guest lecture: Suraj Srinivas from Bosch AI on feature attribution failures. </strong> </td>
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
      <td style="padding:0.6rem;">Counterfactual definitions; actionability and feasibility; robustness and human constraints.
      <strong>Seminar papers:</strong>
      Mothilal et. al., 2020, <a href="https://arxiv.org/pdf/1905.07697">Explaining Machine Learning Classifiers through Diverse
Counterfactual Explanations</a>,
Karimi et. al., 2020, <a href="https://arxiv.org/pdf/2002.06278">Algorithmic Recourse:
from Counterfactual Explanations to Interventions</a>,
Upadhyay et. al., 2020, <a href="https://iis.seas.harvard.edu/papers/upadhyay2025counterfactual.pdf">Explaining Counterfactual Explanations May Not Be the Best Algorithmic Recourse Approachs</a>,
      Turbal et. al., 2025, <a href="https://openreview.net/pdf?id=GNDgQie8W4">ElliCE: Efficient and Provably Robust Algorithmic Recourse via the Rashomon Sets</a>
      </td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">9</td>
      <td style="padding:0.6rem;">March 30</td>
      <td style="padding:0.6rem;">Mechanistic interpretability &amp; mid-project updates</td>
      <td style="padding:0.6rem;">Representations, features, and circuits; how mechanistic interpretability differs from post-hoc explanations; mid-project updates.
      <strong>Seminar papers:</strong>
Olah et. al., 2020, <a href="https://distill.pub/2020/circuits/zoom-in/">Zoom In: An Introduction to Circuits</a>, 
Bricken et. al., 2023, <a href="https://transformer-circuits.pub/2023/monosemantic-features">Towards Monosemanticity: Decomposing Language Models With Dictionary Learning</a></td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">10</td>
      <td style="padding:0.6rem;">April 6</td>
      <td style="padding:0.6rem;">Mechanistic interpretability and large language models</td>
      <td style="padding:0.6rem;">LLM internals; probing vs. circuits; steering vs. understanding; limits of current approaches. <strong> Guest lecture: </strong> Shawn Im from University of Wisconsin–Madison
 "How Do Transformers Learn to Associate Tokens: Gradient Leading Terms Bring Mechanistic Interpretability"</td>
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
      <td style="padding:0.6rem;">Model sets rather than single models; why explanations do not resolve ambiguity; implications for fairness and trust </td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">13</td>
      <td style="padding:0.6rem;">April 27</td>
      <td style="padding:0.6rem;">Interpretability, trustworthiness, and deployment</td>
      <td style="padding:0.6rem;">Fairness, robustness, privacy, unlearning; regulation, accountability, and open problems <strong> Guest lecture: Ben Laufer from Cornell University on Ethical and Trustworthy AI </strong></td>
    </tr>

    <tr>
      <td style="padding:0.6rem;">14</td>
      <td style="padding:0.6rem;">May 4</td>
      <td style="padding:0.6rem;">Final project presentations</td>
      <td style="padding:0.6rem;">In-class final presentations</td>
    </tr>
  </tbody>
</table>
