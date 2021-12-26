Example:

SELECT * FROM items
WHERE owner =
AND itemname=;

Attacks:

foo' OR 'a'='a';

SELECT * FROM items;

Défense contre SQLi:
- requêtes paramétrées
- procédures stockées
- whitelistes
- privilèges de base de données

Plus d'informations : https://www.owasp.org/index.php/SQL_Injection_Prevention_Cheat_Sheet

```
gauntlt-docker .attacks/sql-form.attack
```
