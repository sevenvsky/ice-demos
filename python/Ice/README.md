Demos in this directory:

- [async](./async)

  This demo illustrates the use of Asynchronous Method Invocation
  (AMI) and Asynchronous Method Dispatch (AMD).

- [bidir](./bidir)

  This demo shows how to use bidirectional connections for callbacks.
  This is typically used if the server cannot open a connection to the
  client to send callbacks, for example, because firewalls block
  incoming connections to the client.

- [callback](./callback)

  A simple callback demo that illustrates how a client can pass a
  proxy to a server, invoke an operation in the server, and the server
  call back into an object provided by the client as part of that
  invocation.

- [context](./context)

  This demo shows how to use Ice request contexts.

- [hello](./hello)

  This demo illustrates how to invoke ordinary (twoway) operations, as
  well as how to invoke oneway operations, use datagrams, secure
  invocations, and how to use batched invocations.

- [latency](./latency)

  A simple latency test that measures the basic call dispatch delay of
  Ice.

- [metrics](./metrics)

  This demo illustrates how to retrieve metrics information from an
  Ice application.

- [minimal](./minimal)

  This demo illustrates a minimal Ice application.

- [optional](./optional)

  This demo shows the use of the optional keyword.

- [properties](./properties)

  Shows how to access a server's PropertiesAdmin facet in order to
  retrieve and modify its configuration properties, and how the server
  can receive notifications whenever its properties are changed.

- [session](./session)

  This demo shows how to use sessions to clean up client-specific
  resources in a server after the client shuts down or crashes.

- [throughput](./throughput)

  A simple throughput demo that allows you to send sequences of
  various types between client and server and to measure the maximum
  bandwidth that can be achieved using serialized synchronous
  requests.
