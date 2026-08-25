# Aar-Act: CyberAar Community Knowledge Base

[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](CONTRIBUTING.md)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE)

Community-driven security practices, guides and templates from **CyberAar**, written in French and English.

Most hardening guidance assumes a vendor budget, a fast link and a maintenance
window. This knowledge base is written for the machines that have none of those:
constrained bandwidth, older hardware, no licence to renew, and an operator who
has to be able to read every step and check it themselves. Everything here is
open source, and everything is meant to be verifiable by the person applying it.

The project began in Dakar, prompted by attacks on public systems, and West
African public infrastructure remains the worked example throughout. The
practices are not specific to one country and contributors are welcome wherever
they are.

> *Une infrastructure que l'on peut inspecter, comprendre et corriger soi-même.*

---

## What's Inside

| Directory | Description |
|---|---|
| `practices/` | Security guides and best practices (English) |
| `translations/` | French versions of the guides |
| `examples/` | Templates, case studies and sample reports |

Guides are numbered, and a translation carries the same number as its source
guide so the pair stays obvious.

---

## Related

The automated hardening tooling lives in a separate repository:

- **[cyberaar/aartool](https://github.com/cyberaar/aartool)**: audit, plan,
  apply and prove. Ships the `cyberaar.hardening` Ansible collection and the
  `cyberaar-baseline.sh` audit script.

This repository explains the practice. aartool automates it. A guide here should
make sense to someone who never runs the tool.

---

## How to Contribute

See [CONTRIBUTING.md](CONTRIBUTING.md). In short: new guides go in `practices/`
in English, French versions go in `translations/`, keep pull requests small and
focused, and open an [issue](https://github.com/cyberaar/Aar-Act/issues) to
propose a topic before writing a long one.

---

## License

GPL-3.0. See [LICENSE](LICENSE).
