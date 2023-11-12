<strong>Cahier des charges - Conversion de monnaie</strong> 
<details>
<summary><strong>Analyse client</strong></summary>
MoneyValue est une startup du domaine de la finance qui souhaite développer une plateforme de conversion monétaire. L'objectif est de fournir un service public et gratuit permettant aux utilisateurs de convertir des devises. L'application doit être développée en utilisant Laravel comme framework back-end et Vue.js comme framework front-end.

</details>
<details>
<summary><strong>Choix technologiques</strong></summary>
Côté administration (front-end)
Le choix de Vue.js pour le front-end a été motivé par sa facilité d'utilisation, sa flexibilité et son écosystème riche de bibliothèques et de plugins. Vue.js permettra de créer une interface utilisateur réactive et conviviale pour l'administration.

Côté API (back-end)
L'utilisation de Laravel comme framework back-end a été choisie pour plusieurs raisons. Laravel est un framework PHP populaire qui offre une structure solide pour le développement d'applications web. Il fournit des fonctionnalités avancées telles que la gestion des routes, les contrôleurs de ressources, l'ORM Eloquent pour interagir avec la base de données, ainsi que des outils de validation et d'authentification intégrés.

</details>
<details>
<summary><strong>Liste fonctionnelle</strong></summary>
- Administration</br> 
- Système d'authentification pour l'accès à l'administration user : admin - password : admin</br>
- Affichage de la liste des paires de conversion supportées</br>
- Ajout, modification et suppression d'une paire de conversion</br>
- API</br>
- Récupérer la liste des paires de conversion supportées</br>
- Effectuer une conversion de devise selon une paire existante</br>
</details>
<details>
<summary><strong>Recettage</strong></summary>
<table>
  <thead>
    <tr>
      <th>Fonctionnalité</th>
      <th>Opérationnelle</th>
      <th>Observation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Système d'authentification</td>
      <td>Oui</td>
      <td>Seulement Admin, générer par le seeders</td>
    </tr>
    <tr>
      <td>Affichage des paires de conversion</td>
      <td>Oui</td>
      <td></td>
    </tr>
    <tr>
      <td>Ajout d'une paire de conversion</td>
      <td>Oui</td>
      <td></td>
    </tr>
    <tr>
      <td>Modification d'une paire de conversion</td>
      <td>Oui</td>
      <td></td>
    </tr>
    <tr>
      <td>Suppression d'une paire de conversion</td>
      <td>Oui</td>
      <td></td>
    </tr>
    <tr>
      <td>Affichage du nombre de requêtes</td>
      <td>Oui</td>
      <td></td>
    </tr>
    <tr>
      <td>Vérification du service</td>
      <td>Oui</td>
      <td></td>
    </tr>
    <tr>
      <td>Récupération des paires de conversion</td>
      <td>Oui</td>
      <td></td>
    </tr>
    <tr>
      <td>Conversion de devise</td>
      <td>Oui</td>
      <td></td>
    </tr>
  </tbody>
</table>
</details>

<details>
<summary><strong>Adresse Github</strong></summary>
<p>https://github.com/gravelain/currencyConvertor</p>
</details>