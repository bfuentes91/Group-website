---
layout: default
---
Title: "learning how to build websites with Jekyll"
---
lesson example: "https://carpentries.github.io/lesson-example/"




[] [!][Group website banner] (./image/site_banner.png) (https//my site)

# My research project
## Description
{{ site.description }}

{{% assign lead = site.team_members | where: "role", "project lead" | first %}}
The project is led by {{ lead.name }}.
[See our full team] (about#team). 

{{ lead.name }}

This research project is all about teaching you how to create websites with Github pages
More details from the [About page] (about)
See more [examples of our work] ({{page.lesson-example }})
Have any questions about what we do? [We'd love to hear from you!] (mailto:{{site.email }})

