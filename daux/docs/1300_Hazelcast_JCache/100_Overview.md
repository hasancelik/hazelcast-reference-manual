
Starting with Hazelcast 3.3.1, Hazelcast offers a specification-compliant JCache implementation. To show our commitment to this
important specification that the Java world was waiting for over a decade, we did not just provide a simple wrapper around our existing
APIs; we implemented a caching structure from the ground up to optimize the behavior to the needs of JCache.
The Hazelcast JCache implementation is 100% TCK (Technology Compatibility Kit) compliant and therefore passes all specification
requirements.

In addition to the given specification, we added some features like asynchronous versions of almost all
operations to give the user extra power.  

This chapter gives a basic understanding of how to configure your application and how to setup Hazelcast to be your JCache
provider. It also shows examples of basic JCache usage as well as the additionally offered features that are not part of JSR-107.
To gain a full understanding of the JCache functionality and provided guarantees of different operations, read
the specification document (which is also the main documentation for functionality) at the specification page of <a href="https://www.jcp.org/en/jsr/detail?id=107" target="_blank">JSR-107</a>.





