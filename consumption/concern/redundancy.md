# [CAM](../../) [Consumption Navigator](../): Redundancy

When a consumed API shows problems, one possible strategy is to switch to an alternative API which may not offer the full functionality of the primary one, but still is a better option than simply stopping to consume the API. The functionality may be degraded in terms of functional coverage, or it may be degraded in other acceptable ways, such as providing data that is not quite as up-to-date as the primary API. Having plans for this kind of API redundancy can help to mitigate problems with the primary API, but requires planning and careful management of the secondary API so that it is available can can be used when necessary.

* Do you have at least one alternative provider for each consumed API (which might include changing API providers in the future)?
  
* Have you considered identifying a runtime "failover" plan with a different provider for each consumed API?
  
* Do you have tests in place (to run before deployment) to validate your redundancy implementation?
