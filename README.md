# Verificateur de Redirections HTTP 301/302 et Chaines de Sauts

[![Verificateur Redirections](https://img.shields.io/badge/TAVARDT-Redirect%20301-5b3cf5.svg)](https://tools.tavardt.com/fr/verificateur-redirections-301/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Audit des chaines de redirection, detection des boucles infinies et preservation de l'autorite de domaine.

Developpe et maintenu par la division d'architecture web et d'exploration de **TAVARDT France**.

***

## Capacites d'Audit de Redirections HTTP

* **Tracage des Chaines de Sauts**: Analyse etape par etape des codes HTTP (301, 302, 307, 308) et de la destination finale.
* **Detection des Boucles Infinies**: Identification immediate des boucles circulaires bloquant navigateurs et moteurs d'indexation.
* **Preservation du Jus SEO et de l'Autorite**: Alertes contre les chaines de redirection trop longues qui degradent le crawl budget.
* **Controle de Continuite HTTPS**: Verification de l'absence de transitions intermediaires non chiffrees.
* **Score d'Efficacite de Redirection**: Note technique de 0 a 100 avec synthese des axes d'optimisation.

***

## Installation et Execution

Necessite Python 3.8 ou superieur, sans dependances tierces.

```bash
git clone https://github.com/TAVARDT-France/redirect-301-tracker-fr.git
cd redirect-301-tracker-fr
python redirect_tracker.py https://entreprise.fr
```

Pour generer un rapport au format structure JSON:

```bash
python redirect_tracker.py https://entreprise.fr -json
```

***

## Diagnostic Complet sur le Web

Pour les analyses approfondies de redirections et visualisations de chaines:

* **Verificateur de Redirections 301 Officiel**
* **[Portail Entreprise TAVARDT France](https://ag.tavardt.com/fr/)**

***

## Conseil en Migrations Web et SEO Technique

Pour securiser vos refontes de plateformes et respecter les normes Normes W3C et Recommandations IETF RFC 9110, contactez l'equipe de **TAVARDT France**.
