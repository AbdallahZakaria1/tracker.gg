# PredictionVALORANT.gg
  "Prédire l'issue d'une partie sur un jeu de type FPS (Valorant) grâce au ratio K/D."


Les KDs des joueur et recuperable sur : "https://tracker.gg/valorant"
Le projet consite a predire l'issue d'une partie grace au Kill/deatch des joueurs de la partie,
pour se faire nous allons utilisé une variable aleatoire qui varie entre l'intervalle [0 ; 1], cette variable aleatoire represente la performense d'un joueur sur un round, elle sera multiplier par le KD.

-> si la moyenne de l'equipe A et plus grande que la moyenne de l'equipe B l'equipe A gagne, etc.
