# Overview

Our mission is to create a open source tool to help solution/software architects, tech leads, Principals and general IT people to understand how the applications are connect in the ecossystem of the company

There are several ways to map architecture with a lot of different frameworks, such:

- [Archimate](https://www.archimatetool.com/)
- [UML](https://pt.wikipedia.org/wiki/UML)
- [TOGAF](https://www.opengroup.org/togaf)
- [C4](https://c4model.com/)

Our idea here is not to use a framework and use a more practical way to do it, with less maintenance effort and more visibility

## Overal status
This product is in very early stage and if you want to join the team please contact me on linkedin: https://linkedin.com/in/brunopenso

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

Check [here](./metamodel.md)

## Organization of this product
This product is organized in 3 big repositories:
- Documentation: Generate this [documentation](https://github.com/archbuddy/documentation) that you are reading and hosts the [discussions](https://github.com/archbuddy/documentation/discussions) and [issues](https://github.com/archbuddy/documentation/issues) of all you
- Frontend: [React application](https://github.com/archbuddy/frontend) to show the graph an interact with people
- Backend: [Backend application](https://github.com/archbuddy/backend) to handle all the interactions

## Not covered
This software, **for now**, will not focus on the internal software architecture but in how softwares talk to each other