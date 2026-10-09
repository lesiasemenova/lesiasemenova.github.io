---
layout: page
permalink: /mlii-fall2026/
inline: true
title: mlii_fall2026
related_posts: false
nav: false
---

<style>
  .mlii-page {
    --mlii-accent: var(--global-theme-color, #00693e);
    --mlii-border: var(--global-divider-color, #d8dde3);
    --mlii-surface: var(--global-card-bg-color, rgba(127, 127, 127, 0.06));
  }

  .mlii-page .course-header {
    text-align: center;
    margin: 2rem 0 2.25rem;
  }

  .mlii-page .course-code {
    color: var(--mlii-accent);
    font-size: 0.9rem;
    font-weight: 700;
    letter-spacing: 0.08em;
    margin-bottom: 0.45rem;
    text-transform: uppercase;
  }

  .mlii-page .course-header h1 {
    margin: 0 0 0.35rem;
  }

  .mlii-page .course-term {
    font-size: 1.05rem;
    opacity: 0.82;
  }

  .mlii-page .course-lede {
    font-size: 1.05rem;
    line-height: 1.75;
    margin-bottom: 1.75rem;
  }

  .mlii-page .course-facts {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 0.8rem;
    margin: 1.5rem 0 2rem;
  }

  .mlii-page .course-fact {
    background: var(--mlii-surface);
    border: 1px solid var(--mlii-border);
    border-radius: 0.5rem;
    padding: 0.9rem 1rem;
  }

  .mlii-page .course-fact strong {
    display: block;
    font-size: 0.83rem;
    letter-spacing: 0.04em;
    margin-bottom: 0.25rem;
    text-transform: uppercase;
  }

  .mlii-page .syllabus-link {
    border: 1px solid var(--mlii-accent);
    border-radius: 0.35rem;
    display: inline-block;
    font-weight: 600;
    margin: 0.25rem 0 1.5rem;
    padding: 0.55rem 0.85rem;
  }

  .mlii-page .schedule-wrap {
    border: 1px solid var(--mlii-border);
    border-radius: 0.5rem;
    margin-top: 1rem;
    overflow-x: auto;
  }

  .mlii-page .schedule {
    border-collapse: collapse;
    margin: 0;
    width: 100%;
  }

  .mlii-page .schedule th,
  .mlii-page .schedule td {
    border-bottom: 1px solid var(--mlii-border);
    padding: 0.68rem 0.75rem;
    text-align: left;
    vertical-align: top;
  }

  .mlii-page .schedule th:first-child,
  .mlii-page .schedule td:first-child {
    text-align: center;
    width: 4.5rem;
  }

  .mlii-page .schedule th:nth-child(2),
  .mlii-page .schedule td:nth-child(2) {
    white-space: nowrap;
    width: 10.5rem;
  }

  .mlii-page .schedule tbody tr:last-child td {
    border-bottom: 0;
  }

  .mlii-page .schedule .unit-row th {
    background: var(--mlii-surface);
    color: var(--mlii-accent);
    font-size: 0.84rem;
    letter-spacing: 0.055em;
    padding: 0.6rem 0.75rem;
    text-transform: uppercase;
  }

  .mlii-page .schedule .no-class td {
    opacity: 0.72;
  }

  .mlii-page .schedule .milestone td {
    background: var(--mlii-surface);
  }

  .mlii-page .schedule .lec {
    display: inline-block;
    font-size: 0.78rem;
    font-weight: 600;
    margin-right: 0.35rem;
    min-width: 1.9rem;
    opacity: 0.6;
  }

  .mlii-page .schedule .due {
    color: var(--mlii-accent);
    display: block;
    font-size: 0.88rem;
    font-weight: 600;
    margin-top: 0.2rem;
  }

  .mlii-page .calendar-note {
    font-size: 0.9rem;
    margin-top: 0.8rem;
    opacity: 0.78;
  }

  @media (max-width: 650px) {
    .mlii-page .course-facts {
      grid-template-columns: 1fr;
    }

    .mlii-page .schedule th,
    .mlii-page .schedule td {
      padding: 0.62rem 0.55rem;
    }

    .mlii-page .schedule th:first-child,
    .mlii-page .schedule td:first-child {
      width: 2.5rem;
    }

    .mlii-page .schedule th:nth-child(2),
    .mlii-page .schedule td:nth-child(2) {
      white-space: normal;
      width: 6.5rem;
    }

    .mlii-page .schedule .unit-row th {
      text-align: left;
    }
  }
</style>

<div class="mlii-page">
  <header class="course-header">
    <div class="course-code">CS 536 · 16:198:536:01</div>
    <h1>Machine Learning II</h1>
    <div class="course-term">Graduate course · Fall 2026</div>
  </header>

  <p class="course-lede">
    This course develops the foundations needed to understand and use modern deep learning. We begin with machine-learning basics and linear models, then study multilayer perceptrons, backpropagation, optimization, convolutional and recurrent neural networks, attention and transformers, language models, and deep generative models. Throughout the course, we will connect the mathematics to implementation and examine why these methods work, where they fail, and how to evaluate them carefully.
  </p>

  <div class="course-facts">
    <div class="course-fact">
      <strong>Time</strong>
      Mondays and Thursdays, 12:10–1:30 p.m.
    </div>
    <div class="course-fact">
      <strong>Location</strong>
      Livingston Campus · Tillett Hall 116
    </div>
    <div class="course-fact">
      <strong>Instructor</strong>
      <a href="https://lesiasemenova.github.io/">Lesia Semenova</a> · <a href="mailto:lesia.semenova@rutgers.edu">lesia.semenova@rutgers.edu</a>
    </div>
    <div class="course-fact">
      <strong>Office hours</strong>
      Lesia: after class; email for a longer appointment<br>
      Rushi: Thursdays, 11:00 a.m.–12:00 p.m., Tillett Hall 125 or Zoom (link on Canvas)
    </div>
  </div>

  <h2>Course information</h2>

  <p>
    <strong>Prerequisites.</strong> Students should be comfortable with basic linear algebra, probability, and core machine-learning concepts. You should also be able to implement and debug machine-learning experiments in Python using tools such as NumPy, scikit-learn, and PyTorch.
  </p>

  <p>
    <strong>Assessment.</strong> In-class quizzes account for 20% of the grade; the semester-long research project accounts for 65%; and engagement and attendance account for 15%. There will be three quizzes, and the lowest quiz score will be dropped. Full policies and project requirements are in the syllabus.
  </p>

  <p>
    <strong>Quizzes.</strong> Quizzes take place in class on October 5, November 2, and November 19. Two weeks before each quiz, we release a practice quiz on Canvas, also available as a Canvas quiz for 2 extra-credit points. One week before the quiz, the extra-credit quiz closes and the answers are released.
  </p>

  <p>
    <strong>Project milestones.</strong> Proposals and team declarations were due September 28. Project updates are due Monday, November 2, at 10:00 a.m., and the final project report is due Tuesday, December 1, at 10:00 a.m. Final presentations run December 3–10.
  </p>

  <p>
    <strong>Course communication.</strong> Canvas will be used for announcements, course materials, assignments, and class questions. Please use email for official or sensitive communication.
  </p>

  <a class="syllabus-link" href="/assets/pdf/MLII_fall2026_syllabus.pdf" target="_blank" rel="noopener">
    Full syllabus (PDF)
  </a>

  <h2>Tentative schedule</h2>

  <p>
    Topics and ordering of upcoming lectures may be adjusted based on pacing. Quiz dates and project deadlines are listed below; Canvas remains the place for announcements, materials, and submissions.
  </p>

  <div class="schedule-wrap">
    <table class="schedule">
      <thead>
        <tr>
          <th scope="col">Week</th>
          <th scope="col">Date</th>
          <th scope="col">Topic</th>
        </tr>
      </thead>
      <tbody>
        <tr class="unit-row"><th colspan="3" scope="colgroup">Machine-learning foundations</th></tr>
        <tr><td>1</td><td>Thu, September 3</td><td><span class="lec">L1</span>Course introduction: learning from examples, loss, risk, and generalization</td></tr>
        <tr class="no-class"><td>2</td><td>Mon, September 7</td><td>No class — Labor Day</td></tr>
        <tr><td>2</td><td>Tue, September 8</td><td><span class="lec">L2</span>Cross-validation for evaluation and model selection <em>(Monday class schedule)</em></td></tr>
        <tr><td>2</td><td>Thu, September 10</td><td><span class="lec">L3</span>Evaluation beyond accuracy: ROC curves, imbalanced data, and feature importance</td></tr>
        <tr><td>3</td><td>Mon, September 14</td><td><span class="lec">L4</span>Linear regression, squared loss, and gradient descent</td></tr>
        <tr><td>3</td><td>Thu, September 17</td><td><span class="lec">L5</span>Logistic regression, surrogate losses, and the perceptron</td></tr>

        <tr class="unit-row"><th colspan="3" scope="colgroup">Neural networks</th></tr>
        <tr><td>4</td><td>Mon, September 21</td><td><span class="lec">L6</span>Neural networks: XOR, universal approximation, and backpropagation</td></tr>
        <tr><td>4</td><td>Thu, September 24</td><td><span class="lec">L7</span>Training deep networks: activations, initialization, normalization, and regularization</td></tr>

        <tr class="unit-row"><th colspan="3" scope="colgroup">Convolutional networks and computer vision</th></tr>
        <tr><td>5</td><td>Mon, September 28</td><td><span class="lec">L8</span>Convolutional neural networks: foundations<span class="due">Due: project proposals and team declarations</span></td></tr>
        <tr><td>5</td><td>Thu, October 1</td><td><span class="lec">L9</span>CNN backbones: VGG, batch normalization, and ResNet</td></tr>
        <tr class="milestone"><td>6</td><td>Mon, October 5</td><td><strong>Quiz 1</strong> (Lectures 1–5)</td></tr>
        <tr><td>6</td><td>Thu, October 8</td><td>Guest lecture: Interpretable deep learning for medicine — Alina Barnett (University of Rhode Island)</td></tr>
        <tr><td>7</td><td>Mon, October 12</td><td><span class="lec">L10</span>Modern CNNs, from labels to maps: transfer and representation learning, U-Net, and dense prediction</td></tr>

        <tr class="unit-row"><th colspan="3" scope="colgroup">Classical methods review</th></tr>
        <tr><td>7</td><td>Thu, October 15</td><td><span class="lec">L11</span>Decision trees, random forests, boosting, and support vector machines</td></tr>

        <tr class="unit-row"><th colspan="3" scope="colgroup">Sequences, attention, and language models</th></tr>
        <tr><td>8</td><td>Mon, October 19</td><td><span class="lec">L12</span>Recurrent neural networks, LSTMs, and GRUs</td></tr>
        <tr><td>8</td><td>Thu, October 22</td><td><span class="lec">L13</span>Attention mechanisms: from sequence-to-sequence models to self-attention</td></tr>
        <tr><td>9</td><td>Mon, October 26</td><td><span class="lec">L14</span>Transformers and vision transformers</td></tr>
        <tr><td>9</td><td>Thu, October 29</td><td><span class="lec">L15</span>Bidirectional transformers and BERT</td></tr>
        <tr class="milestone"><td>10</td><td>Mon, November 2</td><td><strong>Quiz 2</strong><span class="due">Due 10:00 a.m.: project updates</span></td></tr>
        <tr><td>10</td><td>Thu, November 5</td><td><span class="lec">L16</span>Autoregressive language models and GPT</td></tr>
        <tr><td>11</td><td>Mon, November 9</td><td><span class="lec">L17</span>Pretraining, fine-tuning, and adapting foundation models</td></tr>

        <tr class="unit-row"><th colspan="3" scope="colgroup">Deep generative models</th></tr>
        <tr><td>11</td><td>Thu, November 12</td><td><span class="lec">L18</span>Latent-variable models and variational autoencoders I</td></tr>
        <tr><td>12</td><td>Mon, November 16</td><td><span class="lec">L19</span>Variational autoencoders II</td></tr>
        <tr class="milestone"><td>12</td><td>Thu, November 19</td><td><strong>Quiz 3</strong></td></tr>
        <tr><td>13</td><td>Mon, November 23</td><td><span class="lec">L20</span>Generative adversarial networks</td></tr>
        <tr class="no-class"><td>13</td><td>Thu, November 26</td><td>No class — Thanksgiving recess</td></tr>
        <tr><td>14</td><td>Mon, November 30</td><td><span class="lec">L21</span>Diffusion models</td></tr>

        <tr class="unit-row"><th colspan="3" scope="colgroup">Course projects</th></tr>
        <tr class="milestone"><td>14</td><td>Tue, December 1</td><td><strong>Final project report due</strong> (10:00 a.m.)</td></tr>
        <tr><td>14</td><td>Thu, December 3</td><td>Final project presentations I</td></tr>
        <tr><td>15</td><td>Mon, December 7</td><td>Final project presentations II</td></tr>
        <tr><td>15</td><td>Thu, December 10</td><td>Final project presentations III</td></tr>
      </tbody>
    </table>
  </div>

  <p class="calendar-note">
    The September 8 Monday-class designation and the November 26 recess follow the <a href="https://scheduling.rutgers.edu/academic-calendar/">Rutgers 2026–2027 academic calendar</a>.
  </p>
</div>
