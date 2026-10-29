---
layout: default
title: "CuRe seminar · 3 November 2026"
description: "A CuRe seminar at KUA and online on cultural reasoning, literary summaries, intertextuality, AI fiction, narrative and retrieval. Registration required."
---

<div class="event-hero">
  <a class="event-back" href="{{ '/' | relative_url }}">← CuRe project</a>
  <p class="eyebrow">Seminar · University of Copenhagen</p>
  <h1>Literature, Narrative and Language Models</h1>
  <p class="event-lead">A CuRe seminar on cultural reasoning, from literary references and clichés to narrative and retrieval.</p>
  <dl class="event-facts">
    <div><dt>When</dt><dd>Tuesday 3 November 2026<br>Coffee from 10:00<br>Talks 10:30–12:00 CET</dd></div>
    <div><dt>Where</dt><dd>KUA / South Campus<br>Room 23.3.17 · Building 23, 3rd floor<br>Emil Holms Kanal 4<br>2300 Copenhagen S, Denmark<br><a href="https://hum.ku.dk/kontakt/kort-soendre-campus/">Campus map</a></dd></div>
    <div><dt>Joining</dt><dd>Registration required<br>In person or online</dd></div>
  </dl>
</div>

The seminar brings together work on literary knowledge, intertextuality, AI-generated fiction, narrative in training data, and retrieval for long texts.

<div class="seminar-callout" id="registration">
  <h2>Registration</h2>
  <p><strong>Registration deadline: 1 November 2026.</strong></p>
  <p>Registration is required for both in-person and online attendance. Please indicate in the form whether you will attend in person at KUA or remotely. The form includes a Zoom registration link for remote attendance.</p>
  <a class="button button-primary" href="https://docs.google.com/forms/d/e/1FAIpQLSdmPYi63KnjVBblY6ITyNZHDd0Jw4hBn57-f6RYA8RMEF2yUg/viewform?usp=header">Register for the seminar <span aria-hidden="true">→</span></a>
</div>

<nav class="section-nav" aria-label="Seminar sections">
  <a href="#registration">Registration</a>
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
    <tr><th scope="row">10:00–10:30</th><td colspan="2">Coffee</td></tr>
    <tr><th scope="row">10:30–10:40</th><td><a href="#cure-overview">CuRe: Evaluating and Improving Cultural Reasoning</a></td><td>Daniel Hershcovich<br>Jens Bjerring-Hansen</td></tr>
    <tr><th scope="row">10:40–10:55</th><td><a href="#novelsum">Cultural memory, close reading and automation. Experiments with literary summarization through LLMs</a></td><td>Alexander Conroy</td></tr>
    <tr><th scope="row">10:55–11:10</th><td><a href="#intertextuality">Retrieving Biblical References in Karen Blixen’s <i>Seven Gothic Tales</i></a></td><td>Shibingfeng Zhang<br>András Kovács</td></tr>
    <tr><th scope="row">11:10–11:30</th><td><a href="#maria-antoniak">What Kinds of Fiction Do AI Users Want? Cliches, Personalization, and Endless Storytelling</a></td><td>Maria Antoniak</td></tr>
    <tr><th scope="row">11:30–11:45</th><td><a href="#teagan-johnson">Characterizing the Narrative Content Across Web-Scale Data</a></td><td>Teagan Johnson</td></tr>
    <tr><th scope="row">11:45–12:00</th><td><a href="#retrieval">Structure-aware Retrieval-Augmented Generation with Long Context</a></td><td>Giovanni Colavizza<br>Theresia Rampisela</td></tr>
  </tbody>
</table>
</div>

<h2 id="talks">Talks and abstracts</h2>

<article class="talk-abstract" id="cure-overview">
  <p class="talk-meta">10:30–10:40 · Daniel Hershcovich and Jens Bjerring-Hansen</p>
  <h3>CuRe: Evaluating and Improving Cultural Reasoning</h3>
  <p>How good are language models at cultural reasoning, and what would it mean to make them better? CuRe approaches these questions through literature, where interpretation depends on context and can support several defensible readings. We introduce the project’s three connected aims: constructing benchmarks for culturally grounded interpretation, evaluating models while preserving ambiguity and scholarly disagreement, and adapting models to improve their reasoning without reinforcing stereotypes. Working with Danish literary texts, the project brings computational methods into dialogue with literary scholarship. We outline the research programme and the questions on which we hope to develop concrete collaborations during the seminar.</p>
  <a class="text-link" href="https://arxiv.org/abs/2609.30897">Read our perspective preprint <span aria-hidden="true">→</span></a>
</article>

<article class="talk-abstract" id="novelsum">
  <p class="talk-meta">10:40–10:55 · Alexander Conroy</p>
  <h3>Cultural memory, close reading and automation. Experiments with literary summarization through LLMs</h3>
  <p>What makes a useful literary summary, and how can language models assist in producing one? Drawing on experiments with late-nineteenth-century Danish-language novels, we examine summaries generated from the text and from author and title alone. We consider how they preserve time, place, characters, plot and themes, and what metadata-based generation reveals about cultural priors and canonical knowledge. The talk explores how automated summarization can support literary research while raising questions about factuality, selection, interpretation and scholarly evaluation.</p>
  <a class="text-link" href="https://aclanthology.org/2026.lrec-1.780.pdf">Related paper: NOVELSUM (LREC 2026) <span aria-hidden="true">→</span></a>
</article>

<article class="talk-abstract" id="intertextuality">
  <p class="talk-meta">10:55–11:10 · Shibingfeng Zhang and András Kovács</p>
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
  <h3>Structure-aware Retrieval-Augmented Generation with Long Context</h3>
  <p>How can we effectively and efficiently navigate a set of long documents to retrieve the relevant parts? In this talk, we will present: (1) a new dataset for long-query and long-document retrieval in the legal domain; and (2) an early work on using documents’ existing structure for RAG.</p>
</article>

<h2 id="contact">Organisers and contact</h2>

Daniel Hershcovich, Jens Bjerring-Hansen and Alexander Conroy.

For questions about the seminar, contact [Daniel Hershcovich](mailto:dh@di.ku.dk).
