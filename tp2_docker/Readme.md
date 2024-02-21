Pour installer docker avec les ligne de commande dans un premmier temps on va faire :

docker pull httpd

Maintenant on va faire docker images afin de voir ce qui tourne sur notre machine 

docker images

On va maintenant en ligne de commande demander de le lancer sur le port 80 ou 8080 qui correspond au port localhost

docker run -v /home/jordan/tp2/DevOps/tp_docker/mon_contenu_web/index.html -p 8080:80 -d httpd

On voit notre fichier se lancer maintenant on va l'arreter

docker stop focused_keller  

On va le supprimer 

docker rm focused_keller

on teste sur le port 8080

et l'on comme dans la consigne on copie les fichier

docker cp /home/jordan/tp2/DevOps/tp_docker

