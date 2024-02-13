---
layout: page
title: BO Hackathon for Chemistry and Materials
menu_title: Home
menu_icon: house-door
---

{:.secondary}
# {{ site.event_date }}, in association with the Acceleration Consortium

<div class="aside">
    <h2><i class="bi bi-calendar3"></i> Event timeline</h2>
    <dl>
        {% if site.registration_status == "soon" or site.registration_status == "open" or site.registration_status == "demo" %}
            <dt>{{ site.registration_opens_date }}</dt>
            <dd>
                Applications open for participants<br>
                {% if site.registration_status == 'open' %}
                    <a href="{{ site.baseurl }}{% link registration.md %}" class="btn">Register now</a>
                {% elsif site.registration_status == 'closed' %}
                    <a class="btn disabled">Registration has closed</a>
                {% elsif site.registration_status == 'soon' %}
                    <a class="btn disabled">Registration opens soon</a>
                {% endif %}
            </dd>
        {% endif %}

        <dt>{{ site.registration_closes_date }}</dt>
        <dd>Applications close</dd>

        <dt>{{ site.event_date }}</dt>
        <dd>Hackathon date</dd>
    </dl>
</div>

{% if site.event_status != "over" %}

The progress of a scientific field is both tracked and propelled through robust benchmarks. With the emergence of new [Bayesian optimization](https://chat.openai.com/share/ac610758-2ac8-4b38-8dd5-25e6c46ad2a6) tools applied or geared towards the physical sciences, it is important to understand its strengths and weaknesses relative to the state of the art. In this hackathon, we will put these tools to the test! Scientists from the Acceleration Consortium @ University of Toronto are hosting a 2-day hackathon on
{{ site.event_date }}, open to researchers, to select or develop Bayesian optimization algorithms and apply them to benchmarking tasks. After the hackathon, results will be collated and presented in a scholarly article (see co-authorship criteria below). Come join us to explore, collaborate, innovate, and contribute to the advancement of Bayesian optimization for the physical sciences.

Researchers can sign up to [topics ranging from]({{ site.baseurl }}{% link projects.md %})
application of algorithms to development of new benchmark tasks, and creating instructional tutorials. [This opportunity]({{ site.baseurl }}{% link registration.md %})
is open to researchers at all levels who are interested in applying Bayesian optimization[<sup>(?)</sup>][faq]{:title="Do I need to use a specific tool or package?"} for accelerated discovery in chemistry and materials science. At minimum, we recommend beginner-to-intermediate Python programming experience and basic familiarity with git and GitHub.[<sup>(?)</sup>][faq]{:title="What are the recommended prerequisites for participation?"}.

## Logistics

The event will take place virtually, using a combination of **video
conferencing** (Zoom) for meetings and seminars, and **discussion forums**
(Slack, Discord) for ongoing comms. Data holding and analysis will take place on...

## Outputs

By the end of the event, we hope to 

[faq]: {{ site.baseurl }}{% link faq.md %}

{% else %}

Scientists from the University of Bristol hosted a X-day hackathon on
{{ site.event_date }}, open to researchers, to...

Researchers could sign up to [topics ranging from]({{ site.baseurl }}{% link projects.md %})
... to ..., and more. Teams were be led by senior academics from a range of
disciplines at the University of Bristol, but participating researchers could be
from any UK academic institution.

The event took place virtually, using a combination of **video conferencing**
(Zoom) for meetings and seminars, and **discussion forums** (Slack) for ongoing
comms. Data holding and analysis took place on...

{% endif %}

## Sponsors 

- [The Acceleration Consortium @ University of Toronto](https://acceleration.utoronto.ca/)
- [Merck KGaA](https://www.emdgroup.com/en)