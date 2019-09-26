# tuto_django_rest_framework
DRF tutorial API REST

## 1 - Models

```bash
-Categories
  - SousCategories
     - Articles
       - Commentaires
        
        
# 1- Categories

-nom
-description
-image
-statut
-date_add
-date_update

# 2- SousCategories

-categorie
-nom
-description
-image
-statut
-date_add
-date_update

# 3- Articles

-souscategorie
-nom
-description
-image
-statut
-date_add
-date_update


# 4- Commentaires

-articles
-user
-description
-statut
-date_add
-date_update


```bash
