telemetry = form of logging

uber service architecture

kibana - ok


# OT signals
1. Traces - errors
2. Metrics - positive data
3. Logs - informative data


# Benefits
1. Unified Approach
2. Interoperability
3. Rich Context


# Signals Process
1. Instrumentation
2. Collection
3. Processing
4. Exporting
5. Analysis, Visualisation

2-5 OT

Flask , fastapi

FlaskInsturmentor().instrument_app(app)

Custom

from opentelemetry import trace
tracer = tracer.get_tracer(__name__)

with tracer.start_as_current_span():
    do s sth


https://grafana.com/blog/2023/11/20/ci-cd-observability-via-opentelemetry-at-grafana-labs/


Sends to the backend json data

Jaeger

