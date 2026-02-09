# Instructions pour GitLab - Trophées NSI 2026

## Étapes à suivre (dans l'ordre)

### 1. Créer son compte GitLab
- Aller sur https://gitlab.com
- S'inscrire avec un pseudo professionnel (ex: prenom-nom)
- Noter votre pseudo pour vos coéquipiers

### 2. Forker le dépôt modèle (UN SEUL membre de l'équipe)
- Aller sur https://gitlab.com/cglesgards/trophees-nsi-2026
- Cliquer sur le bouton "Fork"
- Renommer selon la règle : `2026_ID_nom_du_projet`
  (sans accent, sans espace, sans caractère spécial)
- L'ID sera communiqué sur Éléa

### 3. Inviter les collaborateurs
- Aller dans Manage → Members
- Inviter tous les coéquipiers (rôle: Developer)
- **OBLIGATOIRE** : Inviter le professeur `cglesgards` (rôle: Developer)

### 4. Structure du projet (OBLIGATOIRE)
```
2026_ID_nom_du_projet/
├── readme.md                    # Comment lancer le projet
├── presentation.md              # Description complète du projet
├── licence.txt                  # Licence libre (obligatoire)
├── requirements.txt             # Bibliothèques utilisées
├── sources/                     # Code source
│   ├── main.py                  # Programme principal
│   ├── module1.py
│   └── module2.py
├── data/                        # Ressources (facultatif)
│   ├── images/
│   └── sons/
├── docs/                        # Documentation technique (facultatif)
├── test/                        # Scripts de tests (facultatif)
└── exemples/                    # Captures d'écran, démos (facultatif)
```

### 5. Première tâche : Signer la licence
**CHAQUE membre de l'équipe doit** :
- Modifier le fichier `licence.txt`
- Ajouter son Prénom Nom dans la liste des auteurs
- Faire un commit avec un message clair : "Ajout de [Prénom Nom] dans la licence"

### 6. En-tête obligatoire dans chaque fichier Python
```python
#Projet : NomDuProjet
#Auteurs : Alice Dupont, Bob Martin, Charlie Durand
```

### 7. Bonnes pratiques
- **Messages de commit clairs** : "Ajout fonction calcul_score" ✓ / "modif" ✗
- **Commits fréquents** : Ne pas accumuler 3h de travail
- **Chacun sur des fichiers différents** pour éviter les conflits
- **Communiquer** dans l'équipe sur ce qu'on fait

### 8. Utiliser les Issues pour organiser le travail
- Plan → Issues → New Issue
- Créer une tâche par fonctionnalité
- Assigner à un membre de l'équipe
- Fermer automatiquement avec "closes #3" dans le message de commit

### 9. Workflow recommandé
1. **Fork** (une fois par équipe)
2. **Éditer** un fichier en ligne
3. **Commit** avec un bon message
4. **Répéter**

## Rappel important
- Pas besoin d'installer Git, tout se fait sur gitlab.com
- Le professeur DOIT être invité pour l'évaluation
- Respecter la structure de dossiers imposée
- Chaque élève doit faire au moins un commit