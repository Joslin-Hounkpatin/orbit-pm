### ORBIT PM - Pilotage Financier \& Reporting Projet



**Orbit PM** est une application web de gestion de projet de type SaaS, conçue pour les chefs de projet, les freelances et les décideurs. Contrairement aux outils classiques, Orbit se concentre sur la santé financière et temporelle en corrélant dynamiquement l'utilisation du budget et l'avancement du calendrier.



#### **Pourquoi Orbit PM ?**



Le défi de tout projet est de ne pas consommer son budget plus vite que le temps ne s'écoule. **Orbit PM** résout ce problème grâce à un **algorithme de score de santé propriétaire** qui analyse en temps réel le différentiel entre ces deux métriques cruciales.



#### **Fonctionnalités Clés**



* **Tableau de Bord Analytique** : Visualisation instantanée des indicateurs clés (Projets actifs, Budget engagé, Alertes de risque).
* **Algorithme de Score de Santé** : Un score sur 100 calculé dynamiquement pour chaque projet (Sain, Vigilance, Critique).
* **Visualisation de Données interactive** : Graphiques de performance (ApexCharts) pour suivre les tendances Budget vs Temps.
* **Reporting Professionnel** : Exportez vos données en un clic vers Excel (analyse) ou PDF (présentation client).
* **Internationalisation \& Multi-devises** : Support complet du Français/Anglais et gestion des devises (XOF, EUR, USD).
* **Suivi Opérationnel** : Filtrage en temps réel et gestion complète (CRUD) des projets.
* **Interface Moderne (SaaS Style)** : Design épuré basé sur une grille "Bento", avec mode Glassmorphism et interactions fluides.



#### **Stack Technique**



* **Frontend** : HTML5, CSS3 (Variables CSS, Flexbox, Grid).
* **Framework UI** : Bootstrap 5 (pour une réactivité totale).
* **Logique** : Vanilla JavaScript (ES6+).
* **Graphiques** : ApexCharts.
* **Moteur d'Export** : SheetJS (Excel) \& html2pdf.js (PDF).
* **Stockage** : API LocalStorage (Données persistantes sans backend).





#### **Logique de Calcul (L'Algorithme)**



L'utilité principale d'Orbit réside dans sa capacité à alerter l'utilisateur :



**Formule** :

&#x20;

**Score Santé = 100 - ( % Budget Consommé - % Temps Écoulé )**



Si le pourcentage de budget consommé dépasse largement le pourcentage de temps écoulé, le projet passe automatiquement en statut **Critique**, permettant une intervention proactive.



### **Installation \& Test rapide**



Ce projet est **100% Client-Side** (aucune base de données à configurer).



1. Clonez le projet :





< > Bash



git clone https://github.com/Joslin-Hounkpatin/orbit-pm.git



2\. Ouvrez le fichier index.html dans votre navigateur préféré.

3\. C'est tout ! L'application est prête à l'emploi.



#### **Confidentialité \& Sécurité**



Orbit PM adopte une approche **Privacy-First**. Aucune donnée financière ou personnelle n'est envoyée vers un serveur tiers. Toutes les données sont stockées localement dans votre propre navigateur via le **localStorage**.



### **Contribution \& Open Source**



Ce projet est **Open Source**. Toute contribution est la bienvenue !



1. Forkez le projet.

2\. Créez votre branche (git checkout -b feature/AmazingFeature).

3\. Commitez vos changements (git commit -m 'Add some AmazingFeature').

4\. Pushez la branche (git push origin feature/AmazingFeature).

5\. Ouvrez une Pull Request.



