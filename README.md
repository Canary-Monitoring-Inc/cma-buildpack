# Canary Monitoring Agent Buildpack

This repository contains a Heroku Buildpack for the Canary Monitoring Agent.

To add this buildpack, execute

    heroku buildpacks:add --index 1 https://github.com/Canary-Monitoring-Inc/cma-buildpack
    heroku heroku config:add CANARY_API_TOKEN=<CANARY_API_KEY>

Any Canary In-Process Agents will now have their telemetry collected and sent off to the Canary backend.
