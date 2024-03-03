# Analyse des Sentiments sur le Marché Boursier
## À Propos de Notre Projet:
Nous avons initié un projet visant à étudier l'influence des titres d'actualité sur le sentiment du marché boursier. En utilisant des techniques de web scraping, nous avons collecté des données provenant d'un site web d'actualités financières. Ces données comprennent le titre de l'actualité, sa date et son horodatage. Le but de ce projet est d'analyser ces titres pour en extraire le sentiment général et, éventuellement, de comprendre comment ces sentiments pourraient être corrélés avec les mouvements du marché. À travers cette étude, nous espérons fournir des aperçus précieux en offrant un outil supplémentaire pour anticiper les tendances du marché boursier.

## Méthodologie:
* **Collecte de Données**: Nous avons utilisé des techniques de web scraping pour extraire les titres d'actualité des entreprises sélectionnées à partir d'un site web d'actualités financières. Les entreprises sélectionnées pour cette étude sont Amazon (AMZN), AMD (Advanced Micro Devices), et Google (GOOG).

* **Traitement des Données**: Les données extraites comprennent le titre de l'article, la date et l'heure de publication. Nous avons nettoyé et transformé ces données pour les rendre utilisables dans notre analyse.

* **Analyse des Sentiments**: Nous avons utilisé la bibliothèque NLTK (Natural Language Toolkit) pour effectuer une analyse des sentiments sur les titres d'actualité. Plus précisément, nous avons utilisé le module VADER (Valence Aware Dictionary and sEntiment Reasoner) pour attribuer un score de polarité à chaque titre d'actualité. Ce score représente la positivité ou la négativité du sentiment exprimé dans le titre.

* **Visualisation des Données**: Nous avons utilisé la bibliothèque Matplotlib pour créer des visualisations des données. Nous avons représenté graphiquement la moyenne des scores de polarité pour chaque entreprise sur une période de temps donnée.

## Résultats:
Les résultats de notre analyse montrent que les titres d'actualité peuvent avoir un impact significatif sur le sentiment général du marché boursier. Nous avons observé des variations dans les scores de polarité en fonction des actualités publiées pour chaque entreprise. Par exemple, certains titres peuvent générer des sentiments positifs tandis que d'autres peuvent générer des sentiments négatifs, ce qui peut potentiellement influencer les décisions des investisseurs et les mouvements du marché.

## Limitations et Prochaines Étapes:
Il est important de noter que notre analyse se base uniquement sur les titres d'actualité et ne prend pas en compte d'autres facteurs qui pourraient influencer le marché boursier. De plus, l'analyse des sentiments basée sur les titres d'actualité peut être sujette à des biais et des limitations liés à la qualité des données et à la subjectivité de l'interprétation.
## Equipe de travail:
- [Asmaa Bazighe](https://github.com/AsmaaBazighe)
- [Lina Mouissou](https://github.com/linamouissou)
- [Rihab Idmoussa](https://github.com/rihabidm)
## Licence:
Ce projet est sous licence [MIT License](https://opensource.org/licenses/MIT).


