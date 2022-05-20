# Créer un service de type nodeport

> Ecrire un mafest namespace.yml qui crée un namespace nommé production et lancer la création du namespace

> Ecrire un manifest pod-red.yml pour déployer un pod avec l'image mmumshad/simple-webapp-color en précisant la couleur souhaitée "ROUGE" ; le pod doit etre nommé "app:web"

> Ecrire un manifest pod-green.yml pour déployer un pod avec l'image mmumshad/simple-webapp-color en précisant la couleur souhaitée "VERT" ; le pod doit etre nommé "app:web"

> Lancer les deux pod puis écrivez un manifest service-nodeport-web.yml qui permettra exposer les pods via un service de type node port, le nodeport devra être le 30008 et les target les ports 8080 de nos pods dont le label est « app: web »

> Lancez la création du service et vérifiez qu’il trouve les deux pods

>  Vérifiez que l’application est bien disponible en ouvrant le port 30008 de votre nœud
