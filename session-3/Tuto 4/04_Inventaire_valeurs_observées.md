## 1. Inventaire des valeurs observées

| Donnée | Valeurs observées |
|---|---|
| `nom_auteur` | Madani, Sara, Youssef, Amine, Nadia |
| `prenom_auteur` | Ali, Amrani, Karim, Idrissi, Alaoui |
| `email_auteur` | madani@mail.com, sara@mail.com, youssef@mail.com, amine@mail.com, nadia@mail.com |
| `nom_ville` | Tanger, Rabat |
| `nom_categorie` | Développement, Actualité |

## 2. Valeurs répétées

- **nom_auteur :** Aucune valeur répétée.
- **prenom_auteur :** Aucune valeur répétée.
- **email_auteur :** Aucune valeur répétée.
- **nom_ville :**
  - Tanger apparaît 3 fois.
  - Rabat apparaît 2 fois.
- **nom_categorie :**
  - Développement apparaît 3 fois.
  - Actualité apparaît 2 fois.

## 3. Problème lié à une répétition

J’ai choisi la donnée `nom_ville`. La valeur « Tanger » apparaît trois fois dans le tableau. Si le nom de cette ville devait être modifié, il faudrait mettre à jour les trois occurrences. Si une ligne était oubliée, les données deviendraient incohérentes.

## Conclusion

L’observation des occurrences permet d’identifier les valeurs répétées et de comprendre les risques liés à la modification des données. Cette étape prépare la découverte des entités dans la conception d’une base de données.