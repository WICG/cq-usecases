# Use Cases and Requirements for “Container Queries”

Given a complex responsive layout, developers often require a more granular level of control over how the contents of an individual module will respond relative to the size of their parent container rather than the viewport size. This is prohibitive to the goal of creating modular, independent components, often requiring a number of redundant CSS, complex exception cases, and workarounds, and the problem compounds itself depending on how dramatically a module adapts at each of its breakpoints.

This document aims to present some of the use cases that an “element query” syntax would solve, by allowing authors to define layouts within an individual module on the basis of the size of the module itself, rather than the viewport.

The spec proper can be found at <https://wicg.github.io/cq-usecases/>.

## Found a bug? Want to contribute something?
If you found a problem with the document, no matter how small,
please [file a bug](https://github.com/WICG/cq-usecases/issues).

See also our [contributor's guide](CONTRIBUTING.md).

Proposals for normative changes to this document should take
place on the [WICG mailing list](mailto:public-wicg@w3.org).

## Join us!
[Join the WICG](http://www.w3.org/community/wicg/) and help make the Web a better place for <s>images</s> everything.

[Join us on Slack](https://join.slack.com/t/containerqueries/shared_invite/enQtMzA2OTc5MDUwNjk1LTEwMWEzNjcwMTY1MGYzYWMyOGMxM2MzNDM1OGZjMjM3NDNiMDMxYTk0YjQxN2FjYTZkYmZkMDZmOWE1ODRkZWI).