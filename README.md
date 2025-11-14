
<img width="300" height="100" alt="image" src="https://github.com/user-attachments/assets/511b5d42-37ce-413f-a9c5-da7387e4eb75" />

## Datadog Guide for Service monitoring

- Datadog is an Application Performance Management tool.
- Other examples are: new relic, and dynatrace.


### Four Golden signs of monitoring

<img width="500" height="412" alt="image" src="https://github.com/user-attachments/assets/543049c5-1f82-40b7-95de-25ff3943aad2" />

---

#### How does Datadog collects data?

- From Datadog Agent
- Using Datadog API
- Using Integrations


#### What can Datadog be used for?

- To write easy and fast queries on traces, logs, metrics.
- To monitor server, application downtimes.
- Services request response rates and latencies
- SLOs(Service Level Objectives) like duration/requests etc.

## Datadog Terminology

#### Host

- A host is any physical or virtual operating system instance that you want to monitor with Datadog.
- In simple words, this is the server on which the **Datadog Agent** is installed.


#### Datadog Agent

- Datadog agent is a software that runs on the **hosts**, which collects events and metrics from hosts and sends them to Datadog.
- It acts as a middle layer between host and Datadog website.

#### Datadog Tags

- Tags are a way of adding dimensions to Datadog telemetries so that they can be filtered, aggregated and compared in Datadog visualizations.
- Example: `version: stage` or `version: prod`


## Datadog Agent

#### Working

- It has two major components:
  - **Collector** - collects data from host every 15sec
  - **Forwarder** - sends data to Datadog through `https`
 
- Main config files are `datadog.yaml` (including `config.toml` for macOS).











