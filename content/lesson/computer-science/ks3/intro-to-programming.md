+++
date = "2017-05-20T10:05:06+08:00"
draft = false
title = "Introduction to Programming"
# Menu configuration
[menu.main]
# Creator's Display name
creatordisplayname = "Mick Clarke"
# Creator's Email
creatoremail = "mick.clarke@outlook.com"


# Type of content, set "slide" to display it fullscreen with reveal.js
type="page"

# page identifier (when empty menu entry will not display for this page)
identifier="intro-prog-01" 
# identifier of the parent's page (when empty, page will be attached to rootpage)
parent="cs-main-02" 
# Order page menu entry
weight = 1
+++



An intro to programming

![](/images/lessons/intro-to-prog/IDLE-Editor.png?classes=border,shadow)


Compare code highlighting:

**Simple:**

```python
def _hello():
    # Print out the message
    print ("Hello World!!")

_hello()

```

**Using Pygments (gives you line numbers and other things)**

Syntax in MD is:

~~~text

{{</* highlight go "linenos=inline,hl_lines=2 3" */>}}

YOUR CODE, where 'linenos=inline' turns on line numbering
            and 'hl_lines' gives the range of lines to be highlighted

{{</* / highlight */>}}

~~~

{{< highlight python "linenos=inline,hl_lines=2 3" >}}
def _hello():
    # Print out the message
    print ("Hello World!!")

_hello()

{{< /highlight >}}

**Doesn't render in Edge**

{{<revealjs theme="moon" progress="true" controls="true" progress="true" history="false">}}
## Lesson Overview

A practical lesson as an introduction to learning Python. (One Hour)

___

## Objectives

- Understand what computers are for
- Understand how we can control computers
- Learn how to instruct a computer using **Python**
    + "Hello World!!" (standard)
    + Loops to output many times (intermediate)
    + Strings and manipulation (advanced)
___

## Outcomes

- **All:** 
    + will know that code tells a computer to do work
    + and know what syntax is
- **Most:** 
    + will know how to write simple "Hello World" code in Python
    + and save it to a file to reuse
- **Some:** 
    + will be able to fix errors in their code
    + will add to their code and solve logical problems in the code

---

# Computers

## What is the purpose of a computer?

+ In pairs, discuss and come up with an answer. 
    + [Two minutes]
+ One person from each pair write the answers on whiteboard.

___

## The Answer

- All the answers lead to the right one
    + **Automation!!**
    + Computers do work we find boring, repetitious or difficult.

{{</revealjs>}}

