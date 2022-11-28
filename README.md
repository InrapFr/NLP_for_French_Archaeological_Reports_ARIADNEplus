# NLP for French Archaeological Reports - ARIADNEplus

<br>

This corpus was created within the Task 16.8 of the [ARIADNEplus project](https://ariadne-infrastructure.eu/)[^1]. It was annotated with [INCEpTION](https://inception-project.github.io/) (Ubiquitous Knowledge Processing Lab, TU Darmstadt) and consists so far of six French archaeological reports of the [Inrap](https://www.inrap.fr/) (circa 500 pages for 133,414 tokens and 5078 entities). 

<br>

Six types of entities were annotated and linked to the [Pactols](https://pactols.frantiq.fr/opentheso/) Knowledge Base for the moment: 

| **Name** | **Description** | **Number of occurrences** |
|----------|-----------------|---------------------------|
|     CHRONO     |      Used for temporal references ("Antiquity", "XIIth century", "200 BC", etc.).          |              1082             |
|     CONTEXTE     |        Used for archaeological features ("pit", "ditch", "wall", "hearth", etc.).         |              2399             |
|    INTERVALLE      |        Used for time spans ("from the Neolithic to the late Antiquity", "VIIth-IXth centuries", "between 50 and 70 AD", etc.).         |            225               |
|     MAT     |          Used for materials ("bronze", "dolerite", "ceramic", etc.).       |             123              |
|     MOB     |       Used for physical finds ("bones", "pottery shards", "roof tile", etc.).          |           1170                |
|    TECH_STYLE      |         Used for mentions of techniques and styles of fabrication or construction ("carved", "glazed", "polished", etc.).        |              79             |

<br>

Relations were also created between entities in an experimental way: hasForChronology (aPourChrono), hasForContext (aPourContexte), hasForTimespan (aPourIntervalle), hasForMaterial (aPourMat), hasForTechOrStyle (aPourTechOuStyle).

<br>

The data is available in two formats: CoNLL 2002 and WebAnnoTSV v.3.3.
 
<br>

**Terms of use : https://www.inrap.fr/catalogue-dolia-15609**

<br>

# Le TAL pour les rapports français d'opération archéologique - ARIADNEplus

<br>

Ce corpus a été créé au sein de la tâche 16.8 du [projet ARIADNEplus](https://ariadne-infrastructure.eu/)[^2]. Il fut annoté avec [INCEpTION](https://inception-project.github.io/) (*Ubiquitous Knowledge Processing Lab*, TU Darmstadt) et se compose actuellement de six rapports d'opération archéologique de l'[Inrap](https://www.inrap.fr/) rédigés en français (environ 500 pages pour 133&nbsp;414 tokens et 5078 entités).

<br>

Six types d'entités ont été annotées et reliées à la base de connaissances [Pactols](https://pactols.frantiq.fr/opentheso/) pour le moment : 

| **Nom** | **Description** | **Nombre d'occurrences** |
|----------|-----------------|---------------------------|
|     CHRONO     |      Utilisé pour les références chronologiques ("Antiquité", "XIIe siècle", "200 av. J.-C.", etc.).          |              1082             |
|     CONTEXTE     |        Utilisé pour les faits archéologiques ("fosse", "fossé", "mur", "foyer", etc.).         |              2399             |
|    INTERVALLE      |        Utilisé pour les intervalles chronologiques ("du Néolithique à la fin de l'Antiquité", "VIIe-IXe siècles", "entre 50 et 70 de notre ère", etc.).         |            225               |
|     MAT     |          Utilisé pour les matériaux ("bronze", "dolérite", "céramique", etc.).       |             123              |
|     MOB     |       Utilisé pour le mobilier ("os", "tessons de céramique", "tuile", etc.).          |           1170                |
|    TECH_STYLE      |         Utilisé pour les mentions de techniques et styles de fabrication ou construction ("taillé", "glaçuré", "poli", etc.).        |              79             |

<br>

Des relations furent également créées de manière expérimentale entre les entités : aPourChrono, aPourContexte, aPourIntervalle,  aPourMat, aPourTechOuStyle.

<br>

Les données sont disponibles sous deux formats : CoNLL 2002 et WebAnnoTSV v.3.3.

<br>

**Conditions d'utilisation : https://www.inrap.fr/catalogue-dolia-15609**

<br>

[^1]: ARIADNEplus is funded by the European Commission Horizon2020 programme under under Grant Agreement n. 823914.
[^2]: ARIADNEplus est financé par le programme Horizon2020 de la Commission européenne dans le cadre de la convention de subvention n° 823914.
