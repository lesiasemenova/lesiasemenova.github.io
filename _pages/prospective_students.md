---
layout: page
permalink: /prospective_students/
inline: true
title: prospective
related_posts: false
nav: false
---

Thank you for your interest in my research group! We work on safe, trustworthy, and interpretable AI. A recurring theme is <em>multiplicity</em>: for most learning problems there are many models, representations, reasoning paths, or agent configurations that perform about equally well but behave differently. We study what this reveals about uncertainty and reliability, and how to use it to build systems that are more interpretable, better controlled, and easier to evaluate.

<style>
  .page-nav { margin: -0.25rem 0 1.75rem; font-size: 0.95rem; color: var(--global-text-color-light); }
  .page-nav a { white-space: nowrap; }
  .important-announcement[id] { scroll-margin-top: 90px; }
</style>
<p class="page-nav">On this page: <a href="#phd">PhD applicants</a> &middot; <a href="#rutgers">Rutgers students</a> &middot; <a href="#visiting">Visiting researchers and interns</a> &middot; <a href="#directions">Research directions</a> &middot; <a href="#working">Working with me</a></p>

<p id="phd" class="important-announcement">Prospective Ph.D. Students (Fall 2027)</p>
I am recruiting Ph.D. students to start in Fall 2027. Please apply through the [Rutgers Ph.D. Program in Computer Science](https://www.cs.rutgers.edu/academics/graduate/prospective-students/) and mention my name in your application. <strong>The application deadline is January 1, 2027.</strong> Feel free to also send me a short email with a brief description of your research interests and experience; include your CV and transcript, and put “Prospective Ph.D. Student” in the subject line. A strong background in machine learning, mathematics, or statistics and solid programming skills are expected.

<p id="rutgers" class="important-announcement">Rutgers Undergraduate or Graduate Students</p>
Please visit the [Research page]({{ site.baseurl }}/research/) to learn more about our projects. If you are interested in collaborating, send me an email describing your background and what you would like to work on. Include your CV and transcript, indicate how much time you can dedicate to the project, and add “Rutgers Student Collaborator” to the email subject line. Rutgers undergraduates can also join the group through the [Aresty Research Assistant Program](https://aresty.rutgers.edu/) and the [SUPER program](https://douglass.rutgers.edu/wise/stem-research).

<p id="visiting" class="important-announcement">Visiting Student Researchers or Interns</p>
Several projects would benefit from collaboration with interns or visiting students who have a strong background in machine learning, Python programming, and at least one of: optimization, machine learning theory, mechanistic interpretability, foundation models, or human-computer interaction. If you are interested in working together, send me a brief email outlining your research interests and experience. Include your CV, transcripts, a note on how much time you can dedicate to the project, and add “Visiting Researcher/Intern” to the email subject line. I read every message, though it may take me a little while to reply.

<p id="directions" class="important-announcement">Active directions</p>
Current projects in the group fall into the following areas. You do not need to fit neatly into one of them, this is for general overview of the lab's directions.
<ul>
<li><strong>Interpretability and representation engineering for LLMs.</strong> Reading and editing the internal representations of large language models: which directions in activation space encode concepts, how information flows across layers and attention heads, and how to tell faithful explanations from artifacts of the analysis method. We are particularly interested in what stays stable across representations and what does not.</li>
<li><strong>Steering and AI control.</strong> Using representation-level interventions to steer model behavior, and designing control and monitoring protocols that remain reliable when many behaviors are consistent with the training signal. This connects to alignment, personalization, and safety under distribution shift.</li>
<li><strong>Memory, communication, and collaboration in multi-agent systems.</strong> How should LLM-based agents store, retrieve, and update memory over long horizons? When does communication between agents help, and when does it amplify errors or hide disagreement? We study these questions with an eye on multiplicity: many agent configurations and communication protocols can achieve the same task performance while differing in reliability, cost, and failure modes.</li>
<li><strong>Uncertainty.</strong> Quantifying uncertainty that arises from multiplicity rather than from noise alone, for both classical models and LLMs: when predictions or reasoning paths can be trusted, when a system should abstain, and how to communicate this to decision-makers in domains such as healthcare and public policy.</li>
<li><strong>Theoretical and interpretable machine learning.</strong> Characterizing Rashomon sets (sets of near-optimal models), understanding when simple and interpretable models can match black-box performance, designing algorithms to navigate these sets, and building interpretable models for high-stakes applications. This line of work builds on my earlier research on the Rashomon Effect; see the <a href="{{ site.baseurl }}/research/">research page</a> for details.</li>
<li><strong>Evaluation and dynamic evaluation.</strong> Evaluating models and agents whose behavior changes over time, through interaction, fine-tuning, or updates to their tools and environments; measuring the stability of evaluation results across equally good models; and designing benchmarks that reflect deployment conditions rather than static test sets.</li>
</ul>

<p id="working" class="important-announcement">What it is like to work with me</p>
Advising is the part of this job I like most. I work closely with my students: we meet every week, I read and comment on every draft, we write papers together, and I spend real time on what comes after, whether that is a PhD, a job in industry, or something else.

Research here happens in small teams around a concrete question, and the students who thrive are the ones who show up reliably and get curious about why something works, not just whether it does. In return, I ask for two things. Own your project: take the initiative, lead it, and treat it with care. Communicate early: tell me when you are stuck or when life outside research gets in the way. Problems I know about early are problems we can solve together.

If this kind of partnership sounds like a good fit, write to me.
