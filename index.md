---
layout: about
title: Luiz Felipe Vecchietti
---

I am currently a **Postdoctoral Researcher** at the **Max Planck Institute for Security and Privacy (MPI-SP), Germany** with Director [Meeyoung Cha](https://scholar.google.com/citations?user=iFlnVCoAAAAJ&hl=en). Previously, I was a Postdoctoral Researcher at the Institute for Basic Science, South Korea. I received my PhD from KAIST and my Bachelor's and Master's degrees from the Federal University of Rio de Janeiro, Brazil.

## Research Interests

My research vision is to develop safe artificial intelligence algorithms for multi-agent systems that advance our knowledge on **how humans and machines learn, interact, and collaborate**.

My general research interests include Reinforcement Learning, Multi-Agent Systems, and Robotics. From these, I am particularly interested in:

- **Reinforcement Learning**: continual learning, multi-agent RL, improving sampling efficiency and performance by developing novel credit assignment and exploration methods, and goal-conditioned RL.
- **Multi-Agent Systems**: development of multi-agent RL algorithms in collaborative and collaborative-competitive environments, modeling of continual multi-agent frameworks.
- **Robotics**: end-to-end control, safety and risks of robotic systems, and hardware security.
{% comment %}
- **AI for Science**: generative AI for protein and antibody design, flexible AI architectures (graph neural networks, diffusion models).
{% endcomment %}

{% comment %}
## News

<ul class="news-list">
{% for item in site.data.news limit:10 %}
<li><span class="news-date">[{{ item.date }}]</span> {{ item.text | markdownify | remove: '<p>' | remove: '</p>' | strip_newlines }}</li>
{% endfor %}
</ul>
{% endcomment %}

## Selected Publications

{% bibliography --query @*[selected=true] %}

{% comment %}
## Invited Talks

<ul class="news-list">
{% for talk in site.data.talks %}
<li><span class="news-date">[{{ talk.key }}]</span> <em>{{ talk.title }}</em><br>
{{ talk.venue }}, {{ talk.date }}.{% if talk.note %} <em>{{ talk.note }}</em>{% endif %}</li>
{% endfor %}
</ul>
{% endcomment %}

## Diversity Statement

I am committed to increasing diversity in AI research. If you are from an underrepresented group and need research mentoring and guidance, feel free to contact me for a mentoring session.

## Personal Interests

My personal interests include traveling, sports (football, kickboxing, skate, snowboard, surf, surfskate), music (classical guitar, cavaquinho) and reading (fantasy, science fiction, mountaineering).
