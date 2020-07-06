# [CAM](../../) [Consumption Navigator](../): Replacement

It can be important to have a replacement plan for a consumed API, or to at least start taking notes what could be done if the API becomes unavailable, both temporarily, or permanently. For temporary failures, it may be acceptable to stop depending on it (if the consuming service can still function at a degraded level), or to escalate the outage and have the consuming service fail as well. When the API becomes unavailable, it becomes critical to be able to replace the consumed API as soon as possible, to resume normal operations.

* Do you have a replacement plan in place for each consumed API?
  
* Have you identified at least one replacement for each API you consume?
  
* Do you have protection in place when an API becomes unavailable at runtime (circuit-breaker, etc.)?
  
* Do you have protection in place when you can no longer write to an existing API?
  
* Do you have tests defined that can validate your replacement implementation?
