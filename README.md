![tugboat logo](./tugboat_128.png)

# tugboat

**Targeted Unique Generator**

A lightweight API service that, given a set of environment variables or arguments,
checks for a running resource with an identical configuration in a Docker
or Kubernetes environment. If found, it returns the resource’s identity;
if not, it launches a new one, waits until it is ready, and returns its identity,
ensuring deduplicated, on-demand provisioning of containerized applications.
