+++
date = "2017-05-21T18:36:24+02:00"
creatordisplayname = "Mick CLARKE"
creatoremail = "mick.clarke@outlook.com"
lastmodifierdisplayname = "Mick CLARKE"
lastmodifieremail = "mick.clarke@outlook.com"
tags = ["KS3", "Comp-Sci"]

draft = false
title = "Computer Science - KS3"
# Menu configuration
[menu.main]

# Type of content, set "slide" to display it fullscreen with reveal.js
type="page"

# page identifier (when empty menu entry will not display for this page)
identifier="cs-main-02" 
# identifier of the parent's page (when empty, page will be attached to rootpage)
parent="cs-main-01" 
# Order page menu entry
weight = 1
+++

The flow

{{<mermaid align="left">}}
graph LR;
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
{{< /mermaid >}}