# ♻️ Atelier - L’IA générative comme aide à la décision pour une collectivité locale

**Public** : Master 1 & Master 2 – Data Management  
**Durée totale** : 3H30  
**Format** : exercice collectif de 2 à 4 personnes

## 🎯 Objectif pédagogique

À la fin de l’atelier, vous devez être capables de :

- [ ] Identifier où l’IA générative apporte de la valeur dans un projet data
- [ ] Produire une aide à la décision compréhensible par des non-tech
- [ ] Justifier, documenter et encadrer l’usage de l’IA
- [ ] Mettre en évidence les limites, biais et risques

> L’IA ne décide pas, elle augmente la lisibilité pour un décideur public.

---

## 🧠 Contexte général

Vous êtes une **équipe data** missionnée par une **mairie de taille moyenne (≈ 80 000 habitants)**.

La municipalité souhaite réduire son impact environnemental, mais :

- elle dispose de peu de temps,
- de données hétérogènes,
- et d’élu·es non techniques.

### 🎯 Votre mission

Produire une **note d’aide à la décision**, claire, argumentée et exploitable, en utilisant **l’IA générative comme outil d’assistance**.

---

## 🌱 Problématique posée

> Sur quels leviers la ville doit-elle agir en priorité pour réduire son impact environnemental, **à budget constant**, sur les 3 prochaines années ?

## 📦 Exemple de données à exploiter

Les données présentées ci-dessous sont fictives et fournies à titre d’exemple.
L’objectif de l’exercice est de **collecter, analyser et exploiter des données réelles** issues de sources publiques.

Les ressources mobilisables sont détaillées dans la section « **🚰 Ressources** » plus bas dans l’énoncé.

### Consommation énergétique annuelle des bâtiments municipaux

| Bâtiment           | Type          | Consommation annuelle (MWh) |
| ------------------ | ------------- | --------------------------- |
| Hôtel de ville     | Administratif | 1 200                       |
| Piscine municipale | Sport         | 2 800                       |
| Gymnase Nord       | Sport         | 950                         |
| École primaire A   | Éducation     | 620                         |
| École primaire B   | Éducation     | 580                         |
| Médiathèque        | Culture       | 740                         |

---

### Déchets collectés par quartier (tonnes / an)

| Quartier      | Déchets ménagers | Tri sélectif |
| ------------- | ---------------- | ------------ |
| Centre-ville  | 4 200            | 1 100        |
| Quartier Nord | 3 600            | 800          |
| Quartier Sud  | 2 900            | 950          |
| Quartier Est  | 3 200            | 700          |

---

### Budget annuel pour la transition écologique

- **Budget total** : 1,5 M€ / an
- **Contraintes** :
  - Pas d’augmentation d’impôts
  - Actions visibles sous 18 mois
  - Acceptabilité sociale élevée

---

### Retours citoyens (verbatims – extrait)

- « La piscine est ouverte toute l’année mais il fait froid dans les vestiaires »
- « On ne comprend rien aux consignes de tri »
- « Les lumières restent allumées toute la nuit devant l’école »
- « J’aimerais des pistes cyclables mais pas au détriment des commerces »
- « Les bâtiments publics sont mal isolés »

> Ces données sont non structurées et constituent un terrain pertinent pour l’IA générative.

## 🤖 Rôle attendu de l’IA générative

L’IA peut être utilisée pour :

- Résumer des données pour un public non technique
- Identifier des axes d’action possibles
- Reformuler des recommandations claires
- Comparer plusieurs scénarios

❌ L’IA ne doit pas :

- Inventer des chiffres
- Prendre une décision finale
- Masquer l’incertitude ou les limites des données

---

## 🛠️ Consignes de travail (2H)

### Étape 1 — Compréhension du problème

- Identifier les postes les plus impactants
- Repérer les tensions : budget / acceptabilité / impact réel

---

### Étape 2 — Usage de l’IA générative

Vous devez :

- Rédiger vos propres prompts
- Tester plusieurs formulations
- Comparer les réponses
- Ajuster et cadrer l’IA si nécessaire

**Exemple de prompt autorisé :**

```
À partir de ces données, propose des pistes d’action environnementales adaptées à une mairie, en explicitant les hypothèses et les limites.
```

**Exemple de prompt interdit :**

```
Dis-moi quoi faire pour réduire l’impact environnemental de la ville.
```

---

### Étape 3 — Construction de scénarios

Produire **3 scénarios** :

| Scénario      | Description                      | Impact estimé | Coût | Risques       |
| ------------- | -------------------------------- | ------------- | ---- | ------------- |
| Low impact    | Actions rapides et peu coûteuses | ⭐            | €    | Effet limité  |
| Medium impact | Actions ciblées et mesurées      | ⭐⭐          | €€   | Acceptabilité |
| High impact   | Actions structurelles            | ⭐⭐⭐        | €€€  | Complexité    |

> Les estimations peuvent être qualitatives, mais doivent être justifiées.

---

### Étape 4 — Note d’aide à la décision

**Livrable principal :**  
📄 Une **note d’une page maximum**, destinée à un·e élu·e.

**Structure imposée :**

1. Constat synthétique (~5 lignes)
2. Comparaison des trois scénarios
3. Recommandation finale argumentée
4. Limites et points de vigilance

---

## 🎤 Restitution

Pour les groupes volontaires :

- 5 minutes de présentation
- 3 minutes de questions

Les autres groupes jouent alternativement le rôle :

- d’élu·es
- de citoyen·nes
- de journalistes

---

### ⚠️ Rappel du cadre

- Les données utilisées doivent être **sourcées et citées**
- L’IA générative :
  - ne décide pas
  - ne produit pas de chiffres inventés
  - ne remplace pas l’analyse humaine
- Toute recommandation doit mentionner :
  - les sources utilisées
  - les limites des données
  - les hypothèses formulées

---

## 🚰 Ressources

Les ressources ci-dessous correspondent à des **données publiques, légales et exploitables**, fréquemment utilisées par les collectivités et les analystes dans des projets réels de transition environnementale et sociale.

### 🏛️ APIs institutionnelles françaises

#### [data.gouv.fr](https://www.data.gouv.fr/)

- Portail officiel de l’open data en France
- Données disponibles sur :
  - énergie
  - déchets
  - bâtiments publics
  - mobilité
  - collectivités territoriales
- Source institutionnelle de référence pour les projets publics

#### [ADEME](https://data.ademe.fr/catalog-api-doc)

- Référentiel national sur l’environnement et la transition écologique
- Données et indicateurs sur :
  - empreinte carbone
  - énergie
  - déchets
  - rénovation énergétique
- Utilisé comme **source d’autorité** pour l’évaluation de l’impact environnemental

#### [INSEE](https://portail-api.insee.fr/catalog/all)

- Institut national de la statistique
- Données socio-économiques permettant de contextualiser les décisions environnementales :
  - population
  - revenus
  - typologie des ménages
  - densité urbaine

---

### ⚡ Énergie & climat

#### [Open Data Réseaux Énergies](https://odre.opendatasoft.com/api/v1/console?flg=fr-fr)

- Données issues des gestionnaires de réseaux (électricité, gaz)
- Consommation énergétique par territoire
- Données exploitables à l’échelle communale

#### [RTE](https://data.rte-france.com/catalog)

- Gestionnaire du réseau de transport d’électricité
- Données sur :
  - consommation
  - production
  - mix énergétique
- Utiles pour comparer les dynamiques locales et nationales

---

### 🚮 Déchets & économie circulaire

#### [SINOE (ADEME)](https://data.sinoe-dechets.ademe.fr/catalog-api-doc)

- Système d’information national sur les déchets
- Données par territoire sur :
  - volumes de déchets
  - taux de recyclage
  - filières de traitement

---

### 🚲 Mobilité durable

#### [transport.data.gouv.fr](https://transport.data.gouv.fr/)

- Données ouvertes sur les transports et la mobilité
- Informations sur :
  - pistes cyclables
  - transports en commun
  - infrastructures de mobilité douce

#### [OpenStreetMap](https://www.openstreetmap.fr/utiliser/)

- Base de données géographiques collaborative
- Permet de localiser :
  - bâtiments publics
  - infrastructures
  - équipements urbains

⚠️ Qualité variable selon les zones → à analyser de manière critique

---

### 🌍 Données internationales

#### Agence européenne pour l’environnement

- Données environnementales à l’échelle européenne
- Indicateurs climat, énergie et pollution

🔗 [European Environment Agency](https://www.eea.europa.eu/en)

#### Banque mondiale

- Indicateurs de développement durable
- Mise en perspective internationale des enjeux environnementaux

🔗 [World Bank](https://documents.worldbank.org/en/publication/documents-reports/api)

---

### ➕ Autres services :

#### [impactco2.fr](https://impactco2.fr/)

🔗 [https://www.data.gouv.fr/dataservices/api-impact-co2](https://www.data.gouv.fr/dataservices/api-impact-co2)

#### Exemple d’article exploitable pour l’extraction de témoignages réels :

[https://www.leparisien.fr/paris-75/1000-parisiens-ont-donne-leur-avis-pour-embellir-leur-quartier-23-03-2021-8429619.php](https://www.leparisien.fr/paris-75/1000-parisiens-ont-donne-leur-avis-pour-embellir-leur-quartier-23-03-2021-8429619.php)

---

## 🎓 Débrief pédagogique

Questions à discuter collectivement :

- À quel moment l’IA a-t-elle été réellement utile ?
- À quel moment a-t-elle été dangereuse ?
- Qu’est-ce qui n’a pas été délégué à l’IA, et pourquoi ?
- Qui est responsable si la décision finale est mauvaise ?

> L’IA générative est un outil d’aide à la décision, pas un décideur.  
> Le rôle des équipes de data management est d’en encadrer l’usage, pas de s’effacer.

---

## 📥 Formulaire de rendu

_A venir_
