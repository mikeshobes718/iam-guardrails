# IAM Guardrails

[![CI](https://github.com/mikeshobes718/iam-guardrails/actions/workflows/ci.yml/badge.svg)](https://github.com/mikeshobes718/iam-guardrails/actions/workflows/ci.yml) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

IAM role/policy validation and drift detection with safe update previews; policy-as-code guardrails for AWS environments.

## Features
- IAM policy linting and best-practices validation
- Drift detection vs. desired state (JSON/YAML)
- Safe update previews and apply with backups

## Quickstart
```bash
# Coming soon: CLI entrypoint
python -m iam_guardrails --help
```

## Architecture
- Python + boto3, policy-as-code configuration
- Change plans with explicit approvals

## Roadmap
- Automatic least-privilege suggestions
- CloudTrail-informed risk checks

## License
MIT
