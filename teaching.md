---
layout: photolist
title: Teaching & Supervising
menu: yes
---

## <span style="color:darkblue"> Students & Interns </span>
I supervise undergraduate/master students in the scope of
[Yandex Academic Supervision Program](https://yandex.ru/jobs/vacancies/research/scientific_leadership_prog/), and NLP research interns at [Yandex Research]({{site.yandex_research_main}})

The team:
* Fedor Moiseev, <span style="color:gray">December 2018-current (Yandex Academic Supervision Program)</span>
* Dmitriy Emelyanenko, <span style="color:gray">March 2019-current (Yandex Academic Supervision Program)</span>
* __you?__ Apply [here](https://yandex.ru/jobs/vacancies/research/scientific_leadership_prog/) for Yandex Academic Supervision Program or [here](https://yandex.com/jobs/vacancies/research/intern_researcher_eng) for NLP research internship



## <span style="color:darkblue"> Courses </span>
{% assign courses = (site.data.courses | where: "selected", "y") %}
{% for course in courses %}
{% include course.html course=course %}
{% endfor %}

