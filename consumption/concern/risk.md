# [API](../../) [Consumption Navigator](../): Risk

Each consumed API constitutes a risk because it is a dependency that needs to be managed and this will cost resources over time. If the dependency is not managed, this simply means that the risk is unmanaged and that a failure in the dependency can cause cascading problems. Because of this inherent risk that each dependency causes, it is always important to ask whether it is worth taking the risk, and whether the risk is managed responsibly.

* Do you have a view of all APIs consumed by a single service?
  
* Do you have a plan for replacing each dependency (API) w/ another solution?
  
* What runtime protection do you have in place in case the API becomes too slow, or unreachable?
  
* If you consume data from an API, do you have a plan to manage a cache or duplicate set of that data?
  
* If you write data using an API, do you have runtime protection in place if the service fails to confirm writes/updates/deletes?
  
* Do you monitor the "health stats" of the APIs you are consuming and have alerting to those managing the API and its consumers?

