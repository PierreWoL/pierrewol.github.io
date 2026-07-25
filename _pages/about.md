---
layout: about
title: about
permalink: /

profile:
  align: left
  image: zhenyu-wu-profile.png
  image_circular: true
  more_info: >
    <div class="profile-card">
      <h1 class="profile-name">Zhenyu Wu</h1>
      <p class="profile-role">Ph.D. Candidate in Computer Science</p>
      <div class="profile-meta">
        <a href="https://www.manchester.ac.uk/" target="_blank" rel="noopener noreferrer">University of Manchester</a>
        <a href="mailto:zhenyu.wu@manchester.ac.uk">zhenyu.wu@manchester.ac.uk</a>
      </div>
      <nav class="profile-social-links" aria-label="Professional profiles">
        <a href="https://scholar.google.com/citations?user=Fe9k8sYAAAAJ&amp;hl=en" aria-label="Google Scholar" title="Google Scholar" target="_blank" rel="me noopener noreferrer"><i class="ai ai-google-scholar" aria-hidden="true"></i></a>
        <a href="https://github.com/PierreWoL" aria-label="GitHub" title="GitHub" target="_blank" rel="me noopener noreferrer"><i class="fa-brands fa-github" aria-hidden="true"></i></a>
        <a href="https://www.linkedin.com/in/zhenyu-w-7443a4254/" aria-label="LinkedIn" title="LinkedIn" target="_blank" rel="me noopener noreferrer"><i class="fa-brands fa-linkedin" aria-hidden="true"></i></a>
      </nav>
      <div class="profile-research" aria-label="LLMs, Structured Data and Ontology; Schema and Taxonomy Inference; Data Discovery and Exploration">
        <span class="profile-research-label">Research focus</span>
        <span>LLMs, Structured Data &amp; Ontology</span>
        <span>Schema/Taxonomy Inference</span>
        <span>Data Discovery and Exploration</span>
      </div>
    </div>

selected_papers: true
social: false

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<style>
  @layer theme {
    .post article > .profile {
      float: none !important;
    }
  }

  .post > .post-header {
    display: none;
  }

  .post article {
    display: grid;
    grid-template-columns: 14rem minmax(0, 1fr);
    column-gap: 3rem;
    align-items: start;
  }

  .post article > .profile {
    grid-column: 1;
    grid-row: 1;
    width: 100%;
    margin: 0 !important;
    text-align: center;
  }

  .post article > :not(.profile) {
    grid-column: 2;
    min-width: 0;
  }

  .post article > .profile figure {
    width: 10.5rem;
    margin: 0 auto 1rem;
  }

  .post article > .profile img {
    display: block;
    width: 10.5rem;
    height: 10.5rem;
    aspect-ratio: 1;
    object-fit: cover;
    object-position: center top;
    border-radius: 50%;
  }

  .post article > .profile .more-info {
    margin: 0;
    font-family: inherit;
    text-align: center;
  }

  .profile-card p {
    display: block !important;
    margin: 0;
  }

  .profile-name {
    margin: 0;
    font-size: 1.35rem;
    font-weight: 600;
    line-height: 1.3;
  }

  .profile-role {
    margin-top: 0.4rem !important;
    color: var(--global-text-color-light);
    font-size: 0.9rem;
    line-height: 1.45;
  }

  .profile-meta {
    margin-top: 0.8rem;
    font-size: 0.86rem;
    line-height: 1.55;
  }

  .profile-meta a {
    display: block;
    overflow-wrap: anywhere;
  }

  .profile-social-links {
    display: flex;
    justify-content: center;
    gap: 1rem;
    margin: 1rem 0 1.1rem;
    font-size: 1.35rem;
    line-height: 1;
  }

  .profile-social-links a {
    color: var(--global-text-color);
  }

  .profile-social-links a:hover,
  .profile-social-links a:focus-visible {
    color: var(--global-theme-color);
    text-decoration: none;
  }

  .profile-research {
    padding-top: 1rem;
    border-top: 1px solid var(--global-divider-color);
    font-size: 0.84rem;
    line-height: 1.45;
  }

  .profile-research-label {
    margin-bottom: 0.55rem;
    color: var(--global-text-color-light);
    font-size: 0.7rem;
    font-weight: 600;
    letter-spacing: 0.08em;
    text-transform: uppercase;
  }

  .profile-research span {
    display: block;
  }

  .profile-research span + span {
    margin-top: 0.45rem;
  }

  .about-main-title {
    margin-top: 0;
  }

  @media (max-width: 767.98px) {
    .post article {
      display: block;
    }

    .post article > .profile {
      max-width: 22rem;
      margin: 0 auto 2rem !important;
    }
  }
</style>

<h2 class="about-main-title">About</h2>

I am a final-year Ph.D. candidate in Computer Science at the
[University of Manchester](https://www.manchester.ac.uk/), expecting to complete
my Ph.D. in October 2026.

My research focuses on building practical LLM and machine-learning systems for
heterogeneous structured data. I develop methods that turn minimally documented
table repositories into useful schemas, taxonomies, and semantic relationships,
combining representation learning, prompting, clustering, and structured
validation.

Across my doctoral work, these systems have improved F1/Recall by 30–40% and
Rand Index by 7–10% over prior approaches. My current work extends this direction
to agentic multi-database question answering, schema linking, and Text-to-SQL.

I am interested in **Applied Scientist** and **Research Scientist** opportunities
where language models meet real-world data systems, across Asia-Pacific and
internationally.

[Explore my research](/research/) · [View publications](/publications/) ·
[Read my CV](/cv/)

## Research interests

- Large language models for structured and tabular data
- Schema, taxonomy, and ontology inference
- Knowledge graphs and semantic data integration
- Agentic multi-database question answering
- Representation learning for heterogeneous data repositories

## Selected toolkit

Python · PyTorch · Hugging Face Transformers · vLLM · LangChain · LangGraph ·
SQL · C++ · Linux
