# 🗺️ Documentation et cartographie du réseau

> Schéma unique, à jour, de la topologie physique et logique du laboratoire — condition de survie de tout homelab qui grossit.

## Objectif

Maintenir une représentation visuelle fiable de l'ensemble de l'infrastructure : liaisons physiques et logiques, hyperviseurs, VLAN, charges hébergées par hôte. Ce schéma sert à la fois de documentation d'exploitation et de support de présentation du projet.

## Contenu de la cartographie

- **Liaisons physiques** domestiques vs homelab (distinction visuelle entre le réseau familial et le laboratoire)
- **Liaisons logiques** domestiques vs homelab
- **Hyperviseurs Proxmox** avec le détail des VM/LXC hébergés et leurs ressources allouées
- **Légende par VLAN** (couleur dédiée par domaine : Sécurité, Utilisateur, VPN, Sauvegarde, Serveur, LAN)

## Méthode

Le schéma a été construit et affiné au fil du projet, en particulier lors de la phase de déploiement des 6 VLAN (avril 2026), pour refléter la migration progressive des services vers leur VLAN cible plutôt qu'un état figé du jour 1.

## Pourquoi ça compte

Sur une infrastructure hétérogène avec plusieurs hyperviseurs autonomes (pas de cluster centralisé, voir `proxmox-gestion-ressources-hotes`), il n'existe pas de vue unifiée native. La cartographie manuelle est le seul moyen de garder une vision d'ensemble cohérente et de faciliter le diagnostic en cas d'incident.

## Repos liés

- `conception-infrastructure-datacenter`
- `opnsense-segmentation-vlan`

## Auteur

**Lilian Vertueux** — [LinkedIn](https://www.linkedin.com/in/lilian-vertueux/)
