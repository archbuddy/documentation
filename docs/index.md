# Overview

Our mission is to create a open source tool to help solution/software architects, tech leads, Principals and general IT people to understand how the applications are connect in the ecossystem of the company

There are several ways to map architecture with a lot of different frameworks, such:

- [Archimate](https://www.archimatetool.com/)
- [UML](https://pt.wikipedia.org/wiki/UML)
- [TOGAF](https://www.opengroup.org/togaf)
- [C4](https://c4model.com/)

Our idea here is not to use a framework and use a more practical way to do it, with less maintenance effort and more visibility

## General idea

Based on the C4 Model we are bringing first what we call Level 0 of architecture that it shows something like this:

<div style="text-align: center">
``` mermaid
graph TD;
  SystemA-->SystemB;
  SystemA--Some information-->SystemC;
  SystemC--Some information-->SystemA;
```
</div>

## Metamodel
Defines how all components are connected and can be connected and how you can read it

## Not covered
This software, **for now**, will not focus on the internal software architecture but in how softwares talk to each other