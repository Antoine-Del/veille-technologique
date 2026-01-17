# Veille technologique – Sécurité des systèmes d’exploitation

## Informations

- Nom : Antoine Delahaye  
- Formation : BTS SIO option SISR  
- Période : 2025‑2027  
- Thème de la veille : Sécurité des systèmes d’exploitation et mises à jour  
- Objectif : Suivre l’évolution des vulnérabilités (CVE) et des correctifs de sécurité sur Windows et Linux, ainsi que les bonnes pratiques de patch management.

---

## Présentation du thème

Les systèmes d’exploitation (Windows, Linux, etc.) sont au cœur des infrastructures et sont des cibles privilégiées pour les attaques.  
Chaque nouvelle vulnérabilité découverte est référencée avec un identifiant **CVE** (Common Vulnerabilities and Exposures) et corrigée via des mises à jour de sécurité plus ou moins critiques.

Cette veille a pour but :
- d’identifier les principales vulnérabilités qui touchent les OS serveurs et postes de travail ;
- de comprendre l’impact de ces failles sur la sécurité du système d’information ;
- de suivre les correctifs publiés et les stratégies de déploiement (Windows Update, WSUS, apt/yum, etc.).

---

## Axes de veille

1. **Vulnérabilités et CVE majeures**
   - Suivi des nouvelles CVE affectant Windows Server, Windows 10/11, distributions Linux (Debian, Ubuntu, etc.).
   - Analyse de quelques CVE critiques : contexte, vecteur d’attaque, score CVSS, impact métier.

2. **Patch management et déploiement des mises à jour**
   - Gestion des mises à jour dans les environnements professionnels (WSUS, Intune, outils de gestion de parc, scripts).
   - Stratégies de test, planification et déploiement (mises à jour automatiques, maintenance planifiée, PRA).

3. **Bonnes pratiques de sécurisation des OS**
   - Durcissement des systèmes (GPO, configuration des services, comptes et droits).
   - Sauvegarde, journalisation, supervision de l’état de sécurité.

---

## Outils utilisés pour la veille

### Feedly

Feedly me permet de centraliser tous les flux RSS liés à la sécurité des systèmes d’exploitation.  
J’y ajoute les flux des bulletins de sécurité Microsoft, des distributions Linux et de sites spécialisés en vulnérabilités afin de suivre rapidement les nouvelles CVE et mises à jour critiques. [web:77][web:83]

### YouTube

YouTube est utilisé pour suivre des chaînes orientées administration système et cybersécurité.  
Les vidéos de débrief Patch Tuesday et les analyses de failles permettent de comprendre concrètement l’impact des vulnérabilités et les correctifs à appliquer sur Windows et Linux. [web:80][web:86]

### Google

Google sert à approfondir les recherches sur une CVE précise, un bulletin de sécurité ou un outil de patch management.  
Il permet de trouver la documentation officielle (Microsoft, Debian, Ubuntu, etc.), des articles techniques et des retours d’expérience d’administrateurs système. [web:64][web:82]

### Raindrop.io / Gestion de favoris

Un gestionnaire de favoris comme Raindrop.io est utilisé pour enregistrer les articles importants de la veille.  
Chaque ressource est taguée (Windows, Linux, CVE critique, Patch Tuesday, patch management) afin de pouvoir retrouver facilement les informations lors de la rédaction du dossier.
