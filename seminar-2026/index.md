---
layout: default
title: "CuRe seminar · 3 November 2026"
description: "Public talks at KUA on cultural reasoning, literary summaries, intertextuality, AI fiction, narrative and retrieval."
---

<div class="event-hero">
  <a class="event-back" href="{{ '/' | relative_url }}">← CuRe project</a>
  <p class="eyebrow">Seminar · University of Copenhagen</p>
  <h1>Literature, Narrative and Language Models</h1>
  <p class="event-lead">A CuRe seminar on cultural reasoning, from literary references and clichés to narrative and retrieval.</p>
  <dl class="event-facts">
    <div><dt>When</dt><dd>Tuesday 3 November 2026<br>10:30–12:00 CET</dd></div>
    <div><dt>Where</dt><dd>KUA / South Campus<br>Room 23.3.17</dd></div>
    <div><dt>Joining</dt><dd>Open to everyone<br>No registration required</dd></div>
  </dl>
</div>

The morning brings together work on literary knowledge, intertextuality, AI-generated fiction, narrative in training data, and retrieval for long texts.

**The morning talks are open to everyone; no registration is required.** Coffee, tea and vegan, gluten-free refreshments will be available.

<nav class="section-nav" aria-label="Seminar sections">
  <a href="#programme">Programme</a>
  <a href="#talks">Talks and abstracts</a>
  <a href="#contact">Contact</a>
</nav>

<h2 id="programme">Programme</h2>

All times are local to Copenhagen (CET). **Every talk slot includes questions.**

<div class="schedule-wrap" role="region" aria-label="Seminar timetable" tabindex="0">
<table class="event-schedule">
  <caption>Tuesday 3 November · KUA, room 23.3.17</caption>
  <thead><tr><th scope="col">Time</th><th scope="col">Session</th><th scope="col">Speakers</th></tr></thead>
  <tbody>
    <tr class="schedule-band"><th colspan="3" scope="rowgroup">Public morning talks</th></tr>
    <tr><th scope="row">10:30–10:40</th><td><a href="#cure-overview">CuRe: Evaluating and Improving Cultural Reasoning</a></td><td>CuRe team</td></tr>
    <tr><th scope="row">10:40–10:55</th><td><a href="#booksum">BOOKSUM: What Does a Language Model Know About a Book?</a></td><td>CuRe team</td></tr>
    <tr><th scope="row">10:55–11:10</th><td><a href="#intertextuality">Retrieving Biblical References in Karen Blixen’s <i>Seven Gothic Tales</i></a></td><td>CuRe team</td></tr>
    <tr><th scope="row">11:10–11:30</th><td><a href="#maria-antoniak">What Kinds of Fiction Do AI Users Want? Cliches, Personalization, and Endless Storytelling</a></td><td>Maria Antoniak</td></tr>
    <tr><th scope="row">11:30–11:45</th><td><a href="#teagan-johnson">Characterizing the Narrative Content Across Web-Scale Data</a></td><td>Teagan Johnson</td></tr>
    <tr><th scope="row">11:45–12:00</th><td><a href="#retrieval">Retrieval-augmented generation for long texts</a></td><td>Giovanni Colavizza<br>Theresia Rampisela</td></tr>
  </tbody>
</table>
</div>

<p class="programme-note">CuRe talk titles and abstracts below are provisional; individual presenters will be confirmed. The programme may receive minor updates.</p>

<h2 id="talks">Talks and abstracts</h2>

<article class="talk-abstract" id="cure-overview">
  <p class="talk-meta">10:30–10:40 · CuRe team</p>
  <h3>CuRe: Evaluating and Improving Cultural Reasoning</h3>
  <p>How good are language models at cultural reasoning, and what would it mean to make them better? CuRe approaches these questions through literature, where interpretation depends on context and can support several defensible readings. We introduce the project’s three connected aims: constructing benchmarks for culturally grounded interpretation, evaluating models while preserving ambiguity and scholarly disagreement, and adapting models to improve their reasoning without reinforcing stereotypes. Working with Danish literary texts, the project brings computational methods into dialogue with literary scholarship. We outline the research programme and the questions on which we hope to develop concrete collaborations during the seminar.</p>
</article>

<article class="talk-abstract" id="booksum">
  <p class="talk-meta">10:40–10:55 · CuRe team</p>
  <h3>BOOKSUM: What Does a Language Model Know About a Book?</h3>
  <p>A language model can produce a convincing account of a book without being given the book itself. What does that account reveal about its knowledge? This talk presents our ongoing BOOKSUM work on generating literary summaries from metadata alone, with particular attention to canonical bias: how a work’s literary prominence may affect the model’s account of it. We discuss the challenges of evaluating these summaries and interpreting differences between books. The study also raises broader questions for CuRe about what literary tasks actually measure, and how to distinguish familiarity with a work from an ability to reason about its text.</p>
</article>

<article class="talk-abstract" id="intertextuality">
  <p class="talk-meta">10:55–11:10 · CuRe team</p>
  <h3>Retrieving Biblical References in Karen Blixen’s <i>Seven Gothic Tales</i></h3>
  <p>Literary allusions often transform their sources, making them difficult to retrieve through verbal overlap alone. We present our study of biblical intertextual references in Karen Blixen’s <i>Seven Gothic Tales</i>, comparing sparse and dense retrieval methods across historical language and translation. Fine-tuning improves retrieval, while expert reassessment shows why existing annotations cannot always be treated as exhaustive ground truth. We discuss what this case teaches us about evaluating culturally grounded retrieval and how it can inform CuRe’s broader work on evidence, context and interpretive uncertainty.</p>
  <a class="text-link" href="https://arxiv.org/abs/2609.35765">Read the preprint <span aria-hidden="true">→</span></a>
</article>

<article class="talk-abstract" id="maria-antoniak">
  <p class="talk-meta">11:10–11:30 · Maria Antoniak</p>
  <h3>What Kinds of Fiction Do AI Users Want? Cliches, Personalization, and Endless Storytelling</h3>
  <p>I’ll begin by discussing our recent work on examining AI-generated fiction and observations of user-chatbot conversations in which users prompt for and edit generated stories. Studying this real user behavior breaks many common assumptions about what kinds of fiction people want from models, and has led us to new work on better understanding, measuring, and examining the sources of cliches in both literary texts and generated fiction.</p>
</article>

<article class="talk-abstract" id="teagan-johnson">
  <p class="talk-meta">11:30–11:45 · Teagan Johnson</p>
  <h3>Characterizing the Narrative Content Across Web-Scale Data</h3>
  <p>Narrative is a fundamental mode of human communication, yet the narrative composition of web-scale LLM pretraining corpora remains largely unexplored. We present the first fine-grained study of narrative in DOLMA, a 3-trillion-token open web-scale corpus. Drawing on narrative theory, we operationalize three core narrative elements (agency, setting, and events) as 11 interpretable dimensions. Using ∼400 hand-annotated passages and 25K LLM-labeled passages, we train and validate NARRABERT, two RoBERTa-based models for fine-grained narrative prediction, and apply them to ∼13M passages to create NARRADOLMA. We find that narrative structure is measurable at scale across highly heterogeneous data, and that narrative qualities are unevenly distributed across sources, topics, and formats.</p>
</article>

<article class="talk-abstract" id="retrieval">
  <p class="talk-meta">11:45–12:00 · Giovanni Colavizza and Theresia Rampisela</p>
  <h3>Retrieval-augmented generation for long texts</h3>
  <p>Giovanni will introduce the project’s general direction, and Theresia will present ongoing work on retrieval-augmented generation for long texts.</p>
  <p class="programme-note">Talk title and abstract forthcoming.</p>
</article>

<h2 id="contact">Organisers and contact</h2>

Daniel Hershcovich, Jens Bjerring-Hansen and Alexander Conroy.

For questions about the seminar, contact [Daniel Hershcovich](mailto:dh@di.ku.dk).
