# API [Product](./) [Navigator](../): Testing

With API product being the building blocks of digital transformation, it is important that they go through quality assurance to make them reliable and robust. Testing at the API level means that API products behave as required, run reliably, are robust against unintentional or unintentional ways of how the API is misused, scale as required and/or are protected against being overloaded, and have resilience built-in to avoid the risk of cascading failures. In addition, for consumers of the API product it can be very helpful if they can test their consumption of the API against a version of the product that allows them to conduct realistic tests without having to run them against the production version of the API product.

* Is testing using as much existing tooling as possible?

* Are there metrics in place to evaluate and observe the coverage of tests? Is test coverage mapped back to business requirements?

* Do your tests include scenarios where consumed APIs are not performing or are not reachable, in order to test for resiliency of the API product?

* Do you support testing of API consumers so that clients can be tested against environments or test modes of the API? Does this test environment provide representative test data that reflects the API behavior?

* Does your test strategy anticipate the predicted consumers, their behavior, and their scale?
