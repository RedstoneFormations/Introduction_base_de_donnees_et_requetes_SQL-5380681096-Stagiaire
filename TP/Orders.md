Considérons trois tables : "Customers", "Orders" et "OrderItems". La table "Customers" contient les colonnes suivantes :

- customer_id (int) : identifiant unique du client
- customer_name (varchar) : nom du client
- email (varchar) : adresse e-mail du client

La table "Orders" contient les colonnes suivantes :

- order_id (int) : identifiant unique de la commande
- customer_id (int) : identifiant du client qui a passé la commande
- order_date (date) : date de la commande

La table "OrderItems" contient les colonnes suivantes :

- order_item_id (int) : identifiant unique de l'élément de commande
- order_id (int) : identifiant de la commande à laquelle l'élément appartient
- product_name (varchar) : nom du produit commandé
- quantity (int) : quantité commandée

1. Créez les trois tables "Customers", "Orders" et "OrderItems" avec les contraintes appropriées pour garantir l'intégrité référentielle.
2. Insérez les données suivantes dans la table "Customers" :

| customer_id | customer_name | email                          |
| ----------- | ------------- | ------------------------------ |
| 1           | John Doe      | mailto:johndoe@example.com     |
| 2           | Jane Smith    | mailto:janesmith@example.com   |
| 3           | Mark Johnson  | mailto:markjohnson@example.com |

1. Insérez les données suivantes dans la table "Orders" :

| order_id | customer_id | order_date |
| -------- | ----------- | ---------- |
| 1001     | 1           | 2023-07-01 |
| 1002     | 2           | 2023-07-02 |
| 1003     | 3           | 2023-07-03 |

1. Insérez les données suivantes dans la table "OrderItems" :

| order_item_id | order_id | product_name | quantity |
| ------------- | -------- | ------------ | -------- |
| 1             | 1001     | Product A    | 2        |
| 2             | 1001     | Product B    | 1        |
| 3             | 1002     | Product C    | 5        |
| 4             | 1003     | Product A    | 3        |
| 5             | 1003     | Product B    | 2        |
| 6             | 1003     | Product C    | 1        |

1. Sélectionnez le nom du client, la date de commande et le total des quantités commandées pour chaque client.
