# Hybrid Cloud Patterns

Hybrid Cloud Patterns are an opinionated GitOps environment for OpenShift that lowers the bar for those creating repeatable and declarative deployments. It’s value is most apparent when delivering demos and solutions that combine multiple projects and technologies.  Our skeleton allows creators to focus on what needs to be delivered while we take care of how to do so using best practices.

A common gitops seed, applied to a blank OpenShift cluster and pointing to the solution in Git, allows the cluster to completely configure itself - including elements traditionally handled with scripting and extending beyond the cluster.

With our consistent approach between patterns, consumers and authors know that their investment in understanding one pattern helps them understand any other.  An emphasis on modularity also encourages reuse of building blocks between patterns, further shortening the time needed to generate new demos  and allowing SMEs to focus on leveraging their domain knowledge. 

By making repeatable deployments of even complex solutions easy, we facilitate the use of CI to ensure the solutions do not suffer bit-rot as products release new versions.  The library of patterns make great tests for significant parts of the Red Hat portfolio, and have been shown to catch real world issues before they impacted customers.
