<a href="http://predixdev.github.io/rmd-orchestration/javadocs/index.html" target="_blank" >
	<img height="50px" width="100px" src="images/javadoc.png" alt="view javadoc"></a>
&nbsp;
<a href="http://predixdev.github.io/rmd-orchestration" target="_blank">
	<img height="50px" width="100px" src="images/pages.jpg" alt="view github pages">
</a>
##RMD Orchestration
As data arrives (or changes) an event is placed on a messaging topic. This project reads messages off those queues, decides which Analytic Orchestration to invoke, grabs the BPMN and Analytic Configuration and passes that to the Predix Orchestration engine which in turn invokes [Analytic microservices](https://github.com/predixdev/rmd-analytics).

<img src='https://github.com/predixdev/predix-rmd-ref-app/raw/master/images/RefApp-AnalyticsFlow.png' >

##Tech Stack
- Spring
- SpringBoot
- SpringTest
- Maven
- Rabbit MQ

##Microcomponents
- [AssetBootstrap](https://github.com/predixdev/asset-bootstrap)
- [TimeseriesBootstrap](https://github.com/predixdev/timeseries-bootstrap)
- [PredixMicroServiceTemplates](https://github.com/PredixDev/predix-microservice-templates)
- [PredixRestClient](https://github.com/predixdev/predix-rest-client)

### More Details
* [More GE resources](http://github.com/predixdev/predix-rmd-ref-app/docs/resources.md)
* [RMD Reference App](http://github.com/predixdev/predix-rmd-ref-app)

[![Analytics](https://ga-beacon.appspot.com/UA-82773213-1/rmd-orchestration/readme?pixel)](https://github.com/PredixDev)
