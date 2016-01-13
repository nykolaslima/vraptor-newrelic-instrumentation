# vraptor-newrelic-instrumentation
NewRelic's custom instrumentation to better track VRaptor applications


NewRelic current doesn't support VRaptor framework. This lead to poor monitoring data, not identifying correctly the transactions.
With this instrumentation file, NewRelic will identify transactions by VRaptor's controller methods annotated with `@Post`, `@Get`, `@Patch`, `@Put` and `@Delete`.  
You should copy the  [instrumentation xml](https://github.com/nykolaslima/vraptor-newrelic-instrumentation/blob/master/newrelic-custom-instrumentation.xml) and configure it as described in [NewRelic documentation](https://docs.newrelic.com/docs/agents/java-agent/custom-instrumentation/java-instrumentation-xml)
