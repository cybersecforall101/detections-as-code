# detections-as-code

Detection rules for Elastic, written as code: each rule has its own test
events, a passing validation, and an ATT&CK mapping.

**Status:** work in progress (started Nov 2026).

## Goal
10-15 detections across AWS CloudTrail and Windows endpoint logs, with:
- a positive and a negative test event per rule
- automated validation and tests in CI
- an ATT&CK coverage table
- a write-up of one false-positive fix, with before and after numbers

## Stack
Elastic Stack, Python, KQL, EQL, ECS.

## Licence
MIT for the code and rules in this repo. Elastic's detection-rules repo is
used as a reference only and is under the Elastic License v2.