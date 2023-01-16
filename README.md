# TP_STATELESS

# Q1
 Les API stateless ne stockent pas l'état dans leur propre mémoire, ils peuvent donc être déployés sur n'importe quelle instance disponible sans avoir à se soucier de la synchronisation des données. Cela permet également de faciliter la maintenance et les mises à jour de l'application, car il n'y a pas besoin de s'inquiéter de la gestion de l'état de l'application. Enfin, cela permet de plus de flexibilité pour la mise en place de stratégies de redondance.
 
 # Q2 
 
 Il est possible de créer des volumes et de les lier à des conteneurs serverless.Il est donc important de vérifier les fonctionnalités disponibles pour la plateforme utilisée avant de commencer à utiliser des volumes avec des fonctions serverless.

# Q3

La base est partagé sur plusieurs instances.

# Q4

Certains fournisseurs de services serverless, comme AWS Lambda, ne prennent pas en charge la création de volumes, mais ils offrent des options de stockage alternatives comme S3 ou DynamoDB. 
D'autres plateformes, comme Google Cloud Functions ou Azure Functions, permettent de créer des volumes et de les lier à des conteneurs, mais cela nécessite une configuration supplémentaire et une gestion manuelle des volumes. 

# Q5

Il y a plusieurs points de vigilance à prendre en compte lors du déploiement d'applications serverless :

La gestion des dépendances : les applications serverless peuvent dépendre de certaines librairies ou de certaines ressources externes. Il est important de vérifier que ces dépendances sont compatibles avec la plateforme d'hébergement utilisée.

La gestion des erreurs : les applications serverless peuvent générer des erreurs qui ne sont pas faciles à diagnostiquer. Il est important de mettre en place des outils pour surveiller les erreurs et les événements d'application.

La gestion de la mémoire : les applications serverless sont soumises à des limites de mémoire. Il est important de surveiller les utilisations de la mémoire et de veiller à ce que les applications ne dépassent pas ces limites.

La gestion des performances : les applications serverless peuvent être soumises à des pics de charge. Il est important de surveiller les performances de l'application et de mettre en place des stratégies pour gérer ces pics de charge.

La gestion de la sécurité : les applications serverless peuvent être exposées à des risques de sécurité. Il est important de mettre en place des stratégies de sécurité pour protéger les applications et les données.

La gestion des coûts : les applications serverless peuvent générer des coûts liés à l'utilisation des ressources. Il est important de surveiller les coûts et de mettre en place des stratégies pour minimiser les coûts.

# Q6

![image](https://user-images.githubusercontent.com/119402346/212635991-227ee96f-14ad-45af-832b-80dedb85daa1.png)

# Q7 et 8 

Il est souvent préférable d'utiliser une base de données dans le cloud lorsque vous déployez une application serverless pour les raisons suivantes:

Élasticité : Les bases de données dans le cloud sont généralement conçues pour être élastiques, c'est-à-dire pour s'adapter automatiquement aux besoins en matière de capacité et de performances. Cela permet de gérer efficacement les pics de charge liés à l'utilisation des applications serverless.

Disponibilité : Les bases de données dans le cloud sont généralement conçues pour être hautement disponibles, avec des fonctionnalités de redondance et de récupération après sinistre intégrées. Cela permet de garantir la disponibilité des données même en cas de panne.

Sécurité : Les bases de données dans le cloud sont généralement conçues avec des fonctionnalités de sécurité avancées, telles que l'authentification multi-facteurs et la chiffrement des données. Cela permet de protéger les données contre les fuites et les attaques.

# Q9

Alors non malheureusment mais je commence a le metrtre en place. J'ai demandé un financement du dircteur qui devrait validé pendant la semaine ! je croise les doigts 
