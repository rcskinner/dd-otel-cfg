# Datadog Telemetry Collection Testing

Purpose: Look at the different options available to gather telemetry and visualzie telemetry in Datadog. 

**Configuration Options Evaluated:**
1. Datadog Agent + Datadog SDKs 
2. Datadog Agent + OTel SDKs 
3. OTel Collector + OTel SDKs 


## Target Application 
Working off of the roll-dice python application for the examples:

https://opentelemetry.io/docs/languages/python/getting-started/



## Datadog Agent + Datadog SDKs
 
Leverage the Datadog Agent + Datadog autoinstrumentation in k8s to collect telemetry from the services running 


## Datadog Agent + OTel SDKs
Use the Datadog Agents OTLP Trace Ingest capability to leverage the Datadog Agent for the infrastructure monitoring and the OTel SDKs to instrument the application 

