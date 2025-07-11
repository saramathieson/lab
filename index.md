---
---

# Mathieson Lab Website

We are a computational lab focusing on developing machine learning algorithms for biological data. Currently we are working on inference tasks related to natural selection and demographic inference, as well as generative models for genomic data from humans, mosquitos, and other species.

{% include section.html %}

## Current Projects

{% capture text %}

We are applying generative models to *Anopheles gambiae* mosquitos from Africa to learn about their evolutionary history, specifically migration between populations for the purpose of understanding insecticide resistance.

{% endcapture %}

{%
  include feature.html
  image="images/mosquito.pdf"
  title="Generative models for mosquitos"
  text=text
%}

{% capture text %}

We are working on interpretability approaches for machine learning methods in population genetics, including GANs and CNNs.

{% endcapture %}

{%
  include feature.html
  image="images/interpret.jpg"
  title="Interpretability"
  text=text
%}

{% capture text %}

We are working on transformer and hybrid-style models for a range of tasks, including introgression inference and long-range dependency prediction.

{% endcapture %}

{%
  include feature.html
  image="images/attention.jpg"
  title="Transformers"
  text=text
%}
