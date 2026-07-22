# 🗺️ Documentation et cartographie du réseau

> Schéma unique, à jour, de la topologie physique et logique du laboratoire — condition de survie de tout homelab qui grossit.

## Objectif

Maintenir une représentation visuelle fiable de l'ensemble de l'infrastructure : liaisons physiques et logiques, hyperviseurs, VLAN, charges hébergées par hôte. Ce schéma sert à la fois de documentation d'exploitation et de support de présentation du projet.

## Contenu de la cartographie

- **Liaisons physiques** domestiques vs homelab (distinction visuelle entre le réseau familial et le laboratoire)
- **Liaisons logiques** domestiques vs homelab
- **Hyperviseurs Proxmox** avec le détail des VM/LXC hébergés et leurs ressources allouées
- **Légende par VLAN** (couleur dédiée par domaine : Sécurité, Utilisateur, VPN, Sauvegarde, Serveur, LAN)

## Topologie logique

<img width="1401" height="1175" alt="Homelab-topologie" src="https://github.com/user-attachments/assets/b265a3f6-b470-4f81-83ed-04b6497cb188" />

## Pourquoi ça compte

Sur une infrastructure hétérogène avec plusieurs hyperviseurs autonomes (pas de cluster centralisé, voir `proxmox-gestion-ressources-hotes`), il n'existe pas de vue unifiée native. La cartographie manuelle est le seul moyen de garder une vision d'ensemble cohérente et de faciliter le diagnostic en cas d'incident.

## Repos liés

- [`conception-infrastructure-datacenter`](https://github.com/L-VSIX/conception-infrastructure-datacenter)
- [`opnsense-segmentation-vlan`](https://github.com/L-VSIX/opnsense-segmentation-vlan)

## Auteur

**Lilian Vertueux** — [LinkedIn](https://www.linkedin.com/in/lilian-vertueux/)
