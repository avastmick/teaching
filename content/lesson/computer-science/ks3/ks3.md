+++
date = "2017-05-20T10:05:06+08:00"
draft = false
title = "Computer Science - KS3"
# Menu configuration
[menu.main]
# Creator's Display name
    creatordisplayname = "Mick Clarke"
    # Creator's Email
    creatoremail = "mick.clarke@outlook.com"


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