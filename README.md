# Terraform
Projet AWS deployement Infra 

Nous sommes le groupe 3, composé de : 
- Cheikh ABDALLAH
- Steven ADJI
- Yohann MBEY OZINO
- Sanaa ZIDANE
- Benny KASSANDA

Nous avons effectué le projet consistant à créer une infrastructure complète, permettant de lancer une instance EC2 avec la création de modules : module de création d'instance, module de création de volume EBS, module de création de groupe de sécurité et module de création d'un réseau IP.

Notre code se divise en 5 dossiers :
- app avec un fichier main.tf où nous retrouvons tous nos modules
- ec2module qui est la configuration de création d'une instance ec2
- ebs_volume : configuration d'un volume EBS
- ip_module : configuration de l'adresse IP
- security_group : configuration du groupe de sécurité

