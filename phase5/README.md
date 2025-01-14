# Phase 5: Les fondamentaux de la securité cloud

Auteur: [Dayspring Johnson](https://twitter.com/daycyberwox)

## Comment s’applique cette phase au Cloud??

la securité est le plus grand challenge dans le cloud.Alors que l'adoption du cloud continue de croître,les incidents de sécurité dans le cloud et les vulnérabilités sont également en croissance.

Les composants cloud individuels qui vous ont été présentés au cours des phases précédentes nécessitent tous une sécurité sous une forme ou une autre. Mieux encore, la sécurité doit être prise en compte sous tous les angles afin d'empêcher les acteurs malveillants de trouver et d'exploiter des vulnérabilités dans nos environnements cloud qui pourraient potentiellement conduire à la compromission des données ou de l'infrastructure.

Voici un de mes articles préférés par [Christophe Tafani-Dereeper](https://twitter.com/christophetd) qui couvre les failles de sécurité et les vulnérabilités du cloud:

- [Violations et vulnérabilités de la sécurité du cloud: 2021 en Revue](https://blog.christophetd.fr/cloud-security-breaches-and-vulnerabilities-2021-in-review/)

 Je recommande également de consulter [Securisation DevOps: Securité dans le Cloud](https://www.manning.com/books/securing-devops) par [Julien Vehent](https://twitter.com/jvehent) qui couvre plusieurs des composants de base pour la protection de l'infrastructure cloud, la journalisation, la détection des menaces, etc. Il a même des aides pratiques et visuelles qui aident à apprendre ces concepts.
Une autre recommandation de livre est[Sécurité cloud pratique:Un guide pour une conception et un déploiement sécurisés ](https://www.oreilly.com/library/view/practical-cloud-security/9781492037507/) par [Chris Dotson](https://www.linkedin.com/in/chris-dotson-6a9b55/). Ce livre est une bonne ressource complémentaire au livre précédent car il approfondit divers concepts, normes, cadres et principes requis pour la sécurité du cloud, et comme son nom l'indique, il est pratique.

Rappelez-vous toujours ceci, vous ne pouvez pas sécuriser ce que vous ne comprenez pas, alors assurez-vous de comprendre les composants architecturaux et de base du cloud afin de pouvoir les sécuriser correctement.


## Resources


| Plateformes cloud | Titre  | Description  |
|:-------------- | ------ | ------ |
AWS, Azure & GCP | [Hacking The Cloud](https://hackingthe.cloud/)| Hacking the cloud is an encyclopedia of the attacks/tactics/techniques that are common in cloud exploitation. |
AWS | [Flaws.Cloudf](http://flaws.cloud/)| Through a series of levels you'll learn about common mistakes and gotchas when using Amazon Web Services (AWS). |
AWS | [Flaws2.Cloud](http://flaws2.cloud/)| Similar to the original Flaws.Cloud Challenge this tutorial teaches you AWS security concepts but this time from both an offensive and defensive perspective |
AWS | [Cloud Goat](https://github.com/RhinoSecurityLabs/cloudgoat)| CloudGoat is Rhino Security Labs' "Vulnerable by Design" AWS deployment tool that allows you to hone your cloud cybersecurity skills by creating and completing several "capture-the-flag" style scenarios. |
AWS | [Sadcloud](https://github.com/nccgroup/sadcloud)| Sadcloud is a tool for spinning up insecure AWS infrastructure with Terraform. You can test your AWS security knowledge against these infrastructure. |
AWS | [AWS Well-Architected Labs: Security](https://www.wellarchitectedlabs.com/security/)| The security labs are documentation and code in the format of hands-on labs to help you learn, measure, and build using architectural best practices. |
AWS | [Attack Detection Fundamentals](https://labs.f-secure.com/blog/attack-detection-fundamentals-2021-aws-lab-1/)| This three-part series explores an end-to-end kill chain in AWS and log entries for detection & analysis. |
Azure | [Attack Detection Fundamentals](https://labs.f-secure.com/blog/attack-detection-fundamentals-2021-azure-lab-1/)| This three-part series explores an end-to-end kill chain in Azure and log entries for detection & analysis. |
Azure | [CONVEX](https://github.com/Azure/CONVEX)| Cloud Open-source Network Vulnerability Exploitation eXperience (CONVEX) spins up Capture The Flag environments in your Azure tenant for you to play through.  |
Azure | [Securing Azure Infrastructure - Hands on Lab Guide](https://github.com/azurecitadel/azure-security-lab)| A hands on guide to securing azure infrastructure using various azure security controls. |
Azure | [Azure Security Technologies](https://microsoftlearning.github.io/AZ500-AzureSecurityTechnologies/)| Various labs scenarios covering azure security. |
Azure | [Create an Azure Vulnerable Lab](https://0xpwn.wordpress.com/2022/03/05/setting-up-an-azure-pentest-lab-part-1-anonymous-blob-access/)| A four-part series explaining azure vulnerabilities. |
GCP | [GCP GOAT](https://gcpgoat.joshuajebaraj.com/)| GCP-Goat is intentionally vulnerable GCP environment to learn and practice GCP Security |
GCP | [ThunderCTF](https://aws.amazon.com/training/)| Thunder CTF allows players to practice attacking vulnerable cloud projects on Google Cloud Platform (GCP). In each level, players are tasked with exploiting a cloud deployment to find a "secret" integer stored within it. |
Kubernetes | [Kubernetes Goat](https://madhuakula.com/kubernetes-goat/)| Kubernetes Goat is an interactive Kuberenetes Security Learning Playground |




## Projets 


| Plateformes cloud | Titre  | Description  |
|:-------------- | ------ | ------ |
AWS | [Threat Detection With AWS GuardDuty](https://www.youtube.com/watch?v=lLgqP4cbdWg&t=127s)| A tutorial showing how to use AWS GuardDuty to detect threats. |
AWS | [AWS Threat Simulation & Detection](https://github.com/sbasu7241/AWS-Threat-Simulation-and-Detection/blob/main/aws.credential-access.ec2-get-password-data.md)| This doc shows the use of Stratus Red Team & SumoLogic for attack & detection/analysis. This can replicated using any other SIEM. |
Azure | [Azure Cloud Detection Lab(Blog)](https://cyberwoxacademy.com/azure-cloud-detection-lab-project/), [Azure Cloud Detection Lab(Videos)](https://youtube.com/playlist?list=PLBNtagSCmDWw27ccfeWeiaMcpNIxpGHy4)| A hands-on project showing how to detect threats in an azure environment using Azure Sentinal. |
Azure | [SIEM Tutorial for Beginners Azure Sentinel Tutorial MAP with LIVE CYBER ATTACKS!](https://youtu.be/RoZeVbbZ0o0)| A hands-on project showing how to set up a honey pot and analyzing malicious traffic using Azure Sentinel. |


## Les choses avec lesquelles vous devez être familier avec à la fin de cette phase


- An understanding of core IAM concepts (Users, Roles, Policies, Groups, Service Accounts/Principals, etc.)
- An understanding of how authentication works in the cloud.
- An understanding of secure cloud storage, compute, networking, applications and so on .
- Common security vulnerabilites and misconfigurations in the cloud.
- How to investigate cloud logs and determine if a cloud envrionment has been compromised.
- How to simulate attacks against cloud environments.
- How to deploy vulnerable infrastructure in the cloud for security testing.
- Knowledge and usage various cloud security tools.

## Les Certifications que vous pourriez vouloir voir


- [Certified Cloud Security Professional](https://www.isc2.org/Certifications/CCSP)
- [Microsoft Certified: Security Operations Analyst Associate](https://docs.microsoft.com/en-us/learn/certifications/security-operations-analyst/)
- [Microsoft Certified: Azure Security Engineer Associate](https://docs.microsoft.com/en-us/learn/certifications/azure-security-engineer/)
- [AWS Certified Security - Specialty](https://aws.amazon.com/certification/certified-security-specialty/)
- [Google Professional Cloud Security Engineer](https://cloud.google.com/certification/cloud-security-engineer)

### Practical Certifications (training included)
These are lesser know certifications but they are focused on giving you the training needed as well as hands-on certifications where you put the skills you've learned to use, rather than clicking through multiple choice questions.
- [Certified Az Red Team Professional](https://bootcamps.pentesteracademy.com/course/ad-azure-may-21)
- [Certified Azure Web Application Security Professional](https://bootcamps.pentesteracademy.com/course/azure-appsec-beginner-jul-22)
- [Offensive Azure Security Professional](https://cloudbreach.io/labs/)


