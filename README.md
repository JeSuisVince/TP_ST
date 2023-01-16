# TP_ST

# Q1
 Les API stateless ne stockent pas l'état dans leur propre mémoire, ils peuvent donc être déployés sur n'importe quelle instance disponible sans avoir à se soucier de la synchronisation des données. Cela permet également de faciliter la maintenance et les mises à jour de l'application, car il n'y a pas besoin de s'inquiéter de la gestion de l'état de l'application. Enfin, cela permet de plus de flexibilité pour la mise en place de stratégies de redondance.
 
 # Q2 
 
 Il est possible de créer des volumes et de les lier à des conteneurs serverless. Certains fournisseurs de services serverless, comme AWS Lambda, ne prennent pas en charge la création de volumes, mais ils offrent des options de stockage alternatives comme S3 ou DynamoDB. 
D'autres plateformes, comme Google Cloud Functions ou Azure Functions, permettent de créer des volumes et de les lier à des conteneurs, mais cela nécessite une configuration supplémentaire et une gestion manuelle des volumes. Il est donc important de vérifier les fonctionnalités disponibles pour la plateforme utilisée avant de commencer à utiliser des volumes avec des fonctions serverless.

# Q3

La base est partagé sur plusieurs instances.

# Q4
