Flex4 : On-demand Orchestration of Network Features on the Programmable Data Plane


P4 enables operators to incorporate various network features and customize a switch profile through programming the control flow among these features.
However, as the incorporated features increase in number, the switch profile inevitably incurs growing complexity in development and inflexibility to orchestrate features at runtime.

This framework includes (1) a set of specification primitives, so operators can arbitrarily describe the desired feature orchestration for each flow at runtime without facing the complexity of programming the \textit{switch profile} during development; and (2) an innovative data plane model that supports mapping the user-specified orchestration to the data plane at runtime and flexibly enforces various orchestrations.


We implement Flex4 on software and hardware targets respectively and evaluate it based on comprehensive benchmarks. Results indicate that Flex4 can remarkably simplify the development of P4 programs and enhance the flexibility of the programmable data plane.
