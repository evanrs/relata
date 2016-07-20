# relata
Primitives for an applied ontology

## Motivation

The data most of us will work with will be under defined. We have few constructs describing its nature, we hide knowledge in the implementation. Most of us are constrained to the arrays, maps, numbers, and strings that can be serialized to JSON. We may employ intricate solutions like [GraphQL*]() to get better semantics and enforce a strongly typed interface, but largely we avoid building a foundation to describe this knowledge.

Relata is an exploratory project to provide a tractable interface for describing knowledge.

If that sounds like the death knell of an over ambitious project, well… I would agree. Luckily others have done most of the work for us. This is inspired by work of those brave explorers of [ontologies](https://en.wikipedia.org/wiki/Upper_ontology) who wrestle the sea beast of [mereology](https://en.wikipedia.org/wiki/Mereology]).

Specifically Nicola Guarino, Chris Welty, Giancarlo Guizzardi, and likely many more who I have yet to credit.

Their work on [DOLCE](https://en.wikipedia.org/wiki/Descriptive_Ontology_for_Linguistic_and_Cognitive_Engineering) and [OntoClean](https://en.wikipedia.org/wiki/OntoClean) provide compelling conceptual models to describe the systems we build. Relata is an attempt to codify the notions of Identity, Unity, Rigidity, and Dependence in an implementation designed for humans first and computers second.
