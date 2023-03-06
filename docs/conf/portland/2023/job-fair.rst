:template: {{year}}/generic.html

Job Fair
========

{% include "conf/events/job-fair.rst" %}

Schedule
--------

- Date & Time: **{{ date.day_four.date }}, {{ date.day_four.job_fair_time }} {{tz}}**.
- Location: **{{about.unconfroom}}**.

Full schedule information is available on our :ref:`{{shortcode}}-{{year}}-job-fair` page.

Useful tips
-----------

{% include "conf/events/job-fair-tips.rst" %}
