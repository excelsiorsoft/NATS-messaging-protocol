# NATS-messaging-protocol 



[https://nats.io/](https://nats.io/)

[NATS 2.0 Docs](https://nats-io.github.io/docs/)

[Baeldung Article](https://www.baeldung.com/nats-java-client)

[Source for the article](https://github.com/eugenp/tutorials/blob/master/libraries/src/main/java/com/baeldung/jnats/NatsClient.java)

<u>CloudEvents</u>

Outside the function code itself, applications written as serverless functions are tightly coupled to the cloud platform on which they're hosted. Although events are a common FaaS-triggering mechanism, and every cloud provider supports them in some form, the current proprietary specifications prevent interoperability across clouds. The [CloudEvents ](https://cloudevents.io/)specification is a burgeoning standard that has been accepted into the [CNCF Sandbox](https://www.cncf.io/sandbox-projects/). The standard is still in active development but several language bindings exist and Microsoft has announced first-class support in Azure. Hopefully other cloud providers will follow suit, but so far [AWS does not](https://www.theregister.co.uk/2019/07/16/amazon_aims_to_create_eventdriven_ecosystem_with_eventbridge/).

[CloudEvents Primer](https://github.com/cloudevents/spec/blob/master/primer.md)