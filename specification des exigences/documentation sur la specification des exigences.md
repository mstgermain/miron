# Documentation sur la spécification des exigences

## Objectif

Le cas d’usage supportant le développement de cette ontologie partielle, modulaire et compatible à CIDOC CRM est fondé sur un objectif d’interopérabilité, de repérage et de réutilisation des données sur le patrimoine culturel québécois, à la fois par différentes organisations et institutions et par les traitements informatiques. Une mise en commun des données provenant de sources différentes implique un travail de normalisation, d’organisation et de représentation des connaissances qu’elles constituent. Les DOL et la modélisation sémantique se présentent comme des solutions permettant de i) de pallier certains enjeux liés à la description, ii) considérer et reconnaître formellement les particularités des données sur le patrimoine culturel et iii) poser un geste vers la création d’un réseau de données matérialisant la complémentarité des collections québécoises. Un objectif général guide le développement du SOC, soit d’explorer les relations qui unissent les éléments du patrimoine culturel se trouvant dans les collections issues d’institutions patrimoniales hétérogènes.

À l’heure actuelle, les lignes directrices retrouvées dans le guide de documentation du Réseau Info-Muse de la Société des musées du Québec (SMQ) ne suffisent pas à elles seules pour permettre d’atteindre ces objectifs. De plus, dans une visée de développement d’un référentiel commun pouvant mener à une plateforme de diffusion des collections fédératrice, ce livrable permet de poser certaines bases soutenant l’interopérabilité ainsi qu’une méthode pour atteindre une généralisabilité des résultats.

## Portée

Le principal résultat escompté est un SOC compatible avec CIDOC CRM et composée de différents mécanismes permettant de pallier certains des enjeux associés au mécanisme E55 Type.
Le CRM-SIG rend disponible une implémentation du modèle CIDOC-CRM en RDFS. La version la plus récente de cette implémentation est fondée sur la version 7.1.3 du modèle et fut publiée en mars 2024 à la suite de la publication du modèle en février 2024 . On référence aussi OWL en utilisant la propriété owl:inverseOf pour définir les propriétés inverses. RDFS et OWL 2 sont donc les deux langages d’implémentation privilégiés dans notre contexte.

## Utilisateur finaux prévus

1. Utilisateur 1 – Personne responsable du catalogage exploitant le SOC en
* diminuant l’ambiguïté potentielle associée à l’utilisation de la langue pour la description;

* peuplant automatiquement certains champs de la base de données en fonction de l’objet décrit;

* identifiant la nature d’un objet à cataloguer par le biais de ses caractéristiques.
2. Utilisateur 2 – Gestionnaire de base de données pouvant facilement, grâce à leur normalisation et leur structure, incorporer des données issues du SOC à sa base de données pour l’enrichir ou la compléter;

3. Utilisateur 3 – Chercheur d’information explorant des éléments du patrimoine culturel sur une plateforme de diffusion des collections;

4. Utilisateur 4 – Application du Web sémantique moissonnant des données.

## Exigences ontologiques

### Exigences ontologiques non fonctionnelles

* ENF1. L’ontologie doit être compatible avec CIDOC CRM.

* ENF2. L’ontologie doit être compatible avec les systèmes de classification issus du Guide de documentation du Réseau Info-Muse et de la norme Nomenclature pour le catalogage des objets de musée

* ENF3. L’ontologie doit respecter les principes FAIR appliqués au développement d’ontologie.

* ENF4. L’ontologie doit respecter les principes des DOL et le degré d’ouverture des données.

### Exigences ontologiques non fonctionnelles

- QDC1. Quel est le type d’objet (la catégorie) de l’objet X?

- QDC2. Quelles sont les parties composantes d’un type d’objet X?

- QDC3. Quelle(s) technique(s) de fabrication sont utilisée(s) pour la fabrication d'un type d'objet X?

- QDC4. Quelle est la fonction principale d'un type d'objet X?

- QDC5. Quel(s) terme(s) est utilisé pour désigner un type d'objet X?

- QDC6. Quels termes alternatifs sont utilisés pour désigner un type d'objet X?

- QDC7. Quelle est la définition d'un type d'objet X?

- QDC8. Quel matériau compose généralement un type d'objet X?

- QDC9. Quel médium compose généralement un type d'objet X?

- QDC10. Quel support compose généralement un type d'objet X?

- QDC11. Quelle entité est associée à cet objet? Quelle est la nature du lien?
