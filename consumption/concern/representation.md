# [API](../../) [Consumption Navigator](../): Representation

The consumed API provides a service through some API style and exchanged representations to deliver that service. Coupling can be decreased when the consuming service does not directly depend on the model and the representation of the consumed API, but instead has its own model of the service that it is consuming, and then maps this model to the consumed API's specific representation. In this case, it becomes easier to adjust to changes in the consumed API, or to even replace it with a different one with a different specification, but with the same general model when seen from the perspective of the API consumer.

* Do you convert the representations you are consuming into internal models before operating on that data, i.e. canonical formats?
   
* Do you have code that responsibly handles invalid representations?
  
* Do you robustly handle changes in representations over time (e.g. via evolution of the API you are consuming)?
  
* Do you have runtime protection in place to inspect representations for malicious code injection?
  
* Do you have tests that validate these runtime protections?
