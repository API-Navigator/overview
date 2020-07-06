# [CAM](../../) [Consumption Compass](../): Resilience

A consumed API can behave in unexpected ways by showing degraded behavior, or by becoming unavailable. Consuming services should make sure to keep these behaviors in mind, and to mitigate them as much as possible through responsible coding techniques such as time-outs and fallback solutions. The main goal to keep in mind is that no behavior of the consumed API should make the consuming service behave in unplanned ways.

* Do you have runtime protection in place in case the API becomes too slow, or unreachable?
  
* Do you have runtime support in place for failed API state changes that write data?
  
* Do you have timeouts in place to prevent waiting too long for an API response?
  
* Do you send failfast timing budget values to APIs when you send a request to them?
  
* Do you use parallel requests where possible?

 
