# Lab-Active-Directory
## Introduction à Active Directory (AD DS)

## Objectif
Documenter et synthétiser les concepts fondamentaux d'Active Directory Services (AD DS) étudiés lors de mes sessions de formation.
---
## Qu'est-ce qu'Active Directory ?
- **Définition :** Service d'annuaire développé par Microsoft pour les réseaux de serveurs Windows.
- **Role principal :** Centraliser la gestion des identités, des accès, des utilisateurs et des équipements informatiques au sein d'un réseau d'entreprise.
---
## Conception & Architecture de l'Annuaire

La conception d'un annuaire des ressources commence par la **représentation hiérarchique de l'entreprise**.

C'est une étape primordiale pour :
- **Organiser l'annuaire de manière optimale :** Structurer les ressources (utilisateurs, ordinateurs, serveurs) de façon logique.
- **Simplifier l'administration système :** Rendre la gestion quotidienne plus fluide et évolutive.
- **Faciliter et renforcer la sécurité :** Appliquer des règles d'accès ciblées et sécuriser l'accès aux données sensibles.

### Arborescence type (Exemple de structure d'OU)
MonDomaine.local
  OU_Utilisateurs
    Direction
    Finance
    IT
  OU_Ordinateurs
    Laptops
    Desktops
  OU_Serveurs
