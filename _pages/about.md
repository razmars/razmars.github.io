---
layout: about
title: about
permalink: /
subtitle: Researcher at <a href='https://www.bgu.ac.il/en/'>Ben-Gurion University of the Negev</a>

profile:
  align: right
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Ben-Gurion University of the Negev</p>
    <p>Be'er Sheva, Israel</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items

latest_posts:
  enabled: false
---

I am a researcher at Ben-Gurion University of the Negev, working with Prof. Omri Azencot.
My research sits at the intersection of **generative modeling** and **dynamical systems**: I use Koopman operator
theory to build fast, structured generative models for **probabilistic time-series forecasting**.

Most recently, I developed the **Koopman Generative Operator (KGO)** (NeurIPS 2026). KGO makes flow-matching
generation single-step through a closed-form matrix exponential in a Koopman latent space. It is state of the art
on most ProbTS benchmarks and runs inference at least 25× faster than iterative generative models.
