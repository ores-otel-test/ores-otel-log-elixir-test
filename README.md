# ores-otel-log-elixir-test

Exact-head conformance harness for **elixir**.

This repository tests both `ores-otel/ores.otel.log` and `ORESoftware/next-loggers.ts` using explicit commit SHAs.
The required native command is recorded in `conformance.json`: `mix format --check-formatted && mix test --warnings-as-errors`.
