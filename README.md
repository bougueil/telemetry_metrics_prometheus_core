# TelemetryMetricsPrometheus.Core + ephemeral metrics (garbage collected at scrape time)

EXPERIMENTAL !!

Fork of https://github.com/beam-telemetry/telemetry_metrics_prometheus_core

Ephemeral metrics are garbage collected at scrape time so they **are not retained in memory**.

An ephemeral metrics name starts by the prefix `plot` like `plot.kpi.booking`.
