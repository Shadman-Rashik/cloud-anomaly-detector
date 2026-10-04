# cloud-anomaly-detector
A small Python project where I tried to detect incidents in real AWS server data.

## What it does
- Reads a server metric from the Numenta Anomaly Benchmark (NAB).
- Flags unusual points two ways: a simple rolling rule and Isolation Forest.
- Compares both against the known real incident windows.
