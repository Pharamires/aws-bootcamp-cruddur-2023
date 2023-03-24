# Week 2 — Distributed Tracing

## Required Homework

### Instrument Honeycomb with OTEL

Added opentelemetry instructions to requirements.txt file and all the dependencies to app.py file. Initialized tracing and an exporter that can send data to Honeycomb as welll as automatic instrumentation with Flask in app.py.

### Instrument AWS X-Ray

Added AWS X-Ray to the requirements.txt file as well as dependencies to the app.py. Added xray.json file and created X-Ray group.

![X-Ray Group](/assets/Week-2_Xray_Group.png)

### Instrument AWS X-Ray Subsegments

![X-Ray Subsegments](/assets/Week-2_Xray_Segment.png)

### Configure custom logger to send to CloudWatch Logs

![CloudWatch Logs](/assets/Week-2_CloudWatchLogs.png)

### Integrate Rollbar and capture and error
