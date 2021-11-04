# Les Gardiens d'Âmos

Vous avez aimé **Juliette et les Ptimos** ! Vous allez adorer **Les Gardiens d'Âmos**, l'application mobile de capture d'animaux bien réels !

GdÂ est un jeu d'aventure mobile dans lequel vous incarnez un•e Gardien•ne d'Âmos, qui a pour but de capturer les animaux que vous croiser afin de sauver le futur... 

### But du jeu

Dans un monde ou les espèces se font de plus en plus rare, votre rôle sera de les capturer afin de préserver le futur des espèces. Il faudra donc parcourir vos forêts et vos villes avec votre **Catchâmos** (smartphone) afin de remplir votre **Archâmos** (Pokédex) !

### Système de capture

Les Âmos sont des êtres sensibles et vos actions influent leurs sentiments ! Lors de sa création, une Âmos se voit attribuée des **points de dominance, de stress et de vitesse** . Les deux premiers attributs peuvent atteindre un `maximum de 100 points` pendant la rencontre.

Toutes les Âmos ont quatre types d'actions possibles :

##### Intimidation :

*Permet à l'Âmos de prendre confiance (augmente les points de dominance et réduit son stress).*

Une Âmos va avoir tendance à souvent s'affirmer lorsqu'il sent que sa dominance est basse mais que son stress est haut. 
La distance influe aussi : 

- à `moins de 3m` l'Âmos aura tendance à plus souvent attaqué que rugir

- à `plus de 10m` il aura tendance à essayer de s'éloigner 

  

##### Stupéfaction :

*Plus une Âmos est dominant, plus elle risque de vous "freezer".*

Une Âmos va avoir tendance à plus vous lorsque sa dominance est haute. Par ailleurs, plus le stress élevé et plus le risque d'attaque spéciale est grand.

Fréquence de l'attaque en fonction de la dominance : 

- `0-30` (peu fréquent) 
- `31-55` (assez fréquent) 
- `56+` (très fréquent)

##### Attaque :

*Cette attaque est différente pour chaque Âmos, plus vous êtes proche de lui et plus le risque d'attaque spéciale est grande.* 

Si une Âmos atteint un score de dominance de `100 points`, cela déclenche automatiquement une attaque magique.

Vous êtes libre d'ajuster les fréquences pour rendre le jeu le plus fun possible !


##### Fuite :

En début de **rencontre** une Âmos se situe **entre 5m et 10m** de distance. S'il vient à s'éloigner à plus de 12m alors l'Âmos disparait sans que vous puissiez la rattraper.

Plus l'Âmos est stressé et éloigné et plus il aura tendance à s'éloigner d'avantage.
En cas de trop fort stress, l'Âmos se mettra à attaquer plutôt que de fuir. 

La vitesse de déplassement influe sur la distance d'éloignement (2 ~= 1/2m - 100 ~= 3m)

Fréquence de l'éloignement en fonction du stress : 

- `0-30` (jamais) 

- `40-50` (peu fréquent) 

- `75-84` (assez fréquent)

- `85+` (jamais - devient très aggressif - augmente le risque d'attaque)



### Les Caracteristiques

|   Âmos   | Dom (10-80 / 100) | Stress (10-70 / 100) | Vit (2-100) |   Freezer    |      Attaque      |
| :------: | :---------------: | :------------------: | :---------: | :----------: | :---------------: |
|   Chat   |        50         |          28          |      30     | Ronronnement | Griffure profonde |
|  Chien   |        45         |          25          |      30     |  Aboiement   |  Morsure enragée  |
| Escargot |        10         |          18          |      2      | Bave gluante |   Bave toxique    |
| Mouette  |        22         |          50          |      40     |              |    Coup de bec    |
|  Goelan  |        45         |          40          |      40     |              |      Assault      |
| Cormoran |        25         |          24          |      37     |              |  Plongeon furtif  |
| Ecureil  |        14         |          62          |      15     |              |      Morsure      |
|  Pigeon  |        13         |          36          |      45     |              |   Fiente acide    |
|  Poule   |        18         |          44          |      13     |              |    Bec pointu     |
|  Canard  |        18         |          32          |      55     |              |      Pinçon       |
|  Cochon  |        37         |          19          |      21     |              |      Charge       |
|  Vache   |        23         |          48          |      25     |              |    Piétinement    |
|  Mouton  |        29         |          36          |      24     |              |      Morsure      |


### Méthodologie


Au dela du jeu, l'objectif est de travailler en équipe sur un projet conséquent et de façon pro ! 

On travaillera donc en cycle agile, avec des outils pro (Git / Github / Jira / Frameworks) et en implémentant des systèmes de bug tracking ainsi qu'une page status.



### Vision d'ensemble

Smart : Smartphone
Happy : API
Spotless : Status
Dreamy : Site vitrine


### Première itération

Réalisation d'une app mobile :



- Dépôt Smart
- Maquettage en équipe
- Hooks vs Redux vs Mobx ?
- Clarifai 
- Framework test (choix + implémentation)
- Système de Connexion (Supabase + JWT)
- Crop de l'image 
- Intégrer un viseur
- Qualité de l'image
- Déploiement sur Expo
- Test des 8 animaux
- Game assets pour les 8 animaux
- Supabase :
  - JWT
  - Catch (https://docs.expo.dev/versions/latest/sdk/location/)
    - long
    - lat
    - date
    - altitude
    - accuracy
  - Amos :
    - type
    - img_url
    - nom
    - confiance



