# postgrel
Recherche sur postgrel sql
## Les différentes champs postgresql en django
#### ArrayField
  * Un champ pour stocker des listes de données. La plupart des types de champs peuvent être utilisés ; il suffit de passer une autre instance de champ

### CIText
  * Une classe mixin pour créer des champs texte insensibles à la casse soutenus par le type citext. Lisez les conséquences au niveau des performances avant de l’utiliser.

### HStoreField
 * Un champ pour stocker des paires clé-valeur. Le type de données Python utilisé est un dictionnaire dict. Les clés doivent être des chaînes et les valeurs peuvent être soit des chaînes, soit la valeur

### JSONField
 * Un champ pour stocker des données JSON encodées. En Python, les données sont représentées dans leur format natif correspondant : dictionnaires, listes, chaînes, nombres, booléens

### Champs d’intervalle
  * Il existe cinq types de champs d’intervalle, correspondant au types d’intervalles natifs de PostgreSQL. Ces champs sont utilisés pour stocker un intervalle de valeurs ; par exemple, l’heure de début et de fin d’un événement ou l’intervalle des âges appropriés à une activité.
  - IntegerRangeField
  - BigIntegerRangeField
  - DecimalRangeField
  - DateTimeRangeField
  - DateRangeField

## Utilisation des Champs Postgresql
Pour utiliser  'django.contrib.postgres' à votre réglage INSTALLED_APPS.
```python
from django.contrib.postgres.fields import IntegerRangeField, JsonFiedl

```
