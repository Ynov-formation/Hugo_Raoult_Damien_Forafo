Routes pour les Comptes (/api/accounts)

    POST /: Crée un nouveau compte.
    GET /:accountId: Obtient les détails d'un compte spécifique.
    PUT /:accountId: Met à jour un compte spécifique.
    DELETE /:accountId: Supprime un compte spécifique.

Routes pour les Clients (/api/clients)

    POST /register: Inscription d'un nouvel client.
    POST /login: Connexion d'un client.
    GET /me: Récupère les informations du client connecté (authentification requise).
    PUT /me: Met à jour le profil du client connecté (authentification requise).
    DELETE /me: Supprime le compte du client connecté (authentification requise).

Routes pour les Transactions (/api/transactions)

    POST /: Crée une nouvelle transaction.
    GET /:accountId: Obtient toutes les transactions pour un compte spécifique.
    DELETE /:transactionId: Supprime une transaction spécifique (optionnelle).
