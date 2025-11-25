# TP 8 – Authentification en mémoire avec Spring Security


Ce TP présente les bases de **Spring Security** à travers une authentification simple **en mémoire**, en utilisant deux utilisateurs : `admin` et `user`. Vous allez apprendre :

### Génération automatique de sécurité par Spring Boot

### Configuration d’utilisateurs en mémoire

### Définition des règles d’accès selon les rôles

### Mise en place de routes protégées

### Test des accès via navigateur

## Comptes de test

### Compte utilisateur

* **Username :** `user`
* **Password :** `1111`
* **Accès :** `/user/dashboard`

### Compte administrateur

* **Username :** `admin`
* **Password :** `1234`
* **Accès :** `/user/dashboard` et `/admin/dashboard`

---

## Lancer les tests

Démarrer l’application puis accéder aux URL suivantes :

### • [http://localhost:8080/](http://localhost:8080/)

### • [http://localhost:8080/user/dashboard](http://localhost:8080/user/dashboard)

### • [http://localhost:8080/admin/dashboard](http://localhost:8080/admin/dashboard)
---
<img width="601" height="386" alt="Screenshot 2025-11-25 233356" src="https://github.com/user-attachments/assets/820be4f6-0e48-4185-8a5f-9d47facae2f2" />

<img width="586" height="461" alt="Screenshot 2025-11-25 233402" src="https://github.com/user-attachments/assets/f12e6b51-f3b6-4da1-a107-b16218299466" />

<img width="595" height="526" alt="Screenshot 2025-11-25 233409" src="https://github.com/user-attachments/assets/c6ee418e-35d4-4328-a8bd-4b3eddb9e215" />








