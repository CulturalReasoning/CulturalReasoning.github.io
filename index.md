---
layout: default
---

<div class="page-hero">
  <div class="hero-copy">
    <p class="eyebrow">Independent Research Fund Denmark · 2026–2030</p>
    <h1>Cultural Reasoning for Responsible Language Model Development</h1>
    <p class="hero-question">How good are LLMs at cultural reasoning? Can we make them better? What does “better” even mean?</p>
    <p class="hero-summary">CuRe brings together natural language processing and literary studies to develop better ways of evaluating and training language models for culturally grounded reasoning.</p>
    <div class="hero-actions">
      <a class="button button-primary" href="#hiring">PhD position</a>
      <a class="button button-secondary" href="#publications">Publications</a>
    </div>
  </div>
  <div class="hero-mark">
    <img src="cure_logo.png" alt="CuRe project logo">
  </div>
</div>

<nav class="section-nav" aria-label="Page sections">
  <a href="#questions">Research questions</a>
  <a href="#programme">Research programme</a>
  <a href="#publications">Publications</a>
  <a href="#team">Team</a>
  <a href="{{ '/seminar-2026/' | relative_url }}">November seminar</a>
</nav>

<aside class="seminar-callout" aria-labelledby="seminar-heading">
  <div>
    <p class="card-kicker">3 November 2026 · KUA, room 23.3.17</p>
    <h2 id="seminar-heading">Literature, Narrative and Language Models</h2>
    <p>Join the public morning of our CuRe seminar: talks on literary knowledge, intertextuality, AI fiction, narrative and retrieval. 10:30–12:00; no registration required.</p>
  </div>
  <a class="button button-primary" href="{{ '/seminar-2026/' | relative_url }}">Full programme and abstracts <span aria-hidden="true">→</span></a>
</aside>

<div id="hiring" class="hiring-card">
  <div>
    <p class="card-kicker">We are hiring</p>
    <h2>PhD fellowship in Cultural Reasoning with Language Models</h2>
    <p>The PhD is centred on NLP: benchmark design, retrieval and RAG, model adaptation, training data, expert feedback, and evaluation under ambiguity. Literature provides the demanding test case, but the research questions concern language-model training and evaluation more broadly.</p>
    <div class="job-facts">
      <span><strong>Deadline</strong> 8 November 2026</span>
      <span><strong>Start</strong> 1 February 2027</span>
      <span><strong>Location</strong> Copenhagen</span>
    </div>
  </div>
  <a class="button button-light" href="https://candidate.hr-manager.net/ApplicationInit.aspx?cid=3010&ProjectId=167227&DepartmentId=19976&MediaId=5124&IsAdPreviewRequest=true&AdvertisementId=122993">Read the call and apply</a>
</div>

## Project summary

Culture is not a collection of isolated facts. It is expressed through context, references, recurring patterns, disagreement, and changing interpretations. CuRe studies whether language models can reason with these forms of meaning—and how their evaluation and training should change when no single answer captures the whole task.

We use Danish literature as a rigorous testbed. Literary interpretation requires models to connect claims to textual evidence, use historical and cultural context, consider plausible alternatives, and respond to criticism. These are difficult capabilities that standard factual and multiple-choice benchmarks do not measure well.

<div id="questions" class="question-grid">
  <article class="question-card">
    <span class="question-number">01</span>
    <h3>Build valid benchmarks</h3>
    <p>How can we evaluate culturally grounded interpretive reasoning in domains where no unambiguous ground truth exists?</p>
  </article>
  <article class="question-card">
    <span class="question-number">02</span>
    <h3>Evaluate depth</h3>
    <p>How can evaluation reflect evidence, ambiguity, disagreement, and context rather than reduce interpretation to a single label?</p>
  </article>
  <article class="question-card">
    <span class="question-number">03</span>
    <h3>Train better models</h3>
    <p>How can we adapt and guide LLMs for culturally specific reasoning without reinforcing stereotypes or collapsing plural viewpoints?</p>
  </article>
</div>

## Why literature?

Literature is culturally dense and resistant to easy classification. It gives us a controlled but demanding setting for studying capabilities that matter well beyond literary analysis.

<div class="feature-grid">
  <article>
    <h3>Referencing</h3>
    <p>Recognising quotations, allusions, echoes, and their changing significance across texts and periods.</p>
  </article>
  <article>
    <h3>Reuse</h3>
    <p>Tracing motifs, clichés, idioms, and recurring cultural patterns without treating culture as a fixed stereotype.</p>
  </article>
  <article>
    <h3>Interpretation</h3>
    <p>Supporting readings with evidence, comparing alternatives, and preserving meaningful scholarly disagreement.</p>
  </article>
</div>

## Research programme

<div id="programme" class="wp-grid">
  <article class="wp-card">
    <p class="wp-label">WP1 · Empirical foundations</p>
    <h3>Data and benchmark development</h3>
    <p>Curate Danish literary corpora and co-develop interpretive tasks with literary scholars, using evidence-centred benchmark design and annotations that preserve variation.</p>
  </article>
  <article class="wp-card">
    <p class="wp-label">WP2 · Methodological reflection</p>
    <h3>Reasoning beyond ground truth</h3>
    <p>Evaluate retrieval, RAG, and long-context models; study interpretive hallucinations; and develop protocols that separate identifiable errors, evidential support, and plausibility.</p>
  </article>
  <article class="wp-card">
    <p class="wp-label">WP3 · Model development</p>
    <h3>Adaptation and training</h3>
    <p>Test how pretraining mixtures, contextual resources, fine-tuning, and feedback from literary scholars affect cultural reasoning while preserving ambiguity and plural perspectives.</p>
  </article>
</div>

## Publications

<div id="publications" class="publication-list">
  <article class="publication-card">
    <div class="publication-meta"><span class="tag">Perspective preprint</span><span>2026</span></div>
    <h3><a href="https://arxiv.org/abs/2609.30897">From annotation to reasoning: Culture in language models</a></h3>
    <p class="authors">Daniel Hershcovich, Alexander Conroy, and Jens Bjerring-Hansen</p>
    <p>We argue that cultural evaluation must address interpretive depth: whether a model can support a reading with evidence, consider alternatives, and revise it after criticism. The paper connects benchmark design, expert evaluation that preserves disagreement, and experiments on data, context, and feedback.</p>
    <a class="text-link" href="https://arxiv.org/abs/2609.30897">Read the preprint <span aria-hidden="true">→</span></a>
  </article>

  <article class="publication-card">
    <div class="publication-meta"><span class="tag">Accepted · CHR 2027</span><span>2027</span></div>
    <h3><a href="https://arxiv.org/abs/2609.35765">Retrieving Biblical Intertextual References in Karen Blixen’s <i>Seven Gothic Tales</i></a></h3>
    <p class="authors">András Kovacs, Alexander Conroy, Daniel Hershcovich, and Jens Bjerring-Hansen</p>
    <p>Accepted at <a href="https://2027.computational-humanities-research.org/">Computational Humanities Research (CHR) 2027</a> in Manchester for a long oral presentation (22 minutes including Q&amp;A).</p>
    <p>We compare sparse and dense retrieval methods for finding transformed cultural references across historical language and translation. Fine-tuning improves retrieval substantially, while expert reassessment shows why benchmark annotations cannot always be treated as exhaustive ground truth.</p>
    <a class="text-link" href="https://arxiv.org/abs/2609.35765">Read the preprint <span aria-hidden="true">→</span></a>
  </article>
</div>

## Expected outcomes

<div class="outcome-grid">
  <div><strong>Benchmarks</strong><span>Evidence-centred tasks for cultural and literary reasoning</span></div>
  <div><strong>Data</strong><span>Open corpora and expert annotations grounded in Danish literature</span></div>
  <div><strong>Methods</strong><span>Evaluation protocols that preserve ambiguity and disagreement</span></div>
  <div><strong>Models</strong><span>Training and adaptation strategies for culturally robust reasoning</span></div>
</div>

## Team

<div id="team" class="team-grid">
  <article class="person-card">
    <p class="role">Principal Investigator · NLP</p>
    <h3><a href="https://danielhers.github.io/">Daniel Hershcovich</a></h3>
    <p>Department of Computer Science, University of Copenhagen</p>
  </article>
  <article class="person-card">
    <p class="role">Co-Principal Investigator · Literary Studies</p>
    <h3><a href="https://nors.ku.dk/ansatte/?pure=da/persons/195540">Jens Bjerring-Hansen</a></h3>
    <p>Department of Nordic Studies and Linguistics, University of Copenhagen</p>
  </article>
  <article class="person-card">
    <p class="role">Advisor · NLP</p>
    <h3><a href="https://elliottd.github.io/">Desmond Elliott</a></h3>
    <p>Department of Computer Science, University of Copenhagen</p>
  </article>
  <article class="person-card">
    <p class="role">Postdoctoral Researcher</p>
    <h3>Alexander Conroy</h3>
    <p>Computational literary studies and cultural analytics</p>
  </article>
  <article class="person-card person-card-open">
    <p class="role">Open position · Start February 2027</p>
    <h3><a href="https://candidate.hr-manager.net/ApplicationInit.aspx?cid=3010&ProjectId=167227&DepartmentId=19976&MediaId=5124&IsAdPreviewRequest=true&AdvertisementId=122993">PhD Fellow</a></h3>
    <p>Cultural reasoning, language-model evaluation, and model adaptation</p>
  </article>
</div>

<div class="supporting-grid">
  <div>
    <h3>International collaborators</h3>
    <ul>
      <li>David Bamman, UC Berkeley</li>
      <li>Timothy Tangherlini, UC Berkeley</li>
      <li>Maria Antoniak, University of Colorado</li>
      <li>Jackie Cheung, McGill University</li>
    </ul>
  </div>
  <div>
    <h3>Advisory board</h3>
    <ul>
      <li>Serge Belongie</li>
      <li>Anders Søgaard</li>
      <li>Carsten Levisen</li>
      <li>Bolette Sandford Pedersen</li>
    </ul>
  </div>
</div>

<div class="contact-panel">
  <div>
    <p class="card-kicker">Contact</p>
    <h2>Interested in the project?</h2>
    <p>For research inquiries and collaboration, contact Daniel Hershcovich at <a href="mailto:dh@di.ku.dk">dh@di.ku.dk</a>.</p>
  </div>
  <p class="funding-note">CuRe is funded by the <a href="https://dff.dk/om-fonden/nyheder-og-presse/alle-nyheder/nyheder/2025/oktober/53-mio-kr-til-forskning-i-kunstig-intelligens/">Independent Research Fund Denmark</a> through the thematic programme on artificial intelligence.</p>
</div>
