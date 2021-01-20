## exo2
dans le fichier .gitlab-ci.yml sur la branche master mettez en place  un pipeline qui aura les stages suivants:
- BUILD
- TEST
- DEPLOY
chaque job de chaque stage  doit avoir une partie script ( echo "build" par exemple le job:build du stage build)
mettez deux jobs test:unit et test:fonctionnel  pour le stage TEST 
lancez le pipeline 
