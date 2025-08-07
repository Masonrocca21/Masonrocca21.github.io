---
title: "Incremental Object Referral and Target Absent"
project-type: academic
subtitle: "A study on the human gaze and prediction by algorithms"
modal-id: 6
date: 2025-2-25
img: EyeGaze.png
modal-bg-color: "#f68ffaff"        # Colore di sfondo del popup (es. giallo)
modal-text-color: "#000000ff"      # Colore del testo (es. scuro)
alt: "Screenshot del platform 2D"

description: > # L'uso di > permette di scrivere su più righe
  As part of my academic path in human-computer interaction, I explored the subtle dynamics of how humans process language and visuals in real time, particularly in tasks where eye movements are driven by spoken descriptions.

  To dive deeper into this, I worked on adapting ScanDDM, a neuro-dynamical model for zero-shot attention prediction, to the incremental object referral, a setting in which humans listen to a referring expression while looking at an image, and incrementally shift their gaze based on the words they hear, and target absent task, a setting in which humans listen to a word describing an object missing in an image.

  This project allowed me to:
   - Explore gaze behavior modeling through stochastic differential equations and drift-diffusion mechanisms.
   - Bridge cognitive models with applied machine learning, adapting a scanpath simulator to process language one word at a time.
   - Work with real human gaze data, evaluating performance on the RefCOCO-Gaze dataset.
   - Compare models quantitatively and qualitatively, using human-like metrics such as Sequence Score, Fixation Edit Distance, and ScanMatch.

  Although the model I adapted did not outperform the task-specific state-of-the-art, it produced competitive results, demonstrating that zero-shot models like ScanDDM can be repurposed for incremental, real-time attention prediction — a key component in interactive systems like AR/VR interfaces, gaze-driven UI, and assistive tech.
  This experience strengthened both my research mindset and my ability to work at the intersection of cognitive science, AI, and HCI, advancing my academic growth in understanding how machines can better interpret — and anticipate — human behavior.


role:
  - Designer
  - Programmer
tags:
  - Python
  - Pytorch
  - Machine Learning

project-date: "Febbraio 2025"
client: "Natural interactions and Affective Computing courses"
---