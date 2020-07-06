# [CAM](../../) [Consumption Navigator](../): Reporting

In order to manage the dependency on an API it is important to understand how that external dependency is behaving. This can be useful for observation and for analytical purposes (to understand the history of past behavior patterns), but it also can be used to define normal behavior patterns, and to initiate warnings and mitigation actions when the API starts to behave outside of the bounds of acceptable behavior.

* Do you have an established set of metrics all API consumers must record?
  - Latency, Errors, Traffic, Saturation ([LETS](https://www.amazon.com/Site-Reliability-Engineering-Production-Systems/dp/149192912X/))
  - Utilization, Saturation, Errors ([USE](http://www.brendangregg.com/usemethod.html))
  - Rate, Errors, Duration ([RED](https://www.weave.works/blog/the-red-method-key-metrics-for-microservices-architecture/))

* Do you have the ability to correlate API consumption with application logic?
  
* Do you have a dashboard service in place to display API consumer metrics?
  
* Do you have an automated process that notifies you when metrics are unusual?
  
* Do you have an automated process that takes corrective actions when metrics are unusual?


