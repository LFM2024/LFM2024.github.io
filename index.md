---
title: Home
---

# Abstartact!

{% include figure.html img="uidaho-workshop.jpg" alt="intro image here" caption="Library workshop" width="75%" %}

The successful operation of any autonomous agent heavily depends on capturing and understanding the complex nature of the environment, including its volatile or implicit characteristics. Even though robotics is undergoing rapid development, several application areas are still hindered by limitations in how the environmental information is represented. Qualities that might be missing from state-of-the-art representations include the relations between environment features, meta-information describing the quality and applicability of the representation itself, etc.
Considering these needs, in this workshop, we go beyond the discussion on traditional semantic maps and aim to initiate the development and application of novel implicit and explicit knowledge representations for robotics.
We bring together researchers with versatile expertise and backgrounds to achieve this goal. Through gathering such a group, we aim to fulfil the following three objectives:
1. We aim to provide a platform to formulate and communicate the most urgent needs for representations in robotics.
2. We want to expose the robotic community to recent developments in relevant fields such as AI and cognitive science.
3. As a result, we want to pave the road for developing novel representations reaching beyond the state of the art.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | relative_url }}){% endif %}
{% endfor %}
</div>

> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
