# Custom Suricata Rules

Custom Suricata Rules to support IDS/IPS visibility for protocol or other parameters that are not available in the default ET-Pro or Community Feeds.


## License

Dual-licensed, **attribution required** under both:

- **Code & configuration** (scripts, rules, decoders, pipelines, configs): [Apache License 2.0](LICENSE)
- **Docs, guides & diagrams** (README, docs, diagrams): [CC BY 4.0](LICENSE-docs)

See [`LICENSING.md`](LICENSING.md) and [`NOTICE`](NOTICE). Credit: Lester E. Nichols III, secdoc.tech.

## GitLab CI baseline

GitLab CI runs repository integrity validation and secret scanning. The baseline validates tracked Python syntax, shell syntax, and JSON parsing, while the secret scan uses a pinned public container image. Repository-specific build and test gates remain additive to this baseline.

