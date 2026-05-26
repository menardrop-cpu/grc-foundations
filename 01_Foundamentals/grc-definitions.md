# GRC : définitions et périmètre

## Le sigle

GRC signifie **Governance, Risk, Compliance**. Trois disciplines distinctes mais interconnectées, généralement portées par une fonction transverse dans les organisations matures.

## Governance (Gouvernance)

La gouvernance, c'est l'ensemble des mécanismes par lesquels une organisation est dirigée et contrôlée. Appliquée à l'IT et à la cybersécurité, ça englobe :

* La stratégie de sécurité alignée sur la stratégie business
* Les rôles et responsabilités (RACI)
* Les politiques et procédures qui formalisent le cadre
* Les comités décisionnels (Comité de Sécurité, Comité de Pilotage)
* La supervision (oversight) du dispositif par le top management

La gouvernance répond à la question : **qui décide quoi, selon quelles règles, et qui rend compte à qui** ?

## Risk (Gestion des risques)

La gestion des risques, c'est le processus d'identification, d'évaluation, de traitement et de monitoring des risques affectant les actifs de l'organisation.

Appliquée à la cybersécurité, c'est tout ce qui concerne :

* L'identification des actifs critiques (informations, systèmes, processus)
* L'analyse des menaces et des vulnérabilités
* L'évaluation de l'impact et de la vraisemblance
* Le choix des stratégies de traitement (réduire, transférer, accepter, éviter)
* Le pilotage continu (KRI, Key Risk Indicators)

La gestion des risques répond à la question : **quels événements indésirables pourraient affecter mes objectifs, et comment je m'en protège** ?

## Compliance (Conformité)

La conformité, c'est l'ensemble des activités visant à s'assurer que l'organisation respecte les obligations qui lui sont applicables :

* Lois et réglementations (RGPD, NIS2, DORA, sectorielles)
* Standards et normes auxquels elle s'engage (ISO 27001, SOC 2, PCI DSS)
* Engagements contractuels (clauses de sécurité dans les contrats clients)
* Politiques internes

La conformité répond à la question : **est-ce que je respecte ce à quoi je suis tenu, et comment je le prouve** ?

## L'articulation entre les trois

GRC n'est pas G + R + C juxtaposés. C'est leur intégration qui crée la valeur :

* La **gouvernance** définit ce qui compte et qui décide.
* La **gestion des risques** identifie les écarts entre la situation actuelle et la situation acceptable.
* La **conformité** s'assure que les obligations légales et contractuelles sont respectées, ce qui constitue souvent un sous-ensemble des risques.

Un risque peut être traité par un contrôle qui répond simultanément à une exigence de conformité. Une exigence de conformité non couverte par un contrôle adéquat constitue un risque. La gouvernance arbitre les priorités quand les ressources sont limitées.

## Périmètre d'un analyste GRC

Mon rôle cible (analyste GRC junior) couvre généralement :

* Tenir le registre des risques (risk register) et participer aux campagnes d'analyse
* Réaliser des évaluations de tiers (vendor risk assessment)
* Contribuer aux audits internes et préparer les audits externes
* Documenter les politiques, procédures, et leur révision périodique
* Suivre les indicateurs de conformité et de risque
* Sensibiliser les métiers aux exigences de sécurité

Ce que je ne fais **pas** typiquement en GRC :

* Du pentest technique (c'est l'équipe red team / pentest)
* De la détection d'incident (c'est le SOC)
* De la réponse à incident technique (c'est l'équipe IR)

Le GRC est une fonction de cadre, pas d'opération. Mon outil principal est le tableur, le document, et l'entretien. Pas le terminal.

## GRC vs SecOps : la distinction qui compte

Pour clarifier ma trajectoire, je distingue deux mondes :

| Dimension | GRC | SecOps |
|-----------|-----|--------|
| Horizon | Stratégique et tactique | Opérationnel et temps réel |
| Outils principaux | GRC platform, tableurs, documents | SIEM, EDR, SOAR, scanners |
| Livrables | Rapports, registres, politiques | Alertes, tickets, incidents |
| Compétences clés | Communication, structuration, normes | Analyse technique, scripting, forensique |
| Interlocuteurs | Direction, métiers, auditeurs, régulateurs | Équipes IT, autres analystes SOC, vendors techniques |

Les deux sont nécessaires. Les deux dialoguent. Mais ce sont des métiers distincts avec des compétences distinctes.

Ma cible : GRC, parce que c'est où mon profil (capacité de structuration, communication business) crée le plus de valeur.

## Pour aller plus loin

* [Vocabulaire fondamental du risque](risk-vocabulary.md)
* [Three Lines of Defense](three-lines-of-defense.md)
* [GRC vs disciplines connexes](grc-vs-related-disciplines.md)
