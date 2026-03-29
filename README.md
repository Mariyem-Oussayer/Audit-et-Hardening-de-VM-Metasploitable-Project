# 🔐 Linux Security Framework – Audit, Hardening & Controlled Attack

## 📌 Description
Ce projet consiste en la conception d’un framework modulaire de cybersécurité permettant d’analyser, tester et renforcer la sécurité d’un système Linux.

Le framework adopte une approche Red Team / Blue Team et propose trois modes principaux :
- 🔍 Scan (Audit & Détection)
- ⚔️ Offensive (Simulation d’attaques contrôlées)
- 🛡️ Hardening (Renforcement de la sécurité)

---

## 🎯 Objectifs
- Détecter les vulnérabilités d’un système Linux
- Simuler des attaques internes de manière contrôlée
- Renforcer automatiquement la sécurité selon un scoring
- Générer des rapports détaillés avant/après

---

## ⚙️ Fonctionnalités

### 🔍 Mode Scan (Audit)
- Scan des ports avec Nmap
- Analyse des services exposés
- Audit des configurations système (SSH, Kernel, etc.)
- Détection des mauvaises configurations

### ⚔️ Mode Offensive
- Simulation d’attaques internes :
  - Sniffing ARP
  - Pivot local
- Tests de vulnérabilités en environnement contrôlé

### 🛡️ Mode Hardening
- Application de mesures de sécurité automatiques
- Désactivation des services vulnérables
- Configuration sécurisée du système

### 📊 Reporting
- Génération de rapports détaillés
- Comparaison avant / après (sécurité améliorée)
- Score de sécurité global

---

## 🧩 Architecture

Le projet est basé sur une architecture modulaire avec des plugins :
project/
├── plugins/

│ ├── scan/

│ ├── attack/

│ └── harden/
│
├── config/
├── logs/
├── reports/
└── framework.sh


---

## 🛠️ Technologies utilisées
- Linux
- Bash scripting
- Nmap
- SSH
- Outils réseau

---


