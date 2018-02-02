## FlexMesh : Flexibly Chaining Network Features on Programmable Data Plane


Programmable data planes (PDP) enable operators to incorporate various network features and define the chains of these features in a _switch profile_.
However, with the number of deployed features increasing, the _switch profile_ inevitably faces growing complexity during development and inflexibility to chain network features at runtime.

This paper presents FlexMesh, an integrated platform which aims to introduce flexibility and simplicity to PDP while being compatible with existing programmable devices.
FlexMesh designs (1) a set of chaining primitives, so operators can easily describe the feature chain for each flow without facing the complexity of customizing the switch profile during development;
and (2) a data plane model that can be configured at runtime and flexibly construct user-required feature chains.
We implement FlexMesh based on P4 and evaluate it on software and hardware targets.
Results indicate that with minor performance overheads,
FlexMesh can be an efficient development-assistance tool for operators, as well as an automated platform to flexibly chain network features while keeping rigorous conformance to complex policies.