# Canary Monitoring Agent Buildpack

This repository contains a Heroku Buildpack for the Canary Monitoring Agent.

For an example on how to use this, see https://github.com/Canary-Monitoring-Inc/cma-buildpack-example.

In order to send telemetry data from your other dynos using the Canary Monitoring In-Process Agents,
please make sure to enable DNS in your space, see https://devcenter.heroku.com/articles/dyno-dns-service-discovery,
then configure the in-process agents to point at the dyno you deployed the monitoring agent on.
