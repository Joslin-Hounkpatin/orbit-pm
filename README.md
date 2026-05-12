### ORBIT PRO - Pilotage Financier \& Reporting Projet



**Orbit PM** est une application web de gestion de projet de type SaaS, conçue pour les chefs de projet, les freelances et les décideurs. Contrairement aux outils classiques, Orbit se concentre sur la santé financière et temporelle en corrélant dynamiquement l'utilisation du budget et l'avancement du calendrier.



#### **Pourquoi Orbit PRO ?**



Le défi de tout projet est de ne pas consommer son budget plus vite que le temps ne s'écoule. Orbit PRO résout ce problème grâce à un système de **Pilotage Hybride** qui permet de suivre un projet soit de manière globale, soit de manière granulaire via un gestionnaire de tâches intégré.



#### **Fonctionnalités Clés**



1. **Pilotage Hybride (Double Saisie) :**

   * **Mode Manuel :** Saisie rapide du budget total, du consommé et de l'avancement global.
   * **Mode Granulaire (Tâches) :** Dès que vous ajoutez des tâches, Orbit bascule en mode automatique. Le budget du projet et le montant consommé deviennent la **somme mathématique** de chaque tâche.



**2. Gestion de Tâches Avancée :** Définition de budgets propres par tâche et suivi de progression par paliers réalistes (10%, 25%, 50%, 75%, 100%).



**3. Algorithme de Score de Santé :** Un statut dynamique (Sain, Vigilance, Critique) basé sur le différentiel entre le budget consommé et le temps écoulé.



**4. Tableau de Bord "Bento Grid" :** Visualisation instantanée des KPIs (Projets actifs, Budget engagé, Alertes de risque).



**5. Visualisation interactive :** Graphiques de performance (ApexCharts) comparant les courbes de progression réelle vs temps écoulé.



**6. Reporting Pro :** Exportez vers Excel pour l'analyse de données ou en PDF Haute Définition pour vos présentations clients.



**7. Multi-devises \& i18n :** Support complet FR/EN et gestion des devises (XOF, EUR, USD).



**8. Zéro Débordement :** Interface optimisée pour l'affichage de montants financiers importants (milliards).





#### **Logique de Calcul \& Hiérarchie des Données**



L'intelligence d'Orbit réside dans sa flexibilité. Le moteur de calcul suit une hiérarchie stricte :



1. **Si le projet a des tâches :**

   * **Budget Total** = Σ (Budget de chaque tâche).
   * **Budget Consommé** = Σ (Dépenses de chaque tâche).
   * **Avancement =** Moyenne pondérée par le budget de chaque tâche.



**2. Si le projet n'a pas des tâches :**

* Le Système utilise les valeurs saisies manuellement dans les champs "Budget Global", "Consommé" et "Avancement".

#### 

#### **L'Algorithme de Santé**



Le statut du projet est déterminé par la règle suivante :



  * Critique : Si **Budget Consommé > Budget Prévu** OU si **% Avancement < % Temps écoulé - 15%.**
  * Vigilance : Si **% Avancement < % Temps écoulé.**
  * Sain : Si **% Avancement >= % Temps écoulé.**





#### **Stack Technique**



* **Frontend** : HTML5, CSS3 (Variables CSS, Flexbox, Grid).
* **Framework UI** : Bootstrap 5 (Responsive Design).
* **Logique** : Vanilla JavaScript (ES6+).
* **Graphiques** : ApexCharts (Mode Gradient Area).
* **Moteur d'Export** : SheetJS (Excel) \& html2pdf.js (PDF).
* **Stockage** : API LocalStorage (Données persistantes localement).







### **Installation \& Test rapide**



Ce projet est **100% Client-Side** (aucune base de données ou à configurer).



1. Clonez le projet :





< > Bash



git clone https://github.com/Joslin-Hounkpatin/orbit-pm.git



2\. Ouvrez le fichier index.html dans votre navigateur.

3\. C'est tout ! L'application est prête à l'emploi.



#### **Confidentialité \& Sécurité**



Orbit PM adopte une approche **Privacy-First**. Aucune donnée financière ou personnelle n'est envoyée vers un serveur tiers. Toutes les données sont stockées localement dans votre propre navigateur. Cela garantit une confidentialité totale de vos chiffres d'affaires et budgets.





### **Contribution \& Open Source**



Ce projet est **Open Source**. Toute contribution est la bienvenue !



1. Forkez le projet.

2\. Créez votre branche (git checkout -b feature/AmazingFeature).

3\. Commitez vos changements.

4\. Ouvrez une Pull Request.





*Développé avec passion pour simplifier le pilotage de projet.*

