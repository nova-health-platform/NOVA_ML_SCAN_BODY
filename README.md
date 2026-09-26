<div align="center">
  <img src=".github/assets/banner.png" alt="NOVA_ML_SCAN_BODY banner" width="100%" />

  <h1>NOVA_ML_SCAN_BODY</h1>

  <p>
    Computer vision module for the dermatological check-up feature of the NOVA health platform.
  </p>

<p>
  <a href="https://github.com/nova-health-platform/NOVA_ML_SCAN_BODY/commits/main">
    <img src="https://img.shields.io/github/last-commit/nova-health-platform/NOVA_ML_SCAN_BODY" alt="last update" />
  </a>
  <a href="https://github.com/nova-health-platform/NOVA_ML_SCAN_BODY">
    <img src="https://img.shields.io/github/languages/top/nova-health-platform/NOVA_ML_SCAN_BODY" alt="top language" />
  </a>
</p>

</div>

<br />

## :notebook_with_decorative_cover: Table of Contents

- [About](#star2-about)
  * [Project Status](#construction-project-status)
  * [Tech Stack](#space_invader-tech-stack)
- [Getting Started](#toolbox-getting-started)
- [Related Repositories](#link-related-repositories)
- [Contact](#handshake-contact)

## :star2: About

This repository holds NOVA's body scan module, intended to analyze skin photos through computer vision and help flag areas to monitor as part of the platform's dermatological check-up.

### :construction: Project Status

The repository currently contains only the skeleton of the service: `server.py`, `test.py` and the training notebook `model_scan_body.ipynb` exist but are empty. Model and API development has not started yet, this repository reserves the space for this module within the NOVA architecture.

### :space_invader: Tech Stack

<details>
  <summary>Planned</summary>
  <ul>
    <li><a href="https://www.python.org/">Python</a></li>
    <li><a href="https://flask.palletsprojects.com/">Flask</a> (to be confirmed)</li>
    <li>Computer vision (model to be defined)</li>
  </ul>
</details>

## :toolbox: Getting Started

Nothing to run yet, the service has no implementation.

## :link: Related Repositories

NOVA is split into several independent services:

- [NOVA_WEB](https://github.com/nova-health-platform/NOVA_WEB): web frontend of the platform
- [NOVA_API](https://github.com/nova-health-platform/NOVA_API): central API that orchestrates calls to the models
- [NOVA_DB](https://github.com/nova-health-platform/NOVA_DB): business database
- [NOVA_LOGS_DB](https://github.com/nova-health-platform/NOVA_LOGS_DB): analysis log storage
- [NOVA_ML_ANALYSIS](https://github.com/nova-health-platform/NOVA_ML_ANALYSIS): symptom analysis module
- [NOVA_ML_PREPROD](https://github.com/nova-health-platform/NOVA_ML_PREPROD): model staging environment
- [NOVA_ML_MENTAL_HEALTH](https://github.com/nova-health-platform/NOVA_ML_MENTAL_HEALTH): psychological monitoring module
- [NOVA-CORE](https://github.com/nova-health-platform/NOVA-CORE): architecture overview and local orchestration for the whole platform

## :handshake: Contact

Brieuc Dumortier

[LinkedIn](https://www.linkedin.com/in/dumortier-brieuc/) - [GitHub](https://github.com/BaditSad) - dumortier.contact@gmail.com
