# GraphQL

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- la différence entre REST et GraphQL ✔️

REST : Utilise des URL et des méthodes HTTP spécifiques pour accéder aux données de manière prédéfinie.
GraphQL : Permet de demander des données spécifiques avec une seule requête personnalisée, un seul endpoint

- les besoins auxquels répond GraphQL ✔️

GraphQL: flexibilité et précision des requêtes, simplicité et évolutivité des requêtes de données avec les schéma.

- la définition d'un schéma

Personaliser une reqûete avec un seul endpoint /graphql
exemple:

```
type User {
  id: ID!
  name: String!
  email: String!
}
```

```
type Query {
  users: [User!]!
}
```

- Query ✔️

Un Json qui correspond à un schéma défini.
exemple:

```
{
  users {
    id
    name
    email
  }
}
```

- Mutation ✔️

Modification de données server
exemple creation:

```
mutation {
  createUser(name: "Alice", email: "alice@example.com") {
    id
    name
    email
  }
}
```

- Subscription ✔️

Mise à jour en temps réel des données
exemple:

```
type Subscription {
  newUser: User!
}
```

```
subscription {
  newUser {
    id
    name
    email
  }
}
```

## 💻 J'utilise

### Un exemple personnel commenté ✔️

### Utilisation dans un projet ❌ / ✔️

[lien github](...)

Description :

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
