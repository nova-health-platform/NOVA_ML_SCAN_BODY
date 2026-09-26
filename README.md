<div align="center">

  <h1>NOVA ML Scan Body</h1>

  <p>
    Module de vision par ordinateur pour le check-up dermatologique de la plateforme santé NOVA
  </p>

<p>
  <a href="https://github.com/BaditSad/NOVA_ML_SCAN_BODY/commits/main">
    <img src="https://img.shields.io/github/last-commit/BaditSad/NOVA_ML_SCAN_BODY" alt="last update" />
  </a>
  <a href="https://github.com/BaditSad/NOVA_ML_SCAN_BODY">
    <img src="https://img.shields.io/github/languages/top/BaditSad/NOVA_ML_SCAN_BODY" alt="top language" />
  </a>
</p>

</div>

<br />

# Table des matières

- [À propos](#à-propos)
  * [État du projet](#état-du-projet)
  * [Stack technique](#stack-technique)
- [Démarrage](#démarrage)
- [Dépôts liés](#dépôts-liés)
- [Contact](#contact)

## À propos

Ce dépôt porte le module de scan corporel de NOVA, pensé pour analyser des photos de peau via de la vision par ordinateur et aider à repérer des zones à surveiller dans le cadre du check-up dermatologique proposé par la plateforme.

### État du projet

Le dépôt contient pour l'instant uniquement le squelette du service : `server.py`, `test.py` et le notebook d'entraînement `model_scan_body.ipynb` sont présents mais vides. Le développement du modèle et de l'API n'a pas encore démarré, ce dépôt sert de réservation d'espace pour ce module au sein de l'architecture NOVA.

### Stack technique

<details>
  <summary>Prévu</summary>
  <ul>
    <li><a href="https://www.python.org/">Python</a></li>
    <li><a href="https://flask.palletsprojects.com/">Flask</a> (à confirmer)</li>
    <li>Vision par ordinateur (modèle à définir)</li>
  </ul>
</details>

## Démarrage

Rien à exécuter pour le moment, le service n'a pas encore d'implémentation.

## Dépôts liés

NOVA est découpé en plusieurs services indépendants :

- [NOVA_WEB](https://github.com/BaditSad/NOVA_WEB) : frontend web de la plateforme
- [NOVA_API](https://github.com/BaditSad/NOVA_API) : API centrale qui orchestre les appels aux modèles
- [NOVA_DB](https://github.com/BaditSad/NOVA_DB) : base de données métier
- [NOVA_LOGS_DB](https://github.com/BaditSad/NOVA_LOGS_DB) : journalisation des analyses
- [NOVA_ML_ANALYSIS](https://github.com/BaditSad/NOVA_ML_ANALYSIS) : module d'analyse des symptômes
- [NOVA_ML_PREPROD](https://github.com/BaditSad/NOVA_ML_PREPROD) : environnement de préproduction des modèles
- [NOVA_ML_MENTAL_HEALTH](https://github.com/BaditSad/NOVA_ML_MENTAL_HEALTH) : module de suivi psychologique

## Contact

Brieuc Dumortier

[LinkedIn](https://www.linkedin.com/in/dumortier-brieuc/) - [GitHub](https://github.com/BaditSad) - dumortier.contact@gmail.com
