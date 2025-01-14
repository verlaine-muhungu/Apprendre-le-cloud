# Phase 5: Les fondamentaux de la sécurité cloud 

Auteur: [Dayspring Johnson](https://twitter.com/daycyberwox)

## Comment s'applique cette phase au cloud ?

La sécurité est le plus grand challenge au cloud computing .Alors que l’adoption du cloud continue de croître,les incidents et les vulnérabilités de sécurité du cloud sont également en hausse.

Les composants cloud individuels que vous avez découverts dans les phases précédentes nécessitent tous une sécurité sous une forme ou une autre. Mieux encore,la sécurité doit être envisagée sous tous les angles afin d’empêcher les acteurs malveillants de trouver et d’exploiter les vulnérabilités de nos environnements cloud qui pourraient potentiellement conduire à une compromission des données ou de l’infrastructure.
Voici l’un de mes articles préférés par [Christophe Tafani-Dereeper](https://twitter.com/christophetd) qui couvre les failles et les vulnérabilités de la sécurité du cloud:

- [Failles et vulnérabilités de la sécurité dans le cloud: 2021 en revue](https://blog.christophetd.fr/cloud-security-breaches-and-vulnerabilities-2021-in-review/)

Je recommande aussi de consulter [SécurisationDevOps:La sécurité dans le cloud](https://www.manning.com/books/securing-devops) par [Julien Vehent](https://twitter.com/jvehent) qui couvre plusieurs des composants de base pour la protection de l’infrastructure cloud,la journalisation,la détection des menaces, etc. Il dispose même d’aides pratiques et visuelles qui aident à apprendre ces concepts . 

Un autre livre est [Sécurité Cloud pratique: Guide de conception et de déploiement sécurisés](https://www.oreilly.com/library/view/practical-cloud-security/9781492037507/) par [Chris Dotson](https://www.linkedin.com/in/chris-dotson-6a9b55/). Ce livre est une bonne ressource complémentaire au livre précédent car il approfondit divers concepts, normes, cadres et principes requis pour la sécurité du cloud, et comme son nom l’indique, il est pratique.


Rappelez-vous toujours cela,vous ne pouvez pas sécuriser ce que vous ne comprenez pas, alors assurez-vous de comprendre les composants architecturaux de base du cloud afin de pouvoir les sécuriser correctement.

.


## Resources


| Plateforme cloud | Titre  | Description  |
|:-------------- | ------ | ------ |
AWS, Azure & GCP | [Piratage du cloud](https://hackingthe.cloud/)| Piratage du cloud est une encyclopedie d'attaques/tactiques/techniques qui sont commun dans l'exploitation du cloud. |
AWS | [Flaws.Cloudf](http://flaws.cloud/)| Grâce à une série de niveaux,vous découvrirez les erreurs et les pièges courants lors de l’utilisation d’Amazon Web Services (AWS). |
AWS | [Flaws2.Cloud](http://flaws2.cloud/)| Semblable à l’original Flaws.Cloud Challenge, ce didacticiel vous enseigne les concepts de sécurité AWS, mais cette fois d’un point de vue offensif et défensif.|
AWS | [Cloud Goat](https://github.com/RhinoSecurityLabs/cloudgoat)| CloudGoat est l’outil de déploiement AWS « Vulnerable by Design » de Rhino Security Labs qui vous permet de perfectionner vos compétences en cybersécurité dans le cloud en créant et en complétant plusieurs scénarios de style « capture-the-flag ». |
AWS | [Sadcloud](https://github.com/nccgroup/sadcloud)|Sadcloud est un outil permettant de créer une infrastructure AWS non sécurisée avec Terraform. Vous pouvez tester vos connaissances en matière de sécurité AWS par rapport à ces infrastructures. |
AWS | [AWS Well-Architected Labs: Security](https://www.wellarchitectedlabs.com/security/)| Les laboratoires de sécurité sont de la documentation et du code sous la forme de laboratoires pratiques pour vous aider à apprendre, mesurer et construire à l’aide des meilleures pratiques architecturales.|
AWS | [Attack Detection Fundamentals](https://labs.f-secure.com/blog/attack-detection-fundamentals-2021-aws-lab-1/)| Cette série en trois parties explore une chaîne d’élimination de bout en bout dans AWS et enregistre les entrées pour la détection et l’analyse. |
Azure | [Attack Detection Fundamentals](https://labs.f-secure.com/blog/attack-detection-fundamentals-2021-azure-lab-1/)|Cette série en trois parties explore une chaîne d’élimination de bout en bout dans Azure et enregistre les entrées pour la détection et l’analyse. |
Azure | [CONVEX](https://github.com/Azure/CONVEX)| Cloud Open-source Network Vulnerability Exploitation eXperience (CONVEX) lance les environnements Capture The Flag dans votre client Azure pour que vous puissiez y jouer.  |
Azure | [Securing Azure Infrastructure - Hands on Lab Guide](https://github.com/azurecitadel/azure-security-lab)|Un guide pratique pour sécuriser l’infrastructure azure à l’aide de divers contrôles de sécurité azure. |
Azure | [Azure Security Technologies](https://microsoftlearning.github.io/AZ500-AzureSecurityTechnologies/)| Divers scénarios de laboratoire couvrant la sécurité azure.|
Azure | [Create an Azure Vulnerable Lab](https://0xpwn.wordpress.com/2022/03/05/setting-up-an-azure-pentest-lab-part-1-anonymous-blob-access/)| Une série en quatre parties expliquant les vulnérabilités azure. |
GCP | [GCP GOAT](https://gcpgoat.joshuajebaraj.com/)| GCP-Goat est intentionnellement vulnérable à l’environnement GCP pour apprendre et pratiquer GCP Security |
GCP | [ThunderCTF](https://aws.amazon.com/training/)|Thunder CTF permet aux joueurs de s’entraîner à attaquer des projets cloud vulnérables sur Google Cloud Platform (GCP). Dans chaque niveau, les joueurs sont chargés d’exploiter un déploiement cloud pour trouver un entier « secret » qui y est stocké. . |
Kubernetes | [Kubernetes Goat](https://madhuakula.com/kubernetes-goat/)| Kubernetes Goat est un terrain de jeu interactif d’apprentissage de la sécurité Kubernetes |




## Projets


| Plateforme cloud | Titre | Description  |
|:-------------- | ------ | ------ |
AWS | [Threat Detection With AWS GuardDuty](https://www.youtube.com/watch?v=lLgqP4cbdWg&t=127s)|Un tutoriel qui montre comment utiliser AWS GuardDuty pour detecter les menaces.|
AWS | [AWS Threat Simulation & Detection](https://github.com/sbasu7241/AWS-Threat-Simulation-and-Detection/blob/main/aws.credential-access.ec2-get-password-data.md)|Ce document montre l’utilisation de Stratus Red Team & SumoLogic pour l’attaque et la détection/analyse. Cela peut être répliqué à l’aide de n’importe quel autre SIEM.|
Azure | [Azure Cloud Detection Lab(Blog)](https://cyberwoxacademy.com/azure-cloud-detection-lab-project/), [Azure Cloud Detection Lab(Videos)](https://youtube.com/playlist?list=PLBNtagSCmDWw27ccfeWeiaMcpNIxpGHy4)| Un projet pratique montrant comment détecter les menaces dans un environnement Azure à l’aide d’Azure Sentinel. |
Azure | [SIEM Tutorial for Beginners Azure Sentinel Tutorial MAP with LIVE CYBER ATTACKS!](https://youtu.be/RoZeVbbZ0o0)|Un projet pratique montrant comment configurer un pot de miel et analyser le trafic malveillant à l’aide d’Azure Sentinel . |


## Les choses que vous devez être familier avec à la fin de cette phase


- Une compréhension des concepts IAM de base (utilisateurs, rôles, stratégies, groupes, comptes de service/principaux, etc.)
- Une compréhension du fonctionnement de l’authentification dans le cloud.
- Une compréhension du stockage cloud sécurisé, du calcul, de la mise en réseau, des applications, etc..
- Vulnérabilités de sécurité courantes et erreurs de configuration dans le cloud.
- Comment étudier les logs cloud et déterminer si un environnement cloud a été compromis.
- Comment simuler les attaques contre les environnements cloud.
- Comment deployer des infrastructures vulnerables dans le cloud pour le test de securité.
- Connaissance et usage de divers outils de la securité cloud

## Certifications que vous pourriez vouloir voir


- [Certified Cloud Security Professional](https://www.isc2.org/Certifications/CCSP)
- [Microsoft Certified: Security Operations Analyst Associate](https://docs.microsoft.com/en-us/learn/certifications/security-operations-analyst/)
- [Microsoft Certified: Azure Security Engineer Associate](https://docs.microsoft.com/en-us/learn/certifications/azure-security-engineer/)
- [AWS Certified Security - Specialty](https://aws.amazon.com/certification/certified-security-specialty/)
- [Google Professional Cloud Security Engineer](https://cloud.google.com/certification/cloud-security-engineer)

### Certifications pratiques (Formations incluses)
Ce sont des certifications moins connues, mais elles visent à vous donner la formation nécessaire ainsi que des certifications pratiques où vous mettez les compétences que vous avez appris à utiliser, plutôt que de cliquer sur des questions à choix multiples.
- [Certified Az Red Team Professional](https://bootcamps.pentesteracademy.com/course/ad-azure-may-21)
- [Certified Azure Web Application Security Professional](https://bootcamps.pentesteracademy.com/course/azure-appsec-beginner-jul-22)
- [Offensive Azure Security Professional](https://cloudbreach.io/labs/)
