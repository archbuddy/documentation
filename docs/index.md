# Overview

Our mission is to create a open source tool to help Solution/Software Architects, Tech Leads, Principals and General IT folks to understand how the applications are connect in the ecosystem of the company and some other features that are needed for this job.

Different from other software we will achive enterprise grade product that are only paid, it means, that we aren't delivering a diagram tool but a enterprise grade style where all objects are connect and can be reutilized in any kind of view.

There are several ways to map architecture with a lot of different frameworks, such:

- [Archimate](https://www.archimatetool.com/)
- [UML](https://pt.wikipedia.org/wiki/UML)
- [TOGAF](https://www.opengroup.org/togaf)
- [C4](https://c4model.com/)

Our idea here is not to use a framework and use a more practical way to do it, with less maintenance effort and more visibility but the firsts releases are focused on the C4 model framework.

## Overal status
This product is in very early stage and if you want to join the team please contact me on linkedin: https://linkedin.com/in/brunopenso

## General idea

Based on the C4 Model we are bringing first what we call Level 0 of architecture, or System Landscape, that it shows something like this:

<div style="text-align: center">
``` mermaid
graph TD;
  SystemA-->SystemB;
  SystemA--Some information-->SystemC;
  SystemC--Some information-->SystemA;
```
</div>

## Organization of this product
Check the development menu on the left

## Not covered
This software, **for now**, will not focus on the internal software architecture but in how softwares talk to each other