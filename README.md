<p align="center">
  <img width="540" src='./cps-metamodel.png' />
</p>

<p align="center">
  <strong>CPS-Metamodel.</strong> The antidote to safety, security, and resilience coengineering.
</p>

## About the paper

Georgios Bakirtzis, Tim Sherburne, Stephen Adams, Barry M. Horowitz, Peter Beling, and Cody H. Fleming, "An ontological metamodel for cyber-physical system safety, security, and resilience coengineering" [preprint]

## GraphQL schema

The [GraphQL schema](./cps-metamodel.graphql) is an algorithmic implementation
of the CPS metamodel. Our intention for creating a GraphQL representation is to decouple the metamodel from a particular tool or language. This means that you can use our schema provided you create an interface with GraphQL in your modeling tool of choice. This should be relatively straightforward for most tools. GraphQL also has a built-in querying language, which could be useful for interogating your models for particular pieces of information. An [online portal](https://ma-graphql-playground.now.sh/) is provided to navigate the schema documentation and to experiment with queries and mutations against the [pipeline-cps](https://github.com/coordinated-systems-lab/pipeline-cps) system model. NOTE: mutations do not perform any update and simply return the original model values. A few samples can be found [here](https://gist.github.com/tsherburne/3d3fd799771016ff0535388e1145b56e).

